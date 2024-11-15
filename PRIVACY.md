# 🔏 Privacy Policy

Please read this document carefully if there is any concern in how Dicemos handles your information. 
This policy is automatically accepted as you make use of Dicemos's services.

## 📤 Terminology

- _**Dicemos**_
  - The Discord bot in question. This product is in care of Armano den Boef. The legal owner & only developer of Dicemos.
- _**You, Member, User**_
  - You, a user of Dicemos reading this privacy policy.
- _**Command, Commands**_
  - A command or multiple commands you can execute to which Dicemos responds.
- _**Component, Components**_
  - A dropdown or button, or a collection of both, with which you can further interact with interactions.
- _**Entity, Entities**_
  - A data model that is used to store & retrieve specific information regarding a task executed by Dicemos.
- _**Guild, Guilds**_
  - A Discord server, in Discord's API referred to as this definition.

## 📅 Data collection

### Rolled dices

Dices rolled for each user are kept in history, to chart usage, input and count outcomes. 
This can be accessed via the profile. It is not possible for a user other than the executing user, to access this data.

### Interaction usage

Data is kept about your command & component usage. 
As a command is executed, a **command total** is incremented. 
As a button is pressed, a **component total** is incremented. 
After every command executed, it's name will be stored as your **latest command**. 
The latest command is replaced by its previous entry. Command details are not stored.

### Users

Each user has a unique ID provided by Discord. 
Dicemos uses this ID to associate you with entities it keeps in reference to you.

## 🗃️ Data storage

Data is stored in a MongoDB server, locally hosted on the same machine as Dicemos itself. 
It is safely protected by a security manager & password system. 
The port MongoDB communicates over is locked externally, so no traffic from outside the machine can interfere with or keep tabs on your data. 
> If this security somehow fails, and your data is somehow grabbed or deleted, 
Dicemos will notify you along other users of this event in its built-in notification system.

## ✅ Agreement

By adding Dicemos to your guild or guilds, you agree to the above mentioned policy. 

## ❌ Disagreement

If you disagree with these terms as a guild owner or maintainer, you may remove Dicemos from the guilds in question. 
If you disagree with these terms as a guild member, you may leave the guilds where Dicemos resides.
