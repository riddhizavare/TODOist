<---Sat- Apr 1---->

1. server created and run on port 3000
2. GET /greetings call --> "Hello World" of servers
3. GET /todos call -->
    readData --. readFile -->data(string) --> Array Object (JSON.parse)
    response object --> "message", "data" and "error"
4. POST /todos call -->
    middleware --> to get body from request object --> "express.json()" --> newTodo
    readData --> to get older data (for persistency)
    newTodo --> Pushed to array object --> "elder + newer = final data"
    fs.writeFile --> "final data" --> stringify(array object) --> stored
5. Utils
    import neccessary files/modules
    readData --> "file-path" --> read -->data(string) --> JSON.parse(data) --> Array Object
    module.exports = {...object} --> readData

<--------Wed - Apr 5 --------->

EJS (Embedded JS)--->
it is used to write js in html format


EJS is used to render templates i.e html format


#EJS

basic syntax - <% some code %>
variable & value - <%= varName %>
string in syntax - <% "some value" %>
import syntax - <%- include("path/to/file") %>

partials in ejs -- to import any repeating code like nav and footer



React
library-set of function
open source libarary by facebook
why react

component in react is function 


jsx-return html code
jsx-
writing react code
1.create fun
2.return statement containing html code






website contain--coda,content
use js--to render the page, to fetch dynamic data
type module
defer-


adv
Declaration 
react check where is to change and change only that part not rerender the whole page
virtual dom



Register ->user_info ->save into database

Register -> user_info 



Login -> incoming_info compare with saved_info -> yes login allowed
->no login failed

Login -> incoming_info -> password (plain text) ->compare (with salt) and hash saved in db ->yes or no





