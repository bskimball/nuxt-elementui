module.exports = {
  /*
  ** Headers of the page
  */
  head: {
    title: 'nuxt-elementui',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: 'Nuxt.js project' }
    ],
    link: [
      { rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }
    ]
  },
  /*
  ** Customize the progress-bar color
  */
  loading: { color: '#20a0ff' },
  /*
  **  CSS Imports
   */
  css: ['element-ui/lib/theme-default/index.css'],
  /*
  ** Build configuration
  */
  build: {
    /*
    ** Babel
     */
    babel: {
      'presets': ['vue-app'],
      'plugins': [
        ['component', [{
          'libraryName': 'element-ui',
          'styleLibraryName': 'theme-default'
        }]]
      ],
      'comments': false
    },
    /*
    ** Run ESLINT on save
    */
    extend (config, ctx) {
      if (ctx.isClient) {
        config.module.rules.push({
          enforce: 'pre',
          test: /\.(js|vue)$/,
          loader: 'eslint-loader',
          exclude: /(node_modules)/
        })
      }
    }
  },

}
