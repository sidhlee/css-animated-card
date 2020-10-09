# Animated card with HTML & CSS

from Kevin Powell's tutorial series
[part1-html & css](https://www.youtube.com/watch?v=YmyqlM13JUU&ab_channel=KevinPowell)

## Parcel Setup

First create a `package.json` file in your project directory

```bash
yarn init -y
```

Then, install parcel locally as a dev dependency

'''bash
yarn add parcel-bundler --dev
'''

Add task scripts to `package.json`

```json
{
  "scripts": {
    "dev": "parcel index.html",
    "build": "parcel build index.html"
  }
}
```

Start development server by

```bash
yarn dev
# or
yarn run dev
```
