# React application setup with Vite
---
### Initialize Vite + React
```bash
npm create vite@latest
```

 1. Enter name of project
 2. Select React
 3. Select TypeScript

### cd into project folder
```bash
  cd <project-name>
  npm install
  npm run dev
  ```

### Create git repository
```git
git init
git add .
git commit -m "Initial Commit"
```

## Clean up file structure
- Remove vite.svg in Public Folder
- Delete Assets folder
- Delete App.css
- Delete index.css

#### Current File Stucture
```
public
scr
    - App.tsx
    - main.tsx
.eslintrc.cjs
.gitignore
index.html
package-lock.json
package.json
tsconfig.node.jason
vite.config.ts
```

## Resolve errors from deletions
### in main.tsx
Delete everything in app.tsx

Replace with:
```javascript
export default function App(){
  return <h1>Hello world</h1>
}
```

In main.tsx remove:
```javascript
import './index.css'
```