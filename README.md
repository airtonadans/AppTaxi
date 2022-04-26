# Flutter Taxi App [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


Um aplicativo de táxi iniciante, desenvolvido no Flutter, construído com o padrão BLOC. Tem as seguintes características

- Marcadores de táxi mostrando em diferentes posições no mapa (com base na posição estática)
- Diferentes animações em diferentes partes da tela
- Polilinha mostrando no mapa (dados codificados da API do Google Maps)

Funciona em Android e IOS.

###Capturas de tela

![makephotogallery.net_1580238239.jpg](https://www.dropbox.com/s/dgd40s5752y2jsl/makephotogallery.net_1580238239.jpg?dl=0&raw=1)

### Gravação
![video.gif](https://firebasestorage.googleapis.com/v0/b/smart-ordr.appspot.com/o/ezgif.com-resize.gif?alt=media&token=3d9a010b-ba52-4045-a24e-cb3078e2a2f1)
### Dependencias

This project is built with various awesome open sourced libraries

* [google_maps_flutter](https://pub.dev/packages/google_maps_flutter) -  to show map on screen (Still in beta version)
* [flutter_bloc](https://pub.dev/packages/flutter_bloc) - to mantain state and make every widget independent using blocs 
* [bloc](https://pub.dev/packages/bloc) - to listen events on taps by user and dispatch new state to other widgets
* [equatable](https://pub.dev/packages/equatable) - to make models comparable (Nice Library) 
* [shimmer](https://pub.dev/packages/shimmer) - to show nice loading effect
* [location](https://pub.dev/packages/location) - to get current location of user (Feature to be developed)


### Instalação

Add your API_KEY and your own credentials from your firebase project to android and ios folders. Run following command in cmd and then run your app

```sh
$ pub get
```
### Creditos
Kudos to [Dibbendo Pranto](https://dribbble.com/Dibbendopranto) for this design.


### Desenvolvedor

We are a team of digital nomads who believe in open-source development and free-for-all products.
We welcome anyone who is genuine and interested in developing great product that solve real world problems.

You can get in touch with us at dev@ocg.technology
