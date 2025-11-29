# CSS-Themes
As the name suggests, this repo holds some CSS themes.

## Discord
(Vencord required) Add this line to the top of your Vencord QuickCSS:

```css
@import url("https://raw.githubusercontent.com/PowerPCFan/CSS-Themes/refs/heads/main/discord.css");
```

## Jellyfin
Add one of the following code snippets to Dashboard -> Branding -> *Custom CSS code*:

**Full Skin (Beta)**
```css
@import url("https://raw.githubusercontent.com/PowerPCFan/CSS-Themes/refs/heads/main/jellyfin.css");
```

**Font Only (Very Stable)**
```css
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

.osdTextContainer { font-family: monospace, monospace; }
body,h1,h2,h3,h4,h5,html { font-family: Inter, system-ui, sans-serif; }
```
