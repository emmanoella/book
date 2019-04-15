#Marcdown

  *Est un langage de balisage léger.
  *utilisé pour ajouter facilement du formatage, des liens et des images à du texte brut. 

#SYntaxe
 ##Styles de texte

    _italique_ s'affiche : italique
    **gras** s'affiche : gras
    **_gras-italique_** s'affiche : gras-italique
    ~~barré~~ s'affiche ainsi : barré

  ##Coloration syntaxique

   *Pour ajouter de la coloration syntaxique, saisissez le langage utilisé après les ``` au début de votre bloc de code.

```>Les langages pris en charge sont : diff, apache, makefile, http, json, markdown, javascript, css, nginx, objectivec, python, xml, perl, bash, php, coffeescript, cs (C#), cpp (C++), sql, go, ruby, java, ini, latex```

Exemple :

``` go
package main
import "fmt"
func main() {
        fmt.Println("Hello, ä¸–ç•Œ")
}
```

Tableaux
===

Créez un tableau en plaçant une ligne de tirets sous la ligne d'entête et en séparant les colonnes par une barre verticale | (il n'y a pas besoin d'aligner exactement les colonnes pour que cela fonctionne). Précisez comment aligner les colonnes du tableau en ajoutant des deux-points : dans la ligne d'entête.

| Aligné à gauche  | Centré          | Aligné à droite |
| :--------------- |:---------------:| -----:|
| Colonne gauche 1 |   ce texte        |  $100 |
| Colonne gauche 2 | est             |   $10 |
| Colonne gauche 3 | centré          |    $1 |

