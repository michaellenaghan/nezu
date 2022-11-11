# NEZU

NEZU is a Typlog built-in theme. It is a single column theme. This theme supports
both blog posts and podcast episodes. (This is a modified version of the theme.)

## Install

Head over to **Settings → Themes & Design** and select **Nezu - Modified** theme.

## Configure

> This is the advanced configuration, only available for Pro subscribers.

Create an **asset** JSON in admin portal, set slug to `_config/nezu`. Here is an example of the configration:

```json
{
    "logo": {
        "light": "https://path/to/logo.svg",  // logo for light theme
        "dark": "https://path/to/logo-alt.svg"    // logo for dark theme
    },
    "css_files": [],
    "primary_nav": [],
    "secondary_nav": [],
    "foot_copy: ",  // html for the footer
    "foot_nav": []
}
```

The `primary_nav` and `secondary_nav` should look like this:

```json
  "primary_nav": [
    {
      "title": "...",
      "links": [
        {"title": "...", "subtitle": "...", "url": "..."},
        {"title": "...", "subtitle": "...", "url": "..."}
      ]
    },
    {"title": "...", "url": "..."}
  ],
```

Here's the demo's configration:

```json
{
  "logo": {
    "dark": "https://static.dazzit.com/logos/white.png",
    "light": "https://static.dazzit.com/logos/black.png"
  },
  "foot_copy": "&copy; Dazzit! Corp. / Developer of <a href='https://www.nextaction.app/'>NextAction</a>"
}
```

## License

Copyright of the design and code is reserved by Typlog.
