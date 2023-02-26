<img src="https://github.com/swargarajbhowmik/Clean-Badges/blob/main/featured-2.png?raw=true"  width="100%">

# Clean-Badges (BETA - Buggy)
Clean Badges is a simple and intuitive tool designed to help GitHub users add professional eye-catching badges to their profile/project's readme files. These badges are designed to be sleek and modern, allowing your project to stand out and showcase its status in a clear and concise manner. 

## Table of contents
- [Themes](#themes)
- [API Breakdown](#api-Breakdown)
- [Icons](#icons)
- [License](#license)
- [Credits](#credits)

## Themes

| Theme | Theme Name | Code | Demo |
|---|---|---|---|
| <img src="https://i.imgur.com/IugzQk5.png"> | Simple | `![](https://practicing-wrists.000webhostapp.com/simple.php?text={text}&icon={icon})` | <a href="https://practicing-wrists.000webhostapp.com/simple.php?text=Twitter&icon=twitter">View Demo</a> |
| <img src="https://i.imgur.com/igbF8A2.png"> | Simple (Dark) | `![](https://practicing-wrists.000webhostapp.com/simple.php?text={text}&icon={icon}&iconcolor=light&bgcolor=000&textcolor=fff")` | <a href="https://practicing-wrists.000webhostapp.com/simple.php?text=Twitter&icon=twitter&iconcolor=light&bgcolor=000&textcolor=fff">View Demo</a> |
| <img src="https://i.imgur.com/CyMjWlN.png"> | Ocean | `![](https://practicing-wrists.000webhostapp.com/simple.php?text={text}&icon={icon})` | <a href="https://practicing-wrists.000webhostapp.com/ocean.php?text=Twitter&icon=twitter">View Demo</a> |
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

## Icons

| Name | Badge | Markdown Code |
|---|---|---|
| Apple | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple)```
| Apple Dark | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| AWS | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=aws&icon=aws&bgcolor=FF9900&textcolor=000&iconcolor=dark) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| Bitcoin | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=Bitcoin&icon=Bitcoin&bgcolor=f2a900&textcolor=000&iconcolor=dark) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| Bootstrap | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=Bootstrap&icon=Bootstrap&bgcolor=563D7C&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| BTC | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=aws&icon=BTC&bgcolor=FF9900&textcolor=f2a900&iconcolor=dark) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| Chrome | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=aws&icon=Chrome&bgcolor=4285F4&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| cPanel | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=cPanel&icon=cPanel&bgcolor=ff6c2c&textcolor=000&iconcolor=dark) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| CSS3 | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=CSS3&icon=CSS3&bgcolor=2965f1&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| Google | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=Google&icon=Google&bgcolor=4285F4&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| HTML5 | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=HTML5&icon=HTML5&bgcolor=f06529&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| Telegram | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=Telegram&icon=Telegram&bgcolor=229ED9&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```
| Twitter | ![](https://practicing-wrists.000webhostapp.com/simple.php?text=Twitter&icon=Twitter&bgcolor=00acee&textcolor=fff&iconcolor=light) | ```![](https://practicing-wrists.000webhostapp.com/simple.php?text=apple&icon=apple&bgcolor=000&textcolor=fff&iconcolor=light)```


## License
Clean Badges is licensed under the permissive MIT License, allowing users to use, modify, and distribute the software for both personal and commercial purposes.

## Credits
- Project inspired by <a href="https://github.com/badges/shields">@shields.io</a>
- README.md inspired by <a href="https://github.com/Ileriayo/">@Ileriayo</a>
