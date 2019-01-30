---?video=https://dlmultimedia.esa.int/download/public/videos/2015/04/008/orig-1504_008_AR_EN.mp4
@title[theia2r presentation, 2018-11-08]

## @color[white](theia2r, outil R à l'usage des data CNES)

@snap[north-west]
<h3><span style="color:white;">Pascal Obstétar</span></h3>
<h4><span style="color:white;">2018-11-08</span></h4>
@snapend 


---
@title[Sentienl data]
@transition[slide-in fade-out]
## Sentinel data
- Le [nom des niveaux](http://www.cesbio.ups-tlse.fr/multitemp/?p=2766) de produits ?
- 12 [bandes spectrales](https://sentinel.esa.int/web/sentinel/user-guides/sentinel-2-msi/resolutions/radiometric) à 10, 20 ou 60 mètres de [résolution](https://sentinel.esa.int/web/sentinel/user-guides/sentinel-2-msi/resolutions/spatial) :
    ![Sentinel-2 bands](https://landsat.gsfc.nasa.gov/wp-content/uploads/2015/06/Landsat.v.Sentinel-2.png)
    
Note:
- test de notes

---
@transition[fade-in convex-out]
## Shiny CNES
- Interface web de sélection des serveurs images
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes01.png)

---
@transition[convex-in concave-out]
- Sélection spatio-temporelle des images
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes02.png)

---
@transition[concave-in zoom-out]
- Sélection des indices spectraux
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes03.png)

---
@transition[fade-in convex-out]
- Résultat des pré-calculs
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes04.png)

---
@transition[fade-in convex-out]
- Résultat des prévisions
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes05.png)

---
@transition[fade-in convex-out]
- Résultat arbres scolytés SERTIT
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes06.png)

---
@title[PSI]
@transition[slide-in fade-out]
### @color[white](Points positifs)
- rapidité de calcul amélioré X24 ;
- prise en compte des data en flux ;
- pas nécessaire de partir de points échantillon.

### @color[white](Points de blocage)
- application complexe à reprendre (code de Stéphane DUMAS) ;
- nécessaire d'avoir un serveur rapide et optimisé ;
- nécessité d'avoir des flux ouverts (Géoportail BD ORTHO IRC fermé jusuq'au 04/02/2019).

### @color[white](Perspectives)
- améliorer la rapidité de calcul ;
- mettre en place une équipe de dev ;
- améliorer la prévision.
    
Note:
- diffusion ?

---?video=https://dlmultimedia.esa.int/download/public/videos/2014/10/038/orig-1410_038_AR_EN.mp4
## @color[white](Merci de votre attention)
