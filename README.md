# Adobe themed org/reveal presentation

## Basic setup

Install node.js on your machine

```bsh
brew install nodejs
```

In the `reveal.js` directory, install gulp

```bsh
npm install gulp
```

In the `reveal.js` directory, generate the css-themes to create `dist/theme/adobe.css` from `css/theme/source/adobe.scss`

```bsh
node ./node_modules/gulp/bin/gulp.js css-themes
```

## Steps

- Modify `background-title.psd` to your liking and export it to `background-title.png`.
