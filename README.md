# print-the-first-element-in-the-list-through-javascript

print the first element in the list through javascript
First create a list,

<ul>
      <li>Apple</li>
      <li>Mango</li>
      <li>Strawberry</li>
</ul>

Now create a p tag to display the result

<p id="show"></p>

Now create a script,

<script>
var x = document.getElementsByTagName("li");
document.getElementById("show").innerHTML = x[0].innerHTML;
</script>



//OUTPUT

Apple

//

Thank you for reading the post, i hope you find it useful. Have a great day!
