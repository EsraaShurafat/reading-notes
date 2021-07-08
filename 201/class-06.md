# Javva Script Problem Domain 
![jsObjact](https://miro.medium.com/max/1400/1*2dthqHwybcl7oNgZCmElQw.png)

## GETTING MULTIPLE VALUES OUT OF A FUNCTION
#### Functions can return more than one value using an array. For example, this function calculates the area and volume of a box.
- First, a new function is created call ed get Size(). The area of the box is calculated and stored in a variable called area.  
- The volume is calculated and stored in a variable called vo 1 ume. Both are then placed into an array called shes.  
- This array is then returned to the code that called the getSize() function, allowing the values to be used. 

### The Document Object Model (DOM) 
- specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is  in the browser window. 
#### THE DOM TREE IS A MODEL OF A WEB PAGE .
![Dom](https://www.guru99.com/images/JavaScript/javascript8_1.png)
### Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in  the browser. 
# WORKING WITH THE DOM TREE :
- STEP 1: ACCESS THE ELEMENTS .
- STEP 2: WORK WIT H THOSE ELEMENTS.
### SELECTING AN ELEMENT FROM A NODELIST 
##### There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want. 
- THEtern () METHOD 
1. Select elements that have a cl ass attribute whose value is hot and store the Nodelist in a variable called e 1  ements. 
2. Use the 1 ength property to check how many elements were found. If 1 or more are found, run the code in the if statement. 
3. Store the first element from the Node List in a variable called fi rstitem. (It says 0 because index numbers start at zero.) 
## TRAVERSING THE DOM 
### When you have an element node, you can select another element in relation to it using these five properties. This is known as travers ing the DOM. 
- parentNode 
- previousSibling nextSibling 
- f i rstChil d lastChild 
### HOW TO GET/UPDATE ELEMENT CONTENT 
- So far this chapter has focused on finding elements in the DOM tree. The rest of this chapter shows how to access/update element content. Your choice of techniques depends upon what the element contains. 
### ACCESS & UPDATE A TEXT NODE WITH NODEVALUE 
- When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property. 
```
<li id="one"><em>fresh</em> figs</li> 
```
### ACCESS & UPDATE TEXT WITH TEXTCONTENT (& INN ERTEXT)
- The textContent property allows you to collect or update just the text that is in the containing element (and its children). 
 ```
 <li id="one"><em>fresh</em> figs</ li> 
 ```
 ## ADDING ELEMENTS USING DOM MANIPULATION 
 1. CREATE THE ELEMENT 
 ```
 createEl ement () 
 ```

 2. GIVE IT CONTENT 
 ```
 createTextNode() 
 ```
 3. ADD IT TO THE DOM
 ```
 appendChild() 
 ```
 ## REMOVING ELEMENTS VIA DOM MANIPULATION 
 1. STORE THE ELEMENT TO BE REMOVED IN A VARIABLE 
 2. STORE T HE PARENT OF THAT  ELEMENT IN A VARIABLE 
 3. REMOVE THE ELEMENT FROM ITS CONTA IN IN G ELEMENT 

 ## Summery :
 - The browser represents the page using a DOM tree. 
 - DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes. 
 - You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. 
 - Whenever a DOM query can return more than one node, it will always return a Nadelist. 
 - From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques. 
 - An element node can contain multiple text nodes and child elements that are siblings of each other. 
 - In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). 
 - Browsers offer tools for viewing the DOM tree .   
 
 
 [https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)


