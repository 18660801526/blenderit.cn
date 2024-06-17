---
title: "Node Group Utilities"
description: "Extra options and functions for node groups"
summary: "Extra options and functions for node groups"
date: 2024-03-17 00:00:00
updated: 2024-03-17 00:00:00
author: blenderit
tags: 
    - Node
    - Material
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/default.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/node-group-utilities/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p><a rel="nofollow noopener noreferrer external" target="_blank" href="https://youtu.be/7NJOvjT5w_I"><code>WATCH VIDEO DEMO</code></a></p>
<p><strong>This add-on enhances the functionality of node groups within Blender's node editor, providing additional options and functionality to streamline your workflow and improve efficiency when working with node-based materials, geometries, and compositing setups.</strong></p>
<hr>
<h2>Features</h2>
<p><strong>Set Default Values:</strong> With this feature, you can set the default values of the selected node group to match the current values of its input sockets. It simplifies the process of defining default settings for your node groups, ensuring a consistent starting point whenever you use them. This is particularly useful when you have complex node setups and want to save time setting the default value of each input socket one by one.</p>
<p><strong>Reset to Default Values:</strong> This option allows you to reset the values of the input sockets of the selected node group to their default values. It provides a quick way to revert back to the original settings, making it easier to experiment and iterate on your node group configurations.</p>
<p><strong>Add Socket Maker:</strong> Some socket types can't be directly added to shadee node groups in Blender,  however some of them might be useful, like the Integer, Boolean or String sockets. With Node Group Utilities you can add a node called "Socket Maker"  from the "Add" menu. This acts as a dummy node with various socket types. To create a custom input socket in your node group, simply connect the "Group Input" node to the desired socket from the Socket Maker.</p>
<p><strong>Add Labels:</strong> In Blender versions before 4.0, the node group panels feature was not available. Node Group Utilities provides a workaround for organizing sockets in these older versions. You can select the desired node group, access the right-click menu, and choose "Add Label". This allows you to add a label directly to the node group, making it easier to organize properties clearly</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}