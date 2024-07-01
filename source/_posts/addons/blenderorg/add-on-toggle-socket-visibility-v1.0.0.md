---
title: "Toggle Socket Visibility"
description: "Control which node sockets are visible or not via panel/pop-up"
summary: "Control which node sockets are visible or not via panel/pop-up"
date: 2024-06-22 00:00:00
updated: 2024-06-22 00:00:00
author: blenderit
tags: 
    - Node
    - User Interface
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-toggle-socket-visibility-v1.0.0.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/toggle-socket-visibility/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h2>Features</h2>
<hr>
<p>This addon presents two ways to configure the visibility of node sockets:</p>
<ul>
<li><strong>Sidebar Panel</strong> - A collapsible panel that appears in the N-Panel sidebar.</li>
<li><strong>Pop-up</strong> - A pop-up that can be called via hotkey.</li>
</ul>
<p>These panels list out all the available input &amp; output sockets in the active node.
Depending on the state of the socket, a specific icon is displayed alongside their name:</p>
<ul>
<li><strong>Checkbox</strong> - Denotes whether or not the socket is visible, clicking on this toggles between the hidden/visible state.</li>
<li><strong>Chain</strong> - Socket is linked to something else and its visibility couldn't be edited.</li>
<li><strong>Lock</strong> - Socket's visibility is read-only and is always uneditable.<ul>
<li><em>(Note: This currently only applies to Reroutes)</em></li>
</ul>
</li>
</ul>
<h2>Preferences</h2>
<hr>
<h4>Panel Settings</h4>
<ul>
<li><strong>Orientation</strong> - Specifies in what way the input &amp; output columns will be display.<ul>
<li><em>Options: Automatic, Horizontal, Vertical</em></li>
<li><em>Default Value: Automatic</em></li>
</ul>
</li>
<li><strong>Location</strong> - Specifies which category in the N-Panel sidebar the "Socket Visibility" panel will be placed in. <em>(Note: This is case-sensitive.)</em><ul>
<li><em>Default Value: "View"</em></li>
</ul>
</li>
</ul>
<h4>Pop-up Settings</h4>
<ul>
<li><strong>Width</strong> - Specifies the width of the pop-up panel.<ul>
<li><em>Default Value: 175</em></li>
</ul>
</li>
</ul>
<h4>Keymap List</h4>
<ul>
<li><strong>Call Socket Visibility Pop-up</strong> - Hotkey that calls the pop-up when pressed.<ul>
<li><em>Default Value: Not set to anything.</em></li>
</ul>
</li>
</ul>
<h2>Known Limitations</h2>
<hr>
<ul>
<li>Drawing of sub-panels is not yet supported, inputs &amp; outputs are displayed in a flat list.</li>
</ul>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}