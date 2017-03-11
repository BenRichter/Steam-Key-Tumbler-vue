# Steam-Key-Tumbler-vue
<p align="center">
  <br><br><strong>Steam Key Tumbler</strong> get unused steam keys from your community <br>(based on Vuepack which uses Vue 2, Vuex, Vue-router and Webpack 2)
</p>


# steam-key-tumbler

To start:

```bash
$ yarn install
```

To develop:

```bash
$ yarn run dev
```

To build for production:

```bash
$ yarn run build
```

To lint you code:

```bash
$ yarn run lint
```

---

Generated by [VuePack](https://github.com/egoist/vuepack).
Check out [the docs](https://github.com/egoist/vuepack/tree/master/docs) for more usages.


## Folder Structure

If you did not enable Eletron support, the dest folder is `./dist`, otherwise it's `./app/dist`. 

`./app` folder only exists when you enabled Electron support.

```bash
├── app             # the actual app you want to bundle with Electron
│    ├── dist       # directory which contains all bundled files
│    └── index.js   # entry file for Electron
├── build           # webpack configs and other scripts
├── client          # client-side app files
├── dist            # bundled files and index.html
│    ├── index.html
│    └── [...other bundled files]  
├── tests           # e2e tests written by testcafe 
├── node_modules    # dependencies
└── package.json    # package info
```

## Custom template

You want to customize the output of `index.html`, simply modify [index.html](https://github.com/egoist/vuepack/blob/master/template/build/index.html), see more at [html-webpack-plugin](https://github.com/ampedandwired/html-webpack-plugin).

## License

MIT &copy; [EGOIST](https://github.com/egoist)
