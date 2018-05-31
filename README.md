# RuneScape-Discord Chat Sync

A RuneScape Companion and Discord bot that synchronizes a RuneScape
Friends/Clan Chat with Discord chat.

RuneScape-Discord Chat Sync is a bot written in JavaScript that uses
[Puppeteer](https://github.com/GoogleChrome/puppeteer) to simulate a user
using the [RuneScape Companion](http://runescape.com/companion/comapp.ws)
web app to chat in the Friends/Clan Chat (it's easily configurable). When it
reads a message in the RuneScape chat it outputs it to the Discord chat using
[discord.js](https://discord.js.org), and when it reads a message in the
Discord chat it outputs it in the RuneScape chat, keeping the two chats synced.

This bot can be useful for users who want to continue a RuneScape conversation
without playing the game, people who want to make sure they don't miss part of
a conversation, or to keep chat logs.

It is officially hosted on
[GitHub](https://github.com/aeramos/RuneScape-Discord-Chat-Sync).

### FAQ
* Since the bot is licensed under the
[GNU AGPL-3.0+](https://www.gnu.org/licenses/agpl-3.0.html), do I have to
distribute source code to people who use it when I run it?
    * Yes. All users of the bot **must** be able to get a copy of the source
    code. The license states that:

    > "If your software can interact with users remotely through a computer
    network, you should also make sure that it provides a way for users to get
    its source."

    > "Notwithstanding any other provision of this License, if you modify the
    Program, your modified version must prominently offer all users interacting
    with it remotely through a computer network (if your version supports such
    interaction) an opportunity to receive the Corresponding Source of your
    version by providing access to the Corresponding Source from a network
    server at no charge, through some standard or customary means of
    facilitating copying of software."

    The bot currently does this to what I consider a satisfactory level: it has
    commands that tell the user the name of the project and how to get the
    source code and license information. It also tells the user how to get help
    in the Discord activity field.

    More information can be found in the COPYING file. Please refer to it for
    any licensing issues and in the event of a contradiction between the text
    in the README and the text in COPYING, refer to the text in COPYING.

### MAINTAINERS

 * [Alejandro Ramos](https://github.com/aeramos)

### LICENSE

This program is licensed under the
[GNU AGPL-3.0+](https://www.gnu.org/licenses/agpl-3.0.html).
More information can be found in the COPYING file.

------------------------------

This file is part of RuneScape-Discord Chat Sync

Copyright (C) 2018 Alejandro Ramos

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.