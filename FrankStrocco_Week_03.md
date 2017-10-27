### Rails Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What was your impression of the mob programmimg day? Did you notice any pros or cons of this strategy?
Mob programmimg was better than i thought it was going to be. Seemed like everyone was able to add something useful to the project. I thought there would be a little more arguments on which way to get things done. But the discussions were calm and thoughtful. When we wasted too much time on one thing, we kind of took a vote to move on to another way of coming up with a solution.

#### 2. What is jQuery and what are the two ways you can add it to your project?

[Your Answer]
jQuery is somewhat of a framework for javascript. Giving you shortcut style of adding javascripts to html and css


[Googled Answer]
The purpose of jQuery is to make it much easier to use JavaScript on your website.
jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish,
 and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

The jQuery library contains the following features:

HTML/DOM manipulation
CSS manipulation
HTML event methods
Effects and animations
AJAX
Utilities


#### 3. Write an example of the jQuery function used to make sure the webpage has loaded before trying to load any Javascript.
$(document).ready(function() {
});


#### 4. In a project, what piece do the HTML and CSS form (think MVC roles)? Explain a little bit about this piece or "layer".

//Your Answer
HTML and CSS are for the View in MVC. The View is where the user will interact with our application. It should look good and be well laid out for a
good user experience.

//Googled Answer
View is a user interface. View displays data from the model to the user and also enables them to modify the data. ASP.NET MVC views are stored in Views folder.

#### 5. We learned that JQuery is a javascript library. What do you think a library is? Is it different than a framework? Do 5-10 min of googling to find these anwers.

For example, on Mac OS X frameworks are just libraries, packed into a bundle. Within the bundle you will find an actual dynamic library (libWhatever.dylib). The difference between a bare library and the framework on Mac is that a framework can contain multiple different versions of the library. It can contain extra resources (images, localized strings, XML data files, UI objects, etc.) and unless the framework is released to public, it usually contains the necessary .h files you need to use the library.

A software framework is a re-usable design for a software system (or subsystem). A software framework may include support programs, code libraries, a scripting language, or other software to help develop and glue together the different components of a software project. Various parts of the framework may be exposed through an API..

#### 6. What are wireframes? Explain when and why you might use them.

//Your Answer
wire frames are simple layouts or templates of what you want your website to start off looking like.

//Googled Answer
A website wireframe, also known as a page schematic or screen blueprint, is a visual guide that represents the skeletal framework of a website. Wireframes are created for the purpose of arranging elements to best accomplish a particular purpose.

#### 7. What do we call the code layer that makes it possible for the user to interact with the application?

//Your Answer
Code layer that makes it posssible for the user to interact with the app would be the controller.

//Googled Answer

The ASP.NET MVC framework maps URLs to classes that are referred to as controllers. Controllers process incoming requests, handle user input and interactions, and execute appropriate application logic. A controller class typically calls a separate view component to generate the HTML markup for the request.


#### 8. Write two valid JQuery commands that use any two of these: .click(), .append(), .prepend(), .hide(), .show(), .toggle(), .remove()
Might look similar to this example:

```js
$(document).ready(function(){
  $( "p" ).parent( ".highlighted" ).css( "background", "red" );

  #(".sample").click(function(){
    ".sample").hide();
  })

});

```

#### 9. What do we call the code layer responsible for handling and storing the data and logic?

//Your Answer
code layer responsible for handling and storing data and logic would be the model

//Googled Answer
The central component of MVC, the model, captures the application's behavior in terms of its problem domain, independent of the user interface. The model directly manages the application's data, logic and rules. So the Model is the biggest, most important layer in most MVC applications.


#### 10. How can you traverse up and down the DOM? Give an example of two commands.

//Your Answer
using jquery you can ..

(".div").parent();
("h2").siblings();

//Googled Answer

What is Traversing? jQuery traversing, which means "move through", are used to "find" (or select) HTML elements based on their relation to other elements. Start with one selection and move through that selection until you reach the elements you desire. The image below illustrates an HTML page as a tree (DOM tree).
