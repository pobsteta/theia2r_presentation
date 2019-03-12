---
output:
  pdf_document: default
  html_document: default
---
---?video=https://dlmultimedia.esa.int/download/public/videos/2015/04/008/orig-1504_008_AR_EN.mp4
@title[CNES presentation, 2019-02-12]

## @color[white](shiny-cnes, outil R à l'usage des data CNES)

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
- Résultat des pré-traitement
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes04.png)

---
@transition[fade-in zoom-out]
- Données d'entrée
![Distribution des présences/absences de scolytes](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes09.png)

---
@transition[concave-in zoom-out]
- Sélection des individus atteints
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes08.png)

---
@transition[fade-in convex-out]
- Processus de calcul 1/2
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/poster01.png)

---
@transition[fade-in zoom-out]
- Processus de calcul 2/2
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/poster02.png)

---
@transition[fade-in zoom-out]
- Résultat des prévisions
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/pred_scolyte.png)

---
@transition[fade-in convex-out]
- Résultat arbres scolytés SERTIT
![Interface web de sélection des serveurs image Sentinel](https://github.com/pobsteta/theia2r_presentation/raw/master/images/shinycnes06.png)

---
@title[PSI]
@transition[slide-in fade-out]
### @color[white](Perspectives)
- améliorer la rapidité de calcul ;
- disposer d'une plateforme de calcul ;
- améliorer la prévision.
    
Note:
- diffusion ?

---?video=https://dlmultimedia.esa.int/download/public/videos/2014/10/038/orig-1410_038_AR_EN.mp4
## @color[white](Merci de votre attention)
