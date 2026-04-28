# Slim Server Sidebar

A modular CSS-addon for Discord (compatible with Vencord, Vesktop, and BetterDiscord) that transforms the server list from thick icons into a slinky, collapsible list with names.

## Features
- **Slim by default**: Only 72px wide, keeping your interface clean.
- **Dynamic expansion**: Expands to 240px on `:hover` or `:focus-within`.
- **Tab-style icons**: Icons are transformed into small squares/tabs.
- **Server names**: Automatically extracts and displays server names from the `data-dnd-name` attribute.
- **Modular & Theme-aware**: Uses Discord's native CSS variables to match your active theme.

## Installation

### BetterDiscord
1. Open Discord Settings > BetterDiscord > Themes.
2. Click "Open Theme Folder".
3. Create a new file named `SlimServerSidebar.theme.css`.
4. Paste the following import at the top:
   ```css
   @import url('https://raw.githubusercontent.com/MaxTomahawk/Slim-Server-Sidebar/deploy/SlimServerSidebar.css');
   ```

### Vencord / Vesktop
1. Open Discord Settings > Vencord > Themes.
2. In the "Online Themes" section or "Custom CSS" section, add the following:
   ```css
   @import url('https://raw.githubusercontent.com/MaxTomahawk/Slim-Server-Sidebar/deploy/SlimServerSidebar.css');
   ```

## Development
This project uses SCSS. To compile locally:
1. `npm install`
2. `npm run build`

The project is automatically compiled and deployed to the `deploy` branch via GitHub Actions.

## Direct Link
[SlimServerSidebar.css](https://raw.githubusercontent.com/MaxTomahawk/Slim-Server-Sidebar/deploy/SlimServerSidebar.css)
