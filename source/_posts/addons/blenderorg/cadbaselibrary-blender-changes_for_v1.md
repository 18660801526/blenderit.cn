---
title: "CADBase Library"
description: "This is an addon for synchronizing local data with cloud storage"
summary: "This is an addon for synchronizing local data with cloud storage"
date: 2024-04-18 00:00:00
updated: 2024-04-18 00:00:00
author: blenderit
tags: 
    - Import-Export
    - User Interface
categories:
    - blenderorg
img: https://extensions.blender.org/media/thumbnails/39/397d3ce7f0fb2c97293fd39147d3c8626b899b4bd59e8614ea9357c3975769e1_640x360.webp
showGetMethod: false
copyright: 本插件资源来自官网插件库，遵循开源协议，可免费使用，版权归原作者所有！
source_link: https://extensions.blender.org/add-ons/cadbase-library/
---

{% raw %}
<section id="about" class="mt-3">
            <div class="box style-rich-text">
              <h1>Add-on CADBase Library</h1>
<p>This is an add-on for using components from CADBase in the Blender UI and synchronizing local library data with CADBase cloud storage.</p>
<p>CADBase is a platform for publishing and sharing information about 3D components (parts), drawings and manufacturers.</p>
<p><strong>Important Note:</strong>  To use the add-on, you must have an account on the <a rel="nofollow noopener noreferrer external" target="_blank" href="https://app.cadbase.rs">CADBase Platform</a>. You can also create an account via add-on, if the entered username is free, a new user will be created with the specified username and password.</p>
<h2>Description</h2>
<p>The add-on is designed to use components from CADBase in the Blender interface.<br>
Component modifications contain sets of files for various CAD systems. This add-on will work with data from the Blender set, without downloading documentation and data from other file sets.<br>
Files uploaded to file sets are versioned, allowing you to restore earlier versions, get the old state they were in before the changes, review the changes, and find out who last changed something and caused the problem.</p>
<h3>Dependencies</h3>
<p>This add-on requires no additional steps and will work without additional libraries. But will attempt to perform automatic dependency installation when installing the add-on.</p>
<h5>Installation Blake3</h5>
<p>When installing the add-on, the Blake3 library will be extracted to the site-packages directory of the add-on itself.</p>
<p><strong>Please Note:</strong> The add-on will work without this <em>Blake3</em> library, the only difference is that the files in the CADBase remote storage that have already been uploaded will not be replaced.</p>
<h3>Settings</h3>
<h4>Configuration CADBase Library</h4>
<p>First you need to set the library location. CADBase remote storage will be synchronized with this location. Also there will storage files with technical data for add-on.<br>
This location can be changed in the add-on settings in the field <em>Library path</em>.</p>
<h4>Getting an authorization token</h4>
<p>On the CADBase Library card in the <strong>Add-ons</strong> section of the Blender “Preferences...” there are <strong>username</strong> and <strong>password</strong> fields.<br>
To obtain a token for an existing account or create a new account to access CADBase, you must provide a <strong>username</strong> and <strong>password</strong>. This data will be saved and available after restarting Blender.<br>
After entering these data to receive the token and pressing the <strong>Login</strong> button. Please wait until you receive the token.</p>
<p><strong>Important Note:</strong>  If the access token has expired, you need to repeat the steps above.</p>
<h5>Alternatively</h5>
<p>The disadvantage (or advantage) of this option is that it only saves changes until Blender restarts. After a new startup, Blender restores the data if it is set in the Add-ons Manager.<br>
In the <em>CADBase Library</em> window, click the <strong>Authorization</strong> button.<br>
When the <em>Authorization on CADBase platform</em> window opens, you need to set a <strong>username</strong> and <strong>password</strong> in order to access CADBase.<br>
After entering these data to receive the token and pressing the <strong>OK</strong> button. Please wait until you receive the token.</p>
<h3>First start</h3>
<p>Once installed, the add-on will be available in the <strong>3D View</strong> &gt; <strong>Sidebar menu</strong>.<br>
Select the <strong>CADBase Library</strong> add-on in the <strong>Import-Export</strong> category.</p>
<h3>Control</h3>
<p><code>Open</code> - open the next level (deeper). If a component of a list of user's favorite components is selected, it will open the list of modifications for that component; if a modification of a component modifications list is selected, it will open a set of files for Blender.</p>
<p><code>Go back</code> - return to the previous level (higher). If a set of files is open, the button opens a list of modifications of a component; if a list of modifications of a component is open, the button opens a list of a user's favorite component.</p>
<p><code>Pull (data)</code> - retrieves data from the remote server and updates the local library view.</p>
<p><code>Add component</code> - the button opens a modal window in which ability create a new component (part, project, etc.) with a given name.</p>
<p><code>Link file</code> - link creates a reference to the data in the source file such that changes made there will be reflected in the referencing file the next time it is reloaded.</p>
<p><code>Push (data)</code> - button to upload files from Blender folder (set of files for Blender) of local library to CADBase storage. Before uploading, the hash of existing files in local and remote storage is checked, if they are different, the files in remote storage are updated. The Blake3 library is used to calculate the hash, if it is not available, the hash is not checked and existing files in the remote storage are not updated.</p>
<p><code>Settings</code> - this button opens a modal window where you can specify the path to the local library, where the files received from CADBase will be stored, and the address of CADBase server.</p>
<p><code>Authorization</code> - this button opens a modal window where you can specify login and password from CADBase profile to get a new authorization token. This action must be repeated if the access token is revoked or expired.</p>
<p><em>Changes made through Settings and Authorization will be reset when Blender restarts. For changes to be saved after restarting Blender, they must be made via Add-ons in Preferences...</em></p>
<h2>Usage</h2>
<p>Create new components with the add-on and add target components to bookmarks (favorites) on CADBase website.<br>
In Blender will only display components that the user has bookmarked on CADBase platform, as well as those that have been previously downloaded.</p>
<h3>CADBase Library Browser</h3>
<p>Favorite components are displayed at root level. After selecting and opening a component, a list of its modifications is displayed this Component level. These levels correspond to the location of folders in the directory that is specified in the <code>Library path</code> property.
When you open a modification (modification level), it actually displays files from the Blender file set that is in the Blender folder, not directly in the modification folder.
Files for Blender will be downloaded through this add-on, files from kits for other programs will not be downloaded.</p>
<p>The data display can be divided into three levels, the first one is the root level (<strong>rl</strong>), this level displays all components from the local library, the second one is the component level (<strong>cl</strong>), it displays the list of modifications of the open component, and the third level displays the data of a set of files (<strong>fl</strong>). The folder for Blender file set in local storage is created regardless of the presence of file set in the modification on CADBase platform, the file set will be created automatically when sending files.</p>
<pre><code>-Library path                       # set in add-on (rl)
├── Vertical Pump (@lookme)         # component folder (cl)
│   ├── N1                          # modification folder
│   │   ├── Blender                 # Blender fileset (fl)
│   │   │   ├── modification        # technical data file
│   │   │   ├── vertical Pump.blend # file of the Blender fileset
│   │   │   └── ...                 # files of the Blender fileset
│   │   ├── FreeCAD                 # example file set (fl)
│   │   └── ...                     # other filesets (fl)
│   ├── ...                         # other modifications
│   └── component                   # technical data file
├── ...                             # other components (rl)
├── cadbase_file_2018.log           # stores logs and responses
└── cadbase_file_2018               # technical data file
</code></pre>
<h3>Getting data</h3>
<p>To get the data, click on the <strong>Pull (data)</strong> button. Depending on the open position (directory), this will start the process of retrieving a list of the user's favorite components, a list of component modifications, or downloading files from the file set of the selected component modification for Blender.</p>
<h3>Sending data</h3>
<p>Open the modification from which you want to upload the files.<br>
Click the <strong>Push (data)</strong> button to upload the local files for the set of component modification files to CADBase storage (remote storage).<br>
Information about the upload process will be displayed in the Blender report.<br>
After uploading the files, a message will be displayed in the Blender report with information about the number of successfully uploaded files.</p>
<h2>Additional Information</h2>
<h5>Add-on settings</h5>
<p>The add-on's settings, such as the local library path, server (API Point) address, and access token, are stored in the Blender user settings file (<code>userpref.blend</code>), which is located at the path <code>bpy.utils.resource_path('USER')/config</code>.</p>
<h5>Used (reserved) names in the add-on</h5>
<p>Please don't use <code>cadbase_file_2018</code> and <code>cadbase_file_2018.log</code> as file or folder names in the library path folder. These files store server responses and logs, if you use these filenames for your data, you may lose them.<br>
If you need to save logs to a file (for example, for debugging, study, or other purposes), you need to create a <em>cadbase_file_2018.log</em> file in your local library folder.</p>
<p>In component folders, a <code>component</code> file is created with the technical data about the component.<br>
In fileset folders, a <code>modification</code> file is created with the technical data about the component modification and fileset.</p>
<h5>How the add-on work with data</h5>
<p>To avoid losing local data when downloading from CADBase storage (from remote storage), files already in local storage are skipped.<br>
Before uploading files to CADBase storage (remote storage), the add-on checks for existing files in the remote storage and excludes files from the upload list if their local and remote storage hashes match. A hash is calculated using the Blake3 library.<br>
This check is skipped and previously uploaded files (already in remote storage) are not updated unless the Blake3 library is installed.</p>

            </div>
          </section>
<div style="display: none">blenderorg</div>
{% endraw %}