# Seeds explained
In this guide, you'll learn what a seed is, how to get the current seed, and how to force a seed on your multiplayer server!

### What is a seed?
A seed is a number ranging between 1 and 19 characters long number that decides how your minecraft world looks.
Some seeds are negative numbers, and some are positive. Each world created is fully unique and has its own number, infact, there are about **20,000,000,000,000,000,000**
different combinations of a seed, yes you read that, nearly 2 quintillion.

### How do I find the seed of my current world?
Finding the seed of your world is super easy! All you need to do is run a single command, like so:

![Executing the seed command](https://versatilenode-kb.kawaiicdn.com/assets/images/Jack/Seeds%20Explained/executing-seed-command.png?_t=1615667812)

and if you run the command correctly, you'll get an output similar to this, but instead, you'll have your world's seed in green instead of mine!

![/seed output](https://versatilenode-kb.kawaiicdn.com/assets/images/Jack/Seeds%20Explained/seed-output.png?_t=1615667809)

### How do I force a seed on my server?
Forcing a seed is also super easy, all you need is a way to connect to your server's file access. If you don't know how to connect to your server's sFTP, read [this guide]().
Once you are connected, follow these steps:
- Step 1: Once your server is setup, make sure to **STOP** your server.
- Step 2: Once it's offline, head into your servers files and find the **server.properties** file.
- Step 3: Find the **level-seed** value, and insert your desired string of numbers (aka. the seed you would like to force)

![Level Seed annotated 2](https://versatilenode-kb.kawaiicdn.com/assets/images/Jack/Seeds%20Explained/level-seed-properties.png?_t=1615667817)

- Step 4: Delete the **World** folder in your servers root folder

```Warning: Deleting your server's world folder will remove all player data, all builds and all achievements you have made. It's best to backup your world if you want to keep anything.```

- Step 5: Start your server, and connect!
- Step 6: Ta-da! You have now forced what your minecraft world looks like!

### How do I force a seed on my Singleplayer world?
Forcing a seed on a single-player world is even easier than on a server! Follow these super-simple steps and you'll have a seed in no time:

- Step 1: Head over to the **Minecraft Main Menu** and select **Singleplayer**
- Step 2: Click **Create new world**
- Step 3: Click **More World Options**
- Step 4: Paste your desired seed number in the **Seed** field
- Step 5: (Optional) Customise the other settings to your liking
- Step 6: Hit **Create World**
- Step 7: Waiiiiiiitttttt
- Step 8: Ta-da! Your new world is made with your desired seed!
