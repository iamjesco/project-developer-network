# Dev Network 
An online community for local devs. The devs can come together to exchange knowledge, offer services, ask for collabs etc etc.

### Possible names
* Curaco Coders
* Curaco Coders Club
* Curaco Coders Community
* CurCoders Community
* CurCoders

### Must Haves
* Sign up feature (name, email, password)
* Possibility to comment on blogs.
* Slack group
* Facebook Page

### Nice to haves
* Sign up with Facebook
* Sign up with Github
* Dev rating system (by peers and by having a github and/or portfolio)
* Create complete profiles
* Use Gravatar for Profile Images
* Create posts
* Liking each other's posts

# Tables required (needs normalization)

### Profession Table
* Front-End Developer
* Back-End Developer 
* Full-Stack Developer
* Web Designer
* UI/UX Designer
* Software Engineer
* Tester
* Data Analyst
* Wordpress Developer


### User Table
* username (not null)
* email (not null)
* password (not null)
* role (not null) => Profession table
* is_active (not null)
* rating (nice to have) rated by peers or clients.

### User Profile
* First Name (not null)
* Last Name (not null)
* avatar (can be null)
* location (not null)
* about (not null)
* Experience level (beginner, intermediate, senior)
* tech_skills  (nice to have)
* website - personal portfolio website (can be null)
* github - or other vcs (can be null)
* Job status (employed, unemployed, looking)
* Preferred OS (win10, macos, linux)(nice to have)
