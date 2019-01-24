# Angular features

* Angular extends HTML attributes with ng-directives, and binds data to HTML with Expressions
* The ng-app directive defines an AngularJS application
* The ng-model directive binds the value of HTML controls (input, select, textarea) to application data
* The ng-bind directive binds application data to the HTML view
* Angular starts automatically when the web page has loaded
* The ng-app directive tells Angular that the div element is the "owner" of an Angular application
* The ng-init directive can be used to initialize Angular application variables
* Angular expressions are written inside double braces: {{ expression }}
* Angular expressions bind Angular data to HTML the same way as the ng-bind directive
* Angular controllers control Angular applications and used to serve HTTP requests
* The ng-app directive defines the application, the ng-controller directive defines the controller
* Angular expressions are much like JavaScript expressions - they can contain literals, operators, and variables
* If you remove the ng-app directive, HTML will display the expression as it is, without solving it
* Angular expressions do not support conditionals, loops and exceptions while JavaScript expressions does
* Angular expressions support filters, while JavaScript expressions does not
* Controllers always belong to a module
* A module is created by using the Angular function - angular.module()
* Global functions should be avoided in JavaScript. They can easily be overwritten or destroyed by other scripts, Angular modules reduces this problem, by keeping all functions local to the module
* Calls to angular.module can only be compiled after the Angular library has been loaded
* Angular also lets us to define our own directives
* The ng-repeat directive repeats an HTML element
* The ng-repeat directive actually clones HTML elements once for each item in a collection
* The ng-init directive defines initial values for an Angular application
* In addition to all the built-in Angular directives, we can create our own directives. New directives are created by using the directive() function
* When naming a directive, we must use a camel case name like w3TestDirective, but when invoking it we must use " - " separated name like w3-test-directive
* We can restrict our directives to only be invoked by some of the methods


# Code samples

* Angular Expression - https://github.com/praveenkishor123/Angular/blob/master/angularExpressionExample.html

* Simple greeting message display - https://github.com/praveenkishor123/Angular/blob/master/angularExpressionExample.html

* ng-bind directive - https://github.com/praveenkishor123/Angular/blob/master/ngBindExample.html

* ng-repeat directive - https://github.com/praveenkishor123/Angular/blob/master/ngRepeatExample.html

* ng-model and ng-bind - https://github.com/praveenkishor123/Angular/blob/master/simpleDirectiveExample.html

