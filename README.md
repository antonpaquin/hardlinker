WebUI for hardlinking files from one place to another.

Nice enough that it's _slightly_ less unpleasant than doing it all by hand.

I still need to come up with some kind of automatic parsing mechanism, and beyond that just an auto-fill n+1 button would be nice.

Plus I need to theme the damn thing.

Anton: if you're coming back here after a long time: how to:

- Click dirs / files on top and add them to the bottom
- Top (big) '+' controls target destination kinda like directory. Typically your first is '/media/whatever' and then the rest are individual paths eg ['/media/library/', 'manga', 'series']
- Bottom little '+' is parameters
- big text input is a python format string (params come from little inputs)
- fill out your volume params for everything
- params are all strings, todo parse out ints somehow ({x:03} won't work unless I'm missing something)
- link button runs everything, and if successful removes it from the list

