MooComplete
===========

Add autocomplete functionality to input elements.

How to Use
----------

Add MooComplete:

    new MooComplete('idofelementhere', {
      list: ['list', 'of', 'elements', 'to', 'use', 'to', 'suggest'], // elements to use to suggest.
      mode: 'text' // suggestion mode (tag | text)
      size: 5 // number of elements to suggest
    });

This turns the `<input id="idofelementhere">` into a MooComplete widget. 

You can also pass functions to render the elements in the list. For more documentation on this please check the source and the [advanced example](http://dubbelboer.com/MooComplete/)

Example
-------

You can find an example at [http://dubbelboer.com/MooComplete/](http://dubbelboer.com/MooComplete/)

Screenshots
-----------

![Screenshot](http://dubbelboer.com/MooComplete/demo.png)
![Screenshot](http://dubbelboer.com/MooComplete/demo2.png)

