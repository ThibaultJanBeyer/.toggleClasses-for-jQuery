# .toggleClasses()

 	* 100% free with MIT License (MIT)

This adds the missing .toggleClasses() to jQuery. With toggleClasses you can toggle several classes.

Install
---------------

toggleClass extends jQuery to provide the new method so it is is jQuery dependant. Add jQuery first, then toggleClasses.js to your document after jQuery with this line of code:

```html
<script src="http://thibaultjanbeyer.github.io/.toggleClasses-for-jQuery/toggleClasses.min.js"></script>
```

That's it! Nor you can use .toggleClasses() on any element! Here is an example:

```js
$('myElement').toggleClasses(['myClass1', 'myClass2', 'myClass3']);
```

Here the toggling would look like this: *myClass1 -> myClass2 -> myClass3 -> myClass1 -> etc.* 

Info
---------------------

**.toggleClass( [ classNames ], toggleZero )**

Value		  | Description
------------- | -------------
className	  | Type: String – One or more class names to be toggled through one after another.
toggleZero	  | Type: Boolean – A Boolean value to decide whether the toggling cycle should include a state without any of the classNames.

Example:

```js
$('myElement').toggleClasses(['myClass1', 'myClass2', 'myClass3'], true);
```
 
Here the toggling would look like this: *myClass1 -> myClass2 -> myClass3 -> _____ -> myClass1 -> etc.*  

As "toggleZero" is set to "true" it toggles one more time with no value

------------------
Have Fun !

[![Typewriter Gif](https://thibaultjanbeyer.github.io/DragSelect/typewriter.gif)](http://thibaultjanbeyer.com/)
