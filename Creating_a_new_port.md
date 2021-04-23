# Creating a new port (allocation) on your server, and how to use it
Need to create a new port, or want to change your existing server port? Well this guide will show you how!
Follow the steps below and you'll have a new port in no time!

> 💡 **Tip:** Ports can be used to allow another application to run on your server, such as **Dynmap**. However, setting a new primary port will change the port you use to connect to your server!

> 🚨 **WARNING:** If you set a new primary port, you will have to restart the server, and let all of your players the new IP of the server, or update your Domain DNS Records!


### Pre-Requistes
- At least 1 Minecraft Service
- Access to the **Network** section on the [Game Panel](https://panel.versatilenode.com/)

### Getting Started
Follow the steps below to create a new port in no time!

1. **Step 1:** Login to the [Game Panel](https://panel.versatilenode.com/)
2. **Step 2:** Select your desired server in the server list
3. **Step 3:** Select the `Network` tab at the top of the panel
4. **Step 4:** Select the `Create Allocation` button
5. **Step 5:** Give the new port a description
6. **Step 6:** Ta-da! You now have a new port allocated to your server! 🎉

### Notes
- Selecting the `Make Primary` button on any other ports will change the main port of the server, which is what your players use to connect. If you change the port, you will have to update your domain's DNS records
- You do not have to "Activate" or make any ports primary for them to work. As long as you specify the correct port in the config, applications such as Dynmap are able to run
- If 2 applications or plugins are set to use the same port, you will experience issues! Ensure you only use a port for 1 thing!

### Need Assistance?
If you need help with making and setting up a port, or anything else written in this article, don't hesistate to reach out to our support team!

- Our Discord: https://discord.versatilenode.com/
- Submit a Ticket: https://billing.versatilenode.com/submitticket.php
