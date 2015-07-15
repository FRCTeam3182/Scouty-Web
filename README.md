# Scouty-Web
A website for storing data and scouting information about other teams

### Technical Info

#### How does this work?
This website is built using a framework known as `Ruby on Rails`. For data persistance, `MongoDB` (a non-sql database) is used. For user login and authentication, a gem (library) known as `Devise` is used. For frontend  development, Bootstrap 3.0 CSS framework is used. 

#### How will this connect with the mobile app?
Since the `MongoDB` database will be running on the team server, the app will be able to access it through either API commands using the website or via direct connection (this will be decided by the development team). The app will store all of its data on the database, and this will allow it to sync with the website, so all changes are seen. 

#### Is it secure?
The website itself is very secure. `Devise` hashes all passwords before storing them in the database and supports cookies and sessions. As for the mobile app, the development team will meet to discuss security design, as the decision above will determine how secure the app will be. 
