#Font icons

AnsPress includes a customized set of icons coming from [IcoMoon](https://icomoon.io/). You can either just use some of the included icons, expand the set with new icons or use a custom icons library like FontAwesome.

##Using included set of icons

You can find all included font icons on the [AskBug theme demo page](https://demo.anspress.io/askbug/wp-content/themes/askbug/anspress/fonts/demo.html). To use them, just copy their class name (for example "apicon-home") and add it to the targeted "class" element in your html code. Here are some examples.

####Example #01 : &lt;span&gt; tag

        <span class="apicon-category"></span>

####Example #02 : &lt;i&gt; tag

        <i class="apicon-category"></i>
    
####Example #03 : link
    
        <a href="https://anspress.io/user/john-doe/about/" class="ap-user-menu-about apicon-home">About</a>

##Adding more icons to included set

You can easily add new icons to AnsPress default set by using the IcoMoon library.

1. Go to [IcoMoon app](http://icomoon.io/app).
2. Drag and drop the **anspress.svg** file located in /wp-content/plugins/anspress-question-answer/theme/default/fonts/fonts to the IcoMoon window open in your browser.
3. Select **all** icons from the AnsPress set using the hamburger menu on the right.*(Note: not selecting all of AnsPress default icons might result in display issues - it is **NOT** recommended)*
4. Select any other icons you need on the page.
5. Click on « **Generate Font** » at the bottom of the screen.
6. Check everything is ok and click on « **Download** » at the bottom of the screen.
7. Unzip the downloaded file and find the « **Fonts** » folder (icomoon > Fonts).
8. Rename all 4 files to « anspress » instead of « icomoon » (be careful not delete files extension).
9. Replace the 4 files in located in /wp-content/plugins/anspress-question-answer/theme/default/fonts/fonts with the 4 files you just dowloaded and renamed.

You should now be able to use the class of any icon you added to the set.

##Using a different icons library - Example with FontAwesome

If you wish to use a different icons library than Icomoon, you can do so by following instructions from said library. For the purpose of clarity, let's see one way to include the FontAwesome library in your website.

1. Go to [FontAwesome Get Started page](http://fontawesome.io/get-started/).
2. Download FontAwesome by clicking on the "Download" button in the [Download & Customize section](http://fontawesome.io/get-started/#get-started-download).
3. Unzip the file and copy the entire *font-awesome* directory into your project.
4. In the &lt;head&gt; of your html, reference the location to your *font-awesome.min.css* like this:

        <link rel="stylesheet" href="path/to/font-awesome/css/font-awesome.min.css">
5. You can now used your icons the same way as the IcoMoon library or you can find new ideas by checking [FontAwesome Examples page](http://fontawesome.io/examples/).