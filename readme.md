# The Majors
[The Majors Project](https://richard-l4.github.io/the-majors/)
 In the world of Golf there are four 'Major' tournaments each year that every golfer who is eligible to compete in wants to win. These are the tournaments that a professional golfer's success is judged by the number of major's they have won. The image below is of the 18th hole at The Royal and Ancient Club of St Andrews Scotland. St Andrews is widely regarded as 'the home of golf', this is the place where of all the venues where the Open championship is held a player most wants to win.
![Images of front page of project on all device sizes](/assets/images/Screenshot%202024-11-15%20211628.png)

## Introduction
- I wanted to create a website for anyone who may have an interest in golf. Someone who may have seen a small amount on TV or radio and have an interest to know a little bit about the sport, an overview. 
- It is designed to provide a very base oversight of the big championships that are held each year, where they are held, and the dates.
- A brief history of the two golfers who are widely acknowledged as the founding fathers of the game.
- The trophy itself that goes to the player who wins the tournament and is introduced as "The champion golfer of the year and the winner of the Gold Medal". 

## User Experience
- My aim was to create a clean, crisp front end website that is easy to use, presents the information in a short, concise manner.
- On all pages the user can easily navigate to any part of the site they want to.
- I was keen that even on a small screen the information is presented well, it's not 'overpowering' with too many colours, images and text all in a small space obscuring the users view.
- As a user friendly design users will feel comfortable to return to the site time and time again.
[Back to the top](#the-majors)
## Design
- I initally used Balsamiq to create a skeleton idea for each page of the site.
- This wireframe is of the "Home" index.html page.
- ![New Wireframe1](/assets/images/New%20Wireframe%201.png)
- This wireframe is of the "History" history.html page.
- ![New Wireframe2](/assets/images/New%20Wireframe%202.png)
- This wireframe is of the "Championships" championships.html page.
- ![New Wireframe3](/assets/images/New%20Wireframe%203.png)
- This wireframe is of the "Enquiry" enquiry.html page.
- ![New Wireframe4](/assets/images/New%20Wireframe%204.png)
- This wireframe is of the "Success" success.html page.
- ![New Wireframe5](/assets/images/New%20Wireframe%205.png)
[Back to the top](#the-majors)
## Content
Here is a list of all the content in the project with detailed descriptions as to what has been done and why.
- Nav bar
    - I was very keen that the navigation bar would not be an actual bar as from Bootstrap but buttons or tabs that are fixed to the header section thus making it easy to navigate throughout the site aiding to the user experience. As the tabs would be visible at all times over the top the image it would look much better than a solid bar and not interfere with any of the image as the page is scrolled down.
- In the nav bar image below are the main colours that have been used throughout the site.
    - Solid Gray
    - Gold
    - rgb(89, 128, 150)
    - rgb(201, 201, 233)
    - #00509e
- Typeography
   - 'Dancing Script'
   - I was keen for the Home page that there was a simple message stating straight away what the website is about using a font style that reflexed the backdrop of the image and what the image represents. The Old Course is in the ancient cathedral city of St Andrews Fife in Scotland which I felt warranted an old fashioned style of writting, caligraphy and 'Dancing Script' fitted that perfectly.
   
![nav bar](/assets/images/Screenshot%202024-11-18%20113544.png)
- Logo
    -  The logo is just a simple design from getty images of a golf ball on a tee peg avoiding the use of any brand naming such as Titleist, Taylor Made etc. It occupies an otherwise redundant part of the screen that would look empty otherwise bringing a sense of balance at first sight.
    
 ![logo](/assets/images/Screenshot%202024-11-18%20113610.png)
- Favicon Icon
   - The favicon icon is of Jack Nicklaus 
   ![Jack Nicklaus](/assets/images/apple-touch-icon.png)

- Championship page content
    -  Four clear, nicely centered images giving the user an instant impression of the four major championships with a short dialogue under each stating when they are held and in the case of The Masters, where (as it is always the same venue).

 ![championship](/assets/images/Screenshot%202024-11-18%20113632.png)
- History page content
    -  The same concept as the Championship page of balanced clear information. The image on the left of the person most famous for winning the tournament in the pioneer days and setting in place the legacy of the event.
    -  The middle image, the trophy itself. Not being held by any champion, but as it sits in it's trophy case with a little information as to it's construction and history.

 ![history](/assets/images/Screenshot%202024-11-18%20113713.png)
- Enquiry page content
    -  The site at present is not designed to get the user in contact with any organization in particular, it just to allow anyone who would like more information a simple, easy method of making contact for anything they would like to know. Just name and email address so they can be responded to, without being overbearing and asking for any more personal details which at this stage I felt could be seen as intrusive.

 ![enquiry](/assets/images/Screenshot%202024-11-18%20113745.png)
- Success page conent
    -  From my own personal experiences on many websites, it is always reasurring to get instant feedback that the message / commitment that you have just made has been successful.
    -  The use of the two images is to give the page a little bit of extra colour and life, being the same image on both sides, here I feel works well to balance the page.
    -  The choice of image is as the golfers in the picture are legends of the game: Jack Niklaus the greatest of all time, Tiger Woods the greatest of the modern era, with Rory Mc Ilroy the greatest modern golfer (post year 2000) that the United Kingdom has produced and Georgia Hall the the most successful female golfer of the modern era from the United Kingdom and Lee Trevino who is a long time friend and rival of Jack Nicklaus and a great ambassador in general.

 ![success](/assets/images/Screenshot%202024-11-18%20113840.png)
[Back to the top](#the-majors)
## Development 
- During the project my ideas changed several times as to how to structure it and the conent and styling to use. Below are challenges I faced and the reasons as to the decisions that were made.
    - Being my first solo project, I was keen to reinforce the principal teachings from the three walkthrough projects.
    - The main issue I had several times, was getting the concept idea of what I wanted to do to appear as I wanted. This meant having to look back over previous lessons many times to be able to apply the techniques and syntax to my own personal design.
    - The first big problem and eventual 'penny drop' moment I had was with Bootstrap containers. I had spent all day trying to get what I thought to be a good "GRID" that would be highly responsive to work correctly with no success. Eventually, I finally realised it was a CONTAINER not a GRID that I needed, and with a bit of trial and error was able to get the desired outcome I wanted.
    - My second challenge was during testing. I noticed that the links on the navigation bar were just the words themselves, which I thought looked good against the backdrop of the image. However, when I checked the Enquiry page it was clear that they were obscured the form labels. After a lot of trial and error of many things, again, I finally remembered that you can add a background to the tabs. Once I had a rough version of these implace, it was just a case of the styling to get all the colours to 'sit' / sync well together.
    - My final issue was raised during validation testing. HTML validate picked up that there was an illegal space in the image links to some images. This took some research on Google to discover that the issue of the space (which couldn't be ommitted otherwise the image would not load) could be resolved with a '20%' syntax to substitute for the 'space'.
[Back to the top](#the-majors) 
## Features
- I designed the site to have individual pages to create a cleaner, clearer user experience including a separate "Enquiry" button taken from Bootstrap and then modified and styled to suit the style of the site that is situated slightly away from the main menu tabs.
    - The Enquiry tab itself changes colour on hover to gold. This along with the tab that is highlighted to indicate to the user which page they are currently on was chosen as it is the 'gold medal' that the players are competing for, and I thought the colour contrast worked well on all pages to distinguish location.
- The "Enquiry" page has a custom button with a hover feature to reassure the user that that is how to submit their details and the message they wish to send. This button is just a simple hover design to aid the user with a colour that I thought works well.
- I created a "success" page to give instant confirmation to the user that their message has been successfully submitted, with a link to take the user back to any part of the site they would like to go to.
[Back to the top](#the-majors)

## Future
In the future I would like to add more pages, giving far more detail of the game of golf and it's history, it's champions, both male and female with video clips of the very best at their best with a comprehensive frequently asked questions section.
[Back to the top](#the-majors)
## Technology Used
- HTML
- CSS
- [HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)
- Lighthouse.
[Back to the top](#the-majors)
## Testing
- I used  dev tools and inspect on the preview page to test at first point how the project looked on all screen sizes as a first stage.
- I later tested the site for usability on my own personal phone as well as my own I pad to simulate different screen sizes in a 'real world' environment.
- As an added measure of testing I sent a link of the GitHub site to a friend who is a Developer so he could give me feedback on how he found the site from a user and profession perspective.
- Finally, I connect my laptop to a 2nd screen to see how the site performs on a large screen.
[Back to the top](#the-majors)
## Validation
- I used HTML and CSS validate.
- HTML validate
   - Home (index) page
 ![Home](/assets/images/Screenshot%202024-11-19%20153009.png)
   - Championships page
 ![Championships](/assets/images/Screenshot%202024-11-19%20152840.png)
   - History page
 ![History](/assets/images/Screenshot%202024-11-19%20152713.png)
   - Enquiry page
 ![Enquiry](/assets/images/Screenshot%202024-11-19%20152750.png)
   - Success page
 ![success](/assets/images/Screenshot%202024-11-19%20152930.png)
 - CSS Validate
 ![CSS](/assets/images/Screenshot%202024-11-16%20135305.png)

- Lighthouse assements
    - Home page
 ![Home](/assets/images/Screenshot%202024-11-16%20113200.png)
    - Championships page
 ![Championships](/assets/images/Screenshot%202024-11-16%20113256.png)
    - History page
 ![History](/assets/images/Screenshot%202024-11-16%20113340.png)
    - Enquiry page
 ![Enquiry](/assets/images/Screenshot%202024-11-16%20113518.png)
    - Success page
 ![success](/assets/images/Screenshot%202024-11-16%20113518.png)
## Deployment
- To deploy my project I used [GitHub](https://github.com/) pages by committing and pushing the project from Gitpod to GitHub pages.

## Credits
- During this project I used [Bootstrap](https://getbootstrap.com/) to provide several code blocks as a base template.
- All of the images used have come from [getty images](https://www.gettyimages.co.uk/). 

[Back to the top](#the-majors)


