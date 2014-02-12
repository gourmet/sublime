# Sublime Gourmet

This plugin aims to help [CakePHP][cakephp] developers using the [Gourmet][gourmet] suite of plugins.

## Installation

Use [Sublime Text 2][st2]'s [Package Control][st2-package-control] (Preferences -> Package Control -> Install Package -> Gourmet)
to install this plugin.

## Configuration

@todo Write up.

## Commands

This plugin adds support for running tests (or any CakePHP shell command) from inside Sublime Text 2.

Right-click in the editor to:

* Open the associated test file (i.e. Model/User.php -> Model/UserTest.php)
* Run all tests in the current file
* Run select method unit test - TODO
* Run all unit tests - TODO

Right-click in the side-bar to:

* Open the associated test file (i.e. Model/User.php -> Model/UserTest.php)
* Run all tests in the current file

Go to the Tools menu (Tools -> Gourmet] to:

* Open the associated test file (i.e. Model/User.php -> Model/UserTest.php)
* Run all tests in the current file
* Run select method unit test - TODO
* Run all unit tests - TODO

You can also open up the Command Palette (CMD + SHIFT + P on OSX), and type
'Gourmet' to see what you can do with Gourmet in the currently open file.

## Snippets

We add the following snippets to speed up writing PHP test code.

To use any of the snippets, simply type the name of the snippet, then press the <TAB> key.  Sublime Text 2 will insert
the snippet, and you can then use the <TAB> key to move through any placeholders that you need to replace.

* __gourmet-addTest__: Stubs test method
* __gourmet-newCommonTestCase__: Stubs class TestCase that extends `Common.TestSuite/CommonTestCase`
* __gourmet-addBeforeSave__: Stubs the `Model::beforeSave()` method

## Patches & Features

* Fork
* Mod, fix
* Commit - do not mess with license, todo, version, etc. (if you do change any, bump them into commits of their own that I can ignore when I pull)
* Pull request - bonus point for topic branches

## Bugs & Feedback

http://github.com/gourmet/sublime/issues

## License

Copyright 2014, [Jad Bitar][jadbio]

Licensed under [The MIT License][mit]
Redistributions of files must retain the above copyright notice.

[cakephp]:http://cakephp.org
[gourmet]:https://github.com/gourmet
[st2]:http://www.sublimetext.com/2‎
[st2-package-control]:http://wbond.net/sublime_packages/package_control
[mit]:http://www.opensource.org/licenses/mit-license.php
[jadbio]:http://jadb.io
