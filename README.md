# shinecode
This is a list of the commands that can be used to control the MusicBot. You cannot use commands in private messages. Every command starts with the prefix that you configured. This page assumes your prefix is !, the default.




!command [optional argument] [multiple | choice | argument] <required argument>

Basic description of what the command does. Additional information may be provided.

If a command has a second set of usage text, that means there's another way to use the command.

When using arguments, do not include the brackets ([ ] or < >). These are for indicating the type of argument. If an argument starts with an @, i.e. [@user], this indicates that the argument should be a user mention, not just the name of the user. Discord names are not unique, any user can change their name to anything at any time, including the name of other users.

Note: Possible exception or caveat that the user should take note of when using the command. For example: !command is not a real command, just a place holder to demonstrate the command format. Users should also note that if they have changed the command prefix, that their commands will start with that instead of ! (Ex. >help, >play, >id)




!play <song link>

!play <song text to search for>

Add a song to the queue, or add the first youtube result for the provided search text.

Arguments:

<song link> A link to some song. Links are not limited to youtube, see this FAQ entry.
Example: !play https://www.youtube.com/watch?v=ID-YOUTUBE
<song text to search for> Some search query you want the bot to look up on youtube.
Example: !play I ran seagulls will play I Ran by A Flock of Seagulls.


!queue

Prints the bot's current queue in chat.


!np

Prints the currently playing song in the chat.


!skip

Vote to skip the current song, or if you're the owner, skip the current song.


!shuffle

Shuffles the queue.


!clear

Clears the queue.

!pause

Pauses the playback of the current song.

!resume

Resumes playback of a paused song.


!volume [amount]

Changes the volume of the current song, or prints the current volume if an amount is not specified. This affects all users.



