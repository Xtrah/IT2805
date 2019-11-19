# Assignment questions
## 1 HTML introduction
1. What does the server in the client server architecture do?  
2. What does the client do?  
3. What is an IP address?  
4. What is DNS?  
5. What is the difference between the Internet and WWW?  
6. Explain what HTML is  

## 2 HTML continued, links/paths & CSS introduction
1. Why does inline style CSS override rules defined in style elements and external stylesheets?  
2. Give a brief example of when to use ID (`#id`) and when to use classes (`.class`) in CSS.  
3. What does RGBA mean and what colors can you express with it?  
4. Why do we include CSS files inside the head element and not inside the body element?  
5. What CSS selector matches all the p elements inside the article element in the following HTML?  
    ```html
    <p>This should not match.</p>
    <article>
        <p>This should match.</p>
        <p>This should also match.</p>
        <p>Do not forget about this one!</p>
    </article>
    ```
6. What are the DRY and KISS principles of software design?  

## 3 CSS continued
1. What is the difference between `position: absolute` and `position: fixed`?  
2. With CSS3, how do we access the third element within another element?  

## 4 HTML video & css
1. Why do mobile phones usually ignore auto play on video elements?  
2. What will the CSS snippet at the end of this section do if the visitor is browsing on a device with 320 x 568 resolution?  
3. Mention some of the advantages of having a single responsive website instead of dedicated versions like m.til.no for mobile and til.no for desktop?  
    ```css
    @media only screen
        and (min-device-width : 768px)
        and (max-device-width : 1024px) {
        #logo {
        display: none;
        }
    }
    ```

## 5 Forms, XML and JavaScript
1. Why does the following expression `0.1 + 0.2 === 0.3` evaluate to false in Javascript?  
2. What does the `method` attribute on a `form` element decide?  
3. Explain why the form fields appear in the URL when the method on form element is changed to `GET`?  
4. Why is it considered bad practice to only validate form input with HTML5 and/or Javascript?  
5. When is it appropriate to use `textarea` over `input`?  

## 6 Canvas
1. When calling `getContext('2d')` on a Canvas element, it will return a drawing context (i.e. the type of canvas) - in this case a two-dimensional context. How can we get a threedimensional context instead?  
2. How would you create a blue circle using the Canvas element? Explain with words or code.  
3. What is a more terse (also known as shorter) way of writing the loop in the following using the `Array.filter` method?  
    ```javascript
    const countries = ['Norway', 'Sweden', 'Denmark', 'New Zealand'];
    const countriesStartingWithN = [];
    for (let i = 0; i < countries.length; i++) {
        let country = countries[i];
        if (country.startsWith('N')) {
            countriesStartingWithN.push(country);
        }
    }
    ```

# Exam questions

1. In CSS, you can override precedence rules by adding the ____ property to a style declaration.  
    A. !override  
    B. !main  
    C. !important  
    D. !priority  

2. What is the default value of the position property?  
    A. relative  
    B. absolute  
    C. fixed  
    D. static  

3. What is one advantage that HTML5 APIs offer for modern Web design?  
    A. They enable users to view Flash content on mobile devices.  
    B. They enable developers to create apps without coding skills  
    C. They enable older browsers to display any multimedia content  
    D. They enable users to view multimedia without plug-ins  

4. What is the result of the following code?  
    `var y = Math.floor(3.8);`  
    A. 3.8  
    B. 4  
    C. 3.5  
    D. 3  

5. Graphics defined by SVG is in which format?  
    A. XML  
    B. HTML  
    C. CSS  
    D. Javascript  
    
6. What the following code will do if someone types in “18”?  
    ```javascript
    var age = prompt("Enter your age ");
    var next = age + 1;
    alert("On your next birthday, you'll be "+next);
    ```
    A. It gets an error  
    B. It displays "18"  
    C. It displays "19"  
    D. It displays "181"  

7. How do you select all p elements inside a div element?  
    A. `div.p`  
    B. `div p`  
    C. `div + p`  
    D. `div * p`  

8. How do you display a border like this:  
    The top border = 10 pixels  
    The bottom border = 5 pixels  
    The left border = 20 pixels  
    The right border = 1 pixel  
    A. `border-width:10px 1px 5px 20px;`  
    B. `border-width:5px 20px 10px 1px;`  
    C. `border-width:10px 5px 20px 1px;`  
    D. `border-width:10px 20px 5px 1px;`  

9. From outside to inside, a box (block) has:  
    A. border, margins, padding  
    B. margins, padding, border  
    C. padding, margins, border  
    D. margins, border, padding  

