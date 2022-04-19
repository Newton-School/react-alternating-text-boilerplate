# Alternating character


We have an input with id="input-text" and a div with id="output-holder".

What we need to implement is, whenever we type in input, for each character
we display a span inside <code>#output-holder</code> div but each odd indexed character 
has fontSize 32px and even-indexed character has fontSize 16px.

Example, we type :- "01234" in input.
Inside <code>#output-holder</code> div <br/>
&lt;span>0&lt;/span> // fontSize: 16px  <br/>
&lt;span>1&lt;/span> // fontSize: 32px <br/>
&lt;span>2&lt;/span> // fontSize: 16px <br/>
&lt;span>3&lt;/span> // fontSize: 32px <br/>
&lt;span>4&lt;/span> // fontSize: 16px <br/>

