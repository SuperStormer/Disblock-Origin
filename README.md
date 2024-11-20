<img src="logo.svg" align="right" alt="A mauve-colored Ublock Origin shield with the Discord 'D' in the center.">

# Disblock Origin

An ad-blocker "Theme" for Discord that hides all Nitro and "boost" upsells, alongside some annoyances.


## Installation

Use your favorite client mod (such as Vencord) to add the theme. You can use this URL, which mirrors the files on the repo:
```
https://allpurposem.at/disblock/DisblockOrigin.theme.css
```

To see whether Disblock Origin is properly installed, check for the logo at the bottom of the settings sidebar next to Discord's social logos, you should see a Disblock Origin logo to let you know it's working.

## Customization
Certain features of Disblock Origin are cutomizable by overriding settings listed at the top of the theme file:
https://codeberg.org/AllPurposeMat/Disblock-Origin/src/commit/76d60d22c1e47f5f5f5d12178f08e4352b10d589/DisblockOrigin.theme.css#L9-L36

To change a setting, copy and paste the `:root` block into your custom CSS (accessible on Vencord via **Local Themes** > **Edit QuickCSS**), and any variables you want changed. Use `none` to hide something, and `unset` to show it.

For example, to show the GIF button in the chat box, you can use the following snippet in your custom CSS:
```css
:root {
    /* disable hiding the GIF picker button */
    --display-gif-button: unset;
}
```