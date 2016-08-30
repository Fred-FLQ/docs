#Customizing user profile

##Change default cover image

*Note: as of today, there is no method to change the default cover image through admin panel. For now, you will need to use a ftp client like [FileZilla](https://filezilla-project.org/) to replace the files manually.*

There are 2 ways to change the default cover image. You can replace it either directly in the plugin directory, or create a special folder in your active theme directory (parent theme even if you use a child theme).

###Method 1: Replacing default cover image directly in the plugin directory

*Note: By using this method, you will loose your custom cover image everytime you update the plugin. Please keep at hand a backup of your image (both sizes) to upload it after each update.*

With your ftp client or prefered method, access your site files directory and:

1. Go to .../wp-content/plugins/anspress-question-answer/theme/default/images/;
2. Dowload the files "cover.jpg" and "small_cover.jpg" to your computer;
3. Edit them per your needs or create brand new ones (same size, same name and save them as jpg);
4. Upload your custom "cover.jpg" and "small_cover.jpg" to .../wp-content/plugins/anspress-question-answer/theme/default/images/ to replace the default ones;
5. ... done!

###Method 2: Adding new default cover image in current theme

*Note: By using this method, you will loose your custom cover image everytime you update you theme. **It doesn't matter if you have a child theme because the images need to be uploaded to parent theme directory**. Please keep at hand a backup of your image (both sizes) to upload it after each update.*

With your ftp client or prefered method, access your site files directory and:

1. Dowload the default cover files: [AnsPress cover image](https://github.com/anspress/anspress/raw/master/theme/default/images/cover.jpg) and [AnsPress small cover image](https://github.com/anspress/anspress/raw/master/theme/default/images/small_cover.jpg);
2. Edit them per your needs or create brand new ones (same size, same name and save them as jpg);
3. Go to .../wp-content/themes/your_active_theme/ (Important: if you use a child theme, **go to the parent theme folder**);
4. Create a new folder called "anspress";
5. Go to .../wp-content/themes/your_active_theme/anspress/;
6. Create a new folder called "images";
7. Go to .../wp-content/themes/your_active_theme/anspress/images/;
8. Upload your custom "cover.jpg" and "small_cover.jpg";
9. ...done!


