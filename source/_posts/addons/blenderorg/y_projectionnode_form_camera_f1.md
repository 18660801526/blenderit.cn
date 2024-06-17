---
title: "ProjectionNode from Camera"
description: "Creates a material specified in the Background Image of Camera"
summary: "Creates a material specified in the Background Image of Camera"
date: 2024-03-31 00:00:00
updated: 2024-03-31 00:00:00
author: blenderit
tags: 
    - Node
    - Material
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/default.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/y-projectionnode-form-camera-f1/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>This is an add-on that creates a node that projects a camera map according to the appearance of the image set in the camera's "background".</p>
<h2>Basic usage of add-ons</h2>
<p>The add-on panel appears in the node tab of the sidebar above the shader editor</p>
<p>Select the camera you want to use for projection from the camera pulldown and select the background you want to use.
If no background image is set for the specified camera, items under "Background" will not be displayed.
After specifying the camera with the sketch set, select the image you want to use from the sketch dropdown.
When you press the Make CameraProjection Nodes button
A node group will be created with a name such as [camera name]_[image name]_Projection.</p>
<p>If the material is displayed in the shader editor, add the created node group to the material
If the material is not displayed or you want to use it with another material,
Select from the group items in the Add menu.</p>
<h2>How to use NodeGroup</h2>
<p>By connecting the color output of the created node group to the color input of the shader
The image will be projected from the camera as specified in the sketch.</p>
<p>If you use an image transparent with alpha for the sketch,
The color specified in the color input or the color combined with the image will be output.</p>
<p>There is also a function that uses the color input value when the angle between the camera and the projected surface is larger than the limit angle specified.
You can set the boundary between angle restrictions to be a gradation in the blur settings.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}