# Project Title

Link to the page: [https://ictys.github.io/GDPR/](https://ictys.github.io/GDPR/)

## Used Technologies

### HTML
- [.htaccess & robots.txt (HUN)](https://wpsuli.hu/spam-bot-ellenes-htaccess-es-robots-txt/)
- [Document templates (HUN)](https://hellowp.io/hu/k/becsuletkasszas-termek/)

### SASS / CSS
- [Color Picker](https://imagecolorpicker.com/)
- [Accessibility (A11y) Tools](https://color.adobe.com/create/color-contrast-analyzer)
- [Autoprefixer](https://autoprefixer.github.io/) - Autoprefix the CSS code

### TypeScript / JavaScript
- [UglifyJS](https://skalman.github.io/UglifyJS-online/) - Minify the JS code

## How to Compile / Transpile the SCSS and TS Code

First, install the necessary global packages:

```bash
npm install -g sass typescript
```

Verify the installations:

```bash
tsc --version
sass --version
```

Compile SCSS to CSS:

```bash
sass styles/style.scss styles/style.css --embed-source-map --watch --style=compressed
```

Transpile TypeScript to JavaScript:

```bash
tsc scripts/script.ts --target es5 --inlineSourceMap --watch --allowJs --resolveJsonModule --esModuleInterop
```
