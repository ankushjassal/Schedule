### Q1 To run MarcoPoco program. Open any editor like notepad++, dreamweaver or any other editor -> run program -> on browser open console to check result. 

### Q2 difference between imports, declarations, and providers?

##### imports:- It defines exported modules or default modules like BrowserModule, FormsModule or any other external plugins like bootstrap 3/4.

##### declarations:- It defines components which we are using in our project like appComponent (parent component), directives, pipe and other components which are use in project.

##### providers:- In this we can specify the services that we create which is going to use in single or multiple components as a dependency.

### components, directives, models, modules, and services?

##### components:- it defines class that interact with html files of the component to display on browser. In this you can define 'selector', 'template/templateUrl', 'style/styleUrl' and class to implement any hooks or create functions and events.

##### directives:- If you want to add any external html or css to add any other component you can create directive for this. @Directive is use to create directive. There are many inbuilt directive like *ngIf, *ngSwitch, *ngFor etc.

##### models:- It is basically use for data binding between controller and view and for validations. NgModel directive is use for two way data binding.

##### modules:- Whatever you creating, importing either its buitin component, external component created, services or any other external plugin you install. All these define under "@NgModule".

##### services:- If you want to use same functionality in one or more components than you can create services for this. "@Injectable" directive is use to create service and  to use it you can add in any component user @Component -> providers: [serviceName]. Or you can import service component on top of page then use service in constructor to access any function.
