# atgcolor README

![Sample Colorized Log File (file.out) Screenshot](/imgs/sample_image.png?raw=true "Sample Colorized Log File (file.out)")

Language support to colorize .out files from ATG servers.

## Features

New tokens with textMate to color the logs.

## Extension Settings

## Release Notes

### 1.0.0

Initial release of language support and grammar.

-----------------------------------------------------------------------------------------------------------

The following configuration needs to be added to the settings.json file:
```json
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "source.out",
            "settings": {
                "foreground": "#F9F18F"
            }
        },
        {
            "scope": "debug.source.out",
            "settings": {
                "foreground": "#13C60D"
            }
        },
        {
            "scope": "info.weblogic.out",
            "settings": {
                "foreground": "#13C60D"
            }
        },
        {
            "scope": "notice.weblogic.out",
            "settings": {
                "foreground": "#13C60D"
            }
        },
        {
            "scope": "error.source.out",
            "settings": {
                "foreground": "#E74856"
            }
        },
        {
            "scope": "critical.weblogic.out",
            "settings": {
                "foreground": "#E74856"
            }
        },
        {
            "scope": "info.source.out",
            "settings": {
                "foreground": "#F8F8F2"
            }
        },
        {
            "scope": "trace.source.out",
            "settings": {
                "foreground": "#FD971F"
            }
        },
        {
            "scope": "warning.source.out",
            "settings": {
                "foreground": "#61D6D6"
            }
        },
        {
            "scope": "warning.weblogic.out",
            "settings": {
                "foreground": "#61D6D6"
            }
        }
    ]
}
```
-----------------------------------------------------------------------------------------------------------

