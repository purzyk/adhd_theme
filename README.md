```bash
npm run install
```

npm run dev
npm run build

## FAQ

1. **How can I do inline `background-image: url()` using local images?**

   Webpack won't be aware of the asset you're trying to load by using the normal syntax so you'll have to 'import' the image and then apply it as a background: `style="background-image: url('${require('path/to/image')}');"`.
