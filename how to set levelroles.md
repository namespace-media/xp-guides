# Tutorial: How to add Serverroles as working Levelroles

### Introduction
The ``role`` Command let's you add or remove Levelroles from your Server.
Levelroles are Roles that will be given if a member of your Server reaches a specific Level on the XP Levelsystem.

### Disclaimer
In this Tutorial, we will use the **Standard** Prefix. If you set a custom Prefix, please use that one for the used commands instead.

## Valid Arguments

> Example Usage
- ``.xp role <"add"/"remove"> <level> <@role>``

- ``add`` is the argument to specify, that you want to **add** a new Role to the list of Levelroles. ``remove`` can be used to **remove** a Role from the List.

- ``level`` will be used to set the Level to assign the Role at. **NOTE**: This is not the amount of XP!

- ``@role`` stands for the Mention of the Role you want to add. There must be a role before using this Command, this Command doesn't create new Roles.

# Example Usage

> If there's a Role called "Level 5", you can use a Command like the following
- ``.xp role add 5 @Level 5``
- ``.xp role remove 5 @Level 5``

> If there's a Role called "Customer", you can use a Command like the following
- ``.xp role add 0 @Customer``
- ``.xp role remove 0 @Customer``
**NOTE**: If you've enabled Discord System Welcome Messages, this Role can be used as an Autorole as it will be assigned as soon as someone joins your Server!

> If you have any other questions, feel free to join our [Support Server](https://discord.gg/ccTAnzw)!
