# Mastering MS Teams, or Avoiding the Wrath of Sheriff Matt - Part 1

- [Mastering MS Teams, or Avoiding the Wrath of Sheriff Matt - Part 1](#mastering-ms-teams-or-avoiding-the-wrath-of-sheriff-matt---part-1)
  - [Replying to Existing Threads/Messages](#replying-to-existing-threadsmessages)
  - [Tagging a Channel/User](#tagging-a-channeluser)
  - [Pin or Hide a Channel/Chat](#pin-or-hide-a-channelchat)

When it comes to using [Teams][0], not only are there a plethora of features available to you, there are new ones [added frequently][10] enough that it's difficult to keep up. The intent of this series is to explain as many of those features as possible starting with simple and escalating to more complex. This first entry is going to explain the more basic features so if you're looking for the latest and greatest, this isn't the right article for you 😛

_NOTE: These tips are written with a focus on the Desktop/Web clients. Some will work on mobile, but with slight differences._

## Replying to Existing Threads/Messages

When you're trying to reply to an existing message in a channel, if you click the Reply button before sending your message, it'll be in the same thread. This is *extremely* helpful when it comes to support questions or incidents that require follow up. For example, consider the following scenario:

1. I create a new thread about a question I have regarding whatever, and this thread is referred to as **Thread A**.

2. Someone replies to this thread about my question, and another person replies but not to this thread, they create a new thread:
  ![New_Thread_Reply][3]

3. Now someone else chimes in, but they reply to the original Thread A.
   1. As long as you're watching this channel as it happens, it'll look something like this:
      ![New_Thread_Reply_2][4]

4. Then you go to another channel and come back, but what? Things are in a different order now:
  ![New_Thread_Reply_Order][5]

5. Okay... No big deal, it's just slightly confusing to keep up. But now someone starts a new thread with an entirely different topic, henceforth **Thread B**, and then someone replies to the original Thread A and so it all looks like this:
   ![Thread_B_The_Start][6]

6. Then... You leave the channel and come back, and now things are even more out of order:
   ![Thread_B_The_End][7]

After more and more messages are sent in the various threads, and more threads are created, the one "Message about Thread A" will no longer be near the original Thread A and will be meaningless.

Simply use the reply button underneath the thread, and all these problems are avoided.

## Tagging a Channel/User

When you need to get the attention of an individual or group, tagging them is your best option. Before I get to the how-to portion of this, it's _extremely important_ to note that when it comes to tagging channels or groups of people, everyone in that channel or group will receive a notification that you sent a message.

Teams even has a neat feature that will show you if you're about to tag a lot of people:

![Tagging_Over_1k][1]

See how it says 1477 people will see this message? That means that all 1,445 of them will get a notification that appears on their screen, over everything else they're doing, saying that you just posted a message in that channel. So please, think twice before tagging channels/groups.

Now, in order to tag a channel/person/group, all you have to do is type the `@` key and start typing the name of who you want to tag. Want to tag the GIT channel for support on this weird error you're getting in your git client?

`@GIT`, and it'll give you a lovely pop-up to select who you actually mean:

![Tagging_A_Channel][2]

_P.S. If you post a message that tags users/channels/groups, and then edit that message afterwards, whenever you save it everyone will once again be notified of the message. This happens every time an edit is made and saved._

## Pin or Hide a Channel/Chat

> The primary Team at my job has 71 active channels. Most of which I never look at, but there are 5 that I _need_ to monitor, as well as two which I consider important but not required. Then there are about 10 others which I would consider important to keep around, but only if someone mentions me in it.

If you work for a large corporation, odds are that sounds familiar or is something you're dealing with personally. The best way to calm the storm and organize things in an efficient manner is with pinning and hiding channels of high and low importance respectively.

For example, here is what my Teams setup looks like:

![My_Channels][11]

Now, to do this, you simply right click on the channel you want to modify and click which of the options you'd like. So in order to pin a channel, just right click the channel name and click on Pin. Want it hidden? Just click Hide instead of Pin:

![Pin_A_Channel][9]

Thankfully this one doesn't have any impact on other users, so there's nothing to worry about with this feature, it's purely helpful 😜

[0]: https://products.office.com/en-us/microsoft-teams/group-chat-software
[1]: ./img/Tagging_Over_1k.png
[2]: ./img/Tagging_A_Channel.png
[3]: ./img/New_Thread_Reply.png
[4]: ./img/New_Thread_Reply_2.png
[5]: ./img/New_Thread_Reply_Order.png
[6]: ./img/Thread_B_The_Start.png
[7]: ./img/Thread_B_The_End.png
[8]: ./img/My_Pinned_Channels.png
[9]: ./img/Pin_A_Channel.png
[10]: https://support.office.com/en-us/article/what-s-new-in-microsoft-teams-d7092a6d-c896-424c-b362-a472d5f105de
[11]: ./img/My_Channels.png
[12]: ./img/Hide_a_Channel.png