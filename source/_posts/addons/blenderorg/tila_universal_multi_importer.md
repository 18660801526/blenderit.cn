---
title: "Universal Multi Importer"
description: "Batch Import many file formats at once, Batch process them"
summary: "Batch Import many file formats at once, Batch process them"
date: 2024-06-21 00:00:00
updated: 2024-06-21 00:00:00
author: blenderit
tags: 
    - Import-Export
    - Pipeline
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/tila_universal_multi_importer.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/universal-multi-importer/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h2>Key Features</h2>
<hr>
<p>This addon is made to facilitate the import of data in Blender !</p>
<p>You can :</p>
<ul>
<li>Import multiple files of different formats from the same import dialog.</li>
<li>You can scan for files to import in a folder hierarchy.</li>
<li>(Blender 4.1+ only) Drag and drop any file to import them.</li>
<li>The viewport stays interactive durring the import process, you can setup autosaves durring import.</li>
<li>You can process the imported files with python commands durring import which opens a lot of possibilities</li>
</ul>
<h1>Supported Formats</h1>
<hr>
<table>
<thead>
<tr>
  <th>Mesh Formats</th>
  <th>Image Fommats</th>
  <th>Video Formats</th>
  <th>Animation Formats</th>
</tr>
</thead>
<tbody>
<tr>
  <td>blend</td>
  <td>jpg</td>
  <td>mov</td>
  <td>bvh</td>
</tr>
<tr>
  <td>obj</td>
  <td>jpeg</td>
  <td>mp4</td>
  <td></td>
</tr>
<tr>
  <td>fbx</td>
  <td>gif</td>
  <td>mkv</td>
  <td></td>
</tr>
<tr>
  <td>glb</td>
  <td>png</td>
  <td>mpg</td>
  <td></td>
</tr>
<tr>
  <td>gltf</td>
  <td>tif</td>
  <td>mpeg</td>
  <td></td>
</tr>
<tr>
  <td>x3d</td>
  <td>tiff</td>
  <td>dvd</td>
  <td></td>
</tr>
<tr>
  <td>wrl</td>
  <td>bmp</td>
  <td>dvd</td>
  <td></td>
</tr>
<tr>
  <td>stl</td>
  <td>cin</td>
  <td>vob</td>
  <td></td>
</tr>
<tr>
  <td>ply</td>
  <td>dpx</td>
  <td>avi</td>
  <td></td>
</tr>
<tr>
  <td>abc</td>
  <td>jp2</td>
  <td>dv</td>
  <td></td>
</tr>
<tr>
  <td>dae</td>
  <td>j2c</td>
  <td>flv</td>
  <td></td>
</tr>
<tr>
  <td>svg</td>
  <td>sig</td>
  <td>webm</td>
  <td></td>
</tr>
<tr>
  <td>usd</td>
  <td>rgb</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td>usda</td>
  <td>bw</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td>usdc</td>
  <td>exr</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td>usdz</td>
  <td>hdr</td>
  <td></td>
  <td></td>
</tr>
</tbody>
</table>
<h2><strong>Import Folder</strong></h2>
<hr>
<h3>Recursion Depth</h3>
<p>( Folder mode only ) Determine how many subfolders will be scaned for compatible files to import. <code>0</code> will grab all files in current folder, <code>1</code> will grab everything in current folder and all dirrect subfolders, <code>2</code> will grab all files in the current folder, the dirrect subfolders and the subfolders of each direct subfolders etc ...</p>
<h2><strong>File Count</strong></h2>
<hr>
<h3>Max Simultaneously</h3>
<p>Determine the max number of file to import simultaneously. Each group of files to be imported simultaneously is called a "Batch". Importing multiple file at the same time allow to reduce the import time for small file, but can cause screen freezing or memory issue for biger file. To smartly ballance this, you can check <code>Max batch size</code> and <code>Minimize batch number</code></p>
<h3>Max batch size</h3>
<p>Determine the max batch file size to Import. If a file is a candidate to be include in the current batch, but his filesize would make the batch bigger than <code>Max batch size</code>, then the file will be included in the next batch</p>
<h3>Minimize batch number</h3>
<p>The importer will smartly group files in batches in order to be as close as possible to <code>Max batch size</code> for each batch without exceeding it and without exceeding <code>Max Import Simultaneously</code></p>
<h2><strong>Options</strong></h2>
<hr>
<h3>Create collection per file</h3>
<p>Each imported file will be placed in a new collection named like the file</p>
<h3>Skip already imported files</h3>
<p>if a file have already been imported, the import is skipped for this file, this option is only available if "<code>Create collection per file</code>" is Enable</p>
<h2><strong>Log Display</strong></h2>
<hr>
<h3>Show Log on 3D View</h3>
<p>Display the Log and Progress of the Importing files in the 3D viewport while importing</p>
<h3>Auto Hide Log When Finished</h3>
<p>Automatic hide the log once the Import is Completed</p>
<h3>Wait Before Hiding (s)</h3>
<p>How much time to wait before Hiding the Log</p>
<h3>Refresh viewport after each Import</h3>
<p>Force refresh the viewport after each imported files. It imporoves interactivity, but will slow down the global import time</p>
<h2><strong>Backup</strong></h2>
<hr>
<h3>Save file after import</h3>
<p>At the end of the imprort process, save the current file</p>
<h3>Backup file after each import</h3>
<p>A backup file is saved after each "<code>Backup Step</code>" file is imported</p>
<h3>Backup Step</h3>
<p>The number of file that is imported before saving a backup</p>
<h2><strong>Command Batcher</strong></h2>
<hr>
<h3>Commands</h3>
<p>You create a macro like pyhon commands list. These commands will be executed in a row to all the imported objects after each importes batch.</p>
<p>It will process in that order :</p>
<ul>
<li>Import Batch 1</li>
<li>Run all batch commands in order</li>
<li>Repeat for next Batches...</li>
</ul>
<p>For exemple, if you add this command "<code>bpy.ops.transform.translate(value=(10, 0, 0))</code>", each imported file will be translated 10 meters away on positive X axis</p>
<p>Please note how the commands are written with <code>bpy.ops</code> and all parameters in parentheses</p>
<p>You can't create variable, for loops or if statements. Just commands that blender will execute</p>
<h3>Ignore Command Batcher Errors</h3>
<p>Batch Processing imported files can cause error. Enabling this will continue the import of the following files even if an error occurs. Otherwise, the import process will stop</p>
<h3>Presets</h3>
<p>You can save any list of commands from <code>batch process Imported files</code> to a preset that will be saved on disk. Here you can manage the presets:</p>
<ul>
<li>Creating preset</li>
<li>Loading Preset</li>
<li>Removing Preset</li>
<li>Renaming Preset</li>
</ul>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}