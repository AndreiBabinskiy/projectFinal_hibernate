# projectFinal_hibernate Application
I have worked with various technologies: Hibernate, Redis, Docker, where there is a relational database MySQL with a schema (country-city, language per country). There is a frequent query for cities that is slowing down. The solution is to move all the frequently accessed data to Redis (an in-memory key-value store).
<h2>Task: Create a project using Hibernate, MySQL, Docker, Redis, p6spy</h2>
<h2>Technology Stack:</h2>
<ol>
  <li>Java: Version 18.0.1 Oracle OpenJDK</li>
  <li>Hibernate: Version 5.6.14</li>
  <li>MySQL: Version 8.0.30</li>
  <li>p6spy: Version 3.9.1</li>
</ol>
<h2>My Result</h2>
<ol>
  <li>Redis: 64 ms</li>
  <li>MySQL: 112 ms</li>
</ol>

