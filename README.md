# firefox-css
Custom css setup for firefix

##
1. Open `about:config` page in firefox
2. Enable the following options
    - `toolkit.legacyUserProfileCustomizations.stylesheets`
    - `layers.acceleration.force-enabled`
    - `gfx.webrender.all`
    - `gfx.webrender.enabled`
    - `layout.css.backdrop-filter.enabled`
    - `svg.context-properties.content.enabled`
3. Navigate to `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
4. Create a folder and name it `chrome`
5. Copy the `userChrome.css` file into the `chrome` folder.

Sources:  
https://github.com/FirefoxCSS-Store/FirefoxCSS-Store.github.io/blob/main/README.md#generic-installation
https://www.reddit.com/r/FirefoxCSS/comments/xlw34q/move_minimizemaximizeclose_buttons_to_firefox/
https://mrotherguy.github.io/firefox-csshacks/?file=window_control_placeholder_support.css%2Ctabs_on_bottom.css%2Ctabs_fill_available_width.css%2Ccentered_tab_content.css

