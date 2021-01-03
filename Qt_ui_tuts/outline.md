# Outline

## Introduction to UI frameworks
  * Common Python frameworks
    * Tkinter
    * wx
    * Qt
    * Native

  * Common concepts
    * Object-Oriented-Programming
    * Model-Controller-View
    * Signalling & notifications
     * Qt: Signals & slots
    * Threads
    * WYSIWYG / Visual Editing
    
  * Why Qt?
    * Mature Framework
    * Good documentation
    * Strong Cross-platform support
    * Strong visual tools.
    
## High level overview of Qt
  * Tools
    * IDE (_other than IDLE_)
    * PyQt5 - Primary Qt framework for Python
    	* PySide - alternate implementation
    * Designer - visually build Qt UI
      	* overview of ui.
    * pyuic5 - Convert Designer form to python code
    	* Generate with `__main__` block
  * useful links
    * C++ reference docs
    * Python
    
## Exercise 1: Simple temperature converter
  * Build UI in designer
  * start with main window
  * Add Label, Field, Pushbutton, result field
  * Apply horizontal layout to inputs
  * Apply vertical layout overall
  * Starter Python stub code
  
## Exercise 2: Button widgets!
  * ...

## Exercise ...: Custom Color well button
  * ...

## Introduction to Data views:
  * MCV in action
  * Common types:
    * list
    * tree
    * table - most likely used
  * The custom `QAbstractDataModel` class
    * Relation to Views
    * Readonly vs read/write
      * Focus on readonly initially
      * Minimum function overrides for table
        * `__init__()`
        * `data()`
        * `headerdata()`
        * `rowCount()`
        * `columnCount()`
    * Roles
      * Display
      * Edit
      * Format
      * Checkstate
    * Cell flags
      * Editable
      * Checkable
    * Selection
  * Exercise: Load and display CSV
    * Build UI
      *Table / file menu
    * Write code
      * window
        * `__init__`
        * Open dialog
      * TableModel
        * write functions
      * Status bar ?
      * Error handling
      
      
## Edit from data view:
  * writeable concepts
    * update notifications, etc
  * Extend previous exercise
    * Add Save/Save As options and dialogs
    * Double click to edit support
    * something else...?
  

  
