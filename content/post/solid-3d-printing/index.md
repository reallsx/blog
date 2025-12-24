+++
date = '2025-12-15T13:27:28-06:00'
draft = true
title = 'Solid 3d Printing'
categories = [
    "Technical"
]
tags = [
    "3D Printing",
]
+++

# 3D Printing with 100% infills for larger parts

For a normal FDM 3D printer, usually the objects printed is for the visual or functional prototype and the inner part does not matter that much. So the infill of a print is usually for supporting the structure and it does not require a high infill percentage. Even for some functional parts, usually a smaller infill percentage is preferred for the sake of filament cost and printing time. 100% infill is required only in some specific situations and one of those is printing solid phantom to achieve certain HU value under CT scans.

FDM 3D printing phantom for CT and linac was a thing I was asked to do. Although there are a lot of publications on this topic since probably 2010, I still had some hard time to figure out the printing part and I found that printing a "fully solid" object poses very different technical challenge from just printing weird stuff in general. As it does not look like some of the experience I gained is going to be included, I might use it to populate the blog a bit lmao. If it happens that you found yourself in a similar situation or you are working with the same printer/filament, this at least would provide a datapoint for your reference.

![Stonefil surface](stonefil_surface.jpg)

## Making images look better

You can control image size by mixing Markdown with a little HTML:

```markdown
<img src="stonefil_surface.jpg" alt="Stonefil surface" width="400">
```

You can also set height (or both width and height), for example:

```markdown
<img src="stonefil_surface.jpg" alt="Stonefil surface close-up" width="400" height="300">
```

To place two images side by side, put them in a flex container:

```markdown
<div style="display: flex; gap: 1rem;">
  <img src="stonefil_surface.jpg" alt="Stonefil surface" width="300">
  <img src="stonefil_surface_detail.jpg" alt="Detail view" width="300">
</div>
```

Because this post is a leaf bundle, these paths (`stonefil_surface.jpg`, `stonefil_surface_detail.jpg`) refer to image files stored next to this `index.md`.
