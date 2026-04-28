# Slim Server Sidebar

A modular CSS-addon for Discord (compatible with Vencord, Vesktop, and BetterDiscord) that transforms the server list from thick icons into a slinky, collapsible list with names.

## Features
- **Ultra Slim**: Only 36px wide in collapsed mode.
- **Dynamic expansion**: Expands to 240px on `:hover`.
- **Row Styling**: Compact 24px rows for a dense, professional look.
- **Icon Scaling**: 20px icons for maximum visibility in slim mode.
- **Folder Names**: Automatically extracts and displays folder and server names from the `data-dnd-name` attribute.
- **Modular & Theme-aware**: Uses Discord's native CSS variables to match your active theme.

## Installation
**Powercord Install**: `git clone https://github.com/MaxTomahawk/Slim-Server-Sidebar --branch deploy`

**Vencord Theme**: `https://raw.githubusercontent.com/MaxTomahawk/Slim-Server-Sidebar/deploy/SlimServerSidebar.css`

## Development
This project uses SCSS. To compile locally:
1. `npm install`
2. `npm run build`

The project is automatically compiled and deployed to the `deploy` branch via GitHub Actions.

## Direct Link
[SlimServerSidebar.css](https://raw.githubusercontent.com/MaxTomahawk/Slim-Server-Sidebar/deploy/SlimServerSidebar.css)
