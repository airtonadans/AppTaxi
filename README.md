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

Este projeto é construído com várias bibliotecas de código aberto incríveis

* [google_maps_flutter](https://pub.dev/packages/google_maps_flutter) - para mostrar o mapa na tela (versão beta)
* [flutter_bloc](https://pub.dev/packages/flutter_bloc) - para manter o estado, tornar cada widget independente usando blocos
* [bloc](https://pub.dev/packages/bloc) - para ouvir eventos em toques por usuário e despachar novo estado para outros widgets
* [equatable](https://pub.dev/packages/equatable) - para tornar os modelos comparáveis ​​(Nice Library)
* [shimmer](https://pub.dev/packages/shimmer) - para mostrar bom efeito de carregamento
* [location](https://pub.dev/packages/location) - para obter a localização atual do usuário (Recurso a ser desenvolvido)

### Instalação

Adicione sua API_KEY e suas próprias credenciais do seu projeto do Firebase às pastas android e ios. Execute o seguinte comando em cmd e, em seguida, execute seu aplicativo

```sh
$ pub get
```
### Creditos
To [Dibbendo Pranto](https://dribbble.com/Dibbendopranto) for this design.


### Desenvolvedor

Uma equipe de nômades digitais que acreditam no desenvolvimento de código aberto e produtos gratuitos para todos. Congratulamo-nos com qualquer um que seja genuíno e interessado em desenvolver ótimos produtos que resolvam problemas do mundo real.

Você pode entrar em contato com a equipe em dev@ocg.technology
