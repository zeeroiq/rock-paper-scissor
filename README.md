# rock-paper-scissor
Backend for game ROCK-PAPER-SCISSORS


<div class="semi-bold margin-bottom-20">Rock Paper Scissors API</div><div class="file-problem complete-problem-statement black-333"><h1><strong>[Problem statement]</strong></h1>

<p>&nbsp;</p>

<p>Build a pseudo Backend which plays Rock Paper Scissors with <em>2</em> users.&nbsp;</p>

<p>The rules of the game are as follows:</p>

<ul>
	<li style="">Rock defeats scissors</li>
	<li style="">Paper defeats rock</li>
	<li style="">Scissors defeats paper</li>
	<li style="">It's a Tie if both symbols are same</li>
	<li style="">Score is <em>1</em> for a Win</li>
	<li style="">Score is <em>0</em> for a Tie/Loss</li>
</ul>

<h2><strong>[Minimum requirement]</strong></h2>

<p>— Write a backend in the tech stack mentioned below which exposes an API which returns the necessary response.</p>

<p>— Build a truly random server which returns rock or paper or scissors randomly.&nbsp;</p>

<ul>
	<li style="">A GET Request on /start must send a response READY and a random token.</li>
	<li style="">Each request must send back the server’s move as well as the total Score</li>
	<li style="">A GET Request on /v1/token/rock should return a json containing servers’ move and total score.&nbsp;
	<ul>
		<li style="">Here the token is the token generated in the previous step.</li>
		<li style="">Rock is the user’s move</li>
		<li style="">The response must be Rock/Paper/Scissors alongwith Total Score</li>
	</ul>
	</li>
	<li style="">When anyone reaches a score of 3, the game must end</li>
</ul>

<p><br>
&nbsp;</p>

<h2><strong>[Intermediate]</strong></h2>

<p>— Build an always winning server which returns rock or paper or scissors strategically.&nbsp;</p>

<ul>
	<li style="">A GET Request on /start must send a response READY and a random token.</li>
	<li style="">Each request must send back the server’s move as well as the total Score</li>
	<li style="">A GET Request on /v2/token/rock should return a json containing server’s move and total score.&nbsp;
	<ul>
		<li style="">Here the token is the token generated in the previous step.</li>
		<li style="">Rock is the user’s move</li>
		<li style="">The response must be Paper</li>
	</ul>
	</li>
	<li style="">The game must always end when server wins</li>
</ul>

<p><br>
&nbsp;</p>

<h2><strong>[Advanced]</strong></h2>

<p>— Host the Backend application on a cloud hosting service like AWS/Azure/GCP/Heroku etc. (The link must be active for at least 2 weeks from the date of submission)</p>

<p><br>
&nbsp;</p>

<h2><strong>[Guide]</strong></h2>

<p><strong>Tech Stack - </strong>Spring Boot/Hibernate</p>

<p>Database - Relational database (postgresql, etc) preferred</p>

<p>&nbsp;</p>

<p>You can read more about the game here -&nbsp;</p>

<p><a href="https://en.wikipedia.org/wiki/Rock_paper_scissors" style="" target="_blank">https://en.wikipedia.org/wiki/Rock_paper_scissors</a></p>

<p>&nbsp;</p>