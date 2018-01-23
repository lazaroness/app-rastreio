# app-rastreio

**Aplicativo Desktop para rastreamento de objetos dos correios.**

```bash
# Clone este repositório
git clone https://github.com/lazaroness/app-rastreio.git
# Entre no repositório
cd app-rastreio
# Instale as dependências
npm install
# Execute o aplicativo
npm start
```

# Install Linux

```
su -
npm install -g electron-packager
electron-packager . app-rastreio --platform linux --arch x64 --out /usr/share/
mv /usr/share/app-rastreio-linux-x64/ /usr/share/app-rastreio/
cd /usr/share/app-rastreio/
cp resources/app/img/app-rastreio.png /usr/share/icons
cp resources/app/app-rastreio.desktop /usr/share/applications/app-rastreio.desktop
```

![Inicial](./img/app-linux.png)

[Executando](./video/app.mp4)

[![Executando a aplicação](./img/app-linux.png)](./video/app.mp4)

[![Little red ridning hood](http://i.imgur.com/7YTMFQp.png)](https://vimeo.com/3514904 "Little red riding hood - Click to Watch!")
<!--![Inicial](./img/app-win.png)-->

## Licença

[CC0 1.0 (Public Domain)](LICENSE.md)
