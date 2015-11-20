# Installation and basic config

This topic will guide you for easy installation and configuration of AnsPress.

![](http://localhost/wp3/wp-content/themes/site/images/anspress_install.gif)

### Installation
---

You can simply install it from WP plugin repository
e.g.

**Using The WordPress Dashboard**

1. Navigate to the 'Add New' in the plugins dashboard
2. Search for 'AnsPress'
3. Click 'Install Now'
4. Activate the plugin on the Plugin dashboard

**Uploading in WordPress Dashboard**

1. Download the latest release of AnsPress from http://github.com/anspress/anspress
2. Navigate to the 'Add New' in the plugins dashboard
2. Navigate to the 'Upload' area
3. Select downloaded zip in step one, from your computer
4. Click 'Install Now'
5. Activate the plugin in the Plugin dashboard

**Using FTP**

1. Download `anspress-question-answer.zip`
2. Extract the `anspress-question-answer` directory to your computer
3. Upload the `anspress-question-answer` directory to the `/wp-content/plugins/` directory
4. Activate the plugin in the Plugin dashboard

### Basic config
---

After activating AnsPress make sure to check must have extensions of AnsPress here http://anspress.io/extensions/.

** Base page **

Anspress output everything from shortcode `[anspress]`, so you must have a base page selected in AnsPress options. By default AnsPress check and create a base page while installing. if you want to create it manually follow this steps:

1. Goto WordPress admin and create a new page.
2. You can set page slug to anything you want.
3. Now save the page.
4. Go to `WP-admin -> AnsPress -> Options` and select base page you just created in above steps.
5. Save the option.

**Menu and links**

AnsPress adds new links section in WordPress menu editor `wp-admin->appearance->Menu`. This section contain links:
- Questions (base page)
- Ask (create new question page)
- Users (shows members directory)
- Categories (shows all categories of question, only available if categories extension installed)
You can simply add this links to your theme menu. and save the menu.


