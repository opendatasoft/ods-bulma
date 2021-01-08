## ODS-Bulma

This kit helps ODS CSMs and Labs team to generate a patched version of [Bulma CSS Framework](https://bulma.io/).

It presets many variables with desired font sizes, colors, spacing values etc...
Then, fix conflict between Bulma and ODS stylesheets.

It generates in `/export` folder the CSS file `main.css` (for testing/debugging etc...) and the minified version `ods-bulma.min.css` ready to copy paste into your domain.


### Generate ods-bulma patched css file

While you have node / npm / postcss-cli installed globally, simply run :
 
```
npm run build
```


### Get ods-bulma into your domain

Get this already generated file [ods-bulma.min.css](export/ods-bulma.min.css)

Copy the raw content and paste it into your domain theme stylesheet.

Save, make live.
