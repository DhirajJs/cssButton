cssButton
=========

**Css Button Techniques**
  **Intent** 
  For front developer who want quick and easy way to make nice and expandable button
## Html button structure
```html
    <button type="submit" title="Click Me" class="button">
        <span>
           <span>Click Me</span>
        </span>
    </button>
    <style>
    .button {
     color: #FFF;
    	border: none;
    	font-size: 0.625em;
    	padding: 0.625em 0.5em; }
    
    .button span > span{
    	text-shadow: 1px 1px 0 #67A854; }
  </style>  
```
* **Cross-Browser CSS Gradient button** 

     Only CSS ( no image used nor Javascript magic).
     
     The gradient is cross-browser supported (IE, Firefox 3.6, Chrome, and Safari).
     
     [Visite colorzilla](http://www.colorzilla.com/gradient-editor/)
     
     Flexible and scalable
     
     Fallback: if CSS3 is not supported, it will display a regular button (no gradient and shadow).
           
    ```html
    <button type="submit" title="Click Me" class=""button css3-gradient normal">
        <span>
           <span>Click Me</span>
        </span>
    </button>
    <style>
    .button.css3-gradient {
        background: rgb(80,135,52) no-repeat; /* Old browsers */
       	/* IE9 SVG, needs conditional override of 'filter' to 'none' */
       	background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzUwODczNCIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiM2N2E4NTQiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
       	background-image: -moz-linear-gradient(top,  rgba(80,135,52,1) 0%, rgba(103,168,84,1) 100%); /* FF3.6+ */
       	background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(80,135,52,1)), color-stop(100%,rgba(103,168,84,1))); /* Chrome,Safari4+ */
       	background-image-image: -webkit-linear-gradient(top,  rgba(80,135,52,1) 0%,rgba(103,168,84,1) 100%); /* Chrome10+,Safari5.1+ */
       	background-image: -o-linear-gradient(top,  rgba(80,135,52,1) 0%,rgba(103,168,84,1) 100%); /* Opera 11.10+ */
       	background-image: -ms-linear-gradient(top,  rgba(80,135,52,1) 0%,rgba(103,168,84,1) 100%); /* IE10+ */
       	background-image: linear-gradient(to bottom,  rgba(80,135,52,1) 0%,rgba(103,168,84,1) 100%); /* W3C */
       	filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#508734', endColorstr='#67a854',GradientType=0 ); /* IE6-8 */ }
    <style>
   
   ```
