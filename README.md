# i3 Configuration

This repository contains my personal i3 window manager configuration. It is based on the default configuration generated by `i3-config-wizard` with several customizations to suit my workflow.

## Customizations

Below are the key customizations I have made to the default i3 configuration:

- **Mod Key**: The mod key is set to `Mod4` (usually the Windows key).

- **Font**: The font for window titles and the bar is set to `pango:monospace 8`.

- **Startup Applications**:
  - `dex` is used to start XDG autostart `.desktop` files.
  - `xss-lock` with `i3lock` is used to lock the screen before suspend.
  - `nm-applet` for NetworkManager.

- **Volume Control**: Volume is controlled with `pactl` and the i3status bar is refreshed upon volume change.

- **Window Management**:
  - Floating windows can be dragged with the mouse while holding the `$mod` key.
  - Windows can be focused and moved using both `$mod` + `h/j/k/l` and the arrow keys.
  - The split in horizontal orientation is set to `$mod+g`.

- **Fullscreen Mode**: Fullscreen mode can be toggled with `$mod+f`.

- **Layout Changes**: The layout can be changed to stacking, tabbed, or toggle split with `$mod+s/w/e`.

- **Tiling / Floating Toggle**: Tiling and floating modes can be toggled with `$mod+Shift+space`.

- **Workspaces**: Ten workspaces are pre-defined and can be accessed with `$mod+1` to `$mod+0`.

- **Reloading and Restarting**:
  - The configuration can be reloaded with `$mod+Shift+c`.
  - i3 can be restarted in-place with `$mod+Shift+r`.

- **Exiting i3**: A prompt to exit i3 can be triggered with `$mod+Shift+e`.

- **Resize Mode**: A resize mode is configured to adjust window dimensions with `$mod+r`.

- **Window Switching**: Alt+Tab and Alt+Shift+Tab are used to switch between windows.

- **i3bar**: The i3bar is configured to display workspace information and system status.

## Installation

To use this configuration, clone the repository to your `.config/i3` directory:

```bash
git clone https://github.com/consumer47/i3_config.git ~/.config/i3
