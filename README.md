# QuickAndDirtyHtmlGenerator

this is a quick and dirty, hacked in 10 minutes html generator in python. 
more specificly an Element class that
  
  - just takes tags (n = Element("tag")), no attributes or whatever, 
  - can have inner stuff (n.text("stuff")) 
  - can have children Elements (m = n.append("tag")) 
  - which will be returned as string (n.render()). 
  
do not use anywhere near prod.

code as is. use with caution as you like
