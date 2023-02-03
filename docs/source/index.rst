
=============================
EzBot Framework Documentation
=============================

Framework is designed to easily extend functional of messengers. On current moment,
Telegram is main messenger, that framework is support. Framework have plugin system,
easy instance management by environments.

Main features:

* Powered by **Telethon**, powerful, MTProto, high-level library to interact with **Telegram**.
* Have plugin system, that allows to dynamically add, remove, create and etc. required functions, commands and other.
* Uses environments and instances systems. It allows you to add multiple users to one environment.
* Have powerful, easy in use **Argument Parser**. That have `subcommands`, `type-casting` (including ``list``, ``dict`` types) and more other features.
* Custom powerful, colored logging library **ezlog** (That uses **colorama**. It helps to enable the colors in Windows command line).
* Type-hinted as possible. If you use advanced IDE, programming process with this framework will be easy with type-hints!

How I can use it?
-----------------

If you are an **Developer**, you can use it framework in your projects or use it to create own
plugins.

To get documentation of the framework, check **Framework Reference**.

.. To get documentation how to develop plugins, check **Plugin Developing**.

Good luck!

If you are an **User**, you can use it framework to install plugins and extend your messanger
functional. See **CLI Reference**

.. Will be uncommented, when EzBot will be released
    .. tip:: There have a high-level, GUI manager for this framework - **EzBot**. `Currently,
        this application in the closed development`.

History
-------

First implementation of framework idea it was my project **fTUB**, that has been provided
functional of the **anti-deleting**. But, there wasn't easy plugin system, and all code has
been bad structure. After, I created a **EasyTl** project. This is have a public archive on
my github. After, I closed this project and created this framework for all users of any type.
In this framework I used some features from **EasyTl** and I'm planning to create old functional,
but as plugins. Is: **anti-deleting**, **animations**, **searching from telegram**, and other.
There plugins I will publish on my github and everyone can be use this.

And, sorry for my grammar, I'm live in Ukraine :)

.. toctree::
    :hidden:
    :caption: Plugin Developing

    plugindev/quickstart

.. toctree::
    :hidden:
    :caption: Configurations

    configurations/instance-configuration
    configurations/translations

.. toctree::
    :hidden:
    :caption: Framework Reference

    framework/plugin
    framework/instance
    framework/context
    framework/instancecontext
    framework/translator
    framework/permissions
    framework/pluginloader
    framework/argumentparser.rst
    framework/utils
    framework/ezlog
    framework/cli

.. toctree::
    :hidden:
    :caption: ArgumentParser Reference

    framework/argumentparser/parser
    framework/argumentparser/casts
    framework/argumentparser/_casts
    framework/argumentparser/argumentparseerror