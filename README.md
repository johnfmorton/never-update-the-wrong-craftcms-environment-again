# Never update the wrong Craft CMS environment again

Make sure you're updating the right Craft CMS environment with some questionable graphic design choices.

## About these files

This directory is meant to be used with Craft CSM 5.x and the Control Panel CSS plugin: https://plugins.craftcms.com/cp-css?craft5.

1. Copy the `static` directory to your `web` directory or wherever you keep your public files for your Craft site.
2. Update your `.env` files in your local development and staging sites to include the `web` directory path. For example, `CP_CSS_PATH="/static/css/cp_dev.css` or `/static/css/cp_staging.css`. Leave it unset or blank for production.
3. Set the Control Panel CSS plugin to use the path to the CSS file with the `$CP_CSS_PATH` variable.

Read more at SuperGeekery.com.
