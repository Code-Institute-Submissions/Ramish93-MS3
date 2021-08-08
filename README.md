 ![Image of website landing page](/imagesmd/website.png?raw=true "Title")
# CV Producer
## project name and summry of concept
* As i am learning new technologies with the course it getting easier to use those technologies and make something useful with them on the web. so this project is a reflection of that. this is a simple site that takes user data from input fields provided and then save it in MongoDB with is a data-base and then on user commands it edits delets or updated that data user already inserted.
## view live website [here.](https://ramish93.github.io/HealthyEarth/)
---
## Table of Content:
- [Overview](#overview)
- [Description](#description)
- [Ux](#ux)
- [User Stories](#user-stories)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Bugs and fixes](#Bugs-and-fixes)
- [Deployment](#deployment)
- [Credits](#credits)

## __Overview__:
I designed this website in three pages with same navigation, connect with us and footer section to show consistancy to user and so that they can move around and find register and login information not matter which page they are on.
A vast increase in technology is pushing us all to make new thing and create from what we have.
The goal of web-app is to generate a resume with easeily inputting data into fields and then user are able to perform CURD functionality on it so With the intuative design and easy register user would appriciate a simple easy to navigate but effective design.
## __Description__:
* it is a resume producing web-app that is intended to be accessible on all devices. My goal in this project was to avoid the overinfomation, and to create a good and positive user-experience with ease of user and navigation that will in future boost the company's image and business goals.
---
## UX
### __Strategy__
The idea behind this website is to make user of the technologies learnt throughout the course into making something useful for users and simple. As tremendous increase in technogy it is imparitive to learn new tech and then utilize it into small projects in order to learn them effectivly.
#### Website Goals:
* The basic goal of this web-app is to make a platform for users that is easy to navigate and easy to use and then input basic info about themselves which will be saved in data-base and they are then able to perform CURD functionality on it.
* My target audiance is unemployed people. with this easy to use design it less burdun on user who are already unemployed to create a new resume, with a few simple steps.

#### User goals are:
* We all love to use technology that is less complicated to interact with and more efficient in its ways.
* A simple yet effictive interface can attract users attention and clear area with placeholders make it easier to navigate and interact. 
* A clear fixed navbar is there to make sure that a user if gets lost they can go to desired place with one click.
* All these features mentioned above are included in the project alonge with ability to save data into a data-base and read, update, create and delete it. 

This website would be great in acheiving these goals mentioned above because:

* It would provide a platform for users to go and make their cv's.
* Helping them with easy navigation to register, login, log-out.
* Paricipents will be able to perform CURD functionality on their data.
* A clean sophisticated landing page which is easy to navigate can boost a user and take less time to get the job done.

#### Developement and Bussiness goals:
* A website created to help people make their resume in small easy steps.
* A website created with HTML5, CSS3 and materalizecss framework which is exciting and motivating to look at.
* I am as a developer happy and excited to make it a part of my work port-folio.
* In future seeing the popularity of this project i can think of making it into an web-app that had more functionality in it like choosing the font and choosing between different CV templates.

#### User Stories:
1. As mentioned in the project requirments that this project is more to demonstrate that students are able to use data-bases and perform CURD functionality so my focus is same, therefor there is not any images just sutiable text and placeholder that are easy to navigate.
2. I would like to have intuative design in navigation so i can surf the website easily so my website is easy to navigate with a nav-bar with clear discription of where it takes me materialize did a good job in providing that.
3. As a new user i would like to have all the necessary information infront of me so i don't waste my time looking for what i don't need so the Website has all necessity information on front page.
4. When i see and like the webiste next step would be stating to put in data for resume and this is achived by a form element in the front page.
5. I would like to have options to log-in logout register when i'm on first page for a not-registed user only log-in, register and home page is availabe.
6. I would like to register quick so to make the process easy the top-right button of sign up seprate log-in and register page that will take user to that page.
7. The goal of website is to make user participate in making a CV so With the intuative design and easy sign-up user would feel great after signing up and taking part in it.
8. I would like to contact who made the Website if i have any questions or it i want to build something with it and for that there would be a contact us information in footer.

### **Scope**:
This website take approach of MVP (Minimal VIable Product) method which I considered a good for the following reasons:
* It brings out the basic layout of the website and gives awareness to user how the website is going to look like.
* It gives me an opportunity to see my design taking a beautiful shape and improve it where necessary.
* Includes relevent and defining icons to make webpage look more exciting and fullfilling and easy to navigate.
* Testimonials of pervious users to boost the confidence of first time user and to give them a boost that they are at the right web-app.
* Email address in footer so that user can contact if they want any other information or if they want to build on this project.
### **Structure**:
I designed this website in four pages with same navigation and footer section to show consistancy to user and so that they can move around and find register and contact information not matter which page they are on.
All pages have icons and style that fits perfectly with the purpose of the page. and use of icon enhances user experience. 
There is a base templated which is extended onto all pages with jinja formatting language that makes the templating very easy.
All pages follow same color theme and almost same design to give user a consistency and ease of use.
### **Skeleton**:
The website is divided into four pages first with information about the web-app and text, icons and placeholders to make is easy to navigate. then there are login and register pages which are seprate, a click on the links in navbar will take user to those pages. then user will be able to see the data they have input into a cv format.
 The Wireframes are representation of project's final look.
### **Surface**:
I wanted to make first-time user see what this web-app is about without reading content and i achived it by using relevent icons and placeholder text. it would be very easy to see what this web-app is about and how to use it. The use of colors was decided inorder with the color of all pages gives a relevence and consistency to the web-app and makes user in control.
#### Typography:
* I didn't use any font as the web-app is more focused on use of data-base, flask and heroku and with the standard font the desired result was being produced.
* Any images were not included for the same reason.
### **Features**:
 __Navbar:__ 
 * Navbar is created in dark blue color and nav-links with white to give a clear view to user. Navbar is not fixed to let user explore the full height of website and not getting diturbed by fixed stuck navbar.

 __Home Page:__ 
 * After registering or logging in Home page has a Form element with placeholders that gives a full idea to user what this web-app is about and with full name of website which is self-discriptive. i have made 3 different pages apart from home page so user gets directed to relevent page when they navigate through nav-bar. Then i have feedback section from amazing users and at last the footer with contact via email and copyright information.
 __Register Page:__
 * In Register page i use almost same layout to give consistancy to user and more make them clustered with entirely different dynamics of new page. i used form for registration that will speak with data-base and save the username and passwork(hashed and salted) in data-base.
 __login page:__
 * This is a page for users who are already registered and want to login it has almost same structure and and after loging in user will be directed to the home page. the log-out functionality is a function which will remove the session cookie and log user out.
 * In Footer i also added email address that its easy for user to navitage on all pages.
 ### __Features Left to Implement__:
 * I would love to improve this project with font-styling for user so they can easily make cv in desired fonts.
 * i would like to generate templates for users so they can choose between different templated.
### Design Choices:
* __Font:__ As mentioned above the scope of this web-app is ability to use data-base and relevent technologies to i relied on basic font which is quiet elegent and appealing.
 * __Icons:__ the choice of icon is relevent to the input fields accross all pages so it is very easy to see what an input is for.
 * the place holder text made is easy to navigate the form elements on page.
 
 * __Color:__ Color for the website is blue which is color of confidence and strength. To inspire user that is the first step and then they have a bright future ahead.
 
 * __Layout:__ The website in medium screen is centered on all the pages and there is more content on the landing page. i made this design choice because centered view for medium screen is elegent and easy to read. Which , i think, gives it more aesthatic beauty.


### __Technologies Used__:
#### Languages:
- [HTML](https://en.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)
- [MongoDB](https://cloud.mongodb.com/v2/610826ca5d6f3467c1d962ec#metrics/replicaSet/6108290a6c9a7e0e1b38544a/explorer/MS3/user_info/find)
- [flask](https://flask.palletsprojects.com/en/2.0.x/)
- [Materialize](https://materializecss.com/)
- [Heroku](https://id.heroku.com/login)


#### Libraries used:
* Materialize - A mobile-first responsive library used to construct various parts of the project, including the Navbar, Modal Forms.
* FontAwesome - Used frequently for icons used throughout the website
* Miro - used for the creation of wireframes
#### Version Control:
- [Github](https://github.com/) - Used to store the code and use of Github Pages to deploy the website. 
- [Gitpod](https://gitpod.io/) - Used as the version control IDE for writing code and to further commit and push code to Gihub.
#### Other:
- [Code Institute Course Content](https://courses.codeinstitute.net/) - Source of learning code.
- [ChromeDevTools](https://developers.google.com/web/tools/chrome-devtools) - Used frequently to detect any issues/bugs or layout differences.
* [W3Schools](https://www.w3schools.com/) - used as a general resource.
* [StackOverFlow](https://stackoverflow.com/) - used as a general resource for tips or questions.
- [AmIResponsive](http://ami.responsivedesign.is/) - Used to check how the responsiveness of the website looks in different devices- available at the top of this [README](). 
* [Google Mobile Friendly Test](https://search.google.com/test/mobile-friendly) - Used to test all pages on a mobile device
- [Youtube](https://www.youtube.com/) - Used for help in adding a favicon.
- [BBC.com plant based diet](https://www.bbc.com/news/science-environment-49238749) - Used for help adding content for plant based diet.
* [University of Taxes Cancer Center](https://www.mdanderson.org/publications/focused-on-health/5-benefits-of-a-plant-based-diet.h20-1592991.html) - Used for help adding content Healthy and strong lifestyle.
* [Gresy spoon cafe](https://www.greasyspoon.se/) - Used for help adding content and location of where we do meet-ups.
---
### __Bugs and fixes:__
* My hero image was too bright and the text wasn't clear. i was using opacity on image and then is used linear-gradient technology as follow: 

  __background:linear-gradient(
      rgba(0, 0, 0, 0.1),
      rgba(0, 0, 0, 0.1)
    ),
    url("images/cleanearth.jpeg") no-repeat;
    background-position: center;
    overflow: hidden;__

and the image became dark as i wanted it to be.
* My Importance section and Feedback sections were merging into each other in mobile view but on desktop they were as i wanted them to be. I searched online on youtube, StackOverFlow and W3School i checked my Css file 
to fix the bug. The videos and StackOverFlow helped me figure out the problem which was that i gave Importance Container a fixed height which was causing the merging of content.
* My cover-text was mixing with the heading and text of jumbotron in some mobile views and ipad view i added media quries to fix it but its still not fixed in a few mobile views.
* In mobile view my Importance section was centered aligned with alot of padding on right side which was not something i liked so i add no-gutters class and changed the col-10 offset-1 in small screen view to col-12.
* On the meet-up page the hero image took some time to load which was because of the size of the image was too large and causing this delay. The filesize of the downloaded image was over 3900kb so I changed for another image.
* My form was not validating. upon clicking submit button nothing was happening despite of giving it required attribute. upon checking online on [code acadmey form submit](https://www.codecademy.com/courses/learn-html/lessons/html-form-validation/exercises/required) it was my silly mistake of not adding type="submit" to my button.
---
### __Unfixed bugs__:
* On mobile devises the cover-text container is not showing its full text. it is convaying the information it is intended to but the full text if not visible. I tried to fix it in many ways but everytime i ended up disfiguring some other part of that section. I will however, keep on trying to figure it out.
* Social media icons are not responding at different screen widths as i want them to. They change size when viewed on xl-screen and on xs-screens but i would like them in medium size in medium screen size, which i was unable to figure out how to do. Pretty sure its my some silly mistake.
* Website is on its full width on all devices provided by chrome-dev-tools but it came to my attention in last hour that its showing some side left-out space in iphone 11 and above. Since they are not provided by dev-tools so i didn't know about it earlier. here are the screenshots of both Iphone 12Pro Max and Samsung Note10+. Note 10 is 
deploying website as intended but when we zoom out in Iphone 12ProMax it shows a side zoom. i added viewport size in head of my Html but it is not working. This shows the importance of checking website across different devices.
* On Samsung Note 10 Plus:

 ![Image of website on Samsung note 10 plus](/imagesmd/note10.jpeg?raw=true "Title")

* On Iphone 12 Pro Max:

 ![Image of website on Iphone 12 Pro Max](/imagesmd/iphone12.jpeg?raw=true "Title")

 



---
### __Testing__:
* Form and Modal are tested. If we press the submit button without putting any information in fields the response should be 'Please fill out this field'. it was checked acress different Android Mobiles and tablets and Apple Mobile and tablets.
* All the links in across all three pages take the user to desired location and they open in another tab. They also get highlighted and underlined when hovered and they also have different colors than regular text to make user see them with ease.
* The website is tested in __Android__: Samsung Note 3, Note 4, Galexy S8,S9 Moto 4G, Pixel 2 and 2XL, and __Apple__: Iphone 4,5,6,7,8 and X as well as Ipad and Ipad pro.

* To ensure that the website is responsive across all pages i used. [Google Mobile Friendly Test](https://search.google.com/test/mobile-friendly?utm_source=gws&utm_medium=onebox&utm_campaign=suit). And the result is fully responsive.
* Landing page,
 ![mobile friendly page 1](/imagesmd/pagevalidate1.png?raw=true "Title")
* health page:
 ![mobile friendly page 2](/imagesmd/pagevalidate2.png?raw=true "Title")
* Meetup page:
 ![mobile friendly page 3](/imagesmd/pagevalidate3.png?raw=true "Title")
 * For responsiveness across all devices the website [AmIResponsive](http://ami.responsivedesign.is/) is used. And result is.
  ![Amiresponsive result](/imagesmd/amiresponsive.png?raw=true "Title")

* For Html validation W3 Validator was used, click link to see result. [W3 Html validator](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-dd61392f-e80b-4db4-a829-cf89f148345b.ws-eu03.gitpod.io%2Findex.html).
* Css validator was used to validate css, click link to see result. [W3 Css validator](https://jigsaw.w3.org/css-validator/validator)

### Wireframes:
*  Please click the link to download PDF: ![WireFreames](/wireframes/wireframe.pdf?raw=true "Title")
- Landing Page:
 ![Wireframe of page 1](/wireframes/page1.png?raw=true "Title")

- Healthy diet Page:
 ![Wireframe of page 2](/wireframes/page2.png?raw=true "Title")

- Meetup Page:
 ![Wireframe of page 3](/wireframes/page3.png?raw=true "Title")


___
## Deployment
* First a GIthub account was created, I created new repository by clicking the green button saying "new".In this project I used the Code Institute's student templet.
* Click on the green "gitpod" button which is directed to to [Gitpod](https://gitpod.io/)
* Gitpod is a cloud based version control software which is used to write all of the code for this project.
* It was added commited and pushed in the terminal to Github where it is stored in a repository.
* Under "Settings", I scrolled down to Github Pages and selected "Master Branch", to where the page was automated.
* When it was selected, the project was pushed to Github pages and the URL is then displayed and on clicking it it brings to the weblink.
* The code can be run locally by selecting "clone" which provides an URL you can use on your local computer or "download" option where one can download the zip file on your computer.

To work on this project with local IDE like VScode etc:
* Follow this link to [Healthy Earth Healthy Us!](https://ramish93.github.io/HealthyEarth/).
* Under the Repo name choose "Clone or Download".
* Copy URL in HTTP section.
* In your Editor open the terminal and choose the folder you want to save this project in.
* Type git clone and paste that HTTP URL.
* Press enter and a clone of this repo will be created in your machine and you can work on it now.
---

## Credits

### Content
* The text for sections was inspired and edited from the website, [BBC.com plant based diet](https://www.bbc.com/news/science-environment-49238749),
[University of Taxes Cancer Center](https://www.mdanderson.org/publications/focused-on-health/5-benefits-of-a-plant-based-diet.h20-1592991.html), [Gresy spoon cafe](https://www.greasyspoon.se/).

### Media
* The photos in this website were downloaded from Pexels and Unsplash.

### Acknowledgements

* The idea of this project was inspired because of growth in knowledge and responsibility of people to change the environment to help earth heal, to do something themselves with their own hands which will make them feel good
 and to make changes in their life style to live a healthy life. This plat-form is to give 
them a push start and to persue people who already want this change to start it.
* My Mentor, **Nishant Kumar**, for his guidance, help and advising me to understand what kind of design is better for user.
* Tutor Support, for their efforts support, all the time and great atitude.