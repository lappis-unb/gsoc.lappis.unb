---
name: Security - Implement a logging dashboard for users on Brasil Participativo platform 
deliverables: 'A fully functional, open-source logging dashboard integrated into the Brazil Participativo (BP) ecosystem.'
skill: 'Ruby on Rails, PostgreSQL, JavaScript'
size: "175 hours"
complexity: 'intermediate'
mentors: 
  - telegram_username: ntyamba_kassongo
    github_username: roddas
    email: roddas360@gmail.com
    name: Rodolfo Cabral Neves
    photo: rodolfo.jpg

  - telegram_username: MaiconMares
    github_username: MaiconMares
    email: maiconmaresunb@gmail.com
    name:  Maicon Lucas Mares
    photo: maicon.jpg
---
One of the key security improvements for the Brasil Participativo platform is enabling users to track their authentication history and detect possible bruteforce or dictionary attacks against their accounts. Providing users with a logging dashboard will enhance transparency, security, and control over their access data. 
 
The task consists of three main components: 

- Implement a backend to store authentication logs, including successful logins, failed attempts, and detected dictionary attacks. The logs should also track the IP address, device, and browser or User-Agent used for each authentication attempt to track geolocation. 
- Creating a user-friendly interface where users can view their login history, filter by event type and date, and receive security alerts. 
- Integrating notification mechanisms to inform users of suspicious login activities via in-site messages or email alerts. 

Additional features may include exporting logs in CSV/JSON format and integrating with security modules to analyze attack patterns. This project will empower users with greater control over their account security while strengthening trust in the Brasil Participativo platform. 



<a href="https://gitlab.com/lappis-unb/decidimbr/">Gitlab Repository</a>
