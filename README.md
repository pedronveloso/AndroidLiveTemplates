# Author

Pedro Veloso
( pedro.n.veloso AT gmail.com )
G+ : https://plus.google.com/+PedroVeloso/posts

# AndroidLiveTemplates

This a set of Android Studio Live Templates in form of a file that I use on my IDE, with the purpose of speeding up Android development. It works with both Android Studio and IntelliJ.

# What are Live Templates

From IntelliJ's website:

"Live templates let you insert frequently-used or custom code constructs into your source code file quickly, efficiently, and accurately. They contain predefined code fragments."

# How to install 

Live templates are stored in the following location:


Windows: <your home directory>\.<product name><version number>\config\templates

Linux: ~/.<product name><version number>/config/templates

OS X: ~/Library/Preferences/<product name><version number>/templates


Just copy the _Android.xml_ file to the specified location above. Later on the IDE you can enable/disable each defenition independetly via _Settings_ > _Editor_ > _Live Templates_.

# Template definitions


__Note__: Just type the following abbreviations and hit the "TAB" for accepting the IDE's suggestion.


__Abbreviation__ : _Description_



__fbtn__: _Find Button (Activity)_
__fbtnf__: _Find Button (Fragment)_
__fet__ : _Find EditText (Activtity)_
__fetf__: _Find EditText (Fragment)_
__ftv__: _Find TextView (Activity)_
__ftvf__: _Find TextView (Fragment)_
__soc__ : _Switch Statment for OnClick Handler_
__toast__: _Show short lived toast message_
__ttext__: _Add tools:text attribute_
__xmla__: _Add XML android namespace_
__xmlt__: _Add XML tools namespace_


The following are used for a specialized Log class that I usually use in my projects, that requires no "TAG". You're free to modify it to suit your needs.


__ld__: _Print Debug Log message_
__li__: _Print Info Log message_
__le__: _Print Error Log message_
__lv__: _Print Verbose Log message_
__lw__: _Print Warn Log message_
