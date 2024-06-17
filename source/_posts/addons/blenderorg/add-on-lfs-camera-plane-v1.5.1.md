---
title: "Camera Plane"
description: "Import images and stick them to the camera"
summary: "Import images and stick them to the camera"
date: 2024-06-17 08:57:09
updated: 2024-06-17 08:57:09
author: blenderit
tags: 
    - 3D View
    - Import-Export
    - Object
    - Camera
categories:
    - blenderorg
img: https://extensions.blender.org/media/thumbnails/2a/2a5c3fcde21b3c26fa31e68a58c9a70746569ab88968072bc7e3752408d55215_640x360.webp
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/lfs-camera-plane/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>Import images and parent them to the camera. You can then set the
distance and width from the image object’s or the camera’s properties.
The plane will adjust to the camera’s FOV or focal length.<br>
You can easily import several images at once, which will be equally
spaced in depth. This is useful when creating painted stage-like sets
which need to stick to a camera.</p>
<h2>Workflow</h2>
<h3>Importing</h3>
<ul>
<li>Select the camera;</li>
<li>Click Import Camera Planes from the object properties;</li>
<li>Select images to import;</li>
<li>The panel now extends to show a list of images.</li>
<li>Those images can be filtered, and they can be displayed either in
alphabetical order, or increasing in distance from the camera.</li>
</ul>
<h3>Image settings</h3>
<p>From the Camera Plane panel, you can reorder the planes by setting
their distance from the camera. Like other properties in Blender, you
can click on a distance, drag up or down to include the distance from
other planes, and then drag left or right to change the distance, and
thus move several planes at once.</p>
<p>The scale of each image can likewise be tweaked.</p>
<p>If you select multiple planes, you can "bake them" together to create
a single, new image. This may be useful if you have many images that
constitute a single plane, such as a level of overlay.</p>
<p>When the planes are set up, you can click the Setup Layers button to
create as many view layers as there are planes, and assign them to
collections. That way, they can be rendered and composited individually.</p>
<p>Please see <a rel="nofollow noopener noreferrer external" target="_blank" href="https://lacuisine.tech/cameraplane-a-tool-for-2d-sets/">this
article</a>
for a more in-depth overview of the tool. The interface has since
changed, but the principle is the same.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}