---
title: "Keymesh"
description: "Create stop-motion animations by sculpting frame-by-frame"
summary: "Create stop-motion animations by sculpting frame-by-frame"
date: 2024-05-22 00:00:00
updated: 2024-05-22 00:00:00
author: blenderit
tags: 
    - Animation
    - Sculpt
    - Mesh
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/keymesh.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/keymesh/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <ul>
<li><em>Complete rewrite and revival of iconic Keymesh add-on by Pablo Dobarro, one of the creators of modern sculpt mode. Add-on also includes updates from Aldrin Mathew. Original testing and images/videos by Daniel Martinez Lara</em></li>
</ul>
<p>With Keymesh, you can create stop-motion-like animations inside Blender in a very traditional way. Keymesh makes it possible to swap object data between frames for almost every type of object. That means you can sculpt, model, groom, or paint frame-by-frame to craft beautiful (additive, destructive) animations!</p>
<p>This version of Keymesh has been updated to work on all types of objects so that you can animate flowing hair curves, floating volumes, text changing between frames, or vesimes (mouth-shapes, replacement parts) from curves so that you can animate stop-motion style lip-syncs in a matter of seconds! This implementation also intends to make Keymesh usable in a production environment, both for 3D and actual stop-motion studios.</p>
<h2>Features of the add-on include:</h2>
<ul>
<li><strong>Frame Picker</strong></li>
</ul>
<p>Keymesh has a Frame Picker UI that lists all versions (blocks) of objects you've made with Keymesh, lets you organize them and insert new keyframes for them easily, without having to duplicate keyframes in Dope Sheet. UI also displays how many times each block is used in the animation.</p>
<p><em>(Keymesh can also work as an object versioning add-on, so it is useful for modelers and sculptors too. Internally it works by saving multiple versions of the object data (e.g. Mesh, Curve), meaning you can save, for example, different layers of your sculpting, and different variants of the model you can't decide between. And you can put them on the timeline, scrub, and see all versions of your object in succession!)</em></p>
<hr>
<ul>
<li><strong>Append, Link, and Library Overrides!</strong></li>
</ul>
<p>Keymesh objects can be appended or linked in your scene files. On linked objects all operators except previewing are disabled, but you can make library override, assign it a new local action, and create new animations by placing existing blocks in the timeline. You can't change Keymesh blocks, or create new ones in the scene file, but in the original file you can, and when you refresh your scene file new blocks will be available for linked &amp; overridden objects in Frame Picker, ready to be animated!</p>
<p>This allows you to have “replacement parts workflow”, in which you create all the frames/blocks you’re gonna need beforehand in the object file, and in your scene file you arrange those blocks to animate switching between them. Exactly how the replacement parts method works in real stop-motion productions.</p>
<p><em>(IMPORTANT: Don't forget to disable "Instance Object Data" option in File Browser when you're appending or linking Keymesh object)</em></p>
<hr>
<ul>
<li><strong>Render Farm Support</strong></li>
</ul>
<p>You can bake your Keymesh animation so that it can be sent to the render farm where Keymesh isn't installed. For every Keymesh block, "Convert to Separate Objects" operator (set to Rendering workflow) creates a new object and animates its visibility, so in the end animation looks exactly the same, but instead of Keymesh blocks it shows separate objects. Operator isn't destructive, so you can just delete the collection and run the operator again when you make changes to your animation.</p>
<hr>
<ul>
<li><strong>3D Printing Replacement Parts</strong></li>
</ul>
<p>Operator that turns Keymesh animation into separate objects. A new object will be created for each animated frame and lined up in your scene, ready to be exported and printed. This tool is for people who want to use Keymesh for real-life stop-motion productions by 3D printing animated parts for each frame and using them as replacement parts. Operator can also delete duplicates, so that you never print same thing twice.</p>
<p><em><a rel="nofollow noopener noreferrer external" target="_blank" href="https://www.youtube.com/watch?v=Ry1qvOu9nxQ">(See this Blender Conference presentation about how this feature is used in stop-motion production)</a></em></p>
<hr>
<ul>
<li><strong>Shape Keys to Keymesh</strong></li>
</ul>
<p>Destructive operator that lets you convert shape key animations into Keymesh. Shape keys are removed and instead sculpted animation is baked into Keymesh frames. That means you can combine 3D animation workflow with traditional stop-motion, by doing "Keymesh passes" after you're done with shape keys, and want sculpt details on individual frames.</p>
<hr>
<ul>
<li><strong>And many more on the way!</strong></li>
</ul>
<p>-- PageUp and PageDown (with and without Ctrl) are default shortcuts for inserting new keyframes and jumping in timeline.
-- You can customize your UI and workflow by changing preferences and even enable experimental features if you're feeling risky.</p>
<hr>
<p>This version of the add-on is being developed for a stop-motion animation studio and will receive future updates with new features and improvements. If you want to help out, suggest new features, or report bugs you can reach out at Blender Artists or Github links provided.</p>
<p>We encourage you to share the work that you make with Keymesh with us! You can help by spreading information about the add-on. If you want to make a video tutorial using/about Keymesh you can do so without having to ask, but feel free to contact if you need any help.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}