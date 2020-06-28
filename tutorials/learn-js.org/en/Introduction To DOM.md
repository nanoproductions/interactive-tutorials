Tutorial
--------

Welcome to your first lesson the DOM. The DOM is what makes JavaScript usable with the Browser essentailly.

The DOM stands for **Document Object Model**

So enough with the explanations, let see something in action.

I will setup an `index.html` file with the following code:

    <!DOCTYPE html>
    <html>
    <head>
        <title>JS Sandbox</title>
    </head>
    <body>
        <h1>Hello World!</h1>
    </body>
    <script>
        console.log("Hello World");
    </script>
    </html>

We will be working directly in our HTML file for now to keep things simple, but if you prefer to work in a seperate JS file, then feel free to do so. Just make sure you link your `js` file with your html file.

**Document**

Let's `console.log()` the `document` object in JavaScript.

    console.log(document);

If you were to check the console, you would find:

    <!DOCTYPE html>
    <html>
    <head>
        <title>JS Sandbox</title>
    </head>
    <body>
        <h1>Hello World!</h1>
    </body>
    <script>
        console.log("Hello World");
    </script>
    </html>


Now, if I remember, we `console.log()` the `document` object in JavaScript, and not HTML, so where did the HTML come from. So, in JavaScript, the `document` object refers to the HTML that we have on our page. This is why you will see how the `DOM` binds `JS` and `HTML` together.

**Head**

Let's print out the code that we can find in the `head` of our HTML document.

    console.log(document.head)

And we should see an output of: 

    <head>
        <title>JS Sandbox</title>
    </head>

Exercise
--------

For your exercise, you will be printing out the `body` of our HTML document. 

Just like we printed out the `head`, now it is your turn to print out the `body`.

Tutorial Code
--------

// Here we are printing out the `head`, now you want to edit this line and change it to printing the `body`.

console.log(document.head);

Expected Output
--------

    <body>
        <h1>Hello World!</h1>
    </body>

Solution
--------

// Here we are printing out the `head`, now you want to edit this line and change it to printing the `body`.

console.log(document.body);