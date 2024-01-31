# Firefox-Tab-Preview-On-Hover
Enable Firefox Tab Preview Thumbnail when Hovering over an inactive tab.

Steps:

1. Download the [Tab Preview On Hover](https://addons.mozilla.org/en-US/firefox/addon/tab-preview-on-hover/) Firefox extension.
2. Download this [CSS theme](https://raw.githubusercontent.com/easonwong-de/Tab-Preview-On-Hover/main/CSS%20Theme/userChrome.css)
3. Open a new tab and enter the following in the address bar and press enter:
``` txt
  about:support
```

4. Locate `Profile Folder` and click the `Open Folder` button next to it.
5. In the window that opened up create a new folder called `chrome`.
6. Move the `userChrome.css` file you downloaded to this `chrome` folder.
7. Open a new tab and enter the following in the address bar and press enter:
``` txt
  about:config
```

8. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and turn it to `true`.
9. Navigate back to the `about:support` tab and click on the `Clear startup cache…` button just at the top right (I'm not sure if this step is really needed...).
10. Restart Firefox (Close all instances and open Firefox again).
11. Ba-boom! Tab Tumbnail Preview on hover should now be working!


**Go read the [Tab Preview On Hover Repo](https://github.com/easonwong-de/Tab-Preview-On-Hover) for need to know info about this extension.**

***

SOURCES:

[Tab Preview On Hover Firefox Extension](https://addons.mozilla.org/en-US/firefox/addon/tab-preview-on-hover/)

[Tab Preview On Hover Repo](https://github.com/easonwong-de/Tab-Preview-On-Hover)

