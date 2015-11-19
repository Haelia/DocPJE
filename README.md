CREATION LIVRES
- Manuellement -> DEMICHECK
- Par son ISBN
- Ajouter un livre en scannant son code barre
	-> scanner un code barre
	-> rechercher des métadonées sur Google Book
- Ajouter une illustration en prenant une photo et l'ajouter à la librairie -> DEMI CHECK : on récupère la photo de la galerie..

MODIFIER UN LIVRE

DETRUIRE UN LIVRE -> CHECK

CONSULTER TOUS LES LIVRES -> CHECK
- Afficher la liste de tous les livres -> CHECK

VOIR LES DETAILS D'UN LIVRE
- Montre les détails d'un livre -> fragment

CREER UN FILTRE (liste dynamique)
listes qui montrent tout les livres d'un certain genre/auteur. On peut la créer modifier détruire et afficher le résultat et les listes dynamiques

LISTES DYNAMIQUES / FILTRES
- Afficher les différentes listes dynamiques
- Voir les livres associés à un filtre
- Créer une liste dynamique
- Modifier et supprimer une liste dynamique

IMPORTER/EXPORTER UNE BIBLIO
- Export de la base et des images associées
- Export de la base et des images associées
- Reset

LOOK & FEEL
if(time()){
MENU PRINCIPAL 
- Rendre plus joli
}
if(moretime()){
ALL 
-Rendre tout joli !
}

ERGONOMIE




Insérer bitmap dans DB
http://www.tutorialforandroid.com/2009/10/how-to-insert-image-data-to-sqlite.html

/**
Bitmap to byte[]

Bitmap bmp = intent.getExtras().get("data");
ByteArrayOutputStream stream = new ByteArrayOutputStream();
bmp.compress(Bitmap.CompressFormat.PNG, 100, stream);
byte[] byteArray = stream.toByteArray();

byte[] to bitmap
ImageView myImage = (ImageView) findViewById(R.id.myImage);
byte[] bb = cursor.getBlob(cursor.getColumnIndex(MyBaseColumn.MyTable.ImageField));
myImage.setImageBitmap(BitmapFactory.decodeByteArray(bb, 0, bb.length));
*/
