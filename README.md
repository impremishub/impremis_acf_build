# Impremis WP Starter Theme (Updraft Files)
 Impremis WP Starter Theme (Updraft Files)

# Step 1:
- Download these files

# Step 2:
- Install Fresh Copy of WordPress
- Install Updraft Plugin
- In the "wp-config.php" file, define the WP_HOME and WP_SITEURL with the domain name

# Step 2:
- Create a Backup
- Go to: Dashboard > Settings > UpdraftPlus Backups: http://localhost:8813/wp-admin/options-general.php?page=updraftplus&tab=backups
- Upload the Downloaded Files

# Step 3:
- After uplaoding, select the generated backup
- Click "Restore"
- Finish the resporation

# Step 4:
- You will be asked to login to your dashboard
- If you can't, it means that the Site URL needs to be updated
- When this happens, you need to update the "wp_options" table with your domain

# Step 5:
- Once done, Login to your Dashboard
- Then go to "wp-content/themes" and change the theme's folder name with your Project's Name
