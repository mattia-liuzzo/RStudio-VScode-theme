# RStudio-VScode-theme

A clean and modern theme for **RStudio**, inspired by the popular **VS Code Dark+** color scheme and based on the excellent *Tomorrow Night* theme.

Designed to provide a familiar Visual Studio Code experience while coding in RStudio, with improved readability and a pleasant dark appearance for long coding sessions.

![image](https://user-images.githubusercontent.com/63495216/110667938-0f4d4b00-81cb-11eb-943e-f5951dbed137.png)
![image](https://user-images.githubusercontent.com/63495216/110654675-a65fd600-81be-11eb-8b2a-88e1a4cb1402.png)

# Manual Installation

**Requirements:** RStudio v1.2+

1. Download the `rs-vscode.rstheme` file from this repository.
2. Open **RStudio**.
3. Navigate to **Tools → Global Options → Appearance**.
4. Click **Add...** and select the downloaded theme file.
5. Apply the theme.

# Install from R

You can install and apply the theme directly from the RStudio console:

```r
rstudioapi::addTheme(
  "https://raw.githubusercontent.com/mattia-liuzzo/RStudio-VScode-theme/main/rs-vscode.rstheme",
  apply = TRUE
)
