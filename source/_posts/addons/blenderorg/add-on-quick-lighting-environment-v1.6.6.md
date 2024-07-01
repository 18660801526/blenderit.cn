---
title: "Quick Lighting Environment"
description: "Adds a Basic Lighting Setup to Your Blender Scene"
summary: "Adds a Basic Lighting Setup to Your Blender Scene"
date: 2024-05-19 00:00:00
updated: 2024-05-19 00:00:00
author: blenderit
tags: 
    - Lighting
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-quick-lighting-environment-v1.6.6.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/quick-lighting-environment/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p><strong>QLE</strong> is a Blender 4.2+ add-on that installs a panel named <strong>Quick Lighting Environment</strong> under <code>Properties &gt; Scene</code>.</p>
<hr>
<p>Click <strong>Add Environment</strong> to:</p>
<ul>
<li>Create a <strong>World</strong> named "QLE World" with <code>World &gt; Surface</code> strength set to <code>0.25</code> and a <code>Blackbody</code> value of <code>5454</code>.</li>
<li>Create four positioned <strong>Area Lights</strong> with <code>Blackbody</code> values of <code>3800</code> (Area_Left, orange tint), <code>5454</code> (Area_Fill and Area_Back, equal energy), and <code>20,000</code> (Area_Right, blue tint, or at least as blue as a blackbody light gets).</li>
<li>Create an <strong>Empty</strong> named "Lights_Target" and connects all Lights to it with <code>Track To Object</code> Constraints.</li>
<li>Add a <strong>Mesh</strong> Object named "Backdrop".</li>
<li>If you disconnect/delete a Light, the Backdrop, or the Empty, clicking <strong>Add Environment</strong> re-inserts the missing object or constraint back into your scene.</li>
</ul>
<p>Click <strong>Clear Environment</strong> to:</p>
<ul>
<li>Purge QLE Lights, Backdrop, and Empty from scene, and reset the World from "QLE World" back to the original.</li>
</ul>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}