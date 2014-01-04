limitText
=========

Jquery plugin to limit character on any elements.
##Syntax
    $(".selector").limitText();

##Options/Parameters
Object:

    { selector: ".any-selector" } //Displays the counter of character left there where the selector is assigned.

Object: 

    { text: "any text" } //An optional string or message at the end of counter.
    
Objects:

    { selector: ".any-selector", text: "any text" } //Same as above but combined

##Description
A basic plugin that restricts certain number of characters on the elements, particularly with the attribute contenteditable. This plugin expects a selector on the element/s where the plugin needs to take effect. In addition, it also expects maxlength attribute to tell the plugin to limit the character of that range.  

It can take optional object parameter (selector and text) to add the counter of the remaining characters on the editable element.

##Example:-
    <p class="textarea" maxlength="99" contenteditable="true"></p>
    $(".selector").limitText();
    
##Working Example:-

http://jsfiddle.net/shriek/H7h87/
