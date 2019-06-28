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
* need to make change to style.scss in the Themes Folder
  1. @import 'uswds' Change  to '../uswds'
  2. add @import 'uswds-theme-components'
----------------------------------------------------------------------------------------------------------------------------------
