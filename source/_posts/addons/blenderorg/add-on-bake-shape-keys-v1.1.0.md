---
title: "Bake Shape Keys"
description: "Feature-set for shape keys and shape key animations"
summary: "Feature-set for shape keys and shape key animations"
date: 2024-06-23 08:54:21
updated: 2024-06-23 08:54:21
author: blenderit
tags: 
    - Animation
    - Mesh
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-bake-shape-keys-v1.1.0.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/bake-shape-keys/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <p>Bake Shape Keys is for people who are working with shape keys and shape key animations. It allows you to duplicate, merge, and split shape keys; bake shape key actions with correct interpolation, step, and frame rate, as well as more advanced features, all with a single click.</p>
<p>The purpose of the add-on is to automate and enhance Blender's shape key workflow so that animators can focus the entirety of their time animating. Originally add-on was developed for stop-motion production, so it's equipped with tools for creating and managing 3D printable replacement parts for puppets.</p>
<p>But its general shape key features (duplicating, splitting, and merging shape keys) are useful for modelers and sculptors as well since it allows you to use shape keys more non-destructively.</p>
<p><strong>Features of the add-on include:</strong></p>
<ol>
<li><strong>Insert Keyframe for All Shape Keys</strong></li>
</ol>
<p>Studio experience showed us that keyframing all shape key values is important to avoid unplanned changes in facial animation and doing it manually could be a painstaking process. We added this simple feature to do it with a single click.</p>
<p><img src="https://d1231c29xbpffx.cloudfront.net/cache/01bd08491845fadf234ab957b2b726a8.gif" alt="Keyframe all Shape Keys operator." title="Keyframe all Shape Keys operator in action."></p>
<ol start="2">
<li><strong>Bake Shape Key Action</strong></li>
</ol>
<p>Works similarly to Blender's default Bake Action (which doesn't support shape key animations). This operator looks through the entire shape key animation and keyframes the values for all shape keys on each frame. This feature is extremely useful for both 3D and real-life stop-motion animations, where frame-by-frame changes and constant interpolation is a must.
Bake Shape Key Action has precise control over frame range, step, interpolation, and etc.</p>
<p><em>(By baking shape key animations, you can also get the keyframed spacing and turn them into 3D-printed replacement parts with the Objects from Shape Keys function.)</em></p>
<p><img src="https://d1231c29xbpffx.cloudfront.net/cache/ddcaa9d884291175ad019ee8e8637ded.gif" alt="Bake Shape Key Action operator." title="Bake Shape Key Action operator in action."></p>
<ol start="3">
<li><strong>Duplicate Shape Key</strong></li>
</ol>
<p>In shape key extras panel you'll see new operators that give you missing basic functionalities. You can backup your shape keys, or simply create duplicates. This operation (also Merge and Split) also retains the entire data and animation down to the last keyframe handle position, so you don't have to worry about anything.</p>
<ol start="4">
<li><strong>Split Shape Key</strong></li>
</ol>
<p>You can split shape keys in two (or more parts). Let's say you accidentally sculpted on eyebrows in your mouth shape key. Well, you can go into edit mode, select the top half of the face, click "Split Shape Key" and you'll get two shape keys! One for the selected vertices, and one for unselected.</p>
<p><em>Animation (and other data) will be duplicated on both of them</em></p>
<ol start="5">
<li><strong>Merge Shape Keys</strong></li>
</ol>
<p>Shape keys can be merged with each other, either two at a time or the entire stack if you wish. After merging shape keys will be deleted and replaced with new one that is a blend of both (or all) of them. This is extremely useful for organizational purposes, and also if you don't want to animate all shape keys separately and you wish to have only one f-curve.</p>
<p><em>If you want to keep animation remember that the newly created shape key inherits data from the active (highlighted) shape key</em></p>
<ol start="6">
<li><strong>Objects from Shape Keys</strong></li>
</ol>
<p>This feature is designed for 3D printing but can be used for various purposes. It bakes shape keys on every frame into a duplicated object. When you're done animating (e.g. facial expressions) you can turn them into replacement parts ready for 3D printing with a single click.</p>
<p><em>(This operator can also detect and delete duplicates. It looks through shape key values on every frame, keeps track of everything in .blend file and (optionally) will not create new objects if their exact duplicate already exists. This way you can avoid 3D printing, painting, and managing objects you don't really need.)</em></p>
<p><img src="https://d1231c29xbpffx.cloudfront.net/cache/00d7b89c0733b810bc565ff9c71f85d4.gif" alt="Objects from Shape Keys operator." title="Objects from Shape Keys operator in action."></p>
<p>Watch this <a rel="nofollow noopener noreferrer external" target="_blank" href="https://www.youtube.com/watch?v=Ry1qvOu9nxQ/">Blender Conference presentation</a> to better understand this concept.</p>
<hr>
<h3>Where is the add-on located inside Blender?</h3>
<p>Operators related to shape key animation can be found in the Object - Animation menu in object mode.</p>
<p>Tools related to shape key sculpting (duplicate, split, merge) are located in the Specials menu in the shape key panel in data properties (At the end of the panel you'll also see the "Keyframe All Shape Keys" operator if you more than 3 shape keys, but it can be removed from preferences).</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}