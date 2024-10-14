You have to clone .env.template and rename it to .env and do some changes if you need  
You can change php-version for wp in docker-composer (string 19) 

Work folders put into 
- ./wp-content/themes for themes
- ./wp-content/plugins for plugins

Don't forget to add your theme and plugin into .gitignore with "!" before

To change php version you need to update docker-compose.yml (string 20). To change upload max filesize you have to edit upload.ini (strings 3 and 4)
