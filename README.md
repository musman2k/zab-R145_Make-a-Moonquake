# zab-R145_Make-a-Moonquake

![Moonkit](https://github.com/musman2k/zab-R145_Make-a-Moonquake/assets/89705011/d5cf0b44-0736-4cd8-ae52-66464450a51a)


This is an Interactive 3D moon that was created with Three.js.


---

## Setup

Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

```bash
# Install dependencies
npm install

# Update Browserslist Database
npx browserslist@latest --update-db

# Update Dependencies
npm update postcss css-loader mini-css-extract-plugin

# Install Compatible Versions
npm install postcss@8 css-loader@6 mini-css-extract-plugin@2

# Clear Node Modules and Cache
npm cache clean --force
npm install

# Use Environment Variable in PowerShell
$env:NODE_OPTIONS="--openssl-legacy-provider"

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```
