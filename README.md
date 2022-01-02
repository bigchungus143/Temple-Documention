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

# readfile

readfile does what it is called, reads the content of the file selected

Usage:
```lua
readfile(<string> filename)
```

# writefile

writefile writes content to filename

Usage:
```lua
writefile(<string> filename, <string> content)
```

# hookmetamethod

Hooks the metamethod passed in the object's metatable with hook. A function to call the original metamethod is returned, you must use this function in order to call the original metamethod.

This function will error if an object without a metatable is passed or a invalid metamethod is passed.(took from syn docs because it works the exact same way!)

Usage:
```lua
hookmetamethod(<Object> object, <string> metamethod, <function> hook)
```

# hookfunction

Hooks the function called Function and replaces it with Hook then returning a backup of Function

Usage:
```lua
hookfunction(<function> Function, <function> hook)
```

# securecreate

Creates a secure string

Usage:
```lua
securecreate(<string> script)
```

# secureload

Loads a secure script

Usage:
```lua
secureload(<string> securescript)
```

# protect_gui

Protects the GUI gui

Usage:
```lua
protect_gui(<string> gui)
```

# unprotect_gui

Unprotects the GUI gui

Usage:
```lua
unprotect_gui(<string> gui)
```
