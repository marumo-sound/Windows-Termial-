# Windows_Termial_setting

```

// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation

{
    "$schema": "https://aka.ms/terminal-profiles-schema",

    "defaultProfile": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
    "launchMode": "maximized",
    "copyOnSelect": true,
    "requestedTheme": "dark",

    "profiles":
    {
        "defaults":
        {
            // Put settings here that you want to apply to all profiles
        },
        "list":
        [
            {
                // Make changes here to the powershell.exe profile
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "name": "Windows PowerShell",
                "commandline": "powershell.exe",
                "hidden": false
            },
            {
                // Make changes here to the cmd.exe profile
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "cmd",
                "commandline": "cmd.exe",
                "colorScheme": "One Half Dark",
                "fontSize": 13,
                "fontFace": "Cascadia Code",
                "startingDirectory": "%USERPROFILE%/Downloads",
                "useAcrylic" : true,
                "acrylicOpacity" : 1.0,
                "hidden": false
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure"
            }
        ]
    },

    // Add custom color schemes to this array
    "schemes": [],

    // Add any keybinding overrides to this array.
    // To unbind a default keybinding, set the command to "unbound"
    "keybindings": [
        { "command": "newTab",          "keys": [ "ctrl+t" ]        },
        { "command": "closeTab",        "keys": [ "ctrl+w" ]        },
        { "command": "nextTab",         "keys": [ "ctrl+pagedown" ] },
        { "command": "prevTab",         "keys": [ "ctrl+pageup" ]   },
        { "command": "copy",            "keys": [ "alt+c" ]  },
        { "command": "paste",           "keys": [ "alt+v" ]  },
        { "command": "splitHorizontal", "keys": [ "ctrl+shift+h" ]  },
        { "command": "splitVertical",   "keys": [ "ctrl+shift+v" ]  },
        { "command": "moveFocusLeft" ,  "keys": [ "ctrl+left" ]     },
        { "command": "moveFocusRight",  "keys": [ "ctrl+right" ]    },
        { "command": "moveFocusUp",     "keys": [ "ctrl+up" ]       },
        { "command": "moveFocusDown",   "keys": [ "ctrl+down" ]     }
    ]
}

```
