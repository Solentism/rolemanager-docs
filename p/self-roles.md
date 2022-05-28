---
description: Setting up self roles is a piece of cake with Role Manager v3!
cover: >-
  https://images.unsplash.com/photo-1557683316-973673baf926?crop=entropy&cs=tinysrgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHw4fHxncmFkaWVudHxlbnwwfHx8fDE2NTMxODU2NTU&ixlib=rb-1.2.1&q=80
coverY: 0
---

# Setting up Self Roles

Before going any further, you'll need to ensure you have the `Administrator` permission within the server you're using. If you're the Owner of the server, then you'll have no need to worry about this!

### Creating a Self Role menu within your designated channel!

The first thing you're going to have to do is ensure that Role Manager has the permissions required for its general purpose. If that's the case, then its time to get our hands dirty..

In any channel, type `/self-role create`, this will bring up something looking a little like the image shown below:

![](<../.gitbook/assets/image (5) (1) (1).png>)

Once here, press enter. This will then bring up a list of your Discord server's channels, from here, select the channel in which you'd like the menu "stationed". For the purpose of this tutorial, I'll use the channel #tutorials.

![](<../.gitbook/assets/image (2) (1) (1).png>)

Once you've chosen your channel, you'll see one last required field within the slash command we've been filling out. This is the title field, this is the text that will display at the very top of the menu. For the purpose of this tutorial, we're going to call it "Tutorial Title".

Once you've done this, you'll recieve a message prompt telling you that the menu creation was successful and that it's ready to be used! If you don't get this prompt, there is likely an error in the bots permissions. The prompt looks as shown below:

![](<../.gitbook/assets/image (1) (1) (1).png>)

Each self role menu is attached to an 8 character identifiable string, this is to allow for Role Manager to find the menu you're trying to edit.

From here, copy the 8 character code given to you via the success embed in the aforementioned image. From here, type `/self-role add` and paste the ID into the required field on the command. On here, you'll see another field, this is the field in which you place the role which you'd like to be featured within the menu for people in your server to gain access to. For tutorial purposes, I'll just use a random role laying on my server.

Once you've selected your role, press enter and you're done! You'll recieve a success message and the role will now be attached to the embed menu within your designated channel!

![](<../.gitbook/assets/image (1) (1) (1) (1).png>)

The rest is easy! Have your users go to your designated self roles channel, from there they can click on the dropdown and select the roles they desire!&#x20;

![](<../.gitbook/assets/image (3) (1) (1).png>)

So there you have it! That's how you setup self roles on Role Manager v3! Should you have any further questions or problems, don't hesistate to join our support server over @ [UtiliBots](https://discord.gg/cAtc7kZbPX)!
