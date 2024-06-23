---
title: "Node Group Presets"
description: "Save Node Group values as presets"
summary: "Save Node Group values as presets"
date: 2024-05-31 00:00:00
updated: 2024-05-31 00:00:00
author: blenderit
tags: 
    - Node
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/node_group_presets.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/node-group-presets/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h1>What is NodeGroupPresets?</h1>
<p>NodeGroupPresets is an addon that saves the current values of a given nodegroup into a applyable/editable/copyable preset. Quite useful when building a verstaile node library taking away the bothersome workflow of either copy/pasting multiple values from different instances of a nodegroup or "hardcoding" presets into it's own nodegroups.</p>
<h2>Features</h2>
<p>The main features of this addon are:</p>
<ul>
<li>Save/Apply presets</li>
<li>Update presets with current status</li>
<li>Edit presets, add/removing sockets or changing its name/value</li>
<li>Copy/Past presets from different nodes or files</li>
</ul>
<h4>Save/Apply Preset</h4>
<p><em>Saves supported sockets values/subtype/max&amp;min limits.</em></p>
<ul>
<li><code>Single click</code>: Full save</li>
<li><code>Shift + Click</code>: Partial save</li>
</ul>
<h4>Update Preset</h4>
<p><em>Update values with the node's current values</em>
<em>If socket order changes, you can update the preset order with it</em></p>
<h4>Edit Preset</h4>
<h5>Change values</h5>
<p><em>Change socket values, name from the active preset</em></p>
<h5>Add/Remove sockets</h5>
<p><em>Add or remove sockets from the active preset. Adding has the same <code>Non-shift</code>`Shift` behaviour when saving presets</em></p>
<h4>Copy/Paste Preset to/from clipboard</h4>
<p><em>You can copy/paste presets from different nodegroups, even if they are in different files! Under the hood it copies a JSON dictionary to the clipboard.</em></p>
<h2>Caveats</h2>
<h4>Unique Path [panel name + socket name]</h4>
<p><em>It will only work properly if all socket paths (panel name + socket name) are unique. Meaning, sockets can have the same name as long as they are not in the same panel (base level included).</em></p>
<h4>Same socket type</h4>
<p><em>If socket name changes to a non convertable type, it will ignore it. To make it work again, remove said socket and add it back (update not resolving it automatically seems like a safer option)</em></p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}