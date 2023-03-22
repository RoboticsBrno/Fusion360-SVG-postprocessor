# ⚙️ Fusion 360 - SVG postprocessor

Stránka projektu pro SVG postprocesor pro Fusion 360 CAM, který generuje SVG soubory pro řezání laserem.

Postprocesor podporuje kompenzaci šířky laseru a režimy řezání a gravírování pomocí různých laserových nástrojů.

🔗 Založeno na [Glowforge post-procesoru](https://github.com/garethky/glowforge-colorific-fusion360-post) od společnosti Glowforge.


## Instalace

1. Stáhněte soubor <a href="./Fusion360-SVG-postprocessor.cps" download>Fusion360-SVG-postprocessor.cps</a> a nahrajte ho do složky `Assets/Post Processors` v aplikaci Fusion 360 pomocí tlačítka pro nahrání.
> ![Upload Postprocessor](./docs/media/postprocessor.jpg)
2. Stáhněte soubor <a href="./Fusion360-SVG-tools.json" download>Fusion360-SVG-tools.json</a> a nahrajte ho do složky `Assets/Tools` v aplikaci Fusion 360 pomocí tlačítka pro nahrání.
> ![Upload Tools](./docs/media/tools.jpg)
1. Přejděte do položky `Preferences/Manufacture` v aplikaci Fusion 360 a klikněte na tlačítko `Enable Cloud Libraries`.
> ![Enable Cloud Libraries](./docs/media/EnableCloudLibraries.jpg)
