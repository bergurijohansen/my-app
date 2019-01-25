# How to

## package.json

```
 "homepage": "https://taniarascia.github.io/react-tutorial",
```
and into scripts add:
```  
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```
## terminal

write these commands

```
npm install --save-dev gh-pages
```

remember to push the package json file to github

```
npm run build

npm run deploy
```
