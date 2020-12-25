<img src="/assets/images/profile.png" style="margin: 0;" width="150" height="150">

# Clash Arena

This project, Milestone 1, represents the culmination of knowledge acquired from the User-Centric Front-end portion of the Full Stack Web Develpoer Course with Code Institute.  
The project comprises a static front-end website that displays useful data for the viewer.

**Business Case:**
Clash Arena is a tournament hosting website for casual and competative gamers of popular game titles such as Call of Duty: Warzone, Apex Legends and Fortnite.
The aim of Clash Arena to develop an online community of gamers through promotion of ongoing, organised tournaments and a Discord server (for the purposes of this project, there will only be a link to the main Discord website)  

## UX

**Website UX Goals**

Clash Arena aims to do away with old gamer stereotypes by bringing a new and sleek platform, that makes tournament style competition open to all players.

- Convey the Clash mission statement as quickly as possible (PLAY. COMPETE. WIN).
- Sell the service through tournament's organised by Clash itself, and also user organised tournaments hosted on the Clash platform.
- Target a broad user base.
- Improve user satisfaction.

**User UX Goals**

- Gain access to the websites offers and services with miniml effort.
- Give the user the experience they deserve.
- Reduce the users work load by providing clarity and ease of use.
- Feedback with ease.


### User Story - First Time Visitor

* As a first time user, I want to be able to land on the main page of the website and navigate to all sections easily and smoothly.
* As a first time user, I want to understand within the first 10 seconds what the purpose of the website is.
* As a first time user, I want to access information about the product or service being offered.
* As a first time user, I want to be able to have full website functionality on all devices - mobile, tablet, PC.  
* As a first time user, I want to be able to contact the companies help and/or customer services. 
 
### User Story - Repeat Visitor

* As a repeat user, I want to be able to easily set up my own tournaments.
* As a repeat user, I want to be kept informed about ongoing news and promotions.
* As a repeat user, I want to be able to make new friends to play online with.

### Wireframe

In the initial forming phase I put together this wireframe using Balsamiq Mockups. While the website has maintained the majority of the features, many changes were made along the way. I will try to avoid making such drastic changes in future projects as it caused a lot of delays and changes on the fly during development.

<object data="https://github.com/devgithubs/MS1/blob/master/assets/images/wireframe.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/devgithubs/MS1/blob/master/assets/images/wireframe.pdf">
        <p>The wireframe PDF can be viewed here: <a href="https://github.com/devgithubs/MS1/blob/master/assets/images/wireframe.pdf">Clash Wireframe</a>.</p>
    </embed>
</object>

### Website Architecture - Hierarchy

The Website follows a modern layout comprising a main scroll homepage and navbar that leads to three more pages - Tournaments, Contact and Community, also an inline navbar button links to the Community Discord page. 
All of the pages are linked which makes navigation simple and straightforward.

<img src="/assets/images/hierarchy.PNG" style="margin: 0;" width="500" height="300">

Here we see how the home page looks when viewed on multiple devices: 

<img src="/assets/images/home-page.PNG" style="margin: 0;" width="500" height="300">

Here we see how the contact page looks when viewed on multiple devices:

<img src="/assets/images/contact-page.PNG" style="margin: 0;" width="500" height="300">

Here we see how the tournament page looks when viewed on multiple devices:

<img src="/assets/images/tournament-page.PNG" style="margin: 0;" width="500" height="300">

Here we see how the community page looks when viewed on multiple devices:

<img src="/assets/images/community-page.PNG" style="margin: 0;" width="500" height="300">


## Features

In this section, I go over the different parts of the project as a whole.

As previously mentioned, the Clash website follows a modern design style. 

The color pallette features many dark, neon, and contrasting electric colours that you find on many websites associated with esports such as Twitch where a lot of gamers stream their content.

* **Navigation bar** 

Initially I had designed a logo using free third party software but decided to use just the name _"CLASH"_ in italics in pink against a dark, semi-transparent navbar background.   

The navbar has five inline elements for navigation positioned to the right (end) side of the bar. There are "Home", "Tournament", "Contact", "Community" links and a Discord button. 

* **Hero Image/Callout** 

This part of the home page is probably the most important part of the whole website. The hero image is of a young woman at a gaming arcade, the slogan heading **"PLAY. COMPETE. WIN"** and message CLASH HOSTS TOURNAMENTS FOR COMPETATIVE GAMERS OF ALL SKILL LEVELS overlays the image. 
A "Learn More" button accompanies the message which allows the user to sign up to learn more about the service. The design lets the user immediately know what the serice offering is and a call to action.
Below the scroll is a section called **"What we're about"** which provides further information on the websites features, a button to find out more exists underneath.  
Two further sections exist below that again, a **"What our Player Say"** section with player testimonial and a **"Industry Partner"** section highlighting sponsors.
A footer with all the companies social media links is found at the bottom.

* **Tournaments page**

The Tournament page features another attractive full width and height image. Below that is a Bootstrap card section that contains the current tournaments that players may sign up for.  

* **Contact page**

The contact page features a full screen background image and is overlayed by Clash contact information. A **Sign In** **Sign Up** button cluster draws the user and triggers two seperate modals. One for New users and one for existing.  

* **Community page**

Features more ways in which users can sign up and create bespoke groups and tournaments on the platform. Two buttons prompt the user to find out more.


### Features Left to Implement

A community Discord server & social media.
As is good practice I have made a modal that informs the user that certain parts of the website are still under construction. When the user clicks on any of the buttons in the Tournament & Community pages, a modal pop-up informs the user "website still under construction" and has a button to redirect them to the home page.


## Technologies Used

* Wireframe
    * <a href="https://balsamiq.com/">Balsamiq</a>

* IDE
    * <a href="https://gitpod.io/workspaces/">Gitpod</a>
* Languages
    * <a href="https://en.wikipedia.org/wiki/HTML5">HTML5</a>
    * <a href="https://en.wikipedia.org/wiki/CSS">CSS</a>

* Frameworks/Libraries
    * <a href="https://getbootstrap.com/">Bootstrap</a>
    * <a href="https://fonts.google.com/">Google Fonts - Roboto</a>
    * <a href="https://fontawesome.com/">Font Awesome</a>

* Version Control
    * <a href="https://github.com/">Git</a>

* Media images
    * <a href="https://unsplash.com/">Unsplash</a>


## Testing 

My first method of testing was to check how well the website performed in different browser windows.
The results were very similar across the board and did not notice any major deviation. 

Browser  | Chrome |     FireFox          |    Opera           |  
------------- | ------------- | ------------- | ------------- |
Render  | Good  |   Good            |     Good          |
Response  | Good  |     Good          |    Good           |


* Testing a sample of User Stories

I got a friend who had never seen my website before to test the following user criteria:

_"As a first time user, I want to be able to land on the main page of the website and navigate to all sections easily and smoothly."_

My friend was able to locate all the major areas of the website with ease and did not need to ask any questions related to navigation. 

_As a first time user, I want to be able to have full website functionality on all devices - mobile, tablet, PC._

Again, I asked my friend to try out all the pages and features of the website in the mobile device view in developer tools. The test outcome was positive and there was no issues with this test.  

## Deployment

## Credits

### Content
### Media
### Acknowledgments
--------

