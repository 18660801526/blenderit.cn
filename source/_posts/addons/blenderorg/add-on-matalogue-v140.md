---
title: "Matalogue"
description: "All your node trees in one list"
summary: "All your node trees in one list"
date: 2024-06-23 08:53:00
updated: 2024-06-23 08:53:00
author: blenderit
tags: 
    - Animation
    - Mesh
    - Node
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-matalogue-v140.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/matalogue/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>A Blender add-on that displays a list of materials and other node trees right in the toolbar of the Node Editor.</p>
<p>This makes it easier to <strong>switch between different materials</strong> while shading, and different compositing setups while working with multiple scenes.</p>
<p>Older versions:</p>
<ul>
<li><a rel="nofollow noopener noreferrer external" target="_blank" href="https://raw.githubusercontent.com/gregzaal/Matalogue/4045065/matalogue.py">Blender 2.8 - 3.6</a></li>
<li><a rel="nofollow noopener noreferrer external" target="_blank" href="https://raw.githubusercontent.com/gregzaal/Matalogue/e9aaa80e/matalogue.py">Blender 2.7</a></li>
</ul>
<hr>
<h2>Documentation</h2>
<h3>Trees</h3>
<p>There are multiple sources of node trees in Blender, namely:</p>
<ul>
<li>Shader nodes for both materials and lights</li>
<li>Geometry nodes</li>
<li>Node groups of various types</li>
<li>Compositing</li>
<li>Freestyle nodes (<em>not yet supported</em>)</li>
</ul>
<p>By clicking on one of the listed items, the Node Editor will switch to that tree and select the related objects.</p>
<h5>Materials</h5>
<p>Lists all the materials according to the options below. Click on a name to switch to the nodes for that material.</p>
<ul>
<li><strong>Selected Objects Only</strong> - Only show materials that are assigned to selected objects, otherwise all materials in the current scene are shown.</li>
<li><strong>Visible Layers Only</strong> - Only show materials that are assigned to objects that are on one of the visible layers. Take note that if <em>All Scenes</em> is off, materials on visible layers of other scenes will be shown too.</li>
<li><strong>All Scenes</strong> - Show materials from all scenes, not just the current one. Requires <em>Selected Objects Only</em> to be disabled.</li>
<li><strong>0-User Materials</strong> - Show materials that have no users (those that will be deleted when Blender is closed). Requires <em>All Scenes</em> to be enabled.</li>
</ul>
<h5>Geometry Nodes</h5>
<p>Lists all geometry nodes modifiers and tools in the scene.</p>
<h5>Lighting</h5>
<p>Lists all the <strong>lamp data</strong> in the current scene, as well as the <strong>World</strong> nodes. Click on a name to switch to the nodes for that lamp.</p>
<h5>Compositing</h5>
<p>Lists each scene - clicking on one will take you to the compositing nodes for that scene.</p>
<h3>Special Cases</h3>
<p>When switching to a material that is not actually used by any objects, a dummy object (which has no vertices) is created. This is because the only way to control what material is displayed in the Node Editor via Python is by selecting the object that material is assigned to.</p>
<p>The dummy object is automatically deleted once it is no longer needed (though only when you switch to another material).</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}