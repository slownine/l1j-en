# Introduction #

With the code base being updated to support the latest american client, we will also need to start using a new connector.  Thankfully, l1j-jp2 has a new connector that works perfectly with the American client, and is also very configurable.   Unfortunately, the program you use to set it up along with the instructions are either in Japanese or are just lacking.

# Features #

  * Configurable remotely.  Server admins can set up the initial connector, then repackage it for their users to download, and have it so it loads its configuration from a remote file.  This means anytime your IP changes, or you add another server, your users won't have to do anything.  They'll see those changes automatically next time they open the connector.
  * It has some custom encryption options, but I haven't tested those yet.  I'm just using it with default settings on the server and connector.  I'm not sure what the benefit of this would be, but maybe it would prevent bots from connecting to your servers.  That's assuming it even works.  It's very low on my list of priorities to test this at the moment
  * The connector opens up a menu where you can choose what server you want to connect to.  Obviously the servers are configurable, but the entire program is also theme-able.  Server admins can make it look however they want.  It can also load your own html file for the "news" section like you see on live when you connect.

# Instructions #

I'll put these up soon.  I have it figured out, I just need to start back over with step one and write them down.  It isn't difficult.

Here is a start of some instructions.

  * Download the latest connector from the [Downloads](https://code.google.com/p/l1j-en/downloads/list) tab.  The file is connector.rar.
  * Extract.
  * Go to the Encode folder and run encode.exe.
  * The first box, which on my screen looks like its filled with a few boxes, put in the server name.
  * The box that has 127.0.0.1, put the IP address of your server.
  * On the bottom left is a select box, choose s3ep1.
  * Click the bottom right button.
  * This should create a file called Login.ini.  Edit it and set the remote option to 0 if it is set as one, then copy that, and from the login folder copy Login.exe Login.dll S3EP1.bin and skin to your Lineage folder.
  * Set "Day" in the ini file to 0 or 1 to disable or enable darkness at night time.
  * Run Login.exe and connect to your server!

Now there's other steps and options, if you look at the login.ini that came with it (in the login folder) you can see some of them, including the remote config option.  I'll cover those with better instructions later.  Also the skin folder has the images the program uses for its look, including the buttons, so its possible to edit those so it doesn't look so… Asian.