---
title: "Node Annotator"
description: "Easily create good documentation of your node trees"
summary: "Easily create good documentation of your node trees"
date: 2024-05-22 00:00:00
updated: 2024-05-22 00:00:00
author: blenderit
tags: 
    - Node
    - Geometry Nodes
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/node_annotator.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/node-annotator/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h1>Node Annotator</h1>
<p>A utility add-on, that eases documenting and maintaining node graphs. It supports easy one-click creation and editing of
annotation frames with text blocks. On the side panel of any graph editor, this add-on creates a new section "Node
annotator" within the Node tab.</p>
<h2>Annotation section</h2>
<h3>Description</h3>
<p>A convenience edit field for the newly introduced Blender 4.2 property for the node group's tool-tip. This property is
usually found on the Group tab. The add-on paints a small info icon into the header of node groups, that have a
description and thus a tooltip. This behavior can be turned off in the preferences.</p>
<h3>Create annotation</h3>
<p>This command creates a new yellow annotation box in the current node graph in the middle of the view. It also creates a
new text block and associates it with the annotation. As a last step it opens a new window with the text editor to enter
the annotation text.</p>
<h3>Edit annotation</h3>
<p>The edit annotation command opens a new window with the text editor to edit the selected annotation text.</p>
<h2>Refactoring section</h2>
<p>The refactoring section can be used to find usages of custom node groups within the graph.</p>
<h3>Search type</h3>
<p>A drop down box, that allows to specify which node groups to search within the currently edited node tree.</p>
<h3>Replacement type</h3>
<p>A similar drop down box, but this one specifies the type of the node group to use for replacing a found node.</p>
<h3>Search subgroup</h3>
<p>Starts the search and lists the results in the list box below. Every entry has 2 buttons, one to replace the found node
with the "Replacement type" and one to jump to that node.</p>
<h3>Replace all</h3>
<p>This button refactors all occurrences of the search type to the replacement type.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}