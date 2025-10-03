# Assignment

Design an XML format for representing the menu structure of a computer program. A menu can contain any of the following in any number and order:

* another menu (i.e., a submenu),
* a menu item,
* a separator.

Both menus and menu items must have a name that must be specified using an attribute.

Create a DTD for the format, and also an XML document to demonstrate the use of the format that describes the following menu structure:

* Main:
  * File:
    * New
      * XML
      * JSON
      * Text
    * Open
    * Save
    * Save as
    * [separator]
    * Exit
  * Edit:
    * Undo
    * Redo
    * [separator]
    * Cut
    * Copy
    * Paste
  * Help:
    * About

In this assignment, the goal is not to visually render the document in a web browser.
