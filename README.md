# nest.js
a better way for js

file layout

main
| layout.tsx
| caller.tsx
| costumes.tsx
------

# how it works
----
layout.tsx is used to position elements
caller.tsx is used to create functions and stuff
costumes.tsx allows you to costumize

# example

caller.tsx
call "button-1", btn-primary

layout.tsx
get "button-1" (50, 30, 25,)

costumes.tsx
get "button-1" :(
  background-click = "fffff"
  background = "00000"
  text = "hello world
);
