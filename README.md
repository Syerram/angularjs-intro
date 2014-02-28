# Angurlajs

# EmberJS

* toolbox of concepts & well suited for large framework
* uses handlebars to mesh with Ember code
* Can recompile on the server
* need to get concepts conceptualized before writing code
  * for e.g. to create models, you have extend Ember model [very similar to Backbone]

```javascript
Discourse.Post = Ember.Object.extend({
  liked: false
});

var post = Discourse.Post.create();
```


# AngularJS
* Has no learning curve. no concepts just straight up coding
* gets messy at the end due to no standards
* relies heavily on dirty checking
* Follows MVC pattern
* up and running in no time


# Example
* http://todomvc.com/


# Binding

* Two way binding
* Dirty checking
* Controllers
* Models
* Scope
* Services
  * Backend 
* Directives


# Tips

* Use angular-seed projects to start a project
* Use ng-bind instead of {{}}. Otherwise when the HTML loads you might see {{}} spread out
* Use encapsulation. You will avoid scope headaches.
* Put all server side access in Services
* If you see repeating code, then move code to Services/Filter/Directives or even rootScope
* Use event broadcasting to avoid coupling
* Avoid at all costs doing html inside controllers, services. Do it in directives/filters 