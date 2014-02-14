# Wellington Start-up Weekend 2014 - Angular Bootcamp

This repo contains two sample apps to provide an overview of Angular

## Links

* Angular blog http://blog.angularjs.org/ - good for news etc.
* Angular modules directory http://ngmodules.org/
* [Setting up a fresh angular install with Yeoman](http://www.sitepoint.com/kickstart-your-angularjs-development-with-yeoman-grunt-and-bower/)
* [Restangular](http://ngmodules.org/modules/restangular) - an improved version of
  the built-in $resource
* [Angular UI](https://github.com/angular-ui/ui-router) is recommended if you
  application has anything other than very basic routing needs
* Angular and Rails: [angular-js-rails-resource](http://ngmodules.org/modules/angularjs-rails-resource)
 recommended if you are using rails
* [Conceptual overview of Angular for Jquery folks](http://stackoverflow.com/questions/14994391/how-do-i-think-in-angularjs-if-i-have-a-jquery-background)

## Notes

### Organising code
### DOM

* If you are touching the DOM, always use a directive - [directive docs](http://docs.angularjs.org/guide/directive), [Simple Diretive](http://jsfiddle.net/A8Vgk/7/), [Directive tutorial](http://www.befundoo.com/university/tutorials/angularjs-directives-tutorial/)
* You can get by without understanding the scope digest cycle initially but eventually it will bite you [Simple Overview](http://onehungrymind.com/notes-on-angularjs-scope-life-cycle/) [Complex Overview](https://github.com/angular/angular.js/wiki/Understanding-Scopes)
* always use [angular.element](http://docs.angularjs.org/api/angular.element) to access the DOM
* Gotchya: [ng-include expects an expression, strings must be explicit](http://stackoverflow.com/questions/12521905/angularjs-ng-include-does-not-include-view-unless-passed-in-scope)

### Servers
### Auth
### Routing


