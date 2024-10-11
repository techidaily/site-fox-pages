---
title: Effective Strategies for Building a Powerful Organizational Website
date: 2024-10-10T05:01:51.573Z
updated: 2024-10-11T07:05:01.341Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Effective Strategies for Building a Powerful Organizational Website
thumbnail: https://thmb.techidaily.com/19ce8481b5575ff1faf6716113cc99f8aa092b92d7c87ab230819ca4dc98d6d3.jpg
---

## Effective Strategies for Building a Powerful Organizational Website

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Organization](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Search Pane](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Feature Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Component Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Feature Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Builds](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Analytics](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [SCCM](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ActiveSync](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Organization Page

Windows Installer organizes a product in features and components. A feature is a set of components that are installed together. A component is a piece of the product to be installed and it is the smallest piece of a product that Windows Installer can install.

![Organization page](https://cdn.advancedinstaller.com/img/ui/organization-page.png "Organization page")  

This page allows you to create new features and to select which components belong to a feature. In the left pane there is a tree that hierarchically displays the product's organization. On the first level of the hierarchy there are the features. A feature can contain sub-features and components. A component is made of resources. A resource can be a file, a folder, a registry key or value, a data source, a shortcut, an extension, an environment variable, a service installation, a service operation, an ODBC driver or an ODBC translator. 

Every component has a key resource that can be only a file, a folder, a registry key or value or a data source. The resources are displayed under their component. The key resources are displayed with a key overlaid over the resource's usual image. During an installation Windows Installer decides which features to install along with all the sub-features and the components of the selected features. When a component is installed, all the resources of that component are installed (and only then).

### Organizing components

The components in an Advanced Installer project are created by following the Windows Installer rules and best practices. Therefore, you should follow these rules when reorganizing your installation package:

* Never create two components that install a resource under the same name and target location.
* Two components must not have the same key path file.
* Do not create components containing resources that will need to be installed into more than one directory on the user's system.
* Do not include more than one COM server per component.
* Do not specify more than one file per component as a target for the Start menu or a Desktop shortcut.
* Define a new component for every .exe, .dll, and .ocx file and designate these files as the key path files of their components.
* Define a new component for every .hlp or .chm help file and designate these files as the key path files of their components.
* Define a new component for every file that serves as a target of a shortcut and designate these files as the key path files of their components.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Creating components which don't respect these rules may result in an installation package which doesn't work correctly.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Creating new features

![New Feature](https://cdn.advancedinstaller.com/img/toolbar/feature-new.png "New Feature") Use the \[New Feature \] toolbar button, the “New Feature” tree context menu item or press the Insert key while the “Features And Components” panel is focused. The new feature will be added after the last sub-feature of the selected feature. The feature will get a default name, which you can edit anytime. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)When a new component is created and there is no feature in the project, a new feature, named "MainFeature" will be automatically created. Also when you create a feature from this page and there is no other feature in the project, that feature will also get the name "Main Feature". All the components will be added by default in the "Current Feature".

### Renaming a feature

 Use the “Rename” tree context menu item or press the F2 key while a feature is selected. Only the features names can be edited. 

### Renaming a component

 Use the “Rename” tree context menu item or press the F2 key while a component is selected. This identifier is used in conditions to refer to the installed state or the action state of a component.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)When changing the name of a component, all the conditions that refer to this identifier must be updated accordingly.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Moving a feature up, down, left or right

 Use the “Move Up”, “Move Down”, “Move Left” or “Move Right” tree context menu items or press Shift + Up, Shift + Down, Shift + Left or Shift + Right. When moving to the left, the feature will be moved after the last feature of its parent feature. When moving to the right, the feature will be moved after the last feature of the feature before it. You can also move features and components by drag and drop. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)A feature's position among its siblings is important because at install time, in the Customize dialog, the features will be displayed in the order they appear in the left tree.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915805/19272" target="_top" id="1915805">
  <img src="//a.impactradius-go.com/display-ad/19272-1915805" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915805/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Setting the Current Feature

 Use the “Set As Current” tree context menu item. The Current Feature will be displayed in **bold** text. Newly created components for various resources (files, registry keys, etc.) will always be added to the Current Feature. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)You can also set the Current Feature using the drop-down list box in the toolbar of the Component-producing pages.

### Moving a component between features

 Drag and drop the component to the new feature. 

### Moving resources between components

Use the drag and drop to move the resources (file, registry or data source etc) between components.

When moving resources between components the following restrictions must be taken into consideration:

* The files that are target for Service Installs, File Associations or Advertised Shortcuts, are made key members and cannot be moved into a new component.
* The files of CHI or CNT type cannot be moved. (they follow automatically the component of the corresponding CHM and HLP files)
* If a resource is the only one from the component that can be a key member(e.g. files) and the rest of the resources in the component cannot be key members(e.g. Environments),then the file cannot be moved.
* Resources can only be moved between components if they have the same Directory attribute.
* All the files related to a Java Product cannot be moved because they must be attached to the Java Product file.

### Moving a resource to a new component

Use the "Move To New Component" tree context menu item. The current resource will be moved into a newly created component, in the same feature.

### Setting a resource as Key Member

Use the "Make Key Member" tree context menu item.

### Locating a resource

 Use the “Go To Resource” context menu item or press the F8 key on a selected resource. This command will activate the appropriate page and will select the tree or list item corresponding to the resource.

### Sharing a component

 Drag and drop the component to a new feature while theShift key is pressed, use the “Share” context menu or ribbon button. The component will be present under both features. 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Sharing a feature

Drag and drop the feature to a new feature, while theShift key is pressed. All the components of the dragged feature will be present under both features.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948909/19272" target="_top" id="1948909">
  <img src="//a.impactradius-go.com/display-ad/19272-1948909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding resources to the search list

Use the “Add to list” context menu item or press theF4 key while a tree item is selected.

Use the “Add Children to List” option or press theShift + F4 key to add all the item's children to the list.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing features and shared components

![Remove Feature](https://cdn.advancedinstaller.com/img/toolbar/remove.png "Remove Feature") Use the\[Delete \] toolbar button, the “Delete” tree context menu item or press the Delete key while a feature or component is selected. 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068432/7443" target="_top" id="2068432">
  <img src="//a.impactradius-go.com/display-ad/7443-2068432" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068432/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)A feature must be empty before you can remove it. A regular component cannot be removed, only a shared one. 

### Searching for a feature, component or resource

![Find](https://cdn.advancedinstaller.com/img/ui/search-icons/magnifier.png "Find") Type the label text that you want to search in the top right corner edit box. Press theEnter key to trigger the search.

![Find Next](https://cdn.advancedinstaller.com/img/ui/search-icons/down.png "Find Next") To search for the next value use the _Find Next_ button or press theF3 key. The search results are displayed in the[Search Pane](https://tools.techidaily.com/advancedinstaller/products/).

![Find and Append](https://cdn.advancedinstaller.com/img/ui/search-icons/plus.png "Find and Append") Use the_Find and Append_ button to append the search results to the search pane list.

If you want to search for the whole word you must enclose the string from the combo in quotes (").

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The search is case insensitive.

## Topics

* [Search Pane](https://tools.techidaily.com/advancedinstaller/products/)  
Contains the results of the search.
* [Feature Properties](https://tools.techidaily.com/advancedinstaller/products/)  
Setting a Feature's properties in Advanced Installer.
* [Component Properties](https://tools.techidaily.com/advancedinstaller/products/)  
Setting a Component's properties in Advanced Installer.
* [Feature Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
The "Feature Picker" dialog

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-iconic-trailer-highlight-assortment/"><u>[New] 2024 Approved Iconic Trailer Highlight Assortment</u></a></li>
<li><a href="https://article-files.techidaily.com/new-advanced-techniques-for-bio-linking-on-tiktok/"><u>[New] Advanced Techniques for Bio Linking on TikTok</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-step-up-your-game-mastering-the-art-of-capturing-playthroughs/"><u>[Updated] In 2024, Step Up Your Game Mastering the Art of Capturing Playthroughs</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-youtubes-elite-gear-top-5-video-chat-headsets/"><u>[Updated] In 2024, YouTube's Elite Gear Top 5 Video Chat Headsets</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-shambling-successes-the-cutthroat-list-of-best-zombies-gaming-for-2024/"><u>[Updated] Shambling Successes The Cutthroat List of Best Zombies Gaming for 2024</u></a></li>
<li><a href="https://fox-pages.techidaily.com/8-edition/"><u>8 Edition</u></a></li>
<li><a href="https://fox-pages.techidaily.com/event-management-techniques-mastering-control-and-coordination/"><u>Event Management Techniques: Mastering Control and Coordination</u></a></li>
<li><a href="https://fox-pages.techidaily.com/expert-tips-for-professional-gopro-film-cuts-and-editing-techniques/"><u>Expert Tips for Professional GoPro Film Cuts and Editing Techniques</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015953568-modern-warfare-voice-chat-problems-here-are-the-solutions/"><u>Modern Warfare Voice Chat Problems? Here Are the Solutions</u></a></li>
<li><a href="https://fox-pages.techidaily.com/recognizing-and-avoiding-counterfeit-apple-id-fraud-insights-from-malwarefox/"><u>Recognizing and Avoiding Counterfeit Apple ID Fraud: Insights From MalwareFox</u></a></li>
</ul></div>

