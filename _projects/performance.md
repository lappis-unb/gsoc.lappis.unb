---
name: Improving the performance of Brasil Participativo Platform
skill: ' intermediate/advanced backend Ruby on Rails. Optional: execute and understand performance logs.'
size: "350 hours (we have the mentors also implementing part of the solution)"
complexity: 'hard/difficult'
mentors: 
  - telegram_username: renatocoral
    github_username: renatocoral
    email: renatocoral@gmail.com
    name: Renato Sampaio
    photo: Renato.jpg

  - telegram_username: VictorJorgeFGA
    github_username: VictorJorgeFGA
    email: victor.eng.unb@gmail.com
    name: Victor Jorge Gonçalves
    photo: Victor.jpg
---
Decidim faces significant performance challenges when operating at scale, as it was originally designed for smaller user groups such as cities, councils, and districts. Despite employing a Redis cache service to enhance performance, numerous page loads still necessitate a substantial number of database requests, sometimes reaching up to 300. Additionally, database response times can become sluggish as the platform experiences growth beyond 1 million users, particularly during periods of high activity involving proposals and votes.

This project aims to address these performance issues by analyzing performance logs and implementing potential solutions. The focus lies on optimizing the application level, with anticipated outcomes including enhancements to the caching strategy, reassessment of database indexes, and refactoring of code logic that may contribute to slowdowns in response times as the platform scales. We will make available logs of the plataform in production environment with performance issues. Also, performance tools are being configured to give more performance data to the participant.