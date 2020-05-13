# TK-WD2020-PART2

<h1> Notes on the development of this assessment </h1>

<ul>
    <li>Use vanilla JavaScript</li>
    <li>Use the API option to return the data using a JSON object</li>
    <li>Code it so every 5 seconds the columns get a new set of random numbers</li>
    <li>Make sure the new set of numbers that appear every 5 seconds haven’t appeared before</li>
    <li>There’s no need to make this section overly pretty, but make sure it’s responsive</li>
</ul>

<p>This part was a bit tricky because the API is very slow, the response is very late at times, therefore, since there is a 5 seconds delay before a new request (setInterval), when the API sends a response, it ends up gathering all the requests in the queue.</p>
<p>To avoid this I have used an asynchronous function, and instead of asking the api for a random route, I previously chose a random number so that I can request a specific route.</p>

<ol>
    Random facts:
    <li>Numbers</li>
    <li>Trivia</li>
    <li>Year</li>
</ol>