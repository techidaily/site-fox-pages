---
title: Effective Strategies for Building a Powerful Organizational Website
date: 2024-09-30T20:17:36.935Z
updated: 2024-10-05T21:54:59.818Z
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
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Creating new features

![New Feature](https://cdn.advancedinstaller.com/img/toolbar/feature-new.png "New Feature") Use the \[New Feature \] toolbar button, the “New Feature” tree context menu item or press the Insert key while the “Features And Components” panel is focused. The new feature will be added after the last sub-feature of the selected feature. The feature will get a default name, which you can edit anytime. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)When a new component is created and there is no feature in the project, a new feature, named "MainFeature" will be automatically created. Also when you create a feature from this page and there is no other feature in the project, that feature will also get the name "Main Feature". All the components will be added by default in the "Current Feature".

### Renaming a feature

 Use the “Rename” tree context menu item or press the F2 key while a feature is selected. Only the features names can be edited. 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Renaming a component

 Use the “Rename” tree context menu item or press the F2 key while a component is selected. This identifier is used in conditions to refer to the installed state or the action state of a component.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)When changing the name of a component, all the conditions that refer to this identifier must be updated accordingly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Moving a feature up, down, left or right

 Use the “Move Up”, “Move Down”, “Move Left” or “Move Right” tree context menu items or press Shift + Up, Shift + Down, Shift + Left or Shift + Right. When moving to the left, the feature will be moved after the last feature of its parent feature. When moving to the right, the feature will be moved after the last feature of the feature before it. You can also move features and components by drag and drop. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)A feature's position among its siblings is important because at install time, in the Customize dialog, the features will be displayed in the order they appear in the left tree.

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
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

### Sharing a feature

Drag and drop the feature to a new feature, while theShift key is pressed. All the components of the dragged feature will be present under both features.

### Adding resources to the search list

Use the “Add to list” context menu item or press theF4 key while a tree item is selected.

Use the “Add Children to List” option or press theShift + F4 key to add all the item's children to the list.

### Removing features and shared components

![Remove Feature](https://cdn.advancedinstaller.com/img/toolbar/remove.png "Remove Feature") Use the\[Delete \] toolbar button, the “Delete” tree context menu item or press the Delete key while a feature or component is selected. 

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)A feature must be empty before you can remove it. A regular component cannot be removed, only a shared one. 

### Searching for a feature, component or resource

![Find](https://cdn.advancedinstaller.com/img/ui/search-icons/magnifier.png "Find") Type the label text that you want to search in the top right corner edit box. Press theEnter key to trigger the search.

![Find Next](https://cdn.advancedinstaller.com/img/ui/search-icons/down.png "Find Next") To search for the next value use the _Find Next_ button or press theF3 key. The search results are displayed in the[Search Pane](https://tools.techidaily.com/advancedinstaller/products/).

![Find and Append](https://cdn.advancedinstaller.com/img/ui/search-icons/plus.png "Find and Append") Use the_Find and Append_ button to append the search results to the search pane list.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

If you want to search for the whole word you must enclose the string from the combo in quotes (").

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The search is case insensitive.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vp-tips.techidaily.com/new-finest-choices-free-streaming-tools-suitable-everywhere/"><u>[New] Finest Choices Free Streaming Tools Suitable Everywhere</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-quick-guide-to-the-ifunny-meme-application/"><u>[New] Quick Guide to the iFunny Meme Application</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-guide-to-thriving-as-a-digital-creator-for-2024/"><u>A Guide to Thriving as a Digital Creator for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/comprehensive-guide-to-sns-hdr-pro-and-similar-software/"><u>Comprehensive Guide to SNS HDR Pro and Similar Software</u></a></li>
<li><a href="https://fox-pages.techidaily.com/enhance-your-query-mastering-the-edit-search-dialog/"><u>Enhance Your Query: Mastering the Edit Search Dialog</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/fossil-sport-gear-reviewed-premium-performance-meets-wallet-friendly-prices/"><u>Fossil Sport Gear Reviewed: Premium Performance Meets Wallet-Friendly Prices</u></a></li>
<li><a href="https://fox-pages.techidaily.com/how-to-enable-usb-debugging-on-your-android-device-with-apowersoft-phone-manager/"><u>How to Enable USB Debugging on Your Android Device with Apowersoft Phone Manager</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-t2-pro-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Vivo T2 Pro 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://fox-pages.techidaily.com/how-to-insert-electronic-signatures-into-pdfs-using-simple-techniques/"><u>How To: Insert Electronic Signatures Into PDFs Using Simple Techniques</u></a></li>
<li><a href="https://fox-pages.techidaily.com/mastering-screen-captures-a-step-by-step-guide-for-macos-el-capitan-users/"><u>Mastering Screen Captures: A Step-by-Step Guide for macOS El Capitan Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/netgear-wireless-networking-driver-updates-where-and-how-to-download/"><u>NETGEAR Wireless Networking Driver Updates: Where and How to Download</u></a></li>
<li><a href="https://fox-pages.techidaily.com/private-discussions-enhancing-engagement-through-personalized-interactions/"><u>Private Discussions: Enhancing Engagement Through Personalized Interactions</u></a></li>
<li><a href="https://fox-pages.techidaily.com/seo-best-practices-mastering-the-art-of-configuring-virtual-directories-online/"><u>SEO Best Practices: Mastering the Art of Configuring Virtual Directories Online</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/turning-text-to-audio-with-ais-help/"><u>Turning Text to Audio with AI's Help</u></a></li>
<li><a href="https://fox-pages.techidaily.com/ultimate-technique-to-switch-from-flac-to-lossless-wav-soundtracks/"><u>Ultimate Technique to Switch From FLAC to Lossless WAV Soundtracks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlocking-profitability-on-youtube-shorts-essentials-and-future-earning-prospects-for-2024/"><u>Unlocking Profitability on Youtube Shorts Essentials and Future Earning Prospects for 2024</u></a></li>
</ul></div>

