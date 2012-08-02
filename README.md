another
=======

Another - is a javascript framework, based on Backbone with full integration with Ruby on Rails, first of all ORM and ODM.

===

Main ideas behind this framework:

* SEO compatipable using #! and pushState (hash change should work on both: old and modern browsers)
* Form data binding to the model (resource) to be able to send files (should work as iframe send of the form on old browsers, and on the modern browsers FormData object should be used while XHR sends data)
* ActiveRecord and Mongoid support
* Validation errors parsing
* Nested attributes using both possibilities:
** Embedded has many and has one
** Associated outside models
* Form builder with ability to automatic assign values to inputs and get nested associated models and build fields from them (formFor and fieldsFor)


Made of
=======

* backbone
* jquery.form
* ...

Influence by
============

* Joosy
* Batman.js
* Bootstrap.js