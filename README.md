<img src="https://github.com/swargarajbhowmik/Clean-Badges/blob/main/featured-2.png?raw=true"  width="100%">

# Clean-Badges (BETA - Buggy)
Clean Badges is a simple and intuitive tool designed to help GitHub users add professional eye-catching badges to their profile/project's readme files. These badges are designed to be sleek and modern, allowing your project to stand out and showcase its status in a clear and concise manner. 

## Table of contents
- [Themes](#themes)
- [API Breakdown](#api-Breakdown)
- [Available Icons](#icons)
- [License](#license)
- [Credits](#credits)

## Themes

| Theme | Theme Name | Code | Demo |
|---|---|---|---|
| <img src="https://i.imgur.com/IugzQk5.png"> | Simple | `![](https://practicing-wrists.000webhostapp.com/simple.php?text={text}&icon={icon})` | <a href="https://practicing-wrists.000webhostapp.com/simple.php?text=Twitter&icon=twitter">View Demo</a> |
| <img src="https://imgur.com/CyMjWlN.png"> | Ocean | `![](https://practicing-wrists.000webhostapp.com/simple.php?text={text}&icon={icon})` | <a href="https://practicing-wrists.000webhostapp.com/ocean.php?text=Twitter&icon=twitter">View Demo</a> |
| <img src="https://i.imgur.com/LGDNeV0.png"> | Gradient Bordered 1 | `![](https://practicing-wrists.000webhostapp.com/simple.php?text={text}&icon={icon})` | <a href="https://practicing-wrists.000webhostapp.com/gradient-bordered-1.php?text=Twitter&icon=twitter">View Demo</a> |
| <img src="https://imgur.com/sGqorNo.png"> | Bordered | Coming Soon | Coming Soon |

## API Breakdown
This section provides a comprehensive overview of the various parameter that are available in this badge API.

API URL: https://practicing-wrists.000webhostapp.com/{THEME_NAME}.php
Themes are available <a href="#themes">here</a>!

**Available Parameters**
- `?text={YOUR_TEXT}` This parameter takes "YOUR_TEXT" as input and display it in the badge. (Required)
- `&icon={ICON_NAME}` This parameter takes "ICON_NAME" as input and display it in the badge. <a href="#icons">Here</a> is the list of all available icons! (Optional)
- `&textcolor={HEX_COLOR}` This parameter takes hex color as input and change the color of the text. Don't use "#", Example: FF0000. (Optional)
- `&bordercolor={HEX_COLOR}` This parameter takes hex color as input and change the color of the bordercolor. Don't use "#", Example: FF0000. Not all theme supports this parameter. Only `bordered` supports it. (Optional)
- `&iconcolor={dark/light}` This parameter can take either dark or light as input and change the color of the icon to black and white respectively. (Optional)

## Available Icons

| Name | Badge | Markdown Code |
|---|---|---|
| Apple | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple)```
| Apple Dark | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| AWS | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=aws&icon=aws&bgcolor=FF9900&textcolor=000&iconcolor=dark) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```



## License
Clean Badges is licensed under the permissive MIT License, allowing users to use, modify, and distribute the software for both personal and commercial purposes.

## Credits
- Project inspired by <a href="https://github.com/badges/shields">@shields.io</a>
- README.md inspired by <a href="https://github.com/Ileriayo/">@Ileriayo</a>
