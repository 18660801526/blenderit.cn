---
title: "Sync | Lock Viewport"
description: "Sync multiple viewports at once in real-time"
summary: "Sync multiple viewports at once in real-time"
date: 2024-06-21 00:00:00
updated: 2024-06-21 00:00:00
author: blenderit
tags: 
    - 3D View
categories:
    - blenderorg
img: https://blenderit.cn/images/addons/blenderorg/add-on-k-tools-view-sync-v1.0.5.png
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/k-tools-view-sync/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h1><strong>The Addon:</strong></h1>
<p>With this addon, you will be able to sync all your viewports at once without use the 'Lock Camera to View' Technic. This is useful for keeping both Rendered View and Clay View in sync when checking your scene or locking the view rotation to avoid unwanted misclicks.</p>
<blockquote>
<h2><strong>Notes:</strong></h2>
<p>Active Viewport: Means The viewport you are currently working on and/or the viewport &gt; where the option is enabled.</p>
</blockquote>
<h2><strong>Features</strong></h2>
<ul>
<li><p><strong>Match View:</strong> Match all viewports based on the active one with a single click.</p>
</li>
<li><p><strong>Clip Start | End:</strong> Default Blender view clipping - "Clip Start/End adjusts the minimum and maximum distance range to limit the visible range to the area between two planes that are orthogonal to the viewing direction of the viewport camera. Objects outside this range will not be shown." - Blender Manual*</p>
</li>
<li><p><strong>Focal Length:</strong> Blender's default option - "Control the focal length of the 3D Viewport camera in millimeters, unlike a rendering camera." Blender Manual*</p>
</li>
<li><p><strong>Lock View Rotation:</strong> Prevents rotation of the view camera.</p>
</li>
<li><p><strong>Active:</strong> Locks the active viewport.</p>
</li>
<li><p><strong>Except Active:</strong> Locks all viewport rotations except for the active viewport.</p>
</li>
<li><p><strong>Continuous Sync:</strong> When enabled, it shows two new buttons.</p>
</li>
</ul>
<h2><strong>Synchronization:</strong></h2>
<ul>
<li><p><strong>Sync Interval:</strong> The time interval (in seconds) for synchronization updates; lower values mean faster updates.</p>
</li>
<li><p><strong>Start Sync:</strong> Click to start real-time view camera synchronization.</p>
</li>
</ul>
<h2><strong>Options</strong> (Subpanel):</h2>
<p>These options control what will be updated.</p>
<ul>
<li><p><strong>View Distance:</strong> Updates camera distance when true.</p>
</li>
<li><p><strong>View Location:</strong> Updates camera location when true.</p>
</li>
<li><p><strong>View Rotation:</strong> Updates camera rotation when true.</p>
</li>
<li><p><strong>Camera Zoom:</strong> Updates camera zoom when true.</p>
</li>
<li><p><strong>Camera Offset:</strong> Updates camera offset when true.</p>
</li>
<li><p><strong>View Perspective:</strong> Updates view perspective when true.</p>
</li>
<li><p><strong>Clip Start:</strong> Updates view clipping start when true.</p>
</li>
<li><p><strong>Clip End:</strong> Updates view clipping end when true.</p>
</li>
<li><p><strong>Focal Length:</strong> Updates focal length when true.</p>
</li>
<li><p><strong>All Windows:</strong> Updates occur in all windows when true.</p>
</li>
<li><p><strong>Adjust View Distance:</strong> A multiplier for the view distance. Depending on the viewport size, the image might look far away. This option allows the non-active view to be closer to the object. Lower values bring the view closer to the objects.</p>
</li>
</ul>
<blockquote>
<p><strong>Known Issues:</strong>
When 'Continuous Sync' is on, the Move, Rotate, and Scale gizmos might not work properly at times. However, these functions will work correctly if used via the G, R, and S keys. This bug will be addressed in the next release.</p>
</blockquote>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}