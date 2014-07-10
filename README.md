AngularRESTExamples
===================

AngularJS &amp; REST best practices


#NOTES
##AngularJS Data Modeling
###AngularJS - Using $resource for Data Models  5:29

- AngularJS's $resource service allows you to create convenience methods for dealing with typical RESTful APIs.
- build POST provider use param to grab api
- pass in POST model to add Post to the down
- Posts will query the DOM
- scope for save for text
- delete same as save, remove delete with lodash
- $resource is lacking in creating business logic
- create an orm


###Create a Model Base Class

- write a basic factory
- inject thru a spec helper
- write a test on inheritance, test adding functionality
- test that it adds mehtods to the child class
- add functionality to the base class

###Model Caching

- 

#RESOURCES
[**AngularJS Data Modeling** *source egghead.io*] (https://egghead.io/series/angularjs-data-modeling)
[**Tutorial: Angular + REST Made Simple** *source dreamfactory*] (http://blog.dreamfactory.com/tutorial-angular-and-rest-made-simple)


li ng-class="active:tab === 1"
a ng-click="panel.selectTab()"