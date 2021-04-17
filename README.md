# vue-exam

codigo para img
<img :src="getIconPath(autoEncontrado.imagen)" />

en methods:
getIconPath(iconName) {
      return iconName ? require(`../assets/img/${iconName}`) : "";
    },

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
