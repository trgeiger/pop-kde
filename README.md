# pop-kde
Port of the Pop_OS! GTK theme to KDE Plasma using the Kvantum theme engine.

So far, it includes a Plasma Theme, a Kvantum widget theme, and a colorscheme.

## To-dos:
  * Installation script
  * Plasma Look-and-Feel package
  * Pop-Dark variant
  * Possibly a tweak of proper Breeze window decorations to match Pop
  * Terminal colorscheme (although gruvbox is perfect already...)
  * Packages and/or a PPA 
  
## Recommendations for a unified look:
  * Fira Sans Book size 10 font for General, Small, Toolbar, and Menu
  * Fira Sans Bold size 10 for Window Title
  * FiraCode or FuraCode Nerd Font for Fixed width
  * Install Pop Icons set from the [Pop!_OS](https://github.com/pop-os/icon-theme) github
  * Install the Pop GTK theme from the [Pop!_OS](https://github.com/pop-os/gtk-theme) github and set it for GTK apps
  * If using Latte Dock, remove panel shadow and set panel background to opaque
  * Use the gruvbox colorscheme for Konsole and text editors
  
Feel free to submit bugs if anything looks out of place.

## Notes
This isn't an exact port. Some features of the original GTK theme are difficult, if not impossible, to replicate in the Kvantum engine using .svg files. These include the large shadows on buttons and text input lines. If you think there might be a better compromise for some of features I've been unable to recreate, please let me know! All in all, the Kvantum theme has to be a little flatter than the original GTK--more like the Adapta theme from which the Pop theme is originally forked.
