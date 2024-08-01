Namaste React 

Parcel
- Dev build
- Local Server
- HMR = Hot Module Replacement
- File Watching Algorithms - written in C++
- Caching - Faster Builds
- Image Optimization
- Minification
- Bundling
- Compress
- Consistent Hashing
- Code Splitting
- Differential Bundling - support older browsers
- Diagnostic
- Error Handling
- HTTPs
- Tree Shaking - remove unsed code
- Different dev and prod Bundles

While building using Parcel
- Command = npx parcel build index.html
  Before running this command remove "main": "App.js" from package.json otherwise it will throw an error, because it's automatically generated for you.

browsersList: [
    "Last 2 Chrome version",
    "Last 2 Firefox version",
    "Last 2 versions"
]

Check official documentation and github readme file

JSX(transpilled before it reaches to JS) - Parcel - Babel
JSX is not HTML in JavaScript, it's syntax is similar to XML