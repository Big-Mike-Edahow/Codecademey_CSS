CSS VARIABLES

Defining Variables

CSS Variables are defined the same way as any other CSS declaration, making them syntactically convenient and easy to remember.

Each variable declaration must begin with a double hyphen (--) followed by the variable name. After the variable name is declared a value can then be assigned to it.

In the example below, we have a variable named --main-header-color with a color value #DADECC assigned to it. Note the double hyphen (--) that is preceding the variable name.

h1 {
 --main-header-color : #DADECC;
}

There are specific naming conventions to keep in mind when declaring variables.

The first is that variables are case sensitive, meaning --body-text-color and --Body-Text-Color are two different variables.

It is also good practice to avoid using capital letters in variable names to prevent this type of confusion.

Additionally, it is common to use hyphen delimited strings such as writing --list-background-color instead of --listBackgroundColor when defining a variable name.

Variables mitigate the need to repeat property values and make CSS code easier to read.

You can use variables in CSS to store values.

Variable declaration must start with a double hyphen (--).

Variables must be used as values for CSS properties.

Variables must be used as an argument inside of the var() function.

Variables are subject to both scope and inheritance.

Globally scoped variables are defined inside the :root pseudo-class.

Overriding a variable is done by redefining that variable’s value inside of the desired selector ruleset.

Fallback values can be used to provide a backup value if the initial variable is invalid.

Multiple fallback values can be provided by adding more values inside cascading var() functions.

Responsively designed web pages can be created by combining variables with media queries.
