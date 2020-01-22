# Local Storage
 - The downsides of using cookies as local storage are:
    - Cookies are included with every HTTPS request, so it slows down the web app by sending the same data over and over.
    - Cookies send data unencrypted over the internet
    - Cookies are very limited, specifically to 4kb of data, which is enough to slow down the web app, but not enough to be really useful either.
 - Web Storage can also be referred to as "Local Storage" or "DOM Storage". 
 - It allows for web pages to store named key/value pairs locally.
 - HTML 5 storage is based on key/value pairs. You store data based on a name key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JS, including strings, Booleans, integers, or floats.
 - If you are storing and retrieving data that isn't a string, you will need to use functions like parseInt()
 

