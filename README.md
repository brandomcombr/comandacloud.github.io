## Comanda Cloud APP - IONIC 5

---

#### Instalação do CLI mais recente

```js
$ npm uninstall -g ionic
$ npm install -g @ionic/cli
```

---

## Ionic APIs do projeto

#### Comando para executar na empresa antes de instalar API

```js
$ set NODE_TLS_REJECT_UNAUTHORIZED=0
```

---

#### Criando novo projeto em Ionic

```js
$ ionic start comanda-cloud-app blank
```

---

1. Quando criar um novo projeto ionic5 em angular é preciso instalar a última versão do angular no projeto

```js
$ npm install @ionic/angular@latest --save
$ ng add @ionic/angular
```

---

2. atualizar o arquivo tsconfig.json

```js
{
  //...
  compilerOptions: {
    "skipLibCheck": true,
    //...
  }
}
```

---

3. Instalação AngularFire2 https://github.com/angular/angularfire/

```js
$ npm install @angular/fire firebase --save
```

---

4. Instalação do Storage

```js
$ ionic cordova plugin add cordova-sqlite-storage
$ npm install --save @ionic/storage
```

---

---

5. Instalação do Insomnia

```js
$ ionic cordova plugin add cordova-plugin-insomnia
$ npm install @ionic-native/insomnia
```

---

6. Instalação do Appcenter

```js
$ cordova plugin add cordova-plugin-appcenter-analytics
$ cordova plugin add cordova-plugin-appcenter-crashes
```

# config.xml

```xml
<platform name="android">
  <preference name="APP_SECRET" value="4b136c5d-7689-4dec-819e-f7cab0741e14" />
</platform>
```

---

7. Instalação do InAppBrowser

```js
$ ionic cordova plugin add cordova-plugin-inappbrowser
$ npm install @ionic-native/in-app-browser
```

---

8. Instalação do Bluetooth Serial

```js
$ ionic cordova plugin add cordova-plugin-bluetooth-serial
$ npm install @ionic-native/bluetooth-serial
```

---

9. Instalação do Social Sharing

```js
$ ionic cordova plugin add cordova-plugin-x-socialsharing
$ npm install @ionic-native/social-sharing
```

---

10. Instalação do AdMob Free

```js
$ ionic cordova plugin add cordova-plugin-admob-free --variable ADMOB_APP_ID="<YOUR_ADMOB_APP_ID_AS_FOUND_IN_ADMOB>"
$ npm install @ionic-native/admob-free
```

---

11. Instalação do Google charts

```js
$ npm install ng2-google-charts --save
```

---

11. Instalação do ngneat transloco

```js
$ ng add @ngneat/transloco // adiciona o plugin
$ en, es, pt-PT, pt-BR // quais idiomas vai utilizar
```

---

12. Instalação do Globalization

```js
$ ionic cordova plugin add cordova-plugin-globalization
$ npm install @ionic-native/globalization
```

---

12. Instalação do Native Audio

```js
$ ionic cordova plugin add cordova-plugin-nativeaudio
$ npm install @ionic-native/native-audio
```

---

13. Instalação do Device

```js
$ ionic cordova plugin add cordova-plugin-device
$ npm install @awesome-cordova-plugins/device
$ npm install @awesome-cordova-plugins/core
```

---

##### [markdown-it demo](https://markdown-it.github.io/)
