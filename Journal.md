# Journal

### 2025-04-09
notebook reading-stac.ipynb de Planetary Computer sur Onyxia
 * réécriture du programme de sauvegarde d'une image sur S3 suite nettoyage des commits d'hier
 * attention certaines cellules affiche des images satallites > 300 Mo => ça plante Onyxia (kernel busy , sauvegarde du code impossible)
   
### 2025-04-08
travaillé sur Git (avec Chat GPT):
 * mis à jour .gitignore : ne pas tracker les ipynb_checkpoints, les images (.tiff, .jpg) trop volumineuses 
 * nettoyé les commits, mit en cohérence service Onyxia et GitHub

### 2025-04-07
travaillé sur code Python :
  * affichage / téléchargement des images
  * contenu des tables
  * série longue de couverture nuageuse

### 2025-04-03
fait tourner le notebook reading-stac.ipynb de Planetary Computer sur Onyxia  
  * avec git => probleme = token à chaque push/pull => déclarer le token à l'ouverture du service ?  
  * sauvegarde d'une image sur s3/bballet/test_sat/image.jpg  
    * => paramétrer le service s3 avec import **os** et import **s3fs** => voir doc onyxia "Stockage des données"  
    * => download avec import **requests** & from io import **BytesIO**  


