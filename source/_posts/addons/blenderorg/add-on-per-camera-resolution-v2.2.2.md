---
title: "Per-Camera Resolution"
description: "Every camera should have its resolution"
summary: "Every camera should have its resolution"
date: 2024-05-28 00:00:00
updated: 2024-05-28 00:00:00
author: blenderit
tags: 
    - Scene
    - Camera
categories:
    - blenderorg
img: https://extensions.blender.org/media/thumbnails/c2/c2c9205ead9ad8583eb75c6b8d79db81876df1f24a412ccd3868aaa087afa794_640x360.webp
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/per-camera-resolution/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>Instead of having a globally-defined scene resolution, this add-on
allows you to set a resolution for each camera. Whenever you switch
cameras, either manually or through timeline markers, the scene
resolution will get updated to the camera’s.</p>
<p>You can find the camera resolution settings in the Object Data
properties, under the Camera panel.</p>
<h3>Rendering</h3>
<p>Animating the resolution is not supported by default in Blender, and
regular animation rendering will only use the resolution at render
start.<br>
This add-on provides a new Render Animated Resolution operator which
works around this limitation. Note however that starting a render this
way will lock the interface until the render is complete, or until
Blender is killed.</p>
<h3>Baking render borders</h3>
<p>In addition to providing direct controls for each camera’s resolution,
this add-on allows you to create a new camera by setting a render
border inside the camera view in the 3D viewport (Ctrl + B), and
clicking Bake Render Border in the Custom Resolution panel.<br>
A new camera is created, which uses the exact area defined by the
border. This allows you to select multiple cropped areas in a camera.</p>
<h2>Known issues</h2>
<p>This add-on uses a workaround to animate the camera resolution, which
can sometimes cause stability issues. If you encounter such issues,
try disabling the add-on.</p>
<h2>Translations</h2>
<p>The add-on is currently available in English and French. If you’d like to help translate it to your language, please <a rel="nofollow noopener noreferrer external" target="_blank" href="https://projects.blender.org/pioverfour/per_camera_resolution/issues/new">open an issue</a>.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}