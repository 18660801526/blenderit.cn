---
title: "Face Set Operators"
description: "Convert sculpt mode attributes into anything you need"
summary: "Convert sculpt mode attributes into anything you need"
date: 2024-06-19 00:00:00
updated: 2024-06-19 00:00:00
author: blenderit
tags: 
    - Sculpt
    - Mesh
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-face-set-operators-v1.0.0.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/face-set-operators/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>More advanced uses for sculpt mode face sets inside Blender. Use face sets in Geometry Nodes, as Vertex Groups, or to quickly draw material slots and UV Map with a brush. This add-on makes it possible to divide mesh into separate parts for ANY PURPOSE with brush strokes in sculpt mode, instead of manually selecting faces and assigning them to groups, attributes, and material slots in edit mode.</p>
<ul>
<li><strong>Face Sets to Material Slots</strong></li>
</ul>
<p>Assigning multiple materials on meshes can be a slow process, especially when the mesh is high-poly and selecting faces in the edit mode becomes slow. With this operator you can use brush in sculpt mode to draw face sets where you want your materials to be and them into material slots. Dummy materials will be assigned to every face set which you can later swap with your materials.</p>
<p>This is also useful for ID mapping when you want to export your mesh to external software such as Substance Painter, or for *<strong>Quad Remesher</strong>* add-on to include material slots into the remeshing process.</p>
<ul>
<li><strong>Face Sets to UVMap</strong></li>
</ul>
<p>Selecting edges and marking seams on organic objects is tedious (and also slow for high-poly) in edit mode. With this operator you can draw face sets where you want your UV islands to be, add seams to face set boundaries, and unwrap your mesh according to your drawings. You can also use custom-set edit mode seams alongside face sets.</p>
<ul>
<li><strong>Face Sets to Vertex Groups</strong></li>
</ul>
<p>This operator converts each face set into vertex group, where every vertex inside each face set is assigned to the group with the weight of 1. Makes it possible to select face sets outside sculpt mode and therefore work on them in edit mode, paint modes, and etc.</p>
<ul>
<li><strong>Face Sets to Attribute</strong></li>
</ul>
<p>Face Sets can't be used procedurally in geometry nodes modifiers (by design), but this feature comes close. This operator converts cached face sets into an integer attribute, with each group of faces inside the face set assigned the integer ID from 0 to N. This will allow you to use geometry nodes with your sculpting workflow, create abstract art, or whatever you can imagine, from inside the sculpt mode.</p>
<hr>
<p>Add-on also has features for working on masks:</p>
<ul>
<li><strong>Mask from Edit Mode Selection</strong></li>
</ul>
<p>Like the similar built-in operator for face sets, this will allow you to convert edit mode selections into sculpt masks. Can be called either from edit mode (in Vertex menu), or from sculpt mode (in Mask menu).</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}