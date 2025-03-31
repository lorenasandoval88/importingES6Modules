# importingES6Modules
examples of es6 module imports

// const Plotly =   (await import('https://cdn.jsdelivr.net/npm/plotly.js-dist@3.0.1/plotly.min.js'))

// const plotly = (await import('https://cdn.jsdelivr.net/npm/plotly.js-dist@3.0.1/+esm')).default

// import * as Plotly from 'https://cdn.jsdelivr.net/npm/plotly.js-dist@3.0.1/plotly.min.js'

// const Plotly = (await import("https://cdn.plot.ly/plotly-latest.min.js"))

const Plotly = (await import('https://cdn.jsdelivr.net/npm/plotly.js-dist/+esm')).default
