
# Calendrier Flutter

Ce widget représente un calendrier interactif dans une application mobile Flutter. Il permet à l'utilisateur de sélectionner une date ou une plage de dates et affiche les jours de la semaine et les dates de manière claire et esthétique.

## Fonctionnalités

- Affichage interactif d'un calendrier dans l'application.
- Sélection de dates simples ou de plages de dates.
- Personnalisation des styles pour s'adapter au thème de l'application.

## Captures d'écran

![Capture d'écran du calendrier](screenshot.png)

## Utilisation

Pour utiliser ce widget, vous pouvez l'incorporer dans votre application Flutter en important le fichier `home_page_widget.dart` et en l'appelant dans votre arborescence de widgets.

```dart
import 'home_page_widget.dart';

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Mon Calendrier',
      home: Scaffold(
        body: HomePageWidget(),
      ),
    );
  }
}
```

## Dépendances

Ce widget utilise les dépendances suivantes :
- flutter
- provider

Pour installer ces dépendances, ajoutez les lignes suivantes à votre fichier `pubspec.yaml` :

```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^5.0.0
```

## Auteur

Ce widget a été développé par Paul-Franck Dencausse
