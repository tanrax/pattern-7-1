**Pattern Template 7-1**, an extraordinarily neat architecture that any Web Designer can understand at a glance. Structure with the help of SASS syntax (**.sass extension**).

``` txt
sass/                    
|    
|– abstracts/                
|   |– _functions.sass        
|   |– _mixins.sass     
|   |– _variables.sass   
|– base/              
|   |– _base.sass   
|   |– _fonts.sass   
|   |– _helpers.sass
|   |– _typography.sass
|– components/                
|   |– _button.sass        
|   ...
|– layout/                
|   |– _footer.sass
|   |– _header.sass
|– pages/                
|   |– _home.sass        
|   ...
|– themes/                
|   |– _default.sass        
|   ...
|– vendors/                
|   |– _normalize.sass        
|   ...
`– main.sass             
```

# Compile SASS.

## Install

``` bash
yarn global add node-sass
```

## Run

``` bash
node-sass --output-style compressed sass/main.sass css/main.css
```

## Watch: Autocompile if it detects changes 

``` bash
node-sass --watch --source-map true --output-style compressed sass/main.sass css/main.css
```

**Note:** This template has been created with the help of SASS lang official style guides and [HugoGiraudel](https://github.com/HugoGiraudel/sass-boilerplate) repository. 
