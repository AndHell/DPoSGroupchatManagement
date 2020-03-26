# Introduction
Mobile messaging applications, also known as messenger, are used by over one
billion people to connect to each other and exchange messages. One of the core
features of applications like WhatsApp, Signal, Facebook Messenger, Threema and
Telegram are group chats. Group chats allow multiple users to communicate with
each other over a shared message thread. Users can be added to these threads or
leave them any time.  

To maintain the member list of such a group chat most messenger uses administra-
tors, which are members with additional rights. While all populare messenger uses
centralized servers to distributed messages, some also uses them for the group
managing. This weakens the users privacy, even if the application uses end-to-end
encryption to secure the messages content, and introduces a single point of failure.
Current ideas from secret services such as the GCHQ plan to misuse this by forcing
the services to add ghost users to the groups.  

By using blockchain technology the group management can be distributed be-
tween all members and remove the need to a centralized management. Delegated
Proof of Stake enables to members to elected their administrators and allow all
members to contribute to the group equally.  

This work focuses on Delegated Proof of Stake (DPoS) as consensus protocol and
analyses the usage of such a system for distributed group management in secure
messaging applications. To do so, a protocol is designed which uses Delegated
Proof of Stake and is tested using an autonomous running group simulation.
