# editor-themes
Theme files for code editors including RStudio and Sublime Text.

# Overview of RStudio theme, Breeze
This light breeze theme highlights the current line and the cursor.
![](image/breezetheme_view.png)

## Use RStudio theme, Breeze
To download, launch RStudio. Then, run this code; 

> rstudioapi::addTheme("https://github.com/sook-tusk/editor-themes/RStudio/Breeze.rstheme", apply = TRUE)

To ensure the current line is highlighted, 
tick the box for the `Highlight selected line` option under the menu:
> Tools > Global Options... > Code > Display
![](image/highlightline.png)

# References 
1. To learn how to customise a theme for RStudio, visit here:
https://www.r-bloggers.com/2018/04/make-rstudio-look-the-way-you-want-because-beauty-matters/

