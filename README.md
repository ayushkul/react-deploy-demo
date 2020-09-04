## React Deploy Demo- ReactJS projects

https://ayushkul.github.io/react-deploy-demo

### Video Tutorial -

https://www.youtube.com/channel/UCbaR6YYn5VGXrR5_f-4tNsA

### Development steps-
1. Create React App using npx create-react-app
2. Add Github pages dependency
3. Add homepage url in package.json

    "homepage": "http://yuribenjamin.github.io/my-app"

4. Add deployment scripts in package.json

    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"

5. Add your project to a remote git repository

    git init
    git remote add origin git@github.com:{username}/{repo-name}.git

6. Now deploy it to GitHub Pages. just run the following command :

    npm run deploy
