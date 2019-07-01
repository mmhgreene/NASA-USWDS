--US Web design system on windows--
1. install git
2. install node
3. run git clone on uswds rep 
4. run command in uswds folder(npm init)
5. run command in uswds folder(npm install)
6. install npm package sass in project folder (npm install sass)
7. run program git bash 
8. run command in git bash within the uswds folder (fractal start --sync)
9. run program node.js command prompt.
10. run command in node.js command prompt within uswds folder (sass --watch input.scss output.css) 
11. Now you can make changes to the SCSS files within the Themes folder and it will be compiled.
----------------------------------------------------------------------------------------------------------------------------------
* if you used the command (npm install --save uswds@latest) SCSS files are located in -../node_module/uswds/dist/scss/
* if you used git clone the scss files are located in - uswds/src/stylesheets
* if you used the command (npm install --save uswds@latest) CSS files are located in - ../node_module/uswds/dist/css
----------------------------------------------------------------------------------------------------------------------------------
Need to make change to style.scss in the Themes Folder
  1. @import 'uswds' Change  to '../uswds'
  2. add @import 'uswds-theme-components'
----------------------------------------------------------------------------------------------------------------------------------
Changes Made to the _uswds-theme-color.scss file founded in the Theme folder
* Change the varible value of $theme-color-primary from 'blue-60v' to 'blue-warm-60v'
* Change the varible value of $theme-color-base from 'gray-cool-50'to 'gray-cool-90'
* Change the varible value of $theme-color-secondary from 'red-50' to 'red-50v'
* Change the varible value of $theme-color-accent-cool-light to 'blue-20v'
* Change the varible value of $theme-color-accent-cool to 'blue-30v'
* Change the varible value of $theme-color-accent-cool-dark to 'blue-50'
* Change the varible value of $theme-color-accent-cool-darker to 'blue-70v'
* Change the varible value of $theme-color-warning-lighter to 'gold-5v'
* Change the varible value of $theme-color-warning-light to 'gold-20v'
------------------------------------------------------------------------------------------------------------------------------------------
Changes Made to the _uswds-theme-typography.scss file founded in the Theme folder
 * Change the varible value of $theme-font-type-lang from False to 'helvetica'
 * Change the varible value of $theme-font-role-heading from 'serif' to 'lang'
 * Change the varible value of $theme-h3-font-size from 'lg' to  10
 * Change the varible value of $theme-h4-font-size from 'sm' to  8
 * Change the varible value of $theme-h5-font-size from 'xs' to  'sm'
 * Change the Varible value of $theme-h6-font-size from '3xs' to 'xs'
 
 ---------------------------------------------------------------------------------------------------------------------------------------
 Where things live
* Sytle.scss
  * ../scss/theme/Sytle.scss
* uswds.min.css
  * ../css/uswds.min.css
* _uswds-theme-color.scss
  * ../scss/theme/_uswds-theme-color.scss
* _uswds-theme-typography.scss
  * ../scss/theme/_uswds-theme-typography.scss
  
