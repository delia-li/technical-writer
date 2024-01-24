---
title: Figma Animation
layout: page
---

# Animate your first splash screen in Figma
{: .no_toc }

An animated splash screen can really bring your website or app to life. It’s accessible, enjoyable, and memorable for your users. In this demo, you'll learn how to build this animated splash screen for a mobile app called Rate my Transit.

<video width="800" controls>
  <source src="./splash_animation.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

# Gather the components you’ll be using in your app
Go to the [Google Material UI design library](https://fonts.google.com/icons) and search for `directions bus` and `train`. Download your icons in the `SVG` format.

<img src="./svg_download.png" width="600">

{: .note }
There are thousands of icons you can explore in the Google design suite. There are also [many other design systems](https://www.designsystemsforfigma.com/) that are free to use on Figma!


# Build your frames in Figma.
1. Open Figma and create a new project.
2. Press `F` to open the Frame selection and choose `Android Large`.
3. Drag and drop your two transit icons into your project
4. Select the Frame and change the `Fill` to `000117`, a dark blue color. This will be your background.
5. Select the transit icons and change the color under `Selection Colors` to `21246A`.
6. Press `T` to create text, and type `Rate`.
7. Repeat step 6 but `My` and `Transit`. It is important to have these three words as separate Text objects because you will be animating them separately later.


