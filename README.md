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

![Executando](./video/app.webm)

<!--![Inicial](./img/app-win.png)-->

## Licença

[CC0 1.0 (Public Domain)](LICENSE.md)
