## Sublime Settings
This is a custom collection of user sublime settings I use. Feel free to use them if it helps

This contains a bunch of packages I use as well as an updated `C++` syntax and theme that allows annotations.
Current annotations added `TODO:` `NOTE:` `IMPORTANT:`

If you are using the provided `Preferences.sublime-settings` you might be better off commenting out the following lines:

- // "color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
- // "theme": "Material-Theme.sublime-theme",

If not, Sublime Text won't find the theme and color scheme and throw errors, before we install the Package Control and Material Theme package. You can comment these out after sublime has updated itself

### Annotations only
If you wish to extract just the annotations functionality and not use the whole settings package just copy the following files to your User dir

- `Material Theme` installed?
    - `Material-Theme_Annotations.tmTheme`
- else
    - `Monokai_Annotations.tmTheme`
- `C++_Annotations.sublime-syntax`

To activate add the following to `Preferences.sublime-settings` for User
```json
"color_scheme": "Packages/User/Material-Theme_Annotations.tmTheme",
"theme": "Material-Theme.sublime-theme",
```
Then set your C++ syntax to `C++_Annotations`
