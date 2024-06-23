---
title: "Path Actions"
description: "Open blend folder in OS explorer, and more"
summary: "Open blend folder in OS explorer, and more"
date: 2024-05-18 00:00:00
updated: 2024-05-18 00:00:00
author: blenderit
tags: 
    - System
    - Development
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/SB_path_actions.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/sb-path-actions/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>This addon helps interact with filesystem locations relative to current blend file.</p>
<p>Here is a video demo of the main features : <a rel="nofollow noopener noreferrer external" target="_blank" href="https://www.youtube.com/watch?v=MUz2RAfHA3I">https://www.youtube.com/watch?v=MUz2RAfHA3I</a></p>
<p>See here for illustrated doc : <a rel="nofollow noopener noreferrer external" target="_blank" href="https://github.com/Pullusb/SB_path_actions">https://github.com/Pullusb/SB_path_actions</a></p>
<h3>Open Blend's Folder</h3>
<p>The main feature: A cute little folder button appear on header's top-right that will open current blend's folder in OS file browser.</p>
<p>Modifier-keys + click on the button to trigger other actions:</p>
<ul>
<li><code>Ctrl+Click</code> : Copy file path</li>
<li><code>Ctrl+Shift+Click</code> : Copy directory path</li>
<li><code>Alt+Click</code> : Copy file name</li>
<li><code>Shift+Click</code> : Open Side Blend</li>
</ul>
<h3>Open Side Blend menu</h3>
<p>Clicking on filename open it in your current instance (careful, no warning)
Clicking on the blender file icon open the file in another instance.</p>
<h3>Shortcut</h3>
<p>Add a shortcut to pop up a search field to open blends from history (<code>Ctrl+ Shift + Alt + o</code>).</p>
<h3>Addon preferences</h3>
<p>Add buttons to open blender app related folders (addons, config, etc).</p>
<p>Open any addons folder (button in list or using search feature)</p>
<h3>Blender file browser</h3>
<p>Button to set browser where the blend is</p>
<p>Button to open browsed folder in operating system file browser.</p>
<h4>Switch output path type between relative and absolute</h4>
<p>This is called through F3 search operator, (if you have <code>developer extras</code> enabled in preferences &gt; interface)</p>
<h3>A reload option for developers</h3>
<p>If developer mode is ticked in preference, another button appears at the top corner next to the folder icon.
It triggers a full refresh of the blend (launch the file in a fully new blender instance and close the current),</p>
<p>Useful for super quick reload when developing addons without IDE debugger.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}