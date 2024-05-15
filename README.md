# btbig

**btbig** is a database driven blog for gopher servers (aka a "phlog"). 

It is suitable for all gopher servers which can run "moles" (dynamically 
generated content), and support dynamic gopher menus.  Initially, this 
will be only R-36.net's Geomyidae, and 

In traditional gopher menu usage, the selectable menu options (selectors) 
are the primary focus, and the 'i' information messages are supposed to 
provide additional details about the selectors.

**btbig** flips that relationship on its head and delivers the content as
'i' information messages, giving it primary focus over the selectors. 
Content is delivered as a part of a menu, thus it can always give the user 
other options than simply reading a file and returning to a previous menu.  

This is ideal for sequentially ordered posts, such as one might find in a 
phlog.  Isn't it better to just select "next post", rather than having to 
first go "back", or "up" a menu, and then select "next post" anyway?

