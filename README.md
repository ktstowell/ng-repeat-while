ng-repeat-while
===============

ngRepeat that runs off of an expression evaluation instead of size/contents of a data structure.

Installation
============

bower install ng-repeat-while

Usage
=====
It will simply run as long as the provided expression evaluates to truthiness.
Exposes and $index scope variable, just like normal ng-repeat.

<p ng-repeat-while="$index < $scope.foo">Repeated: {{$index+1}} times!</p>

Demo
====
http://ktstowell.github.io/ng-repeat-while/#/