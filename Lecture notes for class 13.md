# Data persistence 
 - The ability to save data across sessions/visits to page.

 ## 4 Important mandatory operations to have that make data persistence
 C - Create > setItem() = 2 argument: Key, value *adds item* Ex = setItem(dragon:gold)
 R - Read > getItem() = (key) *gets item*
 U - Update > Same as create; if the key is the same, it will override the value setItem (dragon:blue)
 D - Delete/Destroy > removeItem(key) = remove the key/value pair
    Clear() > clears *all* local storage. Probalby used for a hard reset. No arguments are used, just invoke function.

# JSON **IMPORTANT**
*JavaScript Object Notation*
-How you convert string to JS.