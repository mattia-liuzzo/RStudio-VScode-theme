# RStudio-VScode-theme
RStudio theme inspired by VS code colors.

![image](https://user-images.githubusercontent.com/63495216/110652882-0fdee500-81bd-11eb-873e-1aeba30bb95a.png)
![image](https://user-images.githubusercontent.com/63495216/110654675-a65fd600-81be-11eb-8b2a-88e1a4cb1402.png)


# Add theme manually to RStudio
Required: RStudio v1.2+

Download rs-vscode.rstheme file and add it within RStudio.

# Install it
You can also install it and automatically add it with this command:

```
rstudioapi::addTheme("https://raw.githubusercontent.com/mattia-liuzzo/RStudio-VScode-theme/main/rs-vscode.rstheme", apply = TRUE)
```

It requires `rstudioapi` package. You can install it with `devtools::install_github("rstudio/rstudioapi")`.

Enjoy your theme!
