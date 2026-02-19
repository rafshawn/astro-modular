---
title: Image Sizing Test
date: 2026-02-19
description: ""
tags: []
image: ""
imageAlt: ""
imageOG: false
hideCoverImage: false
hideTOC: false
targetKeyword: ""
draft: false
lastModified: 2026-02-19
---
# Image Sizing Test

This page demonstrates how to use Obsidian-style image sizing syntax.

## Obsidian Image Size Syntax

### Width Only (pixels)
![Test Image|300](attachments/spring-flowers.jpg)
This will render the image at 300px wide, height auto.

### Width x Height (pixels)
![Test Image|200x150](attachments/spring-flowers.jpg)
This will render the image at 200px wide and 150px tall.

## Default Behavior

Regular images without size syntax will be:
- Centered automatically
- Display at natural size up to 100% of container
- No cropping or stretching

![Regular Image](attachments/spring-flowers.jpg)
This will render the image normally.

## Examples

```markdown
<!-- Small thumbnail -->
![Logo|80](/images/logo.png)

<!-- Medium image -->
![Screenshot|600](/images/screenshot.png)

<!-- Fixed dimensions -->
![Icon|48x48](/images/icon.png)
```

## Notes

- Images with manual sizing will NOT be automatically added to image grids
- Manually sized images use `object-fit: contain` to prevent cropping
- Regular images remain centered by default
- The lightbox/zoom feature still works for all images