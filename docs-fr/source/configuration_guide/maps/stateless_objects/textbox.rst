===========
Les Textbox
===========

Une textbox permet d'afficher un texte simple ou du HTML.

Onglet General
--------------

+---------------------+------------------------+----------------------------------------------------------------------+
| Valeur              | Par défaut             | Description                                                          |
+=====================+========================+======================================================================+
| text                |                        | Votre propre texte, du HTML est possible. Il y a quelques macros:    |
+---------------------+------------------------+----------------------------------------------------------------------+
| x                   |                        | coordonées sur l'axe des X                                           |
+---------------------+------------------------+----------------------------------------------------------------------+
| y                   |                        | coordonées sur l'axe des Y                                           |
+---------------------+------------------------+----------------------------------------------------------------------+
| z                   |                        | coordonées sur l'axe des Z (profondeur)                              |
+---------------------+------------------------+----------------------------------------------------------------------+
| w                   | auto                   | Largeur de la zone de texte en px (pixels). Régler sur "auto" pour   |
|                     |                        | la mise à l'échelle automatique.                                     |
+---------------------+------------------------+----------------------------------------------------------------------+
| h                   | auto                   | Hauteur de la zone de texte en px (pixels). Régler sur "auto" pour   |
|                     |                        | la mise à l'échelle automatique.                                     |
+---------------------+------------------------+----------------------------------------------------------------------+
| object_id           |                        | Identifiant unique de l'objet généré automatiquement                 |
+---------------------+------------------------+----------------------------------------------------------------------+

Onglet Appearance
-----------------

+---------------------+------------------------+----------------------------------------------------------------------+
| Valeur              | Par défaut             | Description                                                          |
+=====================+========================+======================================================================+
| style               |                        | Style personnalisé pour le texte. A donner comme contenu d'attribut  |
|                     |                        | de style HTML. Par exemple: font-family:sans;font-weight:bold;       |
+---------------------+------------------------+----------------------------------------------------------------------+
| background_color    |                        | Couleur d'arrière-plan de la zone de texte. La couleur doit être     |
|                     |                        | donnée en hexcode. Peut aussi être "transparent".                    |
+---------------------+------------------------+----------------------------------------------------------------------+
| border_color        |                        | Couleur de la bordure de la zone de texte. La couleur doit être      |
|                     |                        | donnée en hexcode. Peut aussi être "transparent".                    |
+---------------------+------------------------+----------------------------------------------------------------------+
