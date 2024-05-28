# README

Sharing this old script I've had for a few years.

I use it to quickly switch between kubernetes contexts

## Usage

Assuming the script has been installed in `/home/user/bin/rofi-kubecontext`:

```
rofi -show kctx -modi 'kctx:/home/user/bin/rofi-kubecontext'
```

## i3 config example
```
bindsym $mod+k exec "rofi -show kctx -modi 'kctx:/home/user/bin/rofi-kubecontext'"
```
