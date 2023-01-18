

## 1. Describe the pros and cons of a few methods of communication between Angular components.

-> via Input() decorator:The @Input() decorator in a child component or directive signifies that the property can receive its value from its parent component.
Example :  @Input() item = ""; // decorate the property with @Input()

-> via ViewChild() decorator: A ViewChild is a component, directive, or element as a part of a template. If we want to access a child component, directive, DOM element inside the parent component, we use the decorator @ViewChild().
Suppose we have two components, a child and a parent one. Since the child component can be located inside the parent component, it can accessed as @ViewChild.
Example: @ViewChild(ChildComponent) chviewChild: ChildComponent;

-> via Output() decorator and EventEmitter:
The @Output() decorator in a child component or directive lets data flow from the child to the parent.
The child component uses the @Output() property to raise an event to notify the parent of the change. To raise an event, an @Output() must have the type of EventEmitter, which is a class in @angular/core
Example : The @Output() decorator in a child component or directive lets data flow from the child to the parent.

-> using Services:Using services, it is easier to store data and make it available in the application.
Building on the application that we created in Introduction to Angular Services we will add an input element so that users can add a string to a list of items. This is a way to pass data using Angular Services


## 2. Describe 3 things you dislike about Angular.

1. view is totally separated from its business logic, namely the html template and component class. I found it’s more pleasurable to mix the html element and its business logic, which is supported in react.

2 .npm packages Third-party less  support TypeScript.

3 .You need to create many files just to make something very small. And the idea of the whole framework, how is it build.

## 3. If there are any items that you did not complete, please list them out.
Tried to complete it as shown in it


## 4. If you had 40 hours to work on this project, please describe all the improvements you would incorporate.

If I had that much time, I would have tried all the data that the API gives that all and display that, and then 
Would have made User Interface attractive,
name-wise sorting,
searching,
user friendly table,
filtering of agency data &
many other operations had done

