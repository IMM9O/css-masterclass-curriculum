# CSS Masterclass Curriculum

Or how to master CSS using available free content.

<p style="text-align: center;">
  <img src="https://images.unsplash.com/photo-1517446915321-65e972f1b494?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80" alt="Photo by Paula May on Unsplash">
  <p style="text-align: center;">Photo by <a href="https://unsplash.com/@paulamayphotography">Paula May</a> on <a href="https://unsplash.com/">Unsplash</a></p>
</p>

<br/>

CSS is a very vast topic seems to be easy at first, but it becomes a pain in a head when you want to master it not for lack of tutorials but for lack of path or full curriculum to mastering it, here I am going to show you how to master CSS by following a curriculum contain very comprehensive resources from the internet, and sure it will be free.

---

## What is CSS?

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file and reduce complexity and repetition in the structural content. (Source: Wikipedia)

---

## How this curriculum work?

In each section you can find 📖 Contents and 📚 Resources, in contents I show to you what topics included in this section then in resources sections I list some of the big and most comprehensive ( articles, videos or courses ) resources covering this topic.
But before you start you need to learn the basics of HTML & CSS then follow the Curriculum to master CSS.

---

## HTML&CSS Basics

- [html & css is hard](https://internetingishard.com/html-and-css/) - A friendly web development tutorial for complete beginners.
- [Learn CSS](https://web.dev/learn/css/) - An evergreen CSS course and reference to level up your web styling expertise.
- [Introduction to HTML](https://scrimba.com/g/ghtml) - Scrimba.
- [Introduction to CSS](https://scrimba.com/g/gintrotocss) - Scrimba.
- [HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE) - by Traversy Media on Youtube.
- [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI) - by Traversy Media on Youtube.

---

## Curriculum

CSS can be categorized into four main categories:

1. **Syntax:** includes selectors, properties, values, and Cascading.
2. **Visual:** includes styling content, and animations.
3. **Layout Module:** includes box model, layout, and responsive web design.
4. **Management:** includes CSS preprocessors, methodologies, and frameworks.

* Core Module

- [CSS Selectors](#css-selectors)
- [CSS Properties](#css-properties)
- [CSS Values](#css-values)
- [CSS Cascading](#The-cascade)

* Typography Module

- [Styling Content](#styling-content)
- [CSS Animations and Drawing](#css-animations-and-drawing)

* Layout Module

- [CSS Box Model](#css-box-model)
- [CSS Layout](#css-layout)
- [Responsive Web Design](#responsive-web-design)

* Design System Module

- [CSS Methodologies](#css-methodologies)
- [CSS Preprocessors](#css-preprocessors)
- [CSS Frameworks](#css-frameworks)

### **Syntax**

<p style="text-align: center;">
  <img src="https://www.w3schools.com/css/selector.gif" alt="css syntax">
  <p style="text-align: center;">Photo taken from w3schools</p>
</p>

<br/>

A CSS rule-set consists of a selector and a declaration block:

The selector points to the HTML element you want to style.
The declaration block contains one or more declarations separated by semicolons.
Each declaration includes a CSS property name and a value, separated by a colon.
A CSS declaration always ends with a semicolon, and declaration blocks are surrounded by curly braces. (Source: w3schools)

### **CSS Selectors**

In CSS, selectors are used to targeting the HTML elements on our web pages that we want to style.

#### 📖 Contents

- **Simple Selectors:**

  - Element
  - Class
  - Id
  - Universal Selector ( _, ns|_, _|_, |\* )

- **Combinators & Multiple selectors:**

  - Group of selector [A, B].
  - Descendant selector [A B].
  - Child selector [A > B].
  - Adjacent sibling selector [A + B].
  - General sibling selector [A ~ B].

- **Attribute Selectors**
- **Pseudo-class Selectors**
- **Pseudo-element Selectors**

#### 📚 Resources

- 📜 [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Selectors) - MDN web docs.
- 📜 [Simple Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Simple_selectors) - MDN web docs.
- 📜 [Combinators & Multiple selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Combinators_and_multiple_selectors) - MDN web docs.
- 📜 [Attribute Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Attribute_selectors) - MDN web docs.
- 📜 [Pseudo-class and Pseudo-element Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Pseudo-classes_and_pseudo-elements) - MDN web docs.

#### [Back to the top](#Curriculum)

### **CSS Properties**

**Note:** You will learn more about properties when you get into proper section but you can learn some generic concept like CSS variables.

#### 📖 Contents

- **CSS Variables**

#### 📚 Resources

- 📀 [Learn CSS Variables Course](https://scrimba.com/g/gcssvariables) - Scrimba.
- 📜 [CSS Custom Properties Guide](https://css-tricks.com/guides/css-custom-properties/) - CSS Tricks.
- 📜 [Everything you need to know about CSS Variables](https://medium.freecodecamp.org/everything-you-need-to-know-about-css-variables-c74d922ea855) - Freecodecamp.

#### [Back to the top](#Curriculum)

### **CSS Values**

CSS values are set against CSS Properties and reside within CSS declaration block, which is a part of the CSS rule/statement.
**Note:** You will learn more about each value type when you get into proper section but you can learn some generic values like rem, colors, calc ...etc.

#### 📖 Contents

- There are 4 types of values in CSS

  - Colors.
  - Length, sizes and numbers.
  - Pre-Defined Options.
  - Functions.

- How CSS values are processed.

  - [Initial value](https://developer.mozilla.org/en-US/docs/Web/CSS/initial_value) - MDN web docs.
  - [Resolved value](https://developer.mozilla.org/en-US/docs/Web/CSS/resolved_value) - MDN web docs.
  - [Specified value](https://developer.mozilla.org/en-US/docs/Web/CSS/specified_value) - MDN web docs.
  - [Computed value](https://developer.mozilla.org/en-US/docs/Web/CSS/computed_value) - MDN web docs.
  - [Used value](https://developer.mozilla.org/en-US/docs/Web/CSS/used_value) - MDN web docs.
  - [Actual value](https://developer.mozilla.org/en-US/docs/Web/CSS/actual_value) - MDN web docs.

#### 📚 Resources

- 📜 [Color](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value) - MDN web docs.
- 📜 [A Nerd’s Guide to Color on the Web](https://css-tricks.com/nerds-guide-color-web/) - CSS Tricks.
- 📜 [CSS Gradients Guides](https://css-tricks.com/guides/css-gradients/) - CSS Tricks.
- 📜 [A Couple of Use Cases for Calc()](https://css-tricks.com/a-couple-of-use-cases-for-calc/) - CSS Tricks.

#### [Back to the top](#Curriculum)


### **The cascade**

Cascading is the algorithm used for solving conflicts where multiple CSS rules apply to an same HTML element.
The cascade algorithm is split into 4 distinct stages.

**Position and order of appearance:** the order of which your CSS rules appear
**Specificity:** an algorithm which determines which CSS selector has the strongest match
**Origin:** the order of when CSS appears and where it comes from, whether that is a browser style, CSS from a browser extension, or your authored CSS
**Importance:** some CSS rules are weighted more heavily than others, especially with the !important rule type

#### 📖 Contents

- **Position and order of appearance:**
    - Inline style
    - Embedded style tag
    - External file

- **Specificity hierarchy:**
    - Universal selector
    - Element or pseudo-element selector
    - Class, pseudo-class, or attribute selector
    - ID selector
    - Inline style attribute
    - !important rule

- **Origin:**
    - User agent base styles: Browser style like chrome, firefox, ...etc.
    - Local user style: System style like windows, android, ..etc.
    - Authored CSS: Any css developer are write
    - Authored `!important`: any `!important` developer are write
-  

#### 📚 Resources

- 📜 [The “C” in CSS: The Cascade](https://css-tricks.com/the-c-in-css-the-cascade/) - CSS Tricks.
- 📜 [Cascading and Inheritance](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance)
- 📹 [CSS Basics (Part2) — Cascades](https://www.youtube.com/watch?v=tZhmjgLQgXU) - by DevTips on Youtube.
- 📹 [CSS Basics (Part6) — Specificity](https://www.youtube.com/watch?v=fy07HYm-geM) - by DevTips on Youtube.
- 📜 [inheritance](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)
- 📜 [Inherit, initial, unset, revert](https://www.quirksmode.org/blog/archives/2021/06/inherit_initial.html)

#### [Back to the top](#Curriculum)

### **CSS Box Model**

<p style="text-align: center;">
  <img src="https://www.w3.org/TR/CSS2/images/boxdim.png" alt="css box model">
  <p style="text-align: center;">Photo taken from w3.org</p>
</p>

<br/>

The CSS box model is the foundation of layout on the Web — each element is represented as a rectangular box, with the box's content, padding, border, and margin built up around one another like the layers of an onion. As a browser renders a web page layout, it works out what styles are applied to the content of each box, how big the surrounding onion layers are, and where the boxes sit in relation to one another. Before understanding how to create CSS layouts, you need to understand the box model. (source: MDN)

#### 📖 Contents

- **Content** (images, text …etc).
- **Fill Area** (the area that contains border, padding, content, and filling with background and background-image).
- **Margins** (Space around elements, outside of any defined borders).
- **Borders** (goes around the padding and content ).
- **Padding** (Transparent area around the content, inside of the box).
- **Box Sizing:**
  - content-box: Width and height only apply to the content of the element.
  - border-box: Include padding and border in the element's total width and height.
- **Box Shadow:**
- **Background:**
  - [background-color](https://developer.mozilla.org/en-US/docs/Web/CSS/background-color).
  - [background-image](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image).
  - [background-size](https://developer.mozilla.org/en-US/docs/Web/CSS/background-size).
  - [background-repeat](https://developer.mozilla.org/en-US/docs/Web/CSS/background-repeat).
  - [background-position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position).
  - [background-origin](https://developer.mozilla.org/en-US/docs/Web/CSS/background-origin).
  - [background-clip](https://developer.mozilla.org/en-US/docs/Web/CSS/background-clip).
  - [background-attachment](https://developer.mozilla.org/en-US/docs/Web/CSS/background-attachment).
  - [background-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode).
  - Multiple Background Images.
  - Linear Gradients.
  - Radial Gradients.
- **clip-path**

#### 📚 Resources

- 📜 [The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model) - MDN web docs.
- 📜 [What You Should Know About Collapsing Margins](https://css-tricks.com/what-you-should-know-about-collapsing-margins/)
- 📜 [Inline Elements and Block Elements in HTML - Explained](https://www.freecodecamp.org/news/inline-elements-and-block-elements-in-html-explained/)
- 📜 [Getting Deep Into Shadows](https://css-tricks.com/getting-deep-into-shadows/)
- 📜 [Every CSS Background Property Illustrated and Explained with Code Examples 🎖️](https://www.freecodecamp.org/news/learn-css-background-properties/)
-  

#### [Back to the top](#Curriculum)

### **Styling Content**

After you learn the box-model, learning styling content _( which is the part of box-model )_ is the big core concept to master. In this section, you will learn how to style those content like images, text, lists, links ...etc.

#### 📖 Contents

- Typography.
- Lists.
- Links.
- Media ( Image, Video, and Audio ).
- Tables.
- Forms.
- Buttons.

#### 📚 Resources

- 📜 [A Complete Guide to the Table Element](https://css-tricks.com/complete-guide-table-element/) - CSS Tricks.
- 📜 [Styling Links](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links) - MDN web docs.

#### [Back to the top](#Curriculum)

### **CSS Layout**

Once you have the ability to target HTML elements for styling, the layout is the next core concept to master.
Layout involves manipulating how elements layout on the page, How much space do they take? Are they side by side or on top of each other?...etc.

#### 📖 Contents

- **Normal flow**
- **The display property:**
  - Block.
  - Inline.
  - Inline-Block.
  - Flexbox.
  - Grid.
  - Table.
- **Floats**
- **Positioning**
  - Default ( no property specified or Static ).
  - Relative.
  - Absoulte.
  - Fixed.
  - Sticky.
  - Stacking Content ( Z-Index property ).
- **Multiple-column layout**

#### 📚 Resources

- 📜 [Learn CSS Layout](http://learnlayout.com/)
- 📹 [Building layouts with flexbox and CSS grids](https://www.youtube.com/watch?v=2GxAElWKaAo)
- 📜 [Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/) - CSS Tricks.

- Flexbox

  - 👩‍💻 [Flexbox Patterns](https://www.flexboxpatterns.com/)
  - 👩‍💻 [Solved by Flexbox](https://philipwalton.github.io/solved-by-flexbox/)
  - 📀 [CSS flexbox Course](https://flexbox.io/) - by WesBos.
  - 📜 [Flexbox Complete Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - CSS Tricks.
  - 📜 [The Complete CSS Flex Tutorial](https://jst.hashnode.dev/complete-css-flex-tutorial)
  - 📜 [Flexbox - The Ultimate CSS Flex Cheatsheet (with animated diagrams!)](https://www.freecodecamp.org/news/flexbox-the-ultimate-css-flex-cheatsheet/) - Freecodecamp.
  - 📜 [The Ultimate Guide to Flexbox  — Learning Through Examples](https://www.freecodecamp.org/news/the-ultimate-guide-to-flexbox-learning-through-examples-8c90248d4676/) - Freecodecamp.
  - 📜 [Understanding Flexbox: Everything you need to know](https://www.freecodecamp.org/news/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af/) - Freecodecamp.

- Grid

  - 👩‍💻 [Grid by Example](https://gridbyexample.com/examples/)
  - 📀 [CSS Grid Course](https://cssgrid.io/) - by WesBos.
  - 📜 [CSS Grid Complete Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - CSS Tricks.
  - 📜 [The Complete CSS Grid Tutorial](https://jst.hashnode.dev/css-grid-tutorial)
  - 📜 [How to create an image gallery with CSS Grid](https://medium.freecodecamp.org/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c) - Freecodecamp.

- Floats

  - 📜 [All About Floats](https://css-tricks.com/all-about-floats/) - CSS Tricks.
  - 📹 [CSS Floats Explained](https://www.youtube.com/watch?v=609adV3pTME) - by DevTips on Youtube.
  - 📹 [CSS Floats and Clears Explained](https://www.youtube.com/watch?v=xFGBNv2KeVU) - by DevTips on Youtube.

- Positioning

  - 📹 [CSS Positioning - part1](https://www.youtube.com/watch?v=kejG8G0dr5U) - by DevTips on Youtube.
  - 📹 [CSS Positioning - part2](https://www.youtube.com/watch?v=Rf6zAP4YnZA) - by DevTips on Youtube.

- Multiple-column layout

  - 📜 [When And How To Use CSS Multi-Column Layout](https://www.smashingmagazine.com/2019/01/css-multiple-column-layout-multicol/) - Smashing Magazine.

#### [Back to the top](#Curriculum)

### **Responsive Web Design**

Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices desktops, tablets, and phones. (Source: w3schools)

#### 📖 Contents

- **Media Queries**
- **Responsive Images**
- **Common Responsive Patterns**
  - Mostly Fluid.
  - Column Drop.
  - Layout Shifter.
  - Off Canvas.
- **Responsive Layout Methods:**
  - Mobile-First.
  - Desktop-First.

#### 📚 Resources

- 📀 [Responsive Images](https://udacity.com/course/responsive-images--ud882)
- 📀 [Responsive Web Design Fundamentals](https://udacity.com/course/responsive-web-design-fundamentals--ud893)
- 📀 [Introduction To Responsive Web Design - HTML & CSS Tutorial](https://www.youtube.com/watch?v=srvUrASNj0s&list=WL)
- 📜 [Learn CSS Media Queries by Building Three Projects](https://www.freecodecamp.org/news/learn-css-media-queries-by-building-projects/)
- 📜 [Learn CSS Flexbox by Building 5 Responsive Layouts](https://www.freecodecamp.org/news/learn-flexbox-build-5-layouts/)

#### [Back to the top](#Curriculum)

### **CSS Animations and Drawing**

CSS Animations involves manipulating how elements should look like over the time by allowing you to specify how elements change from one style to another.

#### 📖 Contents

- **CSS Animations - Transforms:**

  - Transform translate().
  - Transform rotate() and Transform-Origin.
  - Transform scale().
  - Transform skew().
  - Transform Shorthand.

- **CSS Animations - Transitions:**

  - Transition Duration.
  - Transition Property.
  - Transition Timing Function.
  - Transition Delay.
  - Transition Shorthand.

- **CSS Animations - Keyframes:**

  - CSS Animation Keyframes.
  - CSS Animation Duration.
  - CSS Animation Fil Mode.
  - CSS Animation Iteration Count.
  - CSS Animation Delay.
  - CSS Animation Direction.
  - CSS Animation Timing Function.
  - CSS Animation Properties.
  - CSS Animation Shorthand.

- **CSS Shapes:**
  - CSS Shapes: the inset() function.
  - CSS Shapes: The circle() Function.
  - CSS Shapes: The ellipse() Function.
  - CSS Shapes: The polygon() function.
  - CSS Shapes: Shapes from the Alpha Channel.
  - CSS Shapes: Shapes from the Reference Box.

#### 📚 Resources

- 📜 [An Introduction to Web Animations](https://medium.freecodecamp.org/an-introduction-to-web-animations-86f45de2a871) - Freecodecamp.
- 📜 [A Simple CSS Animation Tutorial](https://medium.freecodecamp.org/a-simple-css-animation-tutorial-8a35aa8e87ff) - Freecodecamp.
- 📜 [CSS Animation Performance](https://www.html5rocks.com/en/tutorials/speed/high-performance-animations/)

#### [Back to the top](#Curriculum)




### **CSS Methodologies**

If you're not careful, it is easy to write complex, confusing, and unmaintainable CSS. so there are many ways to manage that.

#### 📖 Contents

- **Common naming conventions:**
  - [BEM](http://getbem.com/).
  - [OOCSS](http://oocss.org/).
  - [SMACSS](https://smacss.com/).
  - [SUITCSS](https://suitcss.github.io/).
  - [Atomic](https://acss.io/).

#### 📚 Resources

- 📜 [BEM For Beginners: Why You Need BEM](https://www.smashingmagazine.com/2018/06/bem-for-beginners/) - Smashing Magazine.

#### [Back to the top](#Curriculum)

### **CSS Preprocessor**

The use of CSS preprocessors has become so important especially when you start working on a large project.
Learn about the most famous and common used preprocessor ( SASS ), Why I use it?, How to use it? and How to writing maintainable and scalable Sass.

#### 📖 Contents

- **Common Preprocessors:**
  - SASS.
  - LESS.
  - Stylus.
  - PostCSS.

#### 📚 Resources

- 📜 [Learn Sass In 15 Minutes | Tutorialzine](https://tutorialzine.com/2016/01/learn-sass-in-15-minutes)
- 📀 [SASS Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iEwigam3gTjU_7IA3W2WZA) - by The Net Ninja on Youtube.
- 📹 [Sass Workflow & Dev Server From Scratch Using Gulp](https://www.youtube.com/watch?v=rmXVmfx3rNo) - by Traversy Media on Youtube.
- 📜 [Sass Guidelines](https://sass-guidelin.es/)
- 📜 [How to structure a Sass project](http://thesassway.com/beginner/how-to-structure-a-sass-project)
- 📜 [PostCSS – A Comprehensive Introduction](https://www.smashingmagazine.com/2015/12/introduction-to-postcss/) - Smashing Magazine.

#### [Back to the top](#Curriculum)

### **CSS Frameworks**

In this area, you can pick up any framework you want, but I will list here the most famous one.

#### 📖 Contents

- **Tailwind CSS**
- **Bootstrap**
- **Bulma**

#### 📚 Resources

- [Tailwind CSS](https://tailwindcss.com/docs/what-is-tailwind/)

  - 📹 [Vanilla CSS vs Bootstrap vs Tailwind CSS - Which one should you choose?](https://www.youtube.com/watch?v=vmXIGdP8KN8)
  - 📹 [Introduction to Tailwind CSS](https://www.youtube.com/playlist?list=PLylMDDjFIp1Dt5hWKHPIHtdF2GFAS8Ak9)
  - 📀 [Tailwind CSS](https://www.youtube.com/playlist?list=PLEhEHUEU3x5p8cxOJ27w20LffCknp935L)

- [Bootstrap](https://getbootstrap.com/)

  - 📀 [Learn Bootstrap 4 Course](https://scrimba.com/g/gbootstrap4) - Scrimba.
  - 📜 [Bootstrap 4: Everything You Need to Know](https://medium.freecodecamp.org/bootstrap-4-everything-you-need-to-know-c750991f6784) - Freecodecamp.
  - 📜 [Bootstrap Framework — Best Practices](https://hackernoon.com/bootstrap-framework-best-practises-b1d81c02d6cf)

- [Bulma](https://bulma.io/)

  - 📀 [learn Bulma Course](https://scrimba.com/g/gbulma) - Scrimba.
  - 📀 [Bulma Crash Course](https://www.youtube.com/watch?v=IiPQYQT2-wg&index=23&list=PLillGF-RfqbZTASqIqdvm1R5mLrQq79CU) - by Traversy Media on Youtube.


#### [Back to the top](#Curriculum)

## Where to go next?

In general, I found this blogs, newsletter or courses the best resources to learn CSS in specific and web development in general and for those who prefer paid courses I list for you the best-paid courses available on the web.

- References 📜

  - [HTML Reference](http://htmlreference.io/)
  - [CSS Reference](http://cssreference.io/)
  - [MDN Dev](https://developer.mozilla.org/en-US/)
  - [The Ultimate Guide to Learning CSS](https://zendev.com/ultimate-guide-to-learning-css.html)

- Courses & Books 📀 📚

  - [The CSS Handbook: a handy guide to CSS for developers](https://www.freecodecamp.org/news/the-css-handbook-a-handy-guide-to-css-for-developers-b56695917d11/)
  - 💲 [CSS - The Complete Guide (incl. Flexbox, Grid & Sass)](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/)
  - 💲 [Advanced CSS and Sass: Flexbox, Grid, Animations and More!](https://www.udemy.com/advanced-css-and-sass/)

- Blogs, Podcast 🎙, Newsletter 📫 & Conferences 📢

  - [CSS Tricks](https://css-tricks.com/)
  - [Smashing Magazine](https://www.smashingmagazine.com/)

### [Back to the top](#Curriculum)
