# Neighborhood Guides site

This uses Vue and Webpack. Particularly, it was generated through `vue-cli`. [More info about this particular setup.](http://vuejs-templates.github.io/webpack/index.html)

Here is some auto-generated help:

## Build Setup
    
    # install dependencies
    npm install
    
    # serve with hot reload at localhost:8080
    npm run dev

    # build for production with minification
    npm run build

For detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Notes from Dan
`index.html` here should probably not be touched by us; webpack (I think) will put the whole site we build into there.

You can probably ignore `build`, `config`, `package.json`, `static`, and `test` too. All our code goes in `src`, I think.

`index.html`, despite the name, is not that important. Nor is `src/main.js`.

Things in `src`:

- `App.vue` is the main UI overview page.
- `components` is where UI components go.
- `assets` is where I've been putting our data files.
- `main.js` was autogenerated, we don't have to touch it I don't think.
- `store` is where the Vuex store (the state cotainer) goes.
