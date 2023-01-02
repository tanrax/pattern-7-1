**Pattern Template 7-1**, an extraordinarily neat architecture that any Web Designer can understand at a glance. Structure with the help of SASS syntax (**.sass extension**).

``` txt
sass/                    
|    
|– abstracts/                   
|   |– _mixins.sass     
|   |– _variables.sass   
|– base/              
|   |– _base.sass   
|   |– _fonts.sass   
|   |– _helpers.sass
|   |– _typography.sass
|– components/   
|   |– _alert.sass     
|   |– _button.sass        
|   ...
|– layout/                
|   |– _footer.sass
|   |– _header.sass
|– pages/                
|   |– _home.sass        
|   ...
|– themes/                
|   |– _dark.sass        
|   |– _light.sass     
|– vendors/                
|   |– _normalize.sass       
|   |– _owl-carousel.sass
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

## Other variants

- [Pattern 7-1 with Split media](https://github.com/tanrax/pattern-7-1-with-split-media): The best, highly recommended ❤️)
- [Pattern 7-1](https://github.com/tanrax/pattern-7-1): Standard. **Not responsive design**.
- [Pattern 7-1 Lite with Split media](https://github.com/tanrax/pattern-7-1-lite-with-split-media): Simplified version for students or very small web sites.
- [Pattern 7-1 Lite](https://github.com/tanrax/pattern-7-1-lite): Simplified version for students or very small web sites. **Not responsive design**.

