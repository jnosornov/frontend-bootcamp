# WEEK 3
---

## TOPICS

*1. json*  
*2. dom*  
*3. flexbox*  
*4. advanced positioning*  
*5. responsive design*  
*6. yeoman*  
*7. bootstrap*

---

## MONDAY

**1. git conflict issues & commands**

**2. JAVASCRIPT OBJECT NOTATION**

*JSON (Javascript Object Notation)* is a text-based data format following javascript object syntax. JSON exist as an string and is use to transfer data across the network (between the server and the client), the data can be access for a particular use before it is converted to native javascript. 

#### JSON methods

*JSON.parse()* this method allows you to convert the data receive from the server represented as string into a        javascript object.

*JSON.stringify()* this method allows you to convert the data send to the server represented as javascript object     into string.

**To test JSON structure:** *[JSON Validator](https://jsonformatter.org/)*

**3. EXERCISE 9**

*def:* create a json structure with a list of humans, where a human has a name, age, a list of pets,
if the human has friends or not, and a list of friends.
*notes:* at least five humans, at least one human should have a friend.

[view exercise solution](../bootcamp-exercises/exercise9/exercise9.json)

**4. DOCUMENT OBJECT MODEL**

*The (Document Object Model) DOM* is a programming interface for HTML and XML documents. It represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree; with them you can change the document's structure, style or content. Nodes can have event handlers attached to them. Once an event is triggered, the event handlers get executed.

The HTML DOM is compound by: 

    - HTML as objects
    - the properties of all HTML elements
    - the methods to access all HTML elements
    - the events for all HTML elements

*As Jeremy Keith said:*

> The DOM represents the web page that’s currently loaded in the browser window. The browser provides a map (or model) of the page. You can use JavaScript to read this map.

*About nodes*

Every element within the HTML tree of the DOM is a node. Higher-up branch nodes are ‘parents’, adjacent branch nodes are ‘siblings’, and lower-down nodes are ‘children’ of their ‘parent’ nodes. All nodes in the tree can be access by programs and scripts. Nodes can be created, modified or deleted.

[Video about DOM nodes](https://www.youtube.com/watch?v=BWVoPxob5DU)

#### HTML DOM TREE REPRESENTATION
![DOM tree representation](./images/html-dom-tree.jpg)

#### HTML DOM DOCUMENTATION

[MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) |
[W3SCHOOLS](https://www.w3schools.com/js/js_htmldom.asp)

**5. EXERCISE 10**

*def:* use the onSubmit event to get the values of the contact form

---
## TUESDAY

**1. training DOM, git**  
**2. CONTENT DELIVERY NETWORK**

*A content delivery network (CDN)* is a system of distributed servers (network) that deliver pages and other Web content to a user, based on the geographic locations of the user, the origin of the webpage and the content delivery server.
This service is effective in speeding the delivery of content of websites with high traffic and websites that have global reach. The closer the CDN server is to the user geographically, the faster the content will be delivered to the user. CDNs also provide protection from large surges in traffic.

*How CDN works:* servers nearest to the website visitor respond to the request. The content delivery network copies the pages of a website to a network of servers that are dispersed at geographically different locations, caching the contents of the page. When a user requests a webpage that is part of a content delivery network, the CDN will redirect the request from the originating site's server to a server in the CDN that is closest to the user and deliver the cached content. CDNs will also communicate with the originating server to deliver any content that has not been previously cached.
The process of bouncing through CDNs is nearly transparent to the user. The only way a user would know if a CDN has been accessed is if the delivered URL is different than the URL that has been requested.

[Taken from](http://www.webopedia.com/TERM/C/CDN.html)

---
## WEDNESDAY

**1. GITHUB FLOW MODEL**

**2. FLEXBOX**


**3. EXERCISE 11**

*def:* build a carousel grid and carousel modal using flexbox

---
## THURSDAY

**1. layout techniques review**

**2. pages for color selection**

---
## FRIDAY

**1. advanced positioning**

**2. RESPONSIVE DESIGN**

*Responsive Web design* is the approach that suggests that design and development should respond to the user’s behavior and environment based on screen size, platform and orientation.The practice consists of a mix of flexible grids and layouts, images and an intelligent use of CSS media queries. As the user switches from their laptop to iPad, the website should automatically switch to accommodate for resolution, image size and scripting abilities. In other words, the website should have the technology to automatically respond to the user’s preferences. This would eliminate the need for a different design and development phase for each new gadget on the market. [Taken from](https://www.smashingmagazine.com)

[responsive design class exercise](../bootcamp-exercises/responsive-design/)

    a. css media queries
    b. disabling viewport zooming
    c. responsive images
    d. responsive image optimization
    e. retina screen

**3. exercise #12**

*def:* use responsive design in your curriculum vitae**

---
## SATURDAY

**1. setting up a yeoman project**

**2. bootstrap**







