# Angular-8 Interview Questions & Answers

> Click :star:if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
|---- | ---------
| <span id="Q1">1</span> | [What is Angular 8?](#what-is-angular-8)|
| <span id="Q2">2</span> | [What is new in Angular 8?](#what-is-new-in-angular-8)|
| <span id="Q3">3</span> | [What are the building blocks of Angular?](#what-are-the-building-blocks-of-angular)|
| <span id="Q4">4</span> | [Which command is used to create service?](#Which-command-is-used-to-create-service)|
| <span id="Q5">5</span> | [What is use of `ngIf` directive?](#What-is-use-of-ngIf-directive)|
| <span id="Q6">6</span> | [What is use of `ngSwitch` directive?](#What-is-use-of-ngSwitch-directive)|
| <span id="Q7">7</span> | [What is use of `ngFor` directive?](#What-is-use-of-ngFor-directive)|
| <span id="Q8">8</span> | [What is use of `ngClass` directive?](#What-is-use-of-ngClass-directive)|
| <span id="Q9">9</span> | [What is use of `ngStyle` directive?](#What-is-use-of-ngStyle-directive)|
| <span id="Q10">10</span> | [What is Angular CLI?](#What-is-Angular-CLI)|
| <span id="Q11">11</span> | [How to install angular CLI?](#How-to-install-angular-CLI)|
| <span id="Q12">12</span> | [What are IDEs that can be used to develop angular application?](#What-are-IDEs-that-can-be-used-to-develop-angular-application)|
| <span id="Q13">13</span> | [What is `src` and `app` folder?](#What-is-src-and-app-folder)|
| <span id="Q14">14</span> | [What is `e2e` folder?](#What-is-e2e-folder)|
| <span id="Q15">15</span> | [How to use bootstrap with angular?](#How-to-use-bootstrap-with-angular)|
| <span id="Q16">16</span> | [Difference between npm start and ng serve?](#Difference-between-npm-start-and-ng-serve)|
| <span id="Q17">17</span> | [Explain Angular application flow.](#Explain-Angular-application-flow)|
| <span id="Q18">18</span> | [What is app-root?](#What-is-app-root)|
| <span id="Q19">19</span> | [What is Module?](#What-is-Module)|
| <span id="Q20">20</span> | [How to create component from CLI?](#How-to-create-component-from-CLI)|
| <span id="Q21">21</span> | [How to use inline template in component?](#How-to-use-inline-template-in-component)|
| <span id="Q22">22</span> | [How to add style to your component in html which will be applicable to that particular component only?](#How-to-add-style-to-your-component-in-html-which-will-be-applicable-to-that-particular-component-only)|
| <span id="Q23">23</span> | [How to use selector as attribute?](#How-to-use-selector-as-attribute)|
| <span id="Q24">24</span> | [How to use selector as class?](#How-to-use-selector-as-class)|
| <span id="Q25">25</span> | [How to use selector as element?](#How-to-use-selector-as-element)|
| <span id="Q26">26</span> | [How to capture data emitted with event in event binding?](#How-to-capture-data-emitted-with-event-in-event-binding)|
| <span id="Q27">27</span> | [How to access property of child component from parent component?](#How-to-access-property-of-child-component-from-parent-component)|
| <span id="Q28">28</span> | [How to pass data from child component to parent component?](#How-to-pass-data-from-child-component-to-parent-component)|
| <span id="Q29">29</span> | [How to perform component communication?](#How-to-perform-component-communication)|
| <span id="Q30">30</span> | [What is view encapsulation and how to disable it?](#What-is-view-encapsulation-and-how-to-disable-it)|
| <span id="Q31">31</span> | [What is use of local reference?](#What-is-use-of-local-reference)|
| <span id="Q32">32</span> | [How to access local reference in Typescript code?](#How-to-access-local-reference-in-Typescript-code)|
| <span id="Q33">33</span> | [What is use of ng-content?](#What-is-use-of-ng-content)|
| <span id="Q34">34</span> | [How to create custom directive?](#How-to-create-custom-directive)|
| <span id="Q35">35</span> | [How to create structural directive?](#How-to-create-structural-directive)|
| <span id="Q36">36</span> | [What is Lifecycle hook in angular?](#What-is-Lifecycle-hook-in-angular)|
| <span id="Q37">37</span> | [What is ngOnChanges()?](#What-is-ngOnChanges)|
| <span id="Q38">38</span> | [What is ngOnInit()?](#What-is-ngOnInit)|
| <span id="Q39">39</span> | [What is ngDoCheck()?](#What-is-ngDoCheck)|
| <span id="Q40">40</span> | [What is ngAfterContentInit()?](#What-is-ngAfterContentInit)|
| <span id="Q41">41</span> | [What is ngAfterContentChecked()?](#What-is-ngAfterContentChecked)|
| <span id="Q42">42</span> | [What is ngAfterViewInit()?](#What-is-ngAfterViewInit)|
| <span id="Q43">43</span> | [What is ngAfterViewChecked()?](#What-is-ngAfterViewChecked)|
| <span id="Q44">44</span> | [What is ngOnDestroy()?](#What-is-ngOnDestroy)|
| <span id="Q45">45</span> | [What are **_services_** generally?](#What-are-services-generally)|
| <span id="Q46">46</span> | [How to create **services** and *injecting* into component typescript class in angular (Steps)?](#How-to-create-services-and-injecting-into-component-typescript-class-in-angular-Steps)|
| <span id="Q47">47</span> | [What is hierarchical dependency injection in angular?](#What-is-hierarchical-dependency-injection-in-angular)|
| <span id="Q48">48</span> | [What is Routing?](#What-is-Routing)|
| <span id="Q49">49</span> | [How to setup routes?](#How-to-setup-routes)|
| <span id="Q50">50</span> | [Which directive should be used for changing route?](#Which-directive-should-be-used-for-changing-route)|
| <span id="Q51">51</span> | <a href="#N51">What is difference between **_'/somepath'_** and **_'somepath'_**?</a>|
| <span id="Q52">52</span> | [How to make selected element active based on selected route?](#How-to-make-selected-element-active-based-on-selected-route)|
| <span id="Q53">53</span> | [How to programmatically trigger route?](#How-to-programmatically-trigger-route)|
| <span id="Q54">54</span> | [How to pass parameters to route?](#How-to-pass-parameters-to-route)|
| <span id="Q55">55</span> | [How to fetch parameters in Route?](#How-to-fetch-parameters-in-Route)|
| <span id="Q56">56</span> | [How to add query params to url?](#How-to-add-query-params-to-url)|
| <span id="Q57">57</span> | [How to add query params programmatically?](#How-to-add-query-params-programmatically)|
| <span id="Q58">58</span> | [How to retrieve query param and fragment from url?](#How-to-retrieve-query-param-and-fragment-from-url)|
| <span id="Q59">59</span> | [How to add child routes?](#How-to-add-child-routes)|
| <span id="Q60">60</span> | [What is use of Wildcard routes?](#What-is-use-of-Wildcard-routes)|
| <span id="Q61">61</span> | [How to apply guard to route?](#How-to-apply-guard-to-route)|
| <span id="Q62">62</span> | [How to create guard?](#How-to-create-guard)|
| <span id="Q63">63</span> | [How to create guard from CLI?](#How-to-create-guard-from-CLI)|
| <span id="Q64">64</span> | [How to guard child routes?](#How-to-guard-child-routes)|
| <span id="Q65">65</span> | [What is HttpClient?](#What-is-HttpClient)|
| <span id="Q66">66</span> | [Which module is required for HttpClient?](#Which-module-is-required-for-HttpClient)|
| <span id="Q67">67</span> | [How to make get request using HttpClient?](#How-to-make-get-request-using-HttpClient)|
| <span id="Q68">68</span> | [How to pass headers to http request?](#How-to-pass-headers-to-http-request)|
| <span id="Q69">69</span> | [How to make post request using HttpClient?](#How-to-make-post-request-using-HttpClient)|
| <span id="Q70">70</span> | [How to make put request using HttpClient?](#How-to-make-put-request-using-HttpClient)|
| <span id="Q71">71</span> | [How to catch error of http request?](#How-to-catch-error-of-http-request)|
| <span id="Q72">72</span> | [Which module is required for httpService?](#Which-module-is-required-for-httpService)|
| <span id="Q73">73</span> | [How to make get request using alternative Http Service instead of HttpClient?](#How-to-make-get-request-using-alternative-Http-Service-instead-of-HttpClient)|
| <span id="Q74">74</span> | [What is Observable?](#What-is-Observable)|
| <span id="Q75">75</span> | [What is use of map() operator in observable?](#What-is-use-of-map-operator-in-observable)|
| <span id="Q76">76</span> | [How to send post request in angular using alternative Http Service instead of HttpClient?](#How-to-send-post-request-in-angular-using-alternative-Http-Service-instead-of-HttpClient)|
| <span id="Q77">77</span> | [What are pipes?](#What-are-pipes)|
| <span id="Q78">78</span> | [What are different built in pipes?](#What-are-different-built-in-pipes)|
| <span id="Q79">79</span> | [How to chain pipes?](#How-to-chain-pipes)|
| <span id="Q80">80</span> | [How to create custom pipe?](#How-to-create-custom-pipe)|
| <span id="Q81">81</span> | [How to pass parameters to custom pipe?](#How-to-pass-parameters-to-custom-pipe)|
| <span id="Q82">82</span> | [What is pure pipe and impure pipe?](#What-is-pure-pipe-and-impure-pipe)|
| <span id="Q83">83</span> | [What are approaches to handle form?](#What-are-approaches-to-handle-form)|
| <span id="Q84">84</span> | [Which module is required for form?](#Which-module-is-required-for-form)|
| <span id="Q85">85</span> | [How to access form input controls in Typescript class?](#How-to-access-form-input-controls-in-Typescript-class)|
| <span id="Q86">86</span> | [What are the important properties of ngForm?](#What-are-the-important-properties-of-ngForm)|
| <span id="Q87">87</span> | [How to access form without submit?](#How-to-access-form-without-submit)|
| <span id="Q88">88</span> | [Why form validation is required?](#Why-form-validation-is-required)|
| <span id="Q89">89</span> | [What are different types of validator functions?](#What-are-different-types-of-validator-functions)|
| <span id="Q90">90</span> | [What are different built-in validators?](#What-are-different-built-in-validators)|
| <span id="Q91">91</span> | [How to add validation messages for input controls in form?](#How-to-add-validation-messages-for-input-controls-in-form)|
| <span id="Q92">92</span> | [What is animation in angular?](#What-is-animation-in-angular)|
| <span id="Q93">93</span> | [How to use animation in angular?](#How-to-use-animation-in-angular)|

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

1. ### What is Angular 8?

    Angular is one of the **most popular** and **open source Front-end or Client-side scripting framework** for building Mobile and Desktop Apps. Angular is written in TypeScript language and It is compiled into JavaScript. Angular community has released the latest version Angular 8 on **28 May 2019**. This version contains some of new features, lot of performance and Workflow Improvements.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q1">**⬆ Back to Question 1**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

2. ### What is new in Angular 8?

    *  Angular Ivy :
        
        *  Ivy is the new compiler/runtime of Angluar available for testing.
        *  It is the latest rendering engine but not defualt engine for Angular 8.
        *  It generates smaller bundles; faster compilation.
        *  It translates the templates and components in HTML and JavaScript.
        *  You can enable Ivy in your project as below : 
        ` ng new angular-project --enable-ivy `

    *  Support for TypeScript (Higher Version) : 

        * It supports TypeScript 3.4; no version below 3.4.
        * It is superset of javascript.
            <img src="images/typescript-javascript.png" width="200px" height="200px" float="right">
        * Points out compilation errors at development time only.
        * Object oriented programming language.
        * Introduces strong typing.
        * Portable across browsers, devices and OS.
        * At the end, In Angular; Typescript is converted into Javascript.

    *  Support for Bazel :

        *  Bazel is build tool developed and used by Google.
        *  The angluar community is working to integrate Bazel tool in to the standard angular toolset to enable developers to perform faster builds on large projects.
        *  It allows to deploy only what has been changed.
        *  Opt-in Option with Angular 8.

    *  Support for Web Worker Bundling :

        * Web workers allow you to run CPU-intensive computations in a background thread, freeing the main thread to update the user interface. 
        * If you find your application performs a lot of computations, such as generating CAD drawings or doing heavy geometrical calculations, using web workers can help increase your application's performance.
        *  With Angular 8, you can now generate new web workers from the CLI. To add a worker to the project, you can run:
        ` ng generate webWorker my-worker `

    *  New changes in ViewChild and ContentChild
    *  Builder API and Workspace APIs in the CLI :
      
       ***_Builder APIs -_***
        * Angular 8 released new Builder APIs that allow you to tap into ng build, ng test and ng run to perform processes like build and deployment.
        * With Angular 8 you can try the latest version of AngularFire(The official Angular library for Firebase), which adds a deploy command, making build & deploy to Firebase easier than ever:
          * ` ng add @angular/fire `
          * ` ng run my-app:deploy `

        ***Workspace APIs -_***
         * Previously developers had to manually open and modify their angular.json to make changes to the workspace configuration.
         * With Angular 8.0, new APIs to make it easier to read and modify this file.

    *  Differential Loading by Default : 
        * Differential loading is a process by which the browser based on its own capabilities chooses between modern or legacy JavaScript.
        *  Creates two bundles which will be loaded according to the browser version and support : 
            1. ES6+ Bundle - For New browsers support; So that new browser loads less code to run the app in the browser.
            2. ES5 Bundle - For Old browsers support; So that old browser loads more code to run the app in the browser.

    *  Improvements in AngularJS Migration
    *  Lazy Loading with Dynamics Imports :

        *  Delay the loading of an object until it is required.
        *  Features loaded only when user the user navigates to their routes for the first time.
        *  Keeps the initial bundle size smaller; decreases load time. 
        *  Standard dynamic import syntax is  used.

        *   ```typescript
            const routes: Routes = [
            {
            path: 'items',
            loadChildren: () => import('./items/items.module').then(m => m.ItemsModule)
            }
            ];
            ```

    *  Opt-in usage sharing
    *  Angular Firebase
    *  Use of SVG as a template

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q2">**⬆ Back to Question 2**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

3. ### What are the building blocks of Angular?

    The Main Building blocks of Angular are
    *  Directives :

        * A directive modifies or manipulate the DOM by changing the appearance, behaviour or layout of DOM elements. Angular Directives are basically a **javaScript Class**.
        * Directives are instructions in DOM, Components are directives as well.
        * Directive has selector which can be used as attribute as well as element in html.
        * Directives are more generally used as attribute.
        e.g.
        
            * **_In Typescript File_** : To create directive.
            ```typescript
            @Directive({
            selector:’[makeAppFancy]’
            })
            ```
            * **_In Html File_** : To use that custom directive.
            ```html
            <p makeAppFancy></p>
            ```
        * There are 3 different directives:
          1. Component Directives : 

              * Directives with html template.

          2. Attribute Directives :

              * Change the appearance or behaviour of an element, component, or another directive which is present. 
              * e.g. **ngStyle**.

          3. Structural Directives :

              * Change the DOM layout by adding or removing DOM elements. 
              * e.g. **ngFor**, **ngIf**.
        * To create directive from CLI : 
              
           *  `ng generate directive <directive name>`

           or
           * `ng g d <directivename>`

    *  Modules : 

        *  Logical groupings of components, directives, services etc.

    *  Components :

        *  Basic building blocks of Angular.
        *  Made up of template, class and metadata.

    *  Meta Data :

        *  Tells Angular how to process a class. It is the information angular needs to decide if the particular class is a component, directive, service or just a regular class.
        * It is used to decorate a class using decorator.

    *  Templates : 

        *  UI/Views of an angular application; created using HTML.

    *  Data Binding : 
        
        *  Data binding is basically communication between Typescript code and template.
        *  Data binding is a core concept in Angular and allows to define communication between a component and the DOM, making it very easy to define interactive applications without worrying about pushing and pulling data. 
        *  There are four forms of data binding(divided as 3 categories) which differ in the way the data is flowing.
          
            1. **From the Component to the DOM:**

                1. **Interpolation:** {{ value }}: Adds the value of a property from the component
                    ```html
                    <li>Name: {{ user.name }}</li>
                    <li>Address: {{ user.address }}</li>
                    ```
                
                2. **Property binding:** [property]=”value”: The value is passed from the component to the specified property or simple HTML attribute
                    ```html
                    <input type="email" [value]="user.email">
                    ```
            2. **From the DOM to the Component:**
                
                1. **Event binding: (event)=”function”:** When a specific DOM event happens (eg.: click, change, keyup), call the specified method in the component
                    ```html
                    <button (click)="logout()"></button>
                    ```
            3. **Two-way binding:**
                
                1. **Two-way data binding:** [(ngModel)]=”value”: Two-way data binding allows to have the data flow both ways. For example, in the below code snippet, both the email DOM input and component email property are in sync
                    ```html
                    <input type="email" [(ngModel)]="user.email">
                    ```  

    *  Dependency Injection : 

        *  Dependency Injection is the technique in which classes receive thier dependencies from the external sources rathor than creating themselves.

    *  Services :

        *  Class with specific purpose.
        *  Used for sharing data, implementing application logic and interacting with external resoures.
        *  A service is used when a common functionality needs to be provided to various modules. Services allow for greater separation of concerns for your application and better modularity by allowing you to extract common functionality out of components.

    Let's create a repoService which can be used across components,

    ```typescript
    import { Injectable } from '@angular/core';
    import { Http } from '@angular/http';

    @Injectable({ // The Injectable decorator is required for dependency injection to work
      // providedIn option registers the service with a specific NgModule
      providedIn: 'root',  // This declares the service with the root app (AppModule)
    })
    export class RepoService{
      constructor(private http: Http){
      }

      fetchAll(){
        return this.http.get('https://api.github.com/repositories');
      }
    }
    ```
    The above service uses Http service as a dependency.  

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q3">**⬆ Back to Question 3**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


4. ### Which command is used to create service?

` ng gernerate service myservice `

The above command generates sleleton myservice class in

***_src/app/myservice.service.ts_***

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q4">**⬆ Back to Question 4**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


5. ### What is use of `ngIf` directive?

* It is allows to add/remove the DOM element.
* **_ngIf_** is structural directive. For structural directives * is used before
directive.
```html
<div *ngIf=”isRole”>
<h3>Hi User</h3>
</div>
```
* In above example only if *isRole* variable is `true` then only **“Hi User”**
text will be displayed on UI.
* To use `else` with `ngIf`:

  * Create `<ng-template>` with local reference and in else place that local reference.

  e.g.
  ```html
  <div *ngIf=”isRole”;else noRole>
  <h3>Hi User</h3>
  </div>

  <ng-template #noRole>
  <h3>Hi Unknown</h3>
  </ng-template >
  ```
  
  * Another alternative could be to use ngIf with ! Expression.
  
  e.g.
  ```html
  <div *ngIf=”isRole >
  <h3>Hi User</h3>
  </div>
  <div *ngIf=”!isRole” >
  <h3>Hi Unknown</h3>
  </div>
  ```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q5">**⬆ Back to Question 5**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


6. ### What is use of `ngSwitch` directive?

* It will enable us to add/remove DOM element. If is same as the switch statement of C#.

```html
<div [ngSwitch]=”value”>
  <p *ngSwitchCase=”1”>Value is 1</p>
  <p *ngSwitchCase=”2”>Value is 1</p>
  <p *ngSwitchDefault>Value is Default</p>
</div>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q6">**⬆ Back to Question 6**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


7. ### What is use of `ngFor` directive?

* **_ngFor_** is used to repeat apart of HTML template once per each item from an iterable list.
* **_ngFor_** is structural directive. For structural directives * is used
before directive.
* It is used with *‘let’*.

e.g.
```html
<li *ngFor=”let country of countryListArray”>{{country}}</li>
```
* It will loop *“li”* element for all **countryListArray**. 
* You can obtain current index of iteration using *“index”* var.

e.g.
```html
<li *ngFor=”let country of countryListArray; let i = index”>{{country}}</li>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q7">**⬆ Back to Question 7**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


8. ### What is use of `ngClass` directive?

* ngClass is used to add/remove CSS Class.
* ngClass is used as property of html element.
* It is attribute directive.
* It is used to dynamically add css class to element.
* ngClass is used with with property binding with square brackets
[].The assigned value is Javascript object with key value pair.

e.g.
```html
<p [ngClass]="{‘classname’: person.country ===‘UK’}">ExampleText</p>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q8">**⬆ Back to Question 8**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


9. ### What is use of `ngStyle` directive?

* It is used to modify the style of an HTML Element using expression and also used to change the styles of HTML Element dynamically.
* `ngStyle` is used as property of html element. 
* It is attribute directive. 
* It is used with square brackets []. [] are not part of directive. ngStyle is then style. The value to style can be string or
method that return string. The assigned value is Javascript object with key value pair.

e.g.
```html
<p [ngStyle=”backgroundColor:getColor()”]>ExampleText</p>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q9">**⬆ Back to Question 9**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----


10. ### What is Angular CLI?

* The Angular CLI is a command-line interface tool that we use to
initialize, develop and maintain Angular applications.
* Creates Angular Application with single line commands.
* Some Angular CLI commands -

    *  ng new - generates new angular projects.
    *  ng build - compiles angular app and builds the project for production.
    *  ng generate - generates components, services, directives, routes, pipes etc.
    *  ng serve - Easily test app locally while development.
    *  ng test - run unit tests.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q10">**⬆ Back to Question 10**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

11. ### How to install angular CLI?

* First install node.js
* Then, open node.js command prompt and issue command : 
  
  * ` npm
install –g @angular/cli `

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q11">**⬆ Back to Question 11**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

12. ### What are IDEs that can be used to develop angular application?

A few main IDEs are :
* Webstorm 
* Visual Studio Code
* Sublime

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q12">**⬆ Back to Question 12**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

13. ### What is `src` and `app` folder?

* In `src` folder - your project is created,
* In `app` folder - you can write your code using components, routes,
directives, services and pipes.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q13">**⬆ Back to Question 13**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

14. ### What is `e2e` folder?

* It is required for end to end testing of angular application.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q14">**⬆ Back to Question 14**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

15. ### How to use bootstrap with angular?

* Open terminal, navigate to project folder.
* Execute npm command: ` npm install --save bootstrap `
* Now verify if node_modules folder contain third party package
bootstrap that we have installed.
* In ` angular.json ` you can see **_styles_** array.
* Add below line to **_styles_** array so that bootstrap can be used in
project,

  ```json
  “styles”:[“../node_modules/bootstrap/dist/css/bootstrap.css”]
  ```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q15">**⬆ Back to Question 15**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

16. ### Difference between npm start and ng serve?

* When you run “npm start” it will call whatever command written
inside ` “start” ` in ` package.json `.
  ```json
  “scripts”: {
  “ng”: “ng”,
  “start”: “ng serves”
  .
  .
  }
  ```
* For example: Above content in package.json will call ` “ng serve” `
when npm start command is executed.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q16">**⬆ Back to Question 16**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

17. ### Explain Angular application flow.
* `main.ts` file
  ```typescript
  import { enableProdMode } from '@angular/core';
  import { platformBrowserDynamic } from '@angular/platform-browser-dynamic';

  import { AppModule } from './app/app.module';
  import { environment } from './environments/environment';

  if (environment.production) {
  enableProdMode();
  }

  platformBrowserDynamic().bootstrapModule(AppModule)
  .catch(err => console.error(err));
  ```
* The ` main.ts ` is the main file of angular application which
bootstraps the app. This main file bootstraps application with
default module as below:
```typescript
platformBrowserDynamic().bootstrapModule(AppModule);
```
* As you can see above “AppModule” is the default module which
will be picked up during application bootstrap.
* ` app.module.ts ` file
  ```typescript
  import { BrowserModule } from '@angular/platform-browser';
  import { NgModule } from '@angular/core';
  import { FormsModule } from '@angular/forms';
  import { HttpClientModule } from '@angular/common/http';

  import { AppComponent } from './app.component';
  // Registering persons component in app module.
  import { PersonsComponent } from './persons/persons.component';
  import { PersonInputComponent } from './persons/person-input.component';
  import { AppRoutingModule } from './app-routing.module';

  @NgModule({
  // the selector of persons component will look in all other component in the declarations.
    declarations: [
      AppComponent,
      PersonsComponent,
      PersonInputComponent
    ],
    imports: [
      BrowserModule,
      FormsModule,
      HttpClientModule,
      AppRoutingModule
    ],
    providers: [],
    bootstrap: [AppComponent]
    })
  export class AppModule { }
  ```
* The ` app.module.ts ` is the default module or you can create your
own modules. 

  * The AppModule is Typescript class with special
decorator or annotation @NgModule which tells angular CLI on
how to process this file. So this will be processed as module file
which will contain all of your Components, Services etc.
```typescript
Bootstrap: [AppComponent]
```
* Above property basically tells angular to bootstrap application with
the AppComponent which becomes default component.
* The AppComponent is picked up during application bootstrap
which is basically the default component of angular application.
* Component is basically view which you see in the browser.
* AppComponent is Typescript class with decorator “@Component”
which contain information about view and how to render
component. You can associate component with view using
“templateUrl” property of @Component decorator.

    * ` app.component.ts` file for **_metadata and application logic_**.
      ```typescript
      import { Component } from '@angular/core';

      @Component({
      selector: 'app-root',
      templateUrl: './app.component.html',
      styleUrls: ['./app.component.css']
      })
      export class AppComponent {
      title = 'Angular-Project';
      }
      ```
    * ` app.component.html ` file for **_view_**
      ```typescript
      <router-outlet></router-outlet>
      ```


**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q17">**⬆ Back to Question 17**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

18. ### What is app-root?

* ` app-root ` is selector of app component which is placed as tag in
` index.html `.

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>AngularProject</title>
  <base href="/">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" type="image/x-icon" href="favicon.ico">
</head>
<body>
  <app-root></app-root>
</body>
</html>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q18">**⬆ Back to Question 18**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

19. ### What is Module?

* Angular uses **_module_** to bundle pieces i.e. components to packages. It gives angular information about functionalities i.e. components, pipes that application has.
* We use `@NgModule` to decorate module. We import `@NgModule` from `@angular/core`.
* To register component in module we can use `declarations` property of @NgModule and import it to tell Typescript its location. e.g.
* ```typescript
  @NgModule({
    imports: [
    BrowserModule,
    ],
    declarations: [AppComponent],
    bootstrap: [AppComponent]
    })
  ```
* Imports property is used to import other modules to current module.
* To create module from CLI :
  `ng generate module <name>`

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q19">**⬆ Back to Question 19**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

20. ### How to create component from CLI?

* `ng generate component <componentname>`
* Above command will create folder with `<componentname>` in app folder with ts, html, css, spec file.It will also add it to `declarations` property in `AppModule` and import it to the `AppModule`.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q20">**⬆ Back to Question 20**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

21. ### How to use inline template in component?
* Use **_“template”_** instead of **_“templateUrl”_** in **@Component**
decorator. If you want to write multiline html code then use **`**
backtick with **“template”** property.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q21">**⬆ Back to Question 21**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----


22. ### How to add style to your component in html which will be applicable to that particular component only?

* This can be achieved by using **“styles”** instead of **“styleUrls”** property of @Component decorator, both properties accept array.
e.g.
```typescript
@Component({
Selector: ‘search’,
stylesUrls: [‘./search.component.less’],
..
})
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q22">**⬆ Back to Question 22**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----


23. ### How to use selector as attribute?

* Enclose selector with square braces.
e.g.
```typescript
@Component({
selector: ‘[search]’,
..
})
```
* And then use it as html attribute. 
```html
<div search> </div>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q23">**⬆ Back to Question 23**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----


24. ### How to use selector as class?

* Add dot (.) at the start of selector name.
```typescript
@Component({
selector: ‘.search’,
. .
})
```
* And then use it in html as class.
```html
<div class=”search”> </div>
```

*Note : Using Selector as `id` is not allowed in angular.*

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q24">**⬆ Back to Question 24**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

25. ### How to use selector as element?

* Use selector property of @Component decorator.
e.g.
```typescript
@Component({
selector: ‘search’,
..
})
```
* And then use it as element in html. 
```html
<search></search>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q25">**⬆ Back to Question 25**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

26. ### How to capture data emitted with event in event binding?

* We can capture data emitted with event in event binding using **$event** as method input,
e.g.
```html
<input type=”text” (input)=”onUpdat($event)”></input>
```
* Through $event data will be received in method with data type as “Event”.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q26">**⬆ Back to Question 26**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

27. ### How to access property of child component from parent component?

* For this you can use **custom property binding**. 
* Lets Say `app` *component* is the parent component. and `child-element` *component* is the child component.
* In *app.component.html* file and then in **child-element component tag** use property to be used in square brackets[] as property binding assign value to it.
e.g.

* `app.component.html`
```html
...
<app-child-element [someproperty]=”true”></app-child-element>
...
```
* Then add decorator `@Input` to the child component property in Typescript file, otherwise property will not be accessible to outside components. 
* `child-element.component.ts`
```typescript
import { Input } from '@angular/core';
...
@Input someproperty;
...
```
* @Input is part of angular core. This is how custom property binding is done.

* In this case, we are passing data from parent component to child
component.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q27">**⬆ Back to Question 27**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

28. ### How to pass data from child component to parent component?

* This can be achieved using event binding.
* Lets say `app` *component* is the parent component. and `child-element` *component* is the child component.
* Create properties in `child-element` *component* which is a child component and assign them EventEmitter in the `child-element.component.ts` file.

e.g.
```typescript
import { Component, EventEmitter } from '@angular/core';

@Component({
  selector: 'app-child-element',
  templateUrl: './child-element.component.html'
})
export class ChildElementComponent {
  onUpdate = new EventEmitter<>();
}
```
* Setup what event should emit using methods in child class.

e.g.
```diff
import { Component, EventEmitter } from '@angular/core';

@Component({
  selector: 'app-child-element',
  templateUrl: './child-element.component.html'
})

export class ChildElementComponent {
  onUpdate = new EventEmitter<>();
+  onUpdateMethod() {
+  this.onUpdate.emit({
+    propertyToBeEmitted: this.propertyToBeEmitted
+  });
+  }
}
```
* Add decorator @Output against property in child component.
e.g.
```diff
+ import { Component, EventEmitter, Output } from '@angular/core';

@Component({
  selector: 'app-child-element',
  templateUrl: './child-element.component.html'
})

export class ChildElementComponent {
+  @Output onUpdate = new EventEmitter<>();
  this.onUpdate.emit({
  onUpdateMethod() {
    propertyToBeEmitted: this.propertyToBeEmitted
  });
  }
}
```
* Use this event in parent html ie `app.component.html` with child component tag.
e.g.
```html
<app-child-element (onUpdate)=”onUpdateMethod($event)”></app-child-element>
```
**_Note_** : To use alias with event -
Pass argument to @output as
`@Output(‘someArgument’)`

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q28">**⬆ Back to Question 28**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

29. ### How to perform component communication?

Component communication can be performed through **property binding**, **event binding** and **services dependency injection**.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q29">**⬆ Back to Question 29**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----


30. ### What is view encapsulation and how to disable it?

* Styles in css files written in component are applied to elements of that particular component only not to its child component, this is called view encapsulation.

* View encapsulation can be disabled by adding encapsulation :

  * `ViewEncapsulation.None` in the @Component decorator.
  * This will apply styles of that component to entire application.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q30">**⬆ Back to Question 30**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

31. ### What is use of local reference?

* Local reference passes element with all its properties to method.
e.g.

```html
<input type=”text” #inputLocalReference/>
<button (click)=”onAddServer(inputLocalReference)”></button>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q31">**⬆ Back to Question 31**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
32. ### How to access local reference in Typescript code? 

* Local reference can be accessed in Typescript code by using
@ViewChild decorator.

e.g.
```typescript
  @ViewChild(‘someLocalReference’) someLocalReference;
```
* Here, `someLocalReference` is local reference. This property can
now be used in Typescript code as:
```typescript
var abc = this.someLocalReference.nativeElement.value;
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q32">**⬆ Back to Question 32**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
33. ### What is use of ng-content? 

* By default anything placed inside opening and closing tag of component is last to be displayed. To display such content you should use `<ng-content>`.
* Consider a simple `<component-content>` component:

  * e.g.
  ```html
  <div>
  Hi, This is components html !!!
  <ng-content></ ng-content >
  </div>
  <component-content>
  <div>This text will be displayed inside ng-content</div>
  </component-content>
  ```
* The HTML content passed within the opening and closing tags
of <component-content> component is the content to be projected. This is what we call Content Projection. The content will
be rendered inside the <ng-content>within the component.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q33">**⬆ Back to Question 33**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
34. ### How to create custom directive?

    1. Create transcript class.
    2. Use **@Directive** on class.
    3. Use selector inside *@Directive*, give appropriate name to *selector*.
    4. Implement **onInit** interface.
    5. In **constructor** of class pass **elementRef**.
    6. In `ngOnInit`- change style of elementRef, this can be done in `constructor` as well.

e.g.
```typescript
@Directive({
selector: ‘[appCustomDirectiveExample]’
})

export class CustomDirectiveExample implements OnInit {

  Constructor(private elementRef : ElementRef) {}

  ngOnInit() {
    this.elementRef.nativeElement.style.color = ‘red’;
  }
}
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q34">**⬆ Back to Question 34**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
35. ### How to create structural directive?

    1. Create _directive_ using angular CLI.
    2. Use **@Input** decorator with property, this property will receive value which will be treated as condition.
    3. Pass **templateRef** and **viewContainerRef** to `constructor`.
    4. Use *templateRef* and *viewContainerRef* to modify DOM based on condition.

e.g.
```typescript
@Directive({
selector: '[cpLoop]'
})

export class CpLoopDecorator {

  constructor( private templateRef: TemplateRef<any>, private viewContainer: ViewContainerRef) { }

  @Input('cpLoop') set loop(num: number) {
    for(var i=0; i < num; i++) {
      this.viewContainer.createEmbeddedView(this.templateRef);
    }
  }
}
```

Place *directive selector* on DOM element.

```html
<ul>
<li *cpLoop="5" >
Hello World!
</li>
</ul>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q35">**⬆ Back to Question 35**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
36. ### What is **_Lifecycle Hook_** in angular?

* A component has a lifecycle managed by Angular.
* Angular creates component, renders it, creates and renders its children, checks it when its data-bound properties change, and destroys it before removing it from the DOM.
* Angular supplies lifecycle hooks that provide visibility into these
key life moments and the ability to act when they occur.

`Angular Lifecycle`

<img src="images/lifecycle.png">

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q36">**⬆ Back to Question 36**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
37. ### What is `ngOnChanges()`?

* It is lifecycle hook method. It is executed multiple times. 
* It is executed when component is created. 
* It is also called when one
of the input property changes i.e. properties decorated with
*@Input*.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q37">**⬆ Back to Question 37**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
38. ### What is `ngOnInit()`?

* It is lifecycle hook method which will be executed once component object is created. 
* It is executed after constructor.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q38">**⬆ Back to Question 38**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
39. ### What is `ngDoCheck()`?

* It is lifecycle hook method which will run on every change detection. 
* e. g. any click, any input check.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q39">**⬆ Back to Question 39**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----
 
40. ### What is `ngAfterContentInit()`?

* It is lifecycle hook method which is called after ng-content has
been projected in the view.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q40">**⬆ Back to Question 40**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

41. ### What is `ngAfterContentChecked()`?

* It is lifecycle hook method which is called after Angular checks the
content projected into the component.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q41">**⬆ Back to Question 41**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

42. ### What is `ngAfterViewInit()`? 

* It is lifecycle hook method which is called when components view
has been initialized or rendered.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q42">**⬆ Back to Question 42**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

43. ### What is `ngAfterViewChecked()`?

* It is a likecycle hook method which is called every time Angular has finished running change detection on a component.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q43">**⬆ Back to Question 43**</a>


----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

44. ### What is `ngOnDestroy()`?

* It is lifecycle hook method which is called once component is
about to be destroyed.
* This method is useful for clean-up work, unsubscribing Observables and detaching event handlers to avoid memory
leaks.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q44">**⬆ Back to Question 44**</a>


----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

45. ### What are **_services_** generally?

* Services are basically used to reduce duplication of code. 
* E.g. for logging you can create service and use it everywhere. 
* Services are used for component communication.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q45">**⬆ Back to Question 45**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

46. ### How to create services and injecting into component typescript class in angular (Steps)?

`Creating Service Manually`
* Create **`<ServiceName>.service.ts`** file say as **`persons.service.ts`** and we will implement our common functionality/application logic.

or

`Creating Service Using Angular CLI`
* `ng generate service <ServiceName>` (or) `ng g service <ServiceName>`
* Say `ng gererate service persons` : this will create a service with name **`persons.service.ts`**

`Implementing Application in Service`

In **persons.service.ts** class.
```typescript
import { Injectable } from '@angular/core';
import { Subject } from 'rxjs';
import { HttpClient } from '@angular/common/http';
import { map } from 'rxjs/operators';

@Injectable({ providedIn: 'root' })
export class PersonsService {
  personChanged = new Subject<string[]>();
  persons: string[] = [];
  // persons: string[] = ['Sandeep', 'Ajay', 'Bhavuk'];

  constructor(private http: HttpClient) { }

  fetchPerson() {
    this.http.get<any>('https://swapi.dev/api/people/').pipe(map(resData => {
      return resData.results.map(character => character.name);
    })).subscribe(TransformedData => {
      console.log(TransformedData);
      this.personChanged.next(TransformedData);
      // this.persons.push(TransformedData);
    });
  }

  addPerson(name: string) {
    this.persons.push(name); // item is push into array but still not updated to the DOM because of angular behavior.
    this.personChanged.next(this.persons); // Here we updating fresh persons array using the object of Subject.
    console.log(this.persons);
  }

  removePerson(name: string) {
    this.persons = this.persons.filter((person, personIndex, personArray) => {
      console.log(person);
      console.log(personIndex);
      console.log(personArray);
      return person !== name;
    });
    console.log(this.persons);
    this.personChanged.next(this.persons);
  }

  // We need to subscribe this event 'personChanged' in other parts of the app.
}
```
_Note :_
    
  1. The @Injectable() decorator marks it as a service that can be injected, root injector which will make our service an application wide singleton.
  2. But Angular can't actually inject it anywhere until you configure an Angular dependency injector with a provider of that service.


`Injecting Service into another typescript class using Dependency Injection`

* Dependency injection (DI), is major application design pattern.
* Angular has its own DI framework that is typically used in the
design of Angular applications to increase their efficiency and
modularity. 
* The DI framework lets you supply data to a component from an injectable service class, defined in its own file.
* Use constructor dependency injection in the class where we want to use this service.

e.g.
```typescript
import { Component, Output, EventEmitter } from '@angular/core';
import { PersonsService } from './persons.service';

@Component({
  selector: 'app-person-input',
  templateUrl: './person-input.component.html',
  styleUrls: ['./person-input.component.css']
})
export class PersonInputComponent {
  // creating object based on this EventEmitter Class, plus this object is also a property of this class 'PersonInputComponent'
  // @Output() personCreate = new EventEmitter<string>();
  enteredPersonName = '';

  constructor(private personService: PersonsService) {

  }

  onCreatePerson() {
    this.personService.addPerson(this.enteredPersonName);
    this.enteredPersonName = '';
  }
}
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q46">**⬆ Back to Question 46**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

47. ### What is hierarchical dependency injection in angular?

* The Angular dependency injection system is hierarchical. 
* There is a tree of injectors that is analogues to an app's component tree.
* You can reconfigure the injectors at any level in that component tree.
---
* If service is provided using providers array to AppModule then service is available application wide, which means it is available to all component, services and directives. 
* Similarly When you
use *providedIn:'root'* of *@Injectable() decorator*, you are configuring the root injector for the app, which is the injector for AppModule due to which service is available application wide.
---
* If service is injected into any component then it will be available to
its child component and to that particular component. 
* You can limit the scope of a provider to a component and its children by
configuring the provider at the component level using the @Component metadata.
* You can configure a provider at the module level using the providedIn metadata option for a non-root NgModule, in order to limit the scope of the provider to that module. 
* This is the equivalent of specifying the non-root module in the @Injectable() metadata. You generally don't need to
specify AppModule with providedIn, because the app's root injector is the AppModule injector. However, if you
configure a app-wide provider in the@NgModule() metadata for AppModule, it overrides one configured for root in
the @Injectable()metadata.
---
* If service is provided in AppModule and AppComponent as well
as particular component nearest dependency injection will
override other dependency injections.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q47">**⬆ Back to Question 47**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

48. ### What is Routing?

* When url changes, based on url major part of DOM also changes. This is called routing.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q48">**⬆ Back to Question 48**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

49. ### How to setup routes?

* Add constant array of type Routes in AppModule, add routes to it as Javascript object.

e.g. 
`In typescript file`
```typescript
const routes_config : Routes = [
  { 
    path: ‘roles’, 
    component: RoleComponent
  },
  { 
    path: ‘home’, 
    component: HomeComponent 
  }
]
```
* Add RouterModule to imports property of @NgModule as,
```typescript
Imports: [ RouterModule.forRoot(routes_config);]
```
* Pass routes_config array to forRoot method of RouterModule.
* Use directive `<router-outlet>` in app.component.html where you want to render the component based on route.

e.g.
```html
<router-outlet></router-outlet>
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q49">**⬆ Back to Question 49**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

50. ### Which directive should be used for changing route?

* **_`routerLink`_** should be used for changing route.

e.g. *In .html file*
```html
<a routerLink='roles'></a>
<a [routerLink]="['users', 'something']" ></a>
```
* **_Note :_** *routerLink* will not reload page unlike href and also state of
application will persist.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q50">**⬆ Back to Question 50**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

 ### <span id="N51">51.</span> What is difference between ‘/somepath’ and ‘somepath’?

* If ‘/somepath’ is used with routerLink it will be absolute path
whereas ‘somepath’ will be relative path.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q51">**⬆ Back to Question 51**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

52. ### How to make selected element active based on selected route?

* routerLinkActive is used for this purpose.
```html
<li routerLinkActive = “active”>
  <a routerLink=’/users’></a>
</li>
```
`[routerLinkActiveOptions]=”{exact: true}”`
* routerLinkActiveOptions can be used with routerLinkActive can be
used with routerLinkActive for exact match of path, this is required
as ‘/’ is part of all routes.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q52">**⬆ Back to Question 52**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

53. ### How to programmatically trigger route?

* Using navigate method of Router.
* First Inject router in constructor and then use navigate method of router.

e.g.
```typescript
this.router.navigate([‘somepath’]);
```
* To make this route relative you can use relativeTo property.

e.g.
```typescript
this.router.navigate([‘servers’], {relativeTo: this.route});
```
**_Note :_** To get currently active route use active route service. 

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q53">**⬆ Back to Question 53**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

54. ### How to pass parameters to route?

* By using colon ‘:’ in route path.

e.g.
```typescript
{ 
  path : ‘user/:id’, 
  component : UserComponent
}
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q54">**⬆ Back to Question 54**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

55. ### How to fetch parameters in Route?

* In Typescript file inject ActivedRoute in constructor.
* Access params from activatedRoute.

e.g.
```typescript
this.activatedRoute.snapshot.params[‘id’];
```
* **‘id’** must be specified as dynamic param in route in AppModule.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q55">**⬆ Back to Question 55**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

56. ### How to add query params to url?

* In `<a>` anchor tag use `[queryparam]` property of routerLink as property binding.

e.g.
```html
<a 
  [routerLink]="[‘/somepath,5,'update']"
  [queryParams]="{allowUpdate: ‘/’}"
  [fragment]="loading"]>
</a>
```
* In Above case url will look like

`localhost:4200/somepath/5/update/allowUpdate=1#loading`

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q56">**⬆ Back to Question 56**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

57. ### How to add query params programmatically?

* By using navigate method of Router.

e.g.
```typescript
this.router.navigate(
  [‘/somepath’, id, ‘update’],
  {queryParams: {allowUpdate:’1’},
  fragment: ‘loading’}
  );
```
* In above case url will be

`localhost:4200:/somepath/1/update?allowUpdate=1#loading`

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q57">**⬆ Back to Question 57**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

58. ### How to retrieve query param and fragment from url?

* By using queryParam and fragment from snapshot property of `ActivatedRoute`.

e.g.
```typescript
this.activatedRoute.snapshot.queryParams
this. activatedRoute.snapshot.fragment
```
* By subscribing to queryParam and fragment of activated route.

e.g.
```typescript
this.activatedRoute.queryParams.subscribe();
this.activatedRoute.fragment.subscribe();
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q58">**⬆ Back to Question 58**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

59. ### How to add child routes?

* By using **‘children’** property of `Routes`.

e.g.
```typescript
const appRoutes : Routes = [
  { 
    path : 'users',
    component: UserComponent,
    children: [
    {
    path:'id',
    component: UserComponent 
    },
    {
    path:'id/update',
    component:UpdateUserComponent
    }]
  }
]
```
* After children routes are added; add `<router-outlet>` in parent
component html file. In this `<router-outlet>` child’s will be loaded.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q59">**⬆ Back to Question 59**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

60. ### What is use of Wildcard routes?

* Wild card route is basically used to handle all routes which are not present in `Routes` array, it should be at the bottom of *Routes* array.

e.g.
```typescript
{
  path: 'error',
  component:ErrorPageComponent
},
{
  path:'**', 
  redirectTo:'/error'
}
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q60">**⬆ Back to Question 60**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

61. ### How to apply guard to route?

* By using **‘canActivate’** property in `routes`.

e.g.
```typescript
{
  path: ‘users’,
  canActivate:[RoleGuard],
  component: UserComponent
}
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q61">**⬆ Back to Question 61**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

62. ### How to create guard?

* Create service with particular guard name.e.g. RoleGuard.
* Implement `CanActivate` interface in this service.
* Implement **canActivate** method. This method will **return `Observable<boolean>` or `Promise<boolean>` or `Boolean`**.
* In *canActivate* method write business logic which will confirm if
route should be accessed or not.
```typescript
canActivate(
  route:ActivatedRouteSnapshot,
  state:RouterStateSnapshot) : Observable<boolean>|Promise<boolean>|boolean
  {
    return true;
  }
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q62">**⬆ Back to Question 62**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

63. ### How to create guard from CLI?

* Below is command to create a new, generic route guard definition
in the given or default project:

`ng generate guard <name> [options]`

or

`ng g guard <name> [options]`

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q63">**⬆ Back to Question 63**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

64. ### How to guard child routes?

* Add **‘canActivateChild’** property in `route` instead of *‘canActivate’*.
* Implement *canActivateChild* interface in guard.
* Implement *canActivateChild* method, it has same return type as **canActivate**.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q64">**⬆ Back to Question 64**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

65. ### What is HttpClient?

* The majority of the front-end applications communicate with
backend services over the HTTP protocol. 
* **HttpClient** in `@angular/common/http` is used to send HTTP requests or make API calls to RESTful endpoints of remote servers in order to fetch data.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q65">**⬆ Back to Question 65**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

66. ### Which module is required for HttpClient?

* `**HttpClientModule**` is required to be imported in AppModule before
using HttpClient.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q66">**⬆ Back to Question 66**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

67. ### How to make get request using HttpClient?

* import **HttpClientModule** into the `AppModule`.
* Inject the **HttpClient** into constructor of service where you want to
use it.

e.g.
```typescript
constructor(private httpClient: HttpClient) { }
```
* Write a method in service and in this method, use get() method of
HttpClient and subscribe to it.

e.g.
```typescript
getSomeData() {
  this.httpClient.get(‘http://localhost:4200/getService’);
  }
```
* Call service method in component where data is needed to be displayed and subscribe to it.
```typescript
showSomeData() {
  this.someDataService.getSomeData()
  .subscribe((data: SomeData) => this.componentData = {
    name: data['name'],
    address: data['address']
  });
}
```
* subscription callback copies the data fields into the component's object, which is data-bound in the component template for display.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q67">**⬆ Back to Question 67**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

68. ### How to pass headers to http request?

* Create header object

e.g.
```typescript
const httpOptions = {
  headers: new HttpHeaders(
    {
      'Content-Type': 'application/json',
      'Authorization': 'my-auth-token'
    }
  )
};
```
* Add this headers to http request.

e.g.
```typescript
this.http.post(‘http://localhost’, data, {headers: headersObj });
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q68">**⬆ Back to Question 68**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

69. ### How to make post request using HttpClient?

* import **HttpClientModule** into the `AppModule`.
* Inject the **HttpClient** into `constructor` of service where you want to
use it.

e.g.
```typescript
constructor(private httpClient: HttpClient) { }
```
* Create Header Options
e.g.
```typescript
const httpOptions = {
  headers: new HttpHeaders(
    {
      'Content-Type': 'application/json',
      'Authorization': 'my-auth-token'
    }
  )
};
```
* Write a method in service and in this method use `post()` method of
**HttpClient** passing url, data and http options to it, then you take
the *Observables* returned by the *HttpClient* methods and passes
observable to the pipe for error handling.

e.g.
```typescript
addSomeData(data: SomeData): Observable<SomeData > {
  this.httpClient.post(
    ‘http://localhost:4200/getService’,
    data, 
    httpOptions
    ).pipe(
          catchError(this.handleError);
          );
}
```
* The Component initiates the actual POST operation by subscribing to the *Observable* returned by this service method.

e.g.
```typescript
this.someDataService.addSomeData(newData).subscribe(data => this.dataArray.push(data));
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q69">**⬆ Back to Question 69**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

70. ### How to make put request using HttpClient?

* Create service.
* Inject http service into constructor of service

e.g.
```typescript
constructor(private http : Http){}
```
* Make http request using post method of http.

e.g.
```typescript
putMethod(users: User) {
  this.http.post(‘http://localhost:8080’, users);
}
```
* `Put` method output is observable.
* Create subscriber to this observable, else http request will not be sent.

e.g.
```typescript
this.putMethodService.putMethod(users).subscribe((responce) => 
console.log(responce)
);
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q70">**⬆ Back to Question 70**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

71. ### How to catch error of http request?

* You could handle in the component by adding a second callback to the `.subscribe()`:

e.g.
```typescript
showConfig() {
  this.configService.getConfig()
  .subscribe(
    (data: Config) => this.config = 
    {...data}, // success path
    error => this.error = error // error path
  );
}
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q71">**⬆ Back to Question 71**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

72. ### Which module is required for httpService?

* `HttpModule` is required to be imported in app module.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q72">**⬆ Back to Question 72**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

73. ### How to make get request using alternative Http Service instead of HttpClient?

* Create service.
* Inject http service into constructor of service

e.g.
```typescript
constructor(private http : Http){}
```
* Make http request using get method of http.

e.g.
```typescript
getMethod() {
  this.http.get(‘http://localhost:4200/getService’);
}
```
* Get method output is observable.
* Create subscriber to this observable,else http request will not be sent.

e.g.
```typescript
this.http. getMethod().subscribe((responce)=>{
console.log(response.json());
},(error)=>console.log(error));
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q73">**⬆ Back to Question 73**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

74. ### What is Observable?

* Observable is basically datasource. 
* In angular we import observable from third party package like **_‘rxjs’_**. 
* It is used to handle asynchronous tasks * e.g. observable is used with http service.
* *Observable* also has **‘observer’** which is implemented using subscribe method. *Observer* handles data in three ways : 

  * Handle normal data, 
  * handle error, 
  * handle completion. 

* In the handling method you can perform your actions.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q74">**⬆ Back to Question 74**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

75. ### What is use of map() operator in observable?

* `map()` operator is basically used to transform response data.

e.g.
```typescript
this.http.get(‘http://localhost:4200/myservice’).map(
(response : Responce) => {
const formattedData = response.json();
return formattedData;
}
);
```
* *map* is useful because it returns transformed observable to all
observers and hence uniformity to all observers receiving data.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q75">**⬆ Back to Question 75**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

76. ### How to send post request in angular using alternative Http Service instead of HttpClient?

* Create service.
* Inject http service into constructor of service

e.g.
```typescript
constructor(private http : Http){}
```
* Make *http* request using post method of http.

e.g.
```typescript
postMethod(users: User) {
  this.http.post(‘http://localhost:8080’, users);
}
```
* Post method output is observable.
* Create subscriber to this observable, else http request will not be sent.

e.g.
```typescript
this.postMethodService.postMethod(users).subscribe((responce) => console.log(responce));
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q76">**⬆ Back to Question 76**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

77. ### What are pipes?

* A pipe takes in data as input and transforms it to a desired
output.
* To create pipe from CLI :

  * `ng generate pipe <name> [options]`
  
  or

  * `ng g pipe <name> [options]`

* To use pipe :

  * Pipe is used with string to be transformed after pipe char.

  e.g.
  ```html  
  <p>The hero's birthday is {{ birthday | date }}</p>
  ```
  * Inside the interpolation expression, you flow the component's birthday value through the **pipe operator ( | )** to the Date pipe function on the right. All pipes work this way.

* To add parameters to a date pipe : 

  * A pipe can accept any number of optional parameters to finetune its output. 
  * To add parameters to a pipe, follow the pipe name with a colon ( : ) and then the parameter value (such as date:"MM/dd/yy").

  e.g.
  ```html
  <p>The hero's birthday is {{ birthday | date:"MM/dd/yy" }} </p>
  ```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q77">**⬆ Back to Question 77**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

78. ### What are different built in pipes?

* currency, 
* date, 
* decimal, 
* json, 
* lowercase, 
* uppercase, 
* percent,
* slice 

are few of the built in pipes.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q78">**⬆ Back to Question 78**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

79. ### How to chain pipes?

* *Pipes* can be chained by repeatedly using pipes.

e.g.
```html
<p>The chained hero's birthday is {{ birthday | date | uppercase}}<p>
```
* **_Note :_** Pipes are applied left to right.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q79">**⬆ Back to Question 79**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

80. ### How to create custom pipe?

* Create class and implement `PipeTransform` interface which will force you to use transform method.
* In **transform** method write transformation logic and return
transformed data.
* Use **@Pipe** decorator on this class and give name to the pipe using name property of *@Pipe*.

e.g.
```typescript
@Pipe({name: 'exponentialStrength'})
export class ExponentialStrengthPipe implements PipeTransform {
  transform(value: number, exponent: string): number
  {
    let expnt = parseFloat(exponent);
    return Math.pow(value, isNaN(expnt) ? 1 : expnt);
  }
}
```
* Use this pipe in template as, 

```html
<p>Super power boost: {{2 |  exponentialStrength: 10}}</p>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q80">**⬆ Back to Question 80**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

81. ### How to pass parameters to custom pipe?

* Add argument to transform method.
```typescript
transform(value: number, exponent: string)
```
* In template pass parameter to pipe using colon **“:”**.
```html
<p>Super power boost: {{2 |  exponentialStrength: 10}}</p>
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q81">**⬆ Back to Question 81**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

82. ### What is pure pipe and impure pipe?

* By default pipes are pure.
* There are two categories of pipes: pure and impure. 

  * Pure pipe: Angular executes a pure pipe only time when it detects a pure change to the input value.
  * Impure pipe: An impure pipe is executed during every component change detection cycle. An impure pipe is called often, as frequently as every keystroke or mouse-move. You make a pipe impure by setting its pure flag to false.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q82">**⬆ Back to Question 82**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

83. ### What are approaches to handle form?

* Angular provides two different approaches to handling user input
through forms: **template-driven** and **reactive**. 
* Both approaches capture users input events from the view, validate the user input, generate a form model and data model to update, and provide a way to track changes.
  
  * **Reactive forms** are more robust: they're more scalable, testable and reusable. If forms are a crucial part of your application, or you're already using reactive patterns for building your application, use reactive forms.
  * **Template-driven forms** are helpful for adding a simple form to an app, such as an email list signup form. They're easy to add to an app, but they don't scale as well as reactive forms. If you have very basic form requirements and logic that can be managed solely in the template, use template-driven forms.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q83">**⬆ Back to Question 83**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

84. ### Which module is required for form?

* **_`FormModule`_**

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q84">**⬆ Back to Question 84**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

85. ### How to access form input controls in Typescript class?

* On form tag create **ngSubmit** event and write method against it.
* Create local reference to form element and assign it values of form using ngForm and pass it to submit method.

e.g.
```html
<form (ngSubmit)=”onSubmit(f)” #f=”ngForm”>
```
* Now if we submit form, form values will be available to onSubmit() method. 
* All values will be available in “value” property of **“ngForm”**.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q85">**⬆ Back to Question 85**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

86. ### What are the important properties of ngForm?

* In Angular, the following statuses are often used by forms:
  * **valid** – state of the validity of all form controls, true if all controls are valid
  * **invalid** – inverse of valid; true if some form control is invalid
  * **pristine** – gives a status about the “cleanness” of the form; true if no form control was modified
  * **dirty** – inverse of pristine; true if some control was modified
  * **disabled** - Reports whether the control is disabled.
  * **enabled** - Reports whether the control is enabled.
  * **touched** - Reports whether the control is touched, meaning that the user has triggered a blur event on it.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q86">**⬆ Back to Question 86**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

87. ### How to access form without submit?

* This can be done by using **ViewChild** decorator and using *localReference* of form argument to it.

e.g.
```typescript
@ViewChild(‘someLocalReference’) anyForm : NgForm;
```
* Then access it in required method.

e.g.
```typescript
this.anyForm;
```

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q87">**⬆ Back to Question 87**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

88. ### Why form validation is required?

* To improve overall data quality by validating user input for accuracy and completeness.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q88">**⬆ Back to Question 88**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

89. ### What are different types of validator functions?

* There are two types of validator functions: sync validators and
async validators.

  * **Sync validators**: functions that take a control instance and immediately return either a set of validation errors or null. You can pass these in as the second argument when you instantiate a *FormControl*.
  * **Async validators**: functions that take a control instance as well as return a Promise or Observable that later emits a set of validation errors or null. You can pass these in as the third argument when you instantiate a *FormControl*.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q89">**⬆ Back to Question 89**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

90. ### What are different built-in validators?

* **min :** Validator that requires the control's value to be greater than
or equal to the provided number.
* **max :** Validator that requires the control's value to be less than or
equal to the provided number.
* **required :** Validator that requires the control have a non-empty value.
* **email :** Validator that requires the control's value pass an email validation test.
* **minLength :** Validator that requires the length of the control's value to be greater than or equal to the provided minimum length.
* **maxLength :** Validator that requires the length of the control's value to be less than or equal to the provided maximum length.
* **pattern :** Validator that requires the control's value to match a regex pattern.

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q90">**⬆ Back to Question 90**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

91. ### How to add validation messages for input controls in form?

* Use span which will display error message along with input control.

e.g.
```html
<input name=”email” required email #email=”ngModel”/>
<span *ngIf=”!email.valid && email.touched”>Please enter valid
email ID!!!</span>
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q91">**⬆ Back to Question 91**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

92. ### What is animation in angular?

* **Animation** provides the illusion of motion: HTML elements change styling over time. 
* Well-designed animations can make your application more fun and easier to use.
* `@angular/animations` is the angular package which is required to be installed for animation.
* You can install it from angular CLI using command npm install

`@angular/animations@latest --save`

**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q92">**⬆ Back to Question 92**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

93. ### How to use animation in angular?

* If you plan to use specific animation functions in component files,
*import* those functions using **@angular/animations**.
* In the component file, add a metadata property called *animations*: within the *@Component()* decorator. You put
the trigger which defines an animation within the animations metadata property.
* Use the **style()** function to define a set of styles to associate with Angular's state() function to define different states to call at the end of each transition.

e.g.
```typescript
state('open', style({
height: '200px',
opacity: 1,
backgroundColor: 'yellow'
})),
state('closed', style({
height: '100px',
opacity: 0.5,
backgroundColor: 'green'
})),
```
* Then, use the **transition()** function which accepts two arguments:

  * the first argument accepts an expression that specifies the direction between two transition states, and 
  * the second argument accepts an animate() function.
* The animate() function (second argument of the transition function) accepts the timings and styles as input parameters.

e.g.
```typescript
transition('open => closed', [ animate('1s') ]),
```
* Above example provides a state transition from open to closed having a one second transition between states.
* An animation needs a trigger, so that it knows when to start.
* The **trigger()** function collects the states and transitions, and gives the animation a name, so that you can bind it to the triggering element in the HTML template.

e.g.
```typescript
@Component({
selector: 'app-open-close',
animations: [
trigger('openClose', [
// ...
state('open', style({
height: '200px',
opacity: 1,
backgroundColor: 'yellow'
})),
state('closed', style({
height: '100px',
opacity: 0.5,
backgroundColor: 'green'
})),
transition('open => closed', [
animate('1s')
]),
transition('closed => open', [
animate('0.5s')
]),
]),
],
templateUrl: 'open-close.component.html',
styleUrls: ['open-close.component.css']
})
export class OpenCloseComponent {
  isOpen = true;
  toggle() {
    this.isOpen = !this.isOpen;
    }
}
```
* The following code snippet binds the trigger to the value of the isOpen property.
```html
<div [@openClose]="isOpen ? 'open' : 'closed'" class="openclose-container">
<p>The box is now {{ isOpen ? 'Open' : 'Closed' }}!</p> 
</div>
```
**[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q93">**⬆ Back to Question 93**</a>

