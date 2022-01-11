# Change the font color of Mate-Panel
I like to use Kali-X, which is a light theme from Kali Linux. I also like to use Mate as my DE. When using Kali-x, the font color on the panel is usually set to grey and the background is black. It's almost impossible to read anything from the panel that way. 
In order to change the color of font, paste: 
```bash
#PanelApplet label,
.mate-panel-menu-bar menubar > menuitem {
    color: #F7347A;
    text-shadow: 1px 1px alpha (#000000, 0.8);
}
```
in *~/.config/gtk-3.0/gtk.css*. 
In order to change the color of the font, change *color: #F7347A;*. For white, use *color: #FFFFFF;*
