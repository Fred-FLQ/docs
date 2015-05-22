#Theme override

AnsPress makes it easy to customize layout. Everything inside a theme folder can be easily overridden. Never directly edit AnsPress files in plugin directory because you'll loose all change while updating.

**Override folder**

1. Create a folder called `anspress` inside your active theme folder. NOTE: must be created inside parent theme, not child theme.
2. Now you can copy files you want to modify from `wp-contents\plugins\anspress-question-answer\theme\default\`.

You must keep the same directory structure if you are modifying sub-folder item. Like if you want to modify `theme\default\css\overrides.css` then in your override folder it should be `anspress\css\overrides.css`.

**Overriding CSS**

For adding or overriding AnsPress styles we suggest to use `overrides.css`. This file is initially left blank so you can add your own styles here.

If you still need help please feel free to ask here http://anspress.io/questions/ask .
