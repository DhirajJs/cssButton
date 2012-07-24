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
    	padding: 0.625em 0.5em;	
    }
    
    .button span > span{
    	text-shadow: 1px 1px 0 #67A854;
    }
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
   ```
