# Tutorial: How to use the editxp Command in your Server

### Introduction
The ``editxp`` Command lets you edit XP Values, which are used to calculate Experience Points for specific Tasks in your Server.
There are 4 Categories which you can edit within this Command!

> Message XP
- This Value will be used to calculate the amount of XP which will be rewarded for one Message every 60 Seconds.

> Voice XP
- This Value will be used to calculate the amount of XP given for a specific time spent in the Voicechat.

> Voice XP Divider
- This Value is a bit different than the ones before. The Time spent in a Voicechat (in ms) will be divided by this amount.
```
1000 = 1 XP/second
10000 = 0.1 XP/second
60000 = 1 XP/minute
```

> Game XP
- This Value will be used to calculate the amount of XP given for executing one of the Commands included in the **Games Module**.
Use the ``module`` Command in order to enable this Module in your Server.

### Disclaimer
All the Commands shown in this Tutorial will be executed with the **Standard** Prefix.
If you changed the Prefix in your Server, please use your Custom Prefix instead.

## Step 1: Know about the Values you can edit
At first, please execute the ``.xp help editxp`` Command, so you can see how to use this Feature.

Available Values are
- ``msg`` for Message XP
- ``vcxp`` for General Voicechat XP
- ``vcdivxp`` which will change the Voicechat XP Divider
- ``gamexp`` for Game XP

In the shown Help Card, you can also view the general usage of this Command.
We will break down the Usage Example a bit, do it's easier to understand.

> Usage Example
- ``.xp editxp <factor> <amount>``

``<factor>`` can be replaced with one of the Values shown above. This value will set which Value should be changed.

``<amount>`` can be set to any Number higher than 1.

> A Command executed in your Server could look like this
- ``.xp editxp msg 50``
- ``.xp editxp vcxp 20``
- ``.xp editxp vcdivxp 60000``
- ``.xp editxp gamexp 75``

## Step 2: Edit a Value

You can get started using the Command now.
**NOTE**: You're not able to set a Value to any negative Number.

Head over to your preferred Text Channel in your Server and make sure one of your Roles allows you to Manage the Server.
If you do have ``MANAGE_SERVER`` Permissions, you're ready to go!
You can use our Examples above or set your own Values.

> If you have any other questions, feel free to join our [Support Server](https://discord.gg/ccTAnzw)!
