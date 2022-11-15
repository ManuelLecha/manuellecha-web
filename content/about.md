---
title: ""
date: 2022-11-07T21:45:33+01:00
draft: false
description: "About Me" 
---

<style>

    /* The actual timeline (the vertical ruler) */
.timeline {
  position: 0;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: white;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #FF9F55;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the right */
.right {
  left: 50%;
}

/* Add arrows to the right container (pointing left) */
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -16px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
/* Place the timelime to the left */
  .timeline::after {
    left: 31px;
  }

/* Full-width containers */
  .container {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

/* Make sure that all arrows are pointing leftwards */
  .container::before {
    left: 60px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }

/* Make sure all circles are at the same spot */
  .right::after {
    left: 15px;
  }

/* Make all right containers behave like the left ones */
  .right {
    left: 0%;
  }
}
</style>

{{<figure src="/roundme.png" alt="This is how I look like" position="center" height="200px" width="200px">}} 

My name is Manuel Lecha and I'm from Barcelona, Spain. I am a Mathematician and a Computer Scientist who has recently graduated from the MSc. in Advanced Mathematics at the Polytechnique University of Catalonia. 


<div class="timeline">
  <div class="container right">
    <div class="content">
      <h2>May 2021 - Oct 2022</h2>
      <p>Doing some stufff babyyy</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>May 2020 - Oct 2021</h2>
      <p>Doing some other stufff babyyy</p>
    </div>
  </div>
</div> 
