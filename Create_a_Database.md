# Creating a MySQL Database
Have lots of data that you need to store? Or want to send data between servers on your network? MySQL is the best way to do it!
Follow the steps below, and you'll have a database up and running in no time!

### Pre-Requisites
- At least 1 Minecraft Service
- Access to your server's [Pterodactyl Panel](https://panel.versatilenode.com/)
- Permission to add, create, and view databases on the panel

### Creating a Database
Creating a database is super easy! Follow these 6 easy steps and you'll have a database in no time!

1. **Step 1:** Login to your game panel
> 💡 **Tip:** You can find the panel login at [https://panel.versatilenode.com/](https://panel.versatilenode.com/)
2. **Step 2:** Select the server you want to create a database on your list of servers
3. **Step 3:** Select the `Databases` Tab at the top of the Game Panel
4. **Step 4:** Select the `New Database` button on the right-hand side
5. **Step 5:** Give your database a memorable name, something that you'll remember, such as `punishments`, or `permissions`, etc.
6. **Step 6:** Ta-Da! You now have a new MySQL Database! 🎉
> ⚠ **Warning:** it is not recommended to change the `Connections From` field, this can cause issues!


### Connecting a plugin to your database
When creating a network of servers, you're going to want to pass data about players between them, right?
Follow the steps below to connect a plugin to your new database.

1. **Step 1:** Login to your server's FTP.
2. **Step 2:** Locate the plugin folder that you would like to connect to the database
3. **Step 3:** Open it's respective settings, or config file, ususally named `config.yml`.
4. **Step 4:** Find the section about connecting to MySQL, or some form of `Database Connection Settings`.

5. **Step 5:** If your plugin asks for a `storage-method`, type `MySQL` in the field
6. **Step 6:** In the `IP` or `Address` field, copy the `Endpoint` address on your Database panel, making sure to remove the `:3306` from the end, as most plugins do not require this.
7. **Step 7:** In the `database-name` (or similar) field, copy the name from your panel (usually in the format `sxxxx_<YourDatabaseName>`)
8. **Step 8:** In the username field, copy and paste the `username` value from the panel, on the right.
9. **Step 9:** Finally, for the password field, press the 👁 icon, and copy the 2nd-to-last value, labelled `Password` into the password field of your chosen plugin.
10. **Step 10:** Reboot your server
11. **Step 11:** Ta-da! You should now have a plugin that successfully connects to your database! 🎉

### Notes
- If your plugin has an option to `Disable SSL Connections`, this is recommended, as SSL isn't support on MySQL at this time.

### Need Assistance?
Still need assistance? Don't worry! Reach out to us using the links below, and we'll help you as soon as we can!

- Our Discord: https://discord.versatilenode.com/
- Submit a ticket on our webiste: https://billing.versatilenode.com/submitticket.php/
