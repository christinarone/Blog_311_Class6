# Blog_311_Class6
Class 6

If a user attempts to create a resource that already exists—for example, an email address that’s already registered—what HTTP status code would you return?
  409 is the response it will return.

Consider a responsive site design that requires a full-width image in all responsive states. What would be the correct way to code this to ensure the page loads the smallest image required to fill the space?
  An example og this would be to change the body content to be set to a maximum width of 1200 pixels.

When should you npm and when should you yarn?
NPM installs dependency packages sequentially, yarn installs in-parallel. Because of this, Yarn performs faster than NPM when installing larger files.

How can you make sure your dependencies are safe?
  Make sure to update all of the security audits of the dependencies.

What are the differences between CHAR and VARCHAR data types (MySQL)?
  CHAR is fixed length while VARCHAR is variable length. That means, a CHAR(x) string has exactly x characters in length, including spaces. A VARCHAR(x) string can have up to x characters and it cuts off trailing spaces, thus might be shorter than the declared length.
  
How else can the JavaScript code below be written using Node.Js to produce the same output?
  console.log("first");
setTimeout(function() {
    console.log("second");
}, 0);
console.log("third");
