# ActiveViewTheme
Sets a new theme for a view when it gains input focus. 

# Usage
Simply create a new color scheme file that you would like to use for your active views. You will probably want to place this in `Packages/User/`. Then, in `Packages/User/ActiveViewTheme.sublime-settings`, create a settings file, specifying the theme to use on active views. The path should be relative to one above the packages directory, the same as `color_scheme` in the `Preferencs.sublime-settings`.

    {
    	"active_theme": <your theme path here>
    }