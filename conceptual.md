### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?
Python is used for server side scripting while Javascript is used for client side scripting

- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.

- What is a unit test?
  A unit test is when your testing one specific line of code

- What is an integration test?
  Integration testing is when your testing more then one line of code

- What is the role of web application framework, like Flask?
  Flask is a small and lightweight Python web framework that provides useful tools and features that make creating web applications in Python easier.

- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?

- How do you collect data from a URL placeholder parameter using Flask?
  You would define a route for the url your trying to access

- How do you collect data from the query string using Flask?
  You would have to import a request method 

- How do you collect data from the body of the request using Flask?
  Use getlist if the key is sent multiple times and you want a list of values. get only returns the first value.

- What is a cookie and what kinds of things are they commonly used for?
  Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network.

- What is the session object in Flask?
  In the flask, a session object is used to track the session data which is a dictionary object that contains a key-value pair of the session variables and their associated values. 

- What does Flask's `jsonify()` do?
  jsonify is a helper method provided by Flask to properly return JSON data.
