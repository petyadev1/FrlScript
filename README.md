# FrlScript
The fastest &amp; easy learnable programming language made by the Followrel team. I'll share the example files here.

<div class="block" id="start">
  <h1>Getting started</h1>
<p>First, download the FrlScript shell <a href="/source/FrlScript.exe" download>here</a>. <br>
You can save & import your <code>.frl</code> script with</p>
  <code>RUN("yourcode.frl")</code>
  <p>Please note that the script and the app should be at the same directory to make it work. You can also define the path inside the brackets.</p>
  <p>When FrlScript finishes executing your code, it will drop you a 0.</p>
  </div>
  <div class="block" id="start">
  <h1>Variables</h1>
<p>So like every language, there are variables in FrlScript. To create one use</p>
  <code>VAR lol = "Hello World" #For strings</code><br><br>
    <code>VAR lol = 1 #For integers</code><br><br>
    <code>VAR lol = true/false #For booleans</code>
  
  <p>You can replace lol with your variable name. It can be anything!</p>
  </div>
  <div class="block" id="start">
  <h1>Logic operations</h1>
<p>What if I want a code that prints "eat" when the apple variable is "red"? You can use IF/ELSE/ELIF statements</p>
  <code>VAR apple = "red"</code><br><br>
    <code>IF apple == "red" THEN</code><br><br>
  <code>  SAY("eat")</code><br><br>
    <code>END</code><br><br>
    </div>

  
  <div class="block" id="start">
  <h1>For loops</h1>
<p>Alright, but how to count to 10 from 0? I will show you!</p>
  <code>FOR i = 0 TO 11 THEN</code><br><br>
    <code>SAY(i)</code><br><br>
  <code>  i + 1</code><br><br>
    <code>END</code><br><br>
  
  
  <p>As you can see, it will count for us.</p>
    </div>




  <div class="block" id="start">
  <h1>Functions</h1>
<p>You can make functions in FrlScript. You can create a function with these lines:</p>
  <code>FUN lol()</code><br><br>
    <code>SAY("lol")</code><br><br>
  <code>END</code><br><br>
    <code>lol()</code><br><br>
  
  
  <p>It will say "lol" when the function is called.</p>
    </div>
