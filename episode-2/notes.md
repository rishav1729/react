# episode-2

● - What is `NPM`?
    -

● - What is `Parcel/Webpack/vite`? Why do we need it?
    - these are bundeler, it budles your app, it packages your app so that it properly ship your app.
    - create-reat app behind the scenes used webpack and babel.
    -      

● - What is `.parcel-cache`
    -

● - What is `npx` ?
    -
    
● - What is difference between `dependencies` vs `devDependencies`
    -dependencies -> used in prod also
    -devDependencies -> req. in developement only like- parcel in our case
    
● - What is Tree Shaking?
● - What is Hot Module Replacement?
● - List down your favourite 5 superpowers of Parcel and describe any 3 of them in your own words.
    -

● - What is `.gitignore`? What should we add and not add into it?
    -file which we want not to be upload/load to github

● - What is the difference between `package.json` and `package-lock.json`
    - package.json is a config. for npm, need -> keeps track of approx versions (according to  ^ - caret and ~ - tilda) of the packages installed in the system/project
    - package-lock.json -> it keep track of all the exact versions of  all the dependencies (including the packages's packages details also) with the hash i.e integrity attached to every dependency.

● - Why should I not modify `package-lock.json`?

● - What is `node_modules` ? Is it a good idea to push that on git?
    -collection of all dependencies
    -contains all the code that we fetched from npm while installing the packages/libraries.           

● - What is the `dist` folder?
● - What is `browserlists`

● -  What is transitive dependency?
    -dependecy that require other dependency to work. eg - parcel (other dependecy - babel, etc)
    -will create dependecy tree
