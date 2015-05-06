# bustout.js
Bustout out of your code into a REPL - Great for Debugging

### why?
Bustout aims to speed development up by allowing you to bustout into a REPL once you hits a specific point in your code, this allows you to inspect what is going on and test multiple changes before continuing.

### usage
in any part of your code add:

    require('bustout')(context);

the context is a reference to the variables you want to inspect, or be able to execute.

