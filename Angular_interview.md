# Angular
### What is Angular Framework?
* Angular is one of the most popular JavaScript frameworks developed and maintained by Google. 
* It is an open-source front-end web framework based on TypeScript. It is  used to build frontend, single-page applications that run on JavaScript
* It is most suited for developing enterprise web applications because its code is reusable and maintainable
*  
* Angular is an open-source web application development framework created by Google. It is used to build frontend, single-page applications that run on JavaScript.
* Angular is an open-source, JavaScript framework wholly written in TypeScript.
* Angular is a TypeScript-based open-source front-end platform that makes it easy to build web, mobile and desktop applications. 
* The major features of this framework include declarative templates, dependency injection, end to end tooling which ease application development.
* Angular was introduced to create Single Page applications. This framework brings structure and consistency to web applications and provides excellent scalability and maintainability.
* it takes care of many aspects of frontend web applications such as HTTP requests, routing, layout, forms, reactivity, validation.
###  What are Single Page Applications (SPA)?
* Single page applications are web based applications that only need to be loaded once, with new functionality consisting of only minor changes to the user interface. 
* It does not load new HTML pages to display the content of the new page, but rather generates it dynamically. This is made feasible by JavaScript's ability to alter
* DOM components on the current page. A Single Page Application method is speedier, resulting in a more consistent user experience

### What are templates in Angular?
A template is a kind of HTML that instructs Angular about how to display a component. An Angular HTML template, like conventional HTML, produces a view, or user interface, in the browser, but with far more capabilities. Angular API evaluates an HTML template of a component, creates HTML, and renders it.

##### There are two ways to create a template in an Angular component:
Inline Template
Linked Template

Inline Template: The component decorator's template config is used to specify an inline HTML template for a component. The Template will be wrapped inside the single or double quotes.
#### Example: 
```
@Component({
    selector: "app-greet",
    template: `<div>
        <h1> Hello {{name}} how are you ? </h1>
        <h2> Welcome to interviewbit ! </h2>
    </div>`
})
```
Linked Template: A component may include an HTML template in a separate HTML file. As illustrated below, the templateUrl option is used to indicate the path of the HTML template file.

#### Example: 
```
@Component({
    selector: "app-greet",
    templateUrl: "./component.html"
})
```

###  What is data binding in Angular?
 * Data binding is one of the most significant and effective elements for creating communication between the DOM and the component.
 * It makes designing interactive apps easier by reducing the need to worry about data pushing and pulling between the component and the template.

#### There are Four types of Data binding in Angular: 
1. Property Binding
2. Event Binding
3. String Interpolation
4. Two way data binding

* **Property Binding**: One method of data binding is called property binding. In property binding, we connect a DOM element's property to a field that is a declared property in our TypeScript component code. In reality, Angular transforms string interpolation into property binding internally.

* **Event Binding** : Using event binding, you may respond to DOM events like button clicks and mouse movements. When a DOM event (such as a click, change, or keyup) occurs, the component's designated method is called.

* **String Interpolation**: In order to export data from TypeScript code to an HTML template( view ), String Interpolation is a one way data binding approach. The data from the component is shown to the view using the template expression enclosed in double curly braces. The value of a component property is added by using string interpolation.

### What are some of the advantages of Angular over other frameworks?
* Angular provides a number of built-in features like routing, state management, rxjs library and http servicesstraight.
* Angular supports two-way data-binding.
* It follows MVC pattern architecture.
* It supports static templates and Angular template.
* It facilitates you to add a custom directive.
* It also supports RESTfull services.
* Validations are supported in Angular.
* Angular provides client and server communication.
* It provides support for dependency injection.
* It provides powerful features like Event Handlers, Animation, etc.
* 

### What is the main purpose of Angular?
* The main purpose of using Angular is to create fast, dynamic and scalable web applications.
* We can create these applications very easily with Angular using components and directives.
* Angular was started as a SPA (Single-Page-Application) framework, and now it supports dynamic content based on different users through dependency injection.
* It provides a platform for easy development of web-based applications

### Directives
Angular 2 provides support for 3 types of the directive. Which are as follows :

* Attribute Directive:  It modifies the behavior or appearance of the HTML element.
* Structural Directive: This Directive is used to change the structure of the element. It basically alters the DOM element, by using this we can add, delete and replace the element with a new element. It modified the DOM layout.
 * Component Directive: We cannot create angular2 applications without components. Now we can have a closer look at how this component work and what type of metadata it contains.
Performance: The performance of the angular 2 application has improved a lot because of fast change detection and offline compilation. support for asynchronous templating and dynamic loading helps in improving the page load and time.
 * Support for a Component-Based Architecture: Angular 2 application is completely based on components. It follows component bases architecture. Which makes our code structure easier.


### Features
* The following are some salient features of Angular:
* Progressive Web Applications (PWA) can be developed using Angular. PWA delivers an app-like experience to the audience using modern web capabilities.
* Applications written in Angular load quickly; moreover, Angular allows you to render the code into HTML & CSS.
* Angular enables developers to create high-end animations that enhance the user experience.
* Angular offers command-line tools to assist developers in building and testing an application.
* The built-in dependency injection of Angular facilitates application development.
* Angular frequently improves its Component Development Kit (CDK) with version upgrades.
* Angular uses TypeScript, which offers efficient bug detection and thereby reduces development time.




