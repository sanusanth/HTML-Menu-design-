# HTML-Menu-design-
The HTML &lt;menu> element represents a group of commands that a user can perform or activate. This includes both list menus, which might appear across the top of a screen, as well as context menus, such as those that might appear underneath a button after it has been clicked.
# The HTML <menu> element represents a group of commands that a user can perform or activate. This includes both list menus, which might appear across the top of a screen, as well as context menus, such as those that might appear underneath a button after it has been clicked.

label 
The name of the menu as shown to the user. Used within nested menus, to provide a label through which the submenu can be accessed. Must only be specified when the parent element is a <menu> in the context menu state

type
This attribute indicates the kind of menu being declared, and can be one of two values.
context  : Indicates the popup menu state, which represents a group of commands activated through another element. This might be as a button menu referenced by a menu attribute of a <button> element, or as context menu for an element with a contextmenu attribute. This value is the default if the attribute is missing and the parent element is also a <menu> element.
toolbar: Indicates the toolbar state, which represents a toolbar consisting of a series of commands for user interaction. This might be in the form of an unordered list of <li> elements, or, if the element has no <li> element children, flow content describing available commands. This value is the default if the attribute is missing.

Usage notes
The <menu> and <ul> elements both represent an unordered list of items. The key difference is that <ul> primarily contains items for display, whilst <menu> is intended for interactive items, to act on.

An HTML menu can be used to create context menus (typically activated by right-clicking another element) or toolbars.

Context menus consist of a <menu> element which contains <menuitem> elements for each selectable option in the menu, <menu> elements for submenus within the menu, and <hr> elements for separator lines to break up the menu's content into sections. Context menus are then attached to the element they're activated from using either the associated element's contextmenu attribute or, for button-activated menus attached to <button> elements, the menu attribute.

Toolbar menus consist of a <menu> element whose content is described in one of two ways: either as an unordered list of items represented by <li> elements (each representing a command or option the user can utilize), or (if there are no <li> elements), flow content describing the available commands and options.

This element was deprecated in HTML4, but reintroduced in HTML5.1 and the HTML living standard. This document describes the current Firefox implementation. Type 'list' is likely to change to 'toolbar' according to HTML5.1.
