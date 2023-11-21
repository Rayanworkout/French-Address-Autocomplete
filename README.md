# French Address Autocomplete 💻

#### Easily enhance your website's address input functionality with free French address autocomplete.
(Traduction française au bas de la page)

Do you have a website where users input French addresses? This script offers an effortless way to add address autocompletion in just a few steps.

Note: *This script provides a less powerful alternative to the Google Maps Places API for house addresses only. It does not include businesses or establishments.*


## How to use ?

#### Installation
Simply add the script at the end of your HTML structure by using the CDN, or download the autocomplete.js as well as icon.svg.

```html
<script src="https://cdn.jsdelivr.net/gh/rayanworkout/French-Address-Autocomplete@master/autocomplete.js" integrity="sha256-P9vZEaiXEfpubFPH86pstIgvHJtSnlHkkVu3mmQClGc=" crossorigin="anonymous"></script>

```

#### Initialize Autocomplete

In your JavaScript file or directly inside the HTML file, identify the input field you want to autocomplete and pass it to the initFrenchAutocomplete function.

Note: the function only accepts one input field, if you want to pass multiple fields, you'll need to use multiple initFrenchAutocomplete() functions.


```javascript
  const inputField = document.queryselector('#myinputfield');
  initFrenchAutocomplete(inputField);
```

### You're ready to go !



## Why Use French Address Autocomplete?
This script leverages Government-issued API, offering accurate and up-to-date address suggestions for French locations.

Seamlessly integrate this feature into your website's address forms, providing users with an efficient and error-free way to input addresses.

API link: https://adresse.data.gouv.fr/api-doc/adresse
## Features

- **Effortless Integration**: Simply include the script, and your address input fields will gain autocompletion functionality.

- **Accurate Suggestions**: Utilizes Government-issued APIs to provide accurate and validated French address suggestions.

- **Free to Use**: Leveraging free-to-access Government APIs, this script allows you to enhance your website without any additional cost.


## Contributing

Contributions are always welcome!

If you have **any** ideas for improvements, feel free to open an issue or create a pull request on GitHub.


## License

[MIT](https://choosealicense.com/licenses/mit/)

# Contenu en français

## Complétion automatique des adresses françaises
Améliorez facilement la fonctionnalité de saisie d'adresse de votre site web avec une complétion automatique gratuite des adresses françaises.


Vous avez un site web où les utilisateurs saisissent des adresses françaises ? Ce script offre un moyen simple d'ajouter la complétion automatique des adresses en seulement quelques étapes.

Remarque : Ce script fournit une alternative moins puissante à l'API Google Maps Places pour les adresses de maisons uniquement. Il n'inclut pas ou peu les entreprises ou les établissements tels que les gares, aéroports ...


### Utilisation

Il suffit simplement d'ajouter le lien du CDN à la fin de votre script HTML comme ci-dessous, puis d'initialiser la fonction.

```html
  <script src="https://cdn.jsdelivr.net/gh/rayanworkout/French-Address-Autocomplete@master/autocomplete.js" integrity="sha256-P9vZEaiXEfpubFPH86pstIgvHJtSnlHkkVu3mmQClGc=" crossorigin="anonymous"></script>

```

#### Initialiser la fonction

Dans votre fichier Javascript ou directement dans une balise script dans votre HTML, identifiez le ou les champs pour lequels vous souhaitez activer l'autocompletion et passez le dans la fonction.

Note: la fonction n'accepte qu'un champ, si vous utilisez plusieurs champs, il faudra appeler la fonction une fois pour chaque champ.

```javascript
  const inputField = document.queryselector('#myinputfield');
  initFrenchAutocomplete(inputField);
```

### Vous êtes prêt à utiliser l'autocomplete !


## Pourquoi utiliser la complétion automatique des adresses françaises ?
Ce script exploite une API émise par le gouvernement, offrant des suggestions d'adresses précises et à jour pour les emplacements français.

En intégrant cette fonctionnalité dans les formulaires d'adresse de votre site web, vous offrez aux utilisateurs un moyen efficace et simple de saisir des adresses, et vous augmentez la précision des données récoltées.

Lien vers l'API du gouvernement: https://adresse.data.gouv.fr/api-doc/adresse


### Caractéristiques

- **Intégration facile** : Il suffit d'inclure le script, et vos champs de saisie d'adresse bénéficieront de la fonctionnalité de complétion automatique.

- **Suggestions précises** : Utilise des APIs émises par le gouvernement pour fournir des suggestions d'adresses françaises précises et validées.

- **Gratuit** : Cette API est gratuitement mise à disposition par le gouvernement, vous pouvez donc améliorer votre site web sans coût supplémentaire.


Les contributions à ce repo sont les bienvenues, si vous avez une idée d'amélioration ou que vous trouvez un bug, n'hésitez pas à ouvrir une Pull Request, une Issue ou me contacter.

## Licence

[MIT](https://choosealicense.com/licenses/mit/)
