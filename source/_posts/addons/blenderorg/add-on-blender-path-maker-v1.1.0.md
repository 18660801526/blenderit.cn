---
title: "Path Maker"
description: "Replaces custom tags in the Output Path"
summary: "Replaces custom tags in the Output Path"
date: 2024-03-17 00:00:00
updated: 2024-03-17 00:00:00
author: blenderit
tags: 
    - Render
categories:
    - blenderorg
img: https://extensions.blender.org/media/thumbnails/db/dbe7ced3e06d35ba03fd48c57c980e9539c8435187b37e4ad8b1864aa29064f4_640x360.webp
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/blender-path-maker/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>The "Path Maker" add-on allows you to write tags in some output paths. Tags will be replace at render time by a string generated with a line of code, a python script or an hardcoded string.</p>
<p>It supports:</p>
<ul>
<li>The "Output Path" in the output properties panels</li>
<li>The "Base Path" in the file output compositor nodes</li>
<li>The "filepath" in the collection exporters (you'll have to use the Path Maker buttons to make it work though)</li>
</ul>
<p>For example:
The tag &lt;scene&gt; can be replace by "bpy.path.display_name_from_filepath(bpy.data.filepath)" so that an Output Path like "C:/hello/&lt;scene&gt;/world" will now be "C:/hello/file_name/world".</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}