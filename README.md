![The javascript web components](https://bossanova.uk/templates/jtools/img/logo.png)

## jTools - The definitive common javascript web components

About
---------
jTools is a collection of lightweight common required javascript web components. It is composed of fully responsive javascript vanilla plugins to help you bring the best user experience to your projects, independent of the platform.</p>

The first version includes several common javascript tools in various frontend applications. jTools is fully and easily integrated with any framework and tools. The first collection brings the following plugins:

* Nice clean and responsive calendar/time picker. This is integrated with jExcel and bring flexibility and responsiveness to your apps and web-based systems;
* Our multi-purpose dropdown aims to give the user the best experience picking one or more options from a list. With a simple directive, you can render that in different modes, such as select box, search bar, mobile picker or a simple list.
* The form tracker will give the chance to track changes from basic to highly dynamic forms in order to remember the user to save their form changes before leaving the page. This is basically the "Are you sure"? javascript plugin.
* A simple color picker
* A very straight forward responsive image thumb view
* A great responsive data timeline
* A simple modal, input mask javascript, mini HTMLeditor and some mobile common web components

Highlights
---------
jTools brings the developer many advantages, such as:

* Make rich and user-friendly web interfaces and applications
* You can easily handle complicated data inputs in a way users are used to
* Improve your clients software experience
* Create rich CRUDS and beautiful UI
* Lean, fast and simple to use
* One code, multiple platform


### Basic demo

Create a multiple and autocomplete responsive dropdown.


```html
<html>
<script src="https://bossanova.uk/jtools/v2/japp.js"></script>
<link rel="stylesheet" href="https://bossanova.uk/jtools/v2/japp.css" type="text/css" />

<div id="dropdown1"></div>

<script>
jApp.dropdown(document.getElementById('dropdown1'), {
    data:[
        'City of London',
        'City of Westminster',
        'Kensington and Chelsea',
        'Hammersmith and Fulham', // (...)
        ],
    autocomplete:true,
    multiple:true,
    width:'280px',
});
</script>
</html>
```
The same code can render in differnet ways\
![Automatically Responsive](https://bossanova.uk/templates/jtools/img/dropdown.png)


Examples
---------

* [Dropdown and autocomplete component](https://bossanova.uk/jtools/dropdown-and-autocomplete)\
Full examples on how to handle simple, advanced, autocomplete and conditional dropdowns.

* [Date and datetime picker](https://bossanova.uk/jtools/date-and-datetime-picker)\
A very simple date and datetime picker full responsive and easy integration

* [Javascript string and number mask](https://bossanova.uk/jtools/date-and-datetime-picker)\
A simple javascript mask plugin

* [Javascript color picker plugin](https://bossanova.uk/jtools/javascript-mask)\
Vanilla javascript colorpicker plugin

* [Javascript contextmenu plugin](https://bossanova.uk/jtools/contextmenu)\
Vanilla javascript contextmenu plugin

* [Javascript image slider plugin](https://bossanova.uk/jtools/image-slider)\
Simple vanilla javascript image slider plugin

* [Javascript mini HTML editor plugin with filter](https://bossanova.uk/jtools/text-editor)\
Simple vanilla javascript image slider plugin

* [Tracking the form changes](https://bossanova.uk/jtools/tracking-for-form-changes)\
Alert the user for unsaved changes in a form before leave any page plugin.

* [Javascript modal plugin](https://bossanova.uk/jtools/modal)\
Simple vanilla javascript modal plugin


## Official website
- [Jtools Official](https://bossanova.uk/jtools)

## Community
- [GitHub](https://github.com/paulhodel/jtools/issues)

## Copyright and license
jTools is released under the [MIT license]. Copyrights belong to Paul Hodel <paul.hodel@gmail.com>

## Other resources

- [jExcel Official](https://bossanova.uk/jexcel)
- [jExcel Pro Official](https://jexcel.net/v3)
- [Banda Base](https://base.mus.br)
