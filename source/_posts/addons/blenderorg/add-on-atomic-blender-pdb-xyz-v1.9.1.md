---
title: "Atomic Blender PDB/XYZ"
description: "Importing atoms listed in PDB and XYZ files into Blender"
summary: "Importing atoms listed in PDB and XYZ files into Blender"
date: 2024-05-14 00:00:00
updated: 2024-05-14 00:00:00
author: blenderit
tags: 
    - Import-Export
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-atomic-blender-pdb-xyz-v1.9.1.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/atomic-blender-pdb-xyz/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>The Atomic Blender (PDB/XYZ) add-on imports atomic structures (molecules, crystals, clusters, particles, surfaces, etc.), which are described in PDB (.pdb) and XYZ files (.xyz). The add-on reads the coordinates of all atoms in the PDB/XYZ file and represents the atoms as balls in the Blender world. Also the sticks, which are described in PDB files only, are shown <strong>if the sticks are explicitly listed in the PDB file</strong>.</p>
<blockquote>
<p><strong>Speed advantage</strong></p>
<p>Thanks to the Blender specific method called 
<a rel="nofollow noopener noreferrer external" target="_blank" href="https://docs.blender.org/manual/en/latest/scene_layout/object/properties/instancing/verts.html">instancing vertices structure</a>,
which is used to build an atomic structure, the speed of the loading
and the general handling of an atomic structure inside the Blender 3D View
is quite fast. Atomic structures with 1000 atoms and much more
can be easily handled.</p>
</blockquote>
<p>For more information see the <a rel="nofollow noopener noreferrer external" target="_blank" href="https://projects.blender.org/extensions/io_mesh_atomic/wiki/Home">wiki page</a> !</p>
<ul>
<li>Location: <em>File -→ Import -→ PDB (.pdb) and File -→ Import -→ XYZ (.xyz)</em></li>
<li><a rel="nofollow noopener noreferrer external" target="_blank" href="https://projects.blender.org/extensions/io_mesh_atomic/wiki/Home">Documentation (Wiki)</a></li>
<li><a rel="nofollow noopener noreferrer external" target="_blank" href="https://blenderartists.org/t/atomic-blender-pdb-xyz-for-blender-2-8-and-higher/1197801">Forum</a></li>
<li>Author: Clemens Barth</li>
</ul>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}