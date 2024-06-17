---
title: "Bioxel Nodes"
description: "For scientific volumetric data visualization in Blender"
summary: "For scientific volumetric data visualization in Blender"
date: 2024-06-13 00:00:00
updated: 2024-06-13 00:00:00
author: blenderit
tags: 
    - Geometry Nodes
    - Render
categories:
    - blenderorg
img: https://extensions.blender.org/media/thumbnails/dd/ddfc963c2aa17a161e6b4ba5015bb9d28b75d21ccde56f5a1d078d8a18b4ecf0_640x360.webp
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/bioxelnodes/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h1>🦖 Bioxel Nodes</h1>
<p>Bioxel Nodes is a Blender extension for scientific volumetric data visualization. It using Blender's powerful Geometry Nodes and Cycles to process and render volumetric data. You are free to share your blender file to anyone who does not install this extension, since most processes were done by Blender's native nodes.</p>
<h2>About</h2>
<p>Before us, there have been many tutorials and extensions for importing volumetric data into Blender. However, we found that there were many scientific issues that were not addressed in place, and the volume render results were not epic. With Bioxel Nodes, you can easily import any format volumetric data into Blender, and more importantly, make a beautiful realistic volume rendering quickly.</p>
<p>Below are some examples with Bioxel Nodes. Thanks to Cycles Render, the volumetric data can be rendered with great detail:</p>
<p><img src="https://omoolab.github.io/BioxelNodes/latest/assets/cover.png" alt="cover"></p>
<p>So how to use this extension? please check <a rel="nofollow noopener noreferrer external" target="_blank" href="https://omoolab.github.io/BioxelNodes/latest/getting-started">Getting Started</a></p>
<h2>Supported Format</h2>
<table>
<thead>
<tr>
  <th>Format</th>
  <th>EXT</th>
  <th>Test</th>
</tr>
</thead>
<tbody>
<tr>
  <td>DICOM</td>
  <td>.dcm, .DICOM</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>BMP</td>
  <td>.bmp, .BMP</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>JPEG</td>
  <td>.jpg, .JPG, .jpeg, .JPEG</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>PNG</td>
  <td>.png, .PNG</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>TIFF</td>
  <td>.tif, .TIF, .tiff, .TIFF</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>Nifti</td>
  <td>.nia, .nii, .nii.gz, .hdr, .img, .img.gz</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>Nrrd</td>
  <td>.nrrd, .nhdr</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>Meta</td>
  <td>.mha, .mhd</td>
  <td>yet</td>
</tr>
<tr>
  <td>HDF5</td>
  <td>.hdf, .h4, .hdf4, .he2, .h5, .hdf5, .he5</td>
  <td>✅ pass</td>
</tr>
<tr>
  <td>VTK</td>
  <td>.vtk</td>
  <td>yet</td>
</tr>
<tr>
  <td>BioRad</td>
  <td>.PIC, .pic</td>
  <td>yet</td>
</tr>
<tr>
  <td>Gipl</td>
  <td>.gipl, .gipl.gz</td>
  <td>yet</td>
</tr>
<tr>
  <td>LSM</td>
  <td>.lsm, .LSM</td>
  <td>yet</td>
</tr>
<tr>
  <td>MINC</td>
  <td>.mnc, .MNC</td>
  <td>yet</td>
</tr>
<tr>
  <td>MRC</td>
  <td>.mrc, .rec</td>
  <td>yet</td>
</tr>
</tbody>
</table>
<h2>Known Limitations</h2>
<ul>
<li>Sections cannot be generated (will be supported soon)</li>
<li>Time sequence volume not supported (will be supported soon)</li>
</ul>
<h2>About EEVEE Render</h2>
<p>Bioxel Nodes is designed for Cycles Render. However, it does support eevee render partially. "Solid Shader" node and "Volume Shader" node have a toggle called "EEVEE Render". If you want to render Bioxel Component in real-time, turn it on.</p>
<p>Also, there are some limitations:</p>
<ol>
<li>Only one cutter supported.</li>
<li>You cannot use "Color Ramp" over 2 colors.</li>
<li>EEVEE Render result is not that great as Cycles does.</li>
</ol>
<blockquote>
<p>"Volume Shader" node is not work properly in EEVEE Next since 4.2. It is because EEVEE Next is not support attributes from instances of volume shader by now. But the Blender 4.2 docs still say attributes reading is ok, so I suppose this feature will eventually be implemented.</p>
</blockquote>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}