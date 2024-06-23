---
title: "Delete Line Shortcut"
description: "Shortcut to delete a line and copy its content"
summary: "Shortcut to delete a line and copy its content"
date: 2024-03-21 00:00:00
updated: 2024-03-21 00:00:00
author: blenderit
tags: 
    - User Interface
    - Text Editor
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/delete-line-addon.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/delete-line-shortcut/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h1>Delete line</h1>
<p><strong>Adds missing shortcut for deleting the line</strong> which behaves just like in the VS Code. So you can paste it afterwards.</p>
<hr>
<h3>Description</h3>
<p>A small addon that adds the funcionality of deleting the current line in the text editor.  And it is also cuting the content into the clipboard. This means you can then paste the deleted line wherever you want.</p>
<p>You do not need to select anything. Just press <code>CTRL + SHIFT + BACKSPACE</code> while in the text editor on some line. The shortcut can be changed in the preferences.</p>
<h3>How it works?</h3>
<p>The shortcut is then editable in the Blenders settings: "Edit &gt; Preferences &gt; Keymap &gt; Text &gt; Text global &gt; Delete line". The way it works is mostly using Blenders built in functions:</p>
<ol>
<li><p>Adding newline character to the current line.</p>
</li>
<li><p>Selecting the whole line.</p>
</li>
<li><p>Cutting the selected content.</p>
</li>
<li><p>Deleting the remaining newline character.</p>
</li>
</ol>
<hr>
<p><strong>Video:</strong>
Video showcase on <a rel="nofollow noopener noreferrer external" target="_blank" href="https://www.youtube.com/watch?v=-JpoWFsWgH4">youtube</a>.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}