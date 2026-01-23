# My rust zed setup with custom theme

Problems comparing to vscode:

1. No sematic tokens + Self {...} is not special (should be resolved soon): https://github.com/zed-industries/zed/pull/46356
2. Zed currently only colors the icon depending on diagnostics, not the file name text (maybe fork? https://github.com/zed-industries/zed/pull/18182)
3. Font ligatures broken at least on Arch Linux (https://github.com/zed-industries/zed/issues/12176)
4. Need more portals in Hyprland - no way to add default picker app (eg Firefox as default browser or nautilus as file manager)
  https://wiki.hypr.land/Hypr-Ecosystem/xdg-desktop-portal-hyprland/
  https://github.com/zed-industries/zed/issues/32704
  xdg-desktop-portal-lxqt 
  edited the
    ~/.config/xdg-desktop-portal/portals.conf
    [preferred]
    default=hyprland
    org.freedesktop.impl.portal.FileChooser=lxqt

5. No smooth scrolling https://github.com/zed-industries/zed/issues/4355
