# Important points  
1. AngularJS is a JavaScript framework.  
2. It can be added to an HTML page with a script tag.  
3. AngularJS extends HTML attributes with Directives, and binds data to HTML with Expressions.  
4. AngularJS extends HTML with ng-directives.  
5. The ng-app directive defines an AngularJS application.  
6. The ng-model directive binds the value of HTML controls (input, select, textarea) to application data.  
7. The ng-bind directive binds application data to the HTML view.  
8. AngularJS starts automatically when the web page has loaded.  
9. The ng-app directive tells AngularJS that the div element is the "owner" of an AngularJS application.  
10. The ng-init directive initializes AngularJS application variables.  
11. AngularJS expressions are written inside double braces: {{ expression }}.  
12. AngularJS expressions bind AngularJS data to HTML the same way as the ng-bind directive.  
13. AngularJS modules define AngularJS applications.  
14. AngularJS controllers control AngularJS applications.  
15. The ng-app directive defines the application, the ng-controller directive defines the controller.  
16. AngularJS modules define applications- var app = angular.module('myApp', []);  
17. AngularJS controllers control applications.  
18. AngularJS expressions can also be written inside a directive: ng-bind="expression".  
19. AngularJS expressions are much like JavaScript expressions: They can contain literals, operators, and variables.  
20. If you remove the ng-app directive, HTML will display the expression as it is, without solving it.  
21. You can write expressions wherever you like, AngularJS will simply resolve the expression and return the result.  
22. Like JavaScript expressions, AngularJS expressions can contain literals, operators, and variables.  
23. Unlike JavaScript expressions, AngularJS expressions can be written inside HTML.  
24. AngularJS expressions do not support conditionals, loops, and exceptions, while JavaScript expressions do.  
25. AngularJS expressions support filters, while JavaScript expressions do not.  
26. Controllers always belong to a module.  
27. A module is created by using the AngularJS function angular.module  
28. It is common in AngularJS applications to put the module and the controllers in JavaScript files.  
29. The [] parameter in the module definition can be used to define dependent modules.  
30. Without the [] parameter, you are not creating a new module, but retrieving an existing one.  
31. Global functions should be avoided in JavaScript. They can easily be overwritten or destroyed by other scripts.  
32. AngularJS modules reduces this problem, by keeping all functions local to the module.  
33. calls to angular.module can only be compiled after the angular library has been loaded.  
34. AngularJS also lets you define your own directives.  
35. AngularJS directives are extended HTML attributes with the prefix ng-  
36. The ng-repeat directive repeats an HTML element.  
37. The ng-repeat directive actually clones HTML elements once for each item in a collection.  
38. The ng-init directive defines initial values for an AngularJS application.  
39. In addition to all the built-in AngularJS directives, you can create your own directives. New directives are created by using the .directive function.  
40. When naming a directive, you must use a camel case name, w3TestDirective, but when invoking it, you must use - separated name, w3-test-directive.
41. You can restrict your directives to only be invoked by some of the methods.  
