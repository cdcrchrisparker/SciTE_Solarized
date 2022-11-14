# SciTE_Solarized
A Solarized theme for SciTE -- [Official Solarized Site](https://ethanschoonover.com/solarized/).

# How to use:
I use this in GNU/Linux only. I've made a few attempts to use it in Windows, however my results were somewhat less than satisfactory.  The basic problem is that the style only seems to alter the various areas inside the program, not the Window itself. I would love to make this work better if anyone has any suggestions.

### So for GNU/Linux...

1. $ mkdir -p ~/.config/SciTE/Solarized
2. Copy SolarDark.properties & SolarLight.properties to that directory
3. In SciTE select Options -> Open User Options File
4. Add the two following lines to the top of your user options file (note that I have Solarized Dark enabled):
  
```
import .config/SciTE/Solarized/SolarDark
# import .config/SciTE/Solarized/SolarLight
```



## Note
This theme is a work in progress - suggestions are welcome, particularly for languages that are obviously not complete.
