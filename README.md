<div align="center">
  <img src="https://i.imgur.com/o558Qnq.png" align="center">
  <br>
  <strong><i>A feature rich Modmail bot for Discord.</i></strong>
  <br>
  <br>

  <a href="https://heroku.com/deploy?template=https://github.com/kyb3r/modmail">
    <img src="https://img.shields.io/badge/deploy_to-heroku-997FBC.svg?style=for-the-badge&logo=Heroku">
  </a>

  <a href="https://github.com/kyb3r/modmail/">
    <img src="https://api.modmail.tk/badges/instances.svg" alt="Bot instances">
  </a>

  <a href="https://discord.gg/j5e9p8w">
    <img src="https://img.shields.io/discord/515071617815019520.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge" alt="Support">
  </a>

  <a href="https://patreon.com/kyber">
    <img src="https://img.shields.io/badge/patreon-donate-orange.svg?style=for-the-badge&logo=Patreon" alt="Python 3.7">
  </a>

  <a href="https://www.python.org/downloads/">
    <img src="https://img.shields.io/badge/Made%20With-Python%203.7-blue.svg?style=for-the-badge&logo=Python" alt="Made with Python 3.7">
  </a>

  <a href="https://github.com/kyb3r/modmail/archive/master.zip">
    <img src="https://counter.modmail-plugins.ionadev.ml/embed/announcement">
  </a>

  <a href="https://travis-ci.com/kyb3r/modmail">
    <img src="https://img.shields.io/travis/com/kyb3r/modmail?style=for-the-badge&logo=Travis">
  </a>  

  <a href="https://github.com/ambv/black">
    <img src="https://img.shields.io/badge/Code%20Style-Black-black?style=for-the-badge">
  </a>

  <a href="https://github.com/kyb3r/modmail/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-agpl-e74c3c.svg?style=for-the-badge" alt="MIT License">
  </a>

<br>
<img src='https://i.imgur.com/fru5Q07.png' align='center' width=500>
</div>


## What is Modmail?

Modmail is similar to Reddit's Modmail both in functionality and purpose. It serves as a shared inbox for server staff to communicate with their users in a seamless way.

## How does it work?
When a member sends a direct message to the bot, a channel or "thread" is created within an isolated category for that member. This channel is where messages will be relayed and where any available staff member can respond to that user.

All threads are logged and you can view previous threads through the corresponding generated log link. [**Example**](https://logs.modmail.tk/example)

## Features

* **Highly Customisable**
  * Bot activity, prefix, category, log channel, etc.
  * Fully customisable command permission system.
  * Interface elements (color, responses, reactions, etc.)
  * Snippets and *command aliases*
  * Minimum account/guild age in order to create a thread.
* **Advanced Logging Functionality**
  * When you close a thread, a [log link](https://logs.modmail.tk/example) is generated and posted to your log channel.
  * Rendered in styled HTML like Discord.
  * Login in via Discord to protect your logs ([Patron only feature](https://patreon.com/kyber)).
  * See past logs of a user with `?logs`
  * Searchable by text queries using `?logs search`
* **Robust implementation**
  * Scheduled tasks in human time, e.g. `?close in 2 hours silently`.
  * Editing and deleting messages is synced on both ends.
  * Support for the full range of message content (mutliple images, files).
  * Paginated commands interfaces via reactions.

This list is ever growing thanks to active development and our exceptional contributors. See a full list of documented commands by using the `help` command.

## Installation

### Locally
Installation locally for development reasons or otherwise is as follows, you will need `python 3.7`.

Clone the repo
```console
$ git clone https://github.com/kyb3r/modmail
$ cd modmail
```

Install dependancies
```console
$ pipenv install
```

Rename the `.env.example` to `.env` and fill out the fields.
And finally, run the bot.
```console
$ pipenv run python3 bot.py
```

### Hosting for patrons

If you don't want to go through the trouble of setting up your own bot, and want to support this project as well, we offer installation, hosting and maintainance for Modmail bots for [**Patrons**](https://patreon.com/kyber). Join the support server for more info!

### Heroku
This bot can be hosted on heroku. Installation via Heroku is done in your web browser. The [**installation guide**](https://github.com/kyb3r/modmail/wiki/Installation) will guide you through the entire installation process. If you run into any problems, join the [development server](https://discord.gg/etJNHCQ) for help and support.

You can also set up autoupdates. To do this, [install the Pull app in your fork](https://github.com/apps/pull). Then go to the Deploy tab in your Heroku account, select GitHub and connect your fork. Turn on auto-deploy for the master branch.


## Sponsors

Sepcial thanks to our sponsors for supporting the project.

<a href='https://www.youtube.com/channel/UCgSmBJD9imASmJRleycTCwQ/featured'>
  <img height=150 src='https://i.imgur.com/WyzaPKY.png' style='margin:10'>
</a>

Become a [sponsor](https://patreon.com/kyber).


## Plugins

Modmail supports the use of third party plugins to extend or add functionality to the bot. This allows the introduction of niche features as well as anything else outside of the scope of the core functionality of Modmail. A list of third party plugins can be found using the `plugins registry` command. To develop your own, check out the [documentation](https://github.com/kyb3r/modmail/wiki/Plugins) for plugins.

## Contributing

Contributions to Modmail are always welcome, whether it be improvements to the documentation or new functionality, please feel free make the change. Check out our contribution [guidelines](https://github.com/kyb3r/modmail/blob/master/CONTRIBUTING.md) before you get started.

This bot is free for everyone and always will be. If you like this project and would like to show your appreciation, here's the link for our **[Patreon](https://www.patreon.com/kyber)**.
