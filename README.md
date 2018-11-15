# Project 0

Web Programming with Python and JavaScript

This is a website for an English course named "Lazy English" which is taught by teacher Sloth (an imaginary person). The website consists of 4 pages: homepage, teacher introduction, course structure and contact page.

All the pages of the website are divided into 2 main part: a navigation bar which has links to all the other pages on top of the page and the main section which has all the content of that page below it.

In the homepage, there is an introduction video of the course. The video is embed by an <iframe> tag and applied Bootstrap's class "embed-responsive" to responds to the change of device size. Next to the video is an unordered list <ul> of questions to define the targeted students of this course. The video and list are placed in a Bootstrap's "row" and will stack vertically in a device with smaller width. Below that is 2 paragraph <p> to shortly describe the course and its results.

In the teacher introduction page (About me), there is an avatar of the teacher and 3 paragraphs <p> for self-introduction. The key words of each paragraphs are bold. The brand is bold in themed color.

In the course structure page, there is a table demonstrating the skills taught in the course and the learning method of each skill.

In the contact page (Get in touch), there are 2 main sections: the contact form and contact details. Bootstrap's grid model is used for layout. The contact details section consists of teacher's email address and phone number and links to the course's social media pages.

This website's stylesheet was written in sass and uses some features of Bootstrap 4. It is fully responsive.