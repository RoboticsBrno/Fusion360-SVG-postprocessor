# ⚙️ Fusion 360 - SVG postprocessor

<p align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FRoboticsBrno%2FFusion360-SVG-postprocessor&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=true"/></a>
<img src="https://img.shields.io/github/license/RoboticsBrno/Fusion360-SVG-postprocessor?style=flat-square">
</p>

Stránka projektu pro SVG postprocesor pro [Fusion 360](https://www.autodesk.cz/products/fusion-360/){target=_blank} CAM, který generuje SVG soubory pro řezání laserem.

Postprocesor podporuje kompenzaci šířky laseru a režimy řezání a gravírování pomocí různých laserových nástrojů.

🔗 Založeno na projektu [Glowforge post-procesor](https://github.com/garethky/glowforge-colorific-fusion360-post){target=_blank}.


## Instalace

1. Stáhněte soubor <a href="./Fusion360-SVG-CAMPost.cps" download>Fusion360-SVG-CAMPost.cps</a> a nahrajte ho do složky `Assets/CAMPost` v aplikaci Fusion 360 pomocí tlačítka pro nahrání. Najdete ho v `Select Tool` v sekci `Cloud`.
> ![Upload Postprocessor](./media/postprocessor.jpg)
2. Stáhněte soubor <a href="./Fusion360-SVG-CAMTools.json" download>Fusion360-SVG-CAMTools.json</a> a nahrajte ho do složky `Assets/CAMTools` v aplikaci Fusion 360 pomocí tlačítka pro nahrání. To do Fusionu přidá defaultní nástroje pro řezání a gravírování.
> ![Upload Tools](./media/tools.jpg)
3. Přejděte do položky `Preferences/Manufacture` v aplikaci Fusion 360 a klikněte na tlačítko `Enable Cloud Libraries`.
> ![Enable Cloud Libraries](./media/EnableCloudLibraries.jpg)
