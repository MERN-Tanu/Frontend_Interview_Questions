# Frontend_Interview_Questions
**HTML Interview Question**
#HTML Interview Questions:

1.Are the HTML tags and elements the same thing?

Ans: No. HTML elements
are defined by a starting tag, may contain some content and a closing tag. For
example,

**HTML Element**

```html
<h1>Heading 1</h1>
is a HTML element but just
```

**HTML Tags**

```html
<h1>is a starting tag and</h1>
is a closing tag.
```

2.What are tags and attributes in HTML?

ans :

```html
tags :
<body></body>
<p></p>
<head></head>
```

```html
Attributes : 1. src 2. alt 3. title 4. style 5.class 6. id
```

9.  Define multipart form data?
    Multipart form data is one of the values of the enctype attribute. It is used to send the file data to the server-side for processing. The other valid values of the enctype attribute are text/plain and application/x-www-form-urlencoded.
10. Describe HTML layout structure.

        `<header>`

        `<footer>`
        `<nav>`
        `<article>`
        `<section>`
        `<aside>`

11. what are void elements in HTML?
    void elements which do not have closing tags or do not need to be closed

        <br/>,<img/>,<hr/>

12. what are different types of lists in html?
    ![1702573251866](image/html/1702573251866.png)
13. what is the difference between id and class attribute of html element?

    ```
    Multiple elements in html can have the same class value,
    whereas a value of id attribute of one element cannot be associated with another html.
    ```

14. How to optimise websites assets loading?

```
- CDN hosting : Content delivery network is geographically     distributed servers to help reduce latency (that experiences very small delay).

- File compression : reduce the size of an asset to reduce the data transfer

- File Concatenation : this reduces the number of http calls
- Minify Script : this reduces the overall file size of js and css files

- Parallel downloads :

```

```
Lazy Loading : (Page will load take sometime)

Lazy loading is a technique for waiting to load certain parts of a webpage — especially images — until they are needed. Instead of loading everything all at once, known as "eager" loading, the browser does not request certain resources until the user interacts in such a way that the resources are needed.
```

![1702574402950](image/html/1702574402950.png)

15. What are the different kinds of Doctypes available?
    The three kinds of Doctypes which are available:
    Strict Doctype
    Transitional Doctype
    Frameset Doctype

16. Please explain how to indicate the character set being used by a document in HTML?
    The character set is defined in <meta> tag inside <head> element.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    ... ...
  </head>
  ...
</html>
```

17. Can we display a web page inside a web page or Is nesting of webpages possible?
    Yes, we can display a web page inside another HTML web page. HTML provides a tag <iframe> using which we can achieve this functionality.

    ```html
    <iframe src="”url" of the web page to embed” />
    ```

```
18. In how many ways can we position an HTML element? Or what are the permissible values of the position attribute?


There are mainly 7 values of position attribute that can be used to position an HTML element:

static: Default value. Here the element is positioned according to the normal flow of the document.

absolute: Here the element is positioned relative to its parent element. The final position is determined by the values of left, right, top, bottom.

fixed: This is similar to absolute except here the elements are positioned relative to the <html> element.

relative: Here the element is positioned according to the normal flow of the document and positioned relative to its original/ normal position.

initial: This resets the property to its default value.

inherit: Here the element inherits or takes the property of its parent
```

```
19.In how many ways you can display HTML elements?

inline: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.

block: using this, we can display any inline element as a block-level element.

inline-block: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.

flex: It displays the container and element as a flexible structure. It follows flexbox property.

inline-flex: It displays the flex container as an inline element while its content follows the flexbox properties.

grid: It displays the HTML elements as a grid container.

none: Using this property we can hide the HTML element.
```

```

20.What is the difference between “display: none” and “visibility: hidden”, when used as attributes to the HTML element.


When we use the attribute “visibility: hidden” for an HTML element then that element will be hidden from the webpage but still takes up space.

Whereas, if we use the “display: none” attribute for an HTML element then the element will be hidden, and also it won’t take up any space on the webpage.

```

```
21.In how many ways can we specify the CSS styles for the HTML element?

Inline: Here we use the ‘style’ attribute inside the HTML element.

Internal: Here we use the <style> tag inside the <head> tag. To apply the style we bind the elements using ‘id’ or ‘class’ attributes.

External: Here we use the <link> tag inside <head> tag to reference the CSS file into our HTML code. Again the binding between elements and styles is done using ‘id’ or ‘class’ attributes.

```

![1702575528475](image/html/1702575528475.png)

```html
22.What are forms and how to create forms in HTML?

<form action="/submit_data.php">
  <label>Enter your name: </label>
  <input type="text" name="name" />
  <label>Enter Mobile number </label>
  <input type="number" name="mobile_no" />
  <input type="submit" value="Submit" />
</form>
```
**---------------------------------------**



```
🚀 Master Your Front-End Developer Interview with these 50 JavaScript Questions! 🚀

1. What is the DOM?
2. Explain the differences between `null` and `undefined`.
3. How does the "strict mode" in JavaScript work?
4. What is the purpose of the `async` keyword?
5. Differentiate between synchronous and asynchronous code.
6. What is a callback function?
7. Explain the concept of "hoisting."
8. How does the "debouncing" of a function work?
9. What is the purpose of the `bind` method?
10. Describe the differences between cookies, sessionStorage, and localStorage.

11. How does CORS (Cross-Origin Resource Sharing) work?
12. What is the purpose of the `this` keyword in JavaScript?
13. Explain the differences between `==` and `===`.
14. How does the event delegation pattern work?
15. What is a closure, and how is it used?
16. How can you optimize website performance?
17. What is the difference between arrow functions and regular functions?
18. Describe the principles of responsive design.
19. Explain the concept of currying in JavaScript.
20. What is the role of the `use strict` directive?

21. How do you handle errors in JavaScript?
22. Explain the significance of the Document Object Model (DOM).
23. What is the purpose of the `map` function in JavaScript?
24. Differentiate between shallow and deep copying objects.
25. How does event bubbling work in the DOM?
26. Explain the concept of two-way data binding.
27. What is the role of a closure in JavaScript?
28. How can you optimize the loading time of a website?
29. What is the significance of the `async` and `await` keywords?
30. Describe the differences between local storage and session storage.

31. How does the "typeof" operator work in JavaScript?
32. Explain the principles of the Single Responsibility Principle (SRP) in software design.
33. What is the purpose of the `finally` block in a try-catch-finally statement?
34. How can you handle cross-browser compatibility issues?
35. What is the role of the `replace` method in strings?
36. How does the prototype chain work in JavaScript?
37. Describe the differences between REST and GraphQL.
38. What is the purpose of the `reduce` function in JavaScript?
39. Explain the concept of memoization.
40. How does the "box model" work in CSS?

41. What are web components, and how do they work?
42. Differentiate between call, apply, and bind methods.
43. How can you optimize images for the web?
44. Explain the purpose of the `defer` attribute in script tags.
45. What is the role of the `let` and `const` keywords in block scope?
46. Describe the differences between CSS Grid and Flexbox.
47. How do you handle asynchronous code in JavaScript?
48. Explain the purpose of the `Intersection Observer` API.
49. What are the benefits of using a CSS preprocessor like Sass?
50. How can you improve website accessibility?

```
