# Installation

```bash
npm install -D parcel-plugin-text
```

# Configuration
If you need to handle others extensions than the default one —*`.txt`*, put a file called `.parcel-plugin-textrc` at the root of your package *— or create an entry `parcel-plugin-text` in your `package.json`* — and set it to a json having the following structure:

```json
{
  "extentions":[
    "vueml",
    "svgsprt",
    "text"
  ]
}
```
