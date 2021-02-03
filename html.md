# html

### elemtnts

```html
<div> <!-- opeening tag -->
    I am some text 
</div> <!--closing tag--> 

<img /> <!-- img is a self-clsing element-->
```

**some common eleements:**
- '<div>': empty box with no default style
- '<img>': image that needs a 'src' attribute
- '<a>': link that needs an 'href' attribute
- '<input>': attributes: :"type", "value"
- '<textarea>: big text input box
- '<button>': clickable! (everything is clickable with the onclick attribute)
- '<select>': select from a list of options in a drop down menu

**other common elements**
- '<header>'
- '<footer>'
- '<section>'
- '<main>'
- '<p>'

### attributes

**allow you to modify HTML elements. In React, these are called "props"**

Attributes are added to the opening tag, before the '>' character. Multiple attributes can be added with space in between.

```html
<!-- apply a class -->
<div class="my-class"></div>

<!-- apply "inline styles -->
<div> style="height:40px"></div>

<!-- listen for a click -->
<button onclick="runFucntion()" onhover=""></button>
```