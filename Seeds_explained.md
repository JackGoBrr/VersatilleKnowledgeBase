# Seeds explained
In this guide, you'll learn what a seed is, how to get the current seed, and how to force a seed on your multiplayer server!

### What is a seed?
A seed is a number ranging between 1 and 19 characters long number that decides how your minecraft world looks.
Some seeds are negative numbers, and some are positive. Each world created is fully unique and has its own number, infact, there are about **20,000,000,000,000,000,000**
different combinations of a seed, yes you read that, nearly 2 quintillion.

### How do I find the seed of my current world?
Finding the seed of your world is super easy! All you need to do is run a single command, like so:

![Executing the seed command]()

and if you run the command correctly, you'll get an output similar to this, but instead, you'll have your world's seed in green instead of mine!

![/seed output]()

### How do I force a seed on my server?
Forcing a seed is also super easy, all you need is a way to connect to your server's file access. If you don't know how to connect to your server's sFTP, read [this guide]().
Once you are connected, follow these steps:
- Step 1: Once your server is setup, make sure to **STOP** your server.
- Step 2: Once it's offline, head into your servers files and find the **server.properties** file.
- Step 3: Find the **level-seed** value, and insert your desired string of numbers (aka. the seed you would like to force)
- Step 4: Delete the `World` folder in your servers root folder

`Warning: Deleting your server's world folder will remove all player data, all builds and all achievements you have made. It's best to backup your world if you want to keep anything.`

- Step 5: Start your server, and connect!
- Step 6: Ta-da! You have now forced what your minecraft world looks like!

### How do I force a seed on my Singleplayer world?
aaaa
