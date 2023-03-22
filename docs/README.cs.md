# ⚙️ Fusion 360 - SVG postprocessor

Stránka projektu pro SVG postprocesor pro Fusion 360 CAM, který generuje SVG soubory pro řezání laserem.

Postprocesor podporuje kompenzaci šířky laseru a režimy řezání a gravírování pomocí různých laserových nástrojů.

🔗 Založeno na projektu [Glowforge post-procesor](https://github.com/garethky/glowforge-colorific-fusion360-post)


## Instalace

1. Stáhněte soubor <a href="./Fusion360-SVG-CAMPost.cps" download>Fusion360-SVG-CAMPost.cps</a> a nahrajte ho do složky `Assets/CAMPost` v aplikaci Fusion 360 pomocí tlačítka pro nahrání. Najdete ho v `Select Tool` v sekci `Cloud`.
> ![Upload Postprocessor](./media/postprocessor.jpg)
2. Stáhněte soubor <a href="./Fusion360-SVG-CAMTools.json" download>Fusion360-SVG-CAMTools.json</a> a nahrajte ho do složky `Assets/CAMTools` v aplikaci Fusion 360 pomocí tlačítka pro nahrání. To do Fusionu přidá defaultní nástroje pro řezání a gravírování.
> ![Upload Tools](./media/tools.jpg)
3. Přejděte do položky `Preferences/Manufacture` v aplikaci Fusion 360 a klikněte na tlačítko `Enable Cloud Libraries`.
> ![Enable Cloud Libraries](./media/EnableCloudLibraries.jpg)