10. Which statement is true?  
    A. An XML document can have one root element  
    B. An XML document can have one child element  
    C. XML elements have to be in lower case  
    D. All of the above  

11. Which of the following statements is true? (2%)  
    A. JPG files are limited to 256 colors.  
    B. GIF files support 8 bit transparency.  
    C. Use GIF files for photographs.  
    D. GIF uses lossless compression algorithm  

12. What is one advantage that HTML5 APIs offer for modern Web design?  
    A. They enable users to view Flash content on mobile devices.  
    B. They enable developers to create apps without coding skills  
    C. They enable older browsers to display any multimedia content  
    D. They enable users to view multimedia without plug-ins  

13. Match each of the TCP/IP layers with the correct protocol.  

    |       Layer       	| Protocol 	|
    |:-----------------:	|:--------:	|
    | Application Layer 	| IP       	|
    | Transport Layer   	| WiFi     	|
    | Network Layer     	| TCP      	|
    | Physical Layer    	| HTTP     	|

14. What is the correct HTML for making a text input field?  
    ```html
    A. <input type="textfield">
    B. <textfield>
    C. <input type="text">
    D. <textinput type="text">
    ```

15. How do you display hyperlinks without an underline?  
    ```css
    A. a {decoration:no-underline;}
    B. a {text-decoration:none;}
    C. a {underline:none;}
    D. a {text-decoration:no-underline;}
    ```

16. What is the correct JavaScript syntax to change the content of the HTML element below?    
    ```html
    <p id="demo">This is a demonstration.</p>
    ```
    ```javascript
    A. document.getElementById("demo").innerHTML = "Hello World!";
    B. #demo.innerHTML = "Hello World!";
    C. document.getElement("p").innerHTML = "Hello World!";
    D. document.getElementByName("p").innerHTML = "Hello World!";
    ```

17. If you wanted to round the corners of a block element, which style property would you apply?  
    ```css
    A. border:
    B. border-arc:
    C. border-deg:
    D. border-radius:
    ```  

18. Consider the table shown below. Which line of code would create the last row of the table?  
    ![q19-table](img/table1.jpg)
    ```html
    A. <tr><td></td><td rowspan=”2”></td></tr>
    B. <tr><td colspan=”2”></td><td rowspan=”2”></td></tr>
    C. <tr><td rowspan=”2”></td></tr>
    D. <tr><td colspan=”2”></td></tr>
    ```

19. How many alert boxes will the following loop produce?    
    ```javascript
    for ( var Index = 0; Index <= 2; ++Index )
    alert( Index );
    ```
    A. 0  
    B. 1  
    C. 2  
    D. 3  

20. Which of the following is the code for accessing the contents of an input box named `userData` on a form?
    ```javascript
    A. document.forms[0].userData  
    B. document.forms[0].userData.value  
    C. document.forms[0].userData.contents  
    D. document.forms[0].userData.data  
    ```

21. Given a file structure in the figure below, if you are working on the source code of `index.html`, which of the following is the correct relative URL for `lecture1.html`?  
    ![q22-file-structure](img/file-structure-1.JPG)
    A. `lecture1.html`  
    B. `lectures/lecture1.html`  
    C. `../lectures/lecture1.html`  
    D. `./lecture1.html`  

22. The syntax for adding a textfield of 3 rows, each of width 40 is:  
    ```html  
    A. <textfield rowspan=”3” colspan=”40”>blah blah</textfield>  
    B. <textfield rows=”3” width=”40”>blah blah</text>  
    C. <text row=”3” width=”40”>blah blah</text>  
    D. <textarea rows=”3” cols=”40”>blah blah</textarea>  
    ```

23. Indicate whether each of the following statements is True or False.  
    A. The below is valid JSON.  
    B. In an HTML form, the method attribute is used to specify the script file that processes the form data  
    C. Domain Name Servers map symbolic computer names to their host names  
    D. XML elements cannot be empty  
    ```json
    {
        "id": 1,
        "name": "A green door",
        "price": 12.50,
        "tags": ["home", "green"]
    }
    ```

24. What is the output when you run the following programs:  
    ```javascript
    var i = 25;
    var j = “25”;
    var k = 2 + “5”;
    var l = “2” + “5”;
    (a) document.write (i == j);
    (b) document.write (i === j);
    (c) document.write (j == k);
    (d) document.write (j === k);
    (e) document.write (i == k);
    (f) document.write (i === k);
    (g) document.write (k == l);
    (h) document.write (k === l);
    ```

[Link to proposed solutions](solutions.md)