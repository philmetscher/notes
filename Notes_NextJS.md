## Styling in Next JS

1. npm install styled-components
2. GlobalStyle(`components/GlobalStyle.js`) importieren und einbinden in `pages/_app.js`
3. Content aus Repo `next.config.js` holen
4. Content aus Repo `pages/_documnent.js` holen

## Fonts & Assets

### Font

1. Google Font Helper besuchen & Font runterladen
2. in `public/fonts` Ordner reinlegen
3. Regeln in `GlobalStyle.js` reinpacken & Pfad prüfen

### Assets

1. Asset (z. B. Image) runterladen
2. in `public/assets/images` Ordner reinlegen
3. referenzieren mit `/assets/images`
4. NextJS Config anpassen
5. Image Komponente von next nutzen <span style="font-size:.7rem">(optional)</span>
   1. weitere Infos [hier](https://nextjs.org/docs/api-reference/next/image)
