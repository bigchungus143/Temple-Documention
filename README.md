# Temple-Documention

This is not an official documentation but a unofficial one to explain what every function does and the usage of them!

# isfolder

isfolder returns if the path you picked is a folder or not

Usage:
```lua
isfolder(<string> path)
```

# isfile

isfile is like isfolder and returns if the path you picked is a file or not

Usage:
```lua
isfile(<string> path)
```

# makefolder

makefolder creates a folder at the path select

Usage:
```lua
makefolder(<string> path)
```

# hookmetamethod

Hooks the metamethod passed in the object's metatable with hook. A function to call the original metamethod is returned, you must use this function in order to call the original metamethod.

This function will error if an object without a metatable is passed or a invalid metamethod is passed.(took for syn docs because it works the exact same way!)

Usage:
```lua
hookmetamethod(<Object> object, <string> metamethod, <function> hook)
```
