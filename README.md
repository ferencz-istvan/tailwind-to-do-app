->npm node package install
(npm init -y) with this code in terminal we created a package.json file.
-> (npm i browserify) - we installed browserify to our node modules. This package can transform  modules (whose  needs "require" keyword) to a single js file, which is understandable for browser
-> run the script with "npm run build", this script is written in package.json file. 
-> this build script is configuring the js file only once
-> we can automate that build script with an other dependency (watchify)
-> after installing watchify (npm i watchify) we wrote a script {"watch": "watchify ./src/app.js -o ./public/bundle.js",} to package.json
-> {npm run watch} script starts a whatch session in terminal, therefore with saving our js file, the output js file will automaticaly update
-> with intalling tailwindCSS we used "Tailwind CLI
" method.