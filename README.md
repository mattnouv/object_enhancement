<i>In this exercise, you’ll refactor some ES5 code into ES2015. Write your code in the sections with a comment to “Write an ES2015 Version”.</i>

  <b>Same keys and values</b>
<br>function createInstructor(firstName, lastName){<br>
  return {<br>
    firstName: firstName,<br>
    lastName: lastName<br>
  }<br>
}

  <b>Same keys and values ES2015</b>
  
/* Write an ES2015 Version */

  <b>Computed Property Names</b><br>
    
var favoriteNumber = 42;<br>

var instructor = {<br>
  firstName: "Colt"<br>
}

instructor[favoriteNumber] = "That is my favorite!<br>
<p><b>Computed Property Names ES2015</b></p>
/* Write an ES2015 Version */<br>
<p><b>Object Methods</b></p>
var instructor = {<br>
  firstName: "Colt",<br>
  sayHi: function(){<br>
    return "Hi!";<br>
  },<br>
  sayBye: function(){<br>
    return this.firstName + " says bye!";<br>
  }<br>
}
<br>
    
   <p><b>Object Methods ES2015</b></p>
/* Write an ES2015 Version */
    <p><b>createAnimal function</b></p>
    <i>Write a function which generates an animal object. The function should accepts 3 arguments:</i><br>
<br>
species: the species of animal (‘cat’, ‘dog’)<br>
verb: a string used to name a function (‘bark’, ‘bleet’)<br>
noise: a string to be printed when above function is called (‘woof’, ‘baaa’)<br>

<br><p>Use one or more of the object enhancements we’ve covered.</p>

const d = createAnimal("dog", "bark", "Woooof!")<br>
// {species: "dog", bark: ƒ}<br>
d.bark()  //"Woooof!"<br>

const s = createAnimal("sheep", "bleet", "BAAAAaaaa")<br>
// {species: "sheep", bleet: ƒ}<br>
s.bleet() //"BAAAAaaaa"<br>
