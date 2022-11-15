---
title: "About"
date: 2022-11-07T21:45:33+01:00
draft: false
description: "About Me" 
---


{{ $asset := resources.Get "/roundme.png" }}
{{ $img := $asset.Fit "100x100" }}

<figure class="image is-3by2">
  <img alt="This is me" src="{{ $img.RelPermalink }}" />
</figure>

<!-- {{<figure src="/roundme.png" alt="This is how I look like" position="center" style="border-radius: 8px; height: 10px; width:10px;">}} -->

