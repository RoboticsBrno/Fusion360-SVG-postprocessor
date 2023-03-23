# ⚙️ Fusion 360 - SVG postprocessor

<p align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FRoboticsBrno%2FFusion360-SVG-postprocessor&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=true"/></a>
<img src="https://img.shields.io/github/license/RoboticsBrno/Fusion360-SVG-postprocessor?style=flat-square">
</p>

Project page for SVG postprocessor for [Fusion 360](https://www.autodesk.cz/products/fusion-360/) CAM that generates SVG files for laser cutting.

Postprocessor supports laser-width compensation and cutting and engraving modes by using different laser tools.

🔗 Based on [Glowforge post-processor](https://github.com/garethky/glowforge-colorific-fusion360-post) by Glowforge.

## Installation

1. Download the file <a href="./Fusion360-SVG-CAMPost.cps" download>Fusion360-SVG-CAMPost.cps</a> and upload it to Fusion 360 `Assets/CAMPost` folder using the upload button.
It will add a custom postprocessor to Fusion 360. You will find them in `Select Tool` in `Cloud` section.
> ![Upload Postprocessor](./docs/media/postprocessor.jpg)
1. Download the file <a href="./Fusion360-SVG-CAMTools.json" download>Fusion360-SVG-CAMTools.json</a> and upload it to Fusion 360 `Assets/Tools` folder using the upload button.
It will add to Fusion default tools for cutting and engraving.
> ![Upload Tools](./docs/media/tools.jpg)
1. Go to Fusion 360 `Preferences/CAMTools` and click to `Enable Cloud Libraries`.
> ![Enable Cloud Libraries](./docs/media/EnableCloudLibraries.jpg)