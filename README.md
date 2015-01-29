# MultiMarkdown-Composer-Localization
New and improved localization for MultiMarkdown Composer version 3

Unfortunately, MultiMarkdown Composer isn't currently a "big" enough project to support a team of developers or pay lots of people to help.  This includes paying for professional localization of the application for all the countries in the world.

We experimented briefly with creating localization files to "crowdsource" some of the effort.  A few brave people volunteered their time, but it wasn't enough to qualify as actual localization, so it wasn't practical.

In version 3, there's a new approach.  Under the "Edit" menu, there is an item "Customize Menus".  This opens up the Application Support folder where you will find a file named "MultiMarkdown Composer-CustomMenu.plist" (or something similar).  This is a text file (more specifically, a Property List file).  You can edit it with any plain text editor (e.g. TextEdit) or the Property List Editor application if you have it.

Editing this file allows you to change several things:

*	You can customize the keyboard shortcuts for various menu commands, including changing the modifier keys (e.g. Shift, Control, etc.)
*	You can rename menu commands -- either to a different language, or simply to something that makes more sense to you.

Simply find the command you want to change, and edit the "newTitle" key.  **DON'T** change the "originalTitle" key -- that must remain unchanged.

This new approach is **much** easier for you to use, and offers more flexibility.

If you want to share your customizations, check out the repo on [Github](https://github.com/fletcher/MultiMarkdown-Composer-Localization).  The `master` branch is the basic English version, and other versions can be added to different branches, e.g. `de` for German, `fr` for French, etc.  You can browse to see if anyone has started a localization for your language.  **NOTE**:  I speak English, a bit of German, and even less French.  I can't verify the accuracy, or even the appropriateness of any of these files.  If you find something that is inappropriate, please let me know and I can change it.  Browse at your own risk, but hopefully it will all stay clean and accurate.

For the moment, this does not apply to Preferences.  It does apply to:

*	The HUD panel titles and buttons
*	The Info Assistant (HUD and at the bottom of the editor)
