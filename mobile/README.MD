# Tindev Mobile
### Instalação

Instale todas as dependencias e inicie o servidor

```sh
$ cd mobile
$ npm install
```
### Rodar no Android Via USB ( Necessário ativar depuração USB)
```sh
$ adb reverse tcp:3333 tcp:3333
$ react-native run-android
```

### Rodar no IOS (Necessário ter um MacOS)
```sh
$ react-native run-ios
```