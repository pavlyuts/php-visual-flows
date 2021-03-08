# Work under progress
# Low-code/nocode stateful flow-based engine for PHP with visual editor

## Purpose

This package intended to build statefull application logic for inter-API glue, dialogs, small applications, and simple REST services, combining different APIs into one interface, including statefull session API with callbacks. 

May be used for USSD/SMS dialog flow, API-to-API bridging, chatbot logic definition and a lot of other purposes.

Built with mind to put as much logic as possible to visual editor, but still be able to add more complex processing by PHP code.

It could be easy to extent for new type of nodes, new kind of APIs and all other matters. Support for PSR-4 autoload and PSR-3 logging.

*Not properly tested, use at your own risk!*

Please, refer [project Wiki](https://github.com/pavlyuts/php-visual-flows/wiki) for details.

## Installation
(It will be }In the Composer storage. Just add proper require section:

    "require": {
        "pavlyuts/visual-flows": "*"
    }
It is a good idea to fix the version you use. Don't use next version without review, I can't promose backward compatibility even will try to keep it. Please, review the [changelog](https://github.com/pavlyuts/php-visual-flows/blob/master/CHANGELOG.md) before to change version.

## Dependencies
- psr/log: ^1.1
- "smarty/smarty": "~3.1"

