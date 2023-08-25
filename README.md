# Impremis WP Starter Theme (Updraft Files)
 Impremis WP Starter Theme (Updraft Files)

# Step 1:
- Download these files

# Step 2:
- Install Fresh Copy of WordPress
- Install Updraft Plugin
- In the "wp-config.php" file, define the WP_HOME and WP_SITEURL with your local domain name

# Step 3:
- Create a Backup
- Go to: Dashboard > Settings > UpdraftPlus Backups: [localdomain]/wp-admin/options-general.php?page=updraftplus&tab=backups
- Upload the Downloaded Files

# Step 4:
- After uplaoding, select the generated backup
- Click "Restore"
- Finish the resporation

# Step 5:
- You will be asked to login to your dashboard
- If you can't, it means that the Site URL needs to be updated
- When this happens, you need to update the "wp_options" table with your domain

# Step 6:
- Once done, Login to your Dashboard
- Then go to "wp-content/themes" and change the theme's folder name with your Project's Name
- Then open terminal
- Run "npm install"
- Run "npm run build"

# NOTES
- For additional guide, watch this loom video: https://www.loom.com/share/461e1f0336664555bed1f12832f2459c
  
