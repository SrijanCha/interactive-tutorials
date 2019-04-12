<!DOCTYPE HTML>
<html>
    
    <head>
    <style>
    .one {
        color: pink;
         text-decoration: none; 
          font-family: helvetica; 
          font-size: 24px;
        }

a:hover{
	color: red;
	text-decoration: underline;
}

    </style>
    
    </head>
  <h1>Link Design</h1>
  
  <p>
    All links are started in HTML by the "a href" command. "href" links to another webpage, which can be specified inline.
    <ul>
      <li>&lt;a href = "#"&gt A link &lt;/a&gt;  </li> 
    </ul>
  <a href = "#"> A link </a><br><br>

  A link by itself is just that - a link. Compared to the rest of the text, it appears blue and underlined. It appears purple instead of blue if you have visited.

Through CSS, you can change the appearance of your link by targeting the “a” element. Common changes are changing the text-color (color), removing the underline (text-decoration), changing font (font-family), and even the size (font-size).
  <br>
  <br>
  
  <ul>
      <li>a {<br>
        color: pink;<br>
        text-decoration: none; <br>
        font-family: helvetica; <br>
        font-size: 24px; <br>
        }  </li> 
    </ul>
  <a class="one" href = "#"> A link </a>
  
  </p>
  <br>



  <h1> States of a link</h1>

  <p>
      Links have states, which describe how they appear in user interactions. The primary kinds are hover, visited, and active.<br><br>
    
    Hover describes when the mouse cursor is on top, or hovering over a link. To change the appearance during the hover, edit the CSS file at the “a” target followed by “:hover”
    
    <ul>
      <li>
        a:hover{<br>
	        Color: red;<br>
	        Text-decoration: underline;<br>
        }<br>

      </li> 
    </ul>
  <a class = "one" href = "#">A link</a>
  </p>


</html>
