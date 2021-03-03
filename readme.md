<span id="index"></span>
## Index
 <a href="#project">Project Idea 💁</a>
1. <a href="#ux">UX 👌</a>
1. <a href="#features">Features 👍</a>
1. <a href="#technologies">Technologies Used 👉</a>
1. <a href="#testing">Testing 🔧</a>
1. <a href="#deployment">Deployment 💥</a>
1. <a href="#credits">Credits 👋</a>



<span id="project"></span>
# The Car Club
## [Code Institute](https://codeinstitute.net)
### Full Stack Web Development Course
### Milestone Project 2 - Interactive Frontend Development
--------------------------------------
![The Car Club](img/Capture.JPG "The Car Club")

The idea to create a car logos memory game *The Car Club* came from my son who explores and learnes car makes while outside on a walk. To make this project more attractive for everyone I was looking for an API which would fetch different logos from manufacturers all over the world for each game.


<span id="ux"></span>
# 1. UX 👌
## 1.1 Strategy 👪

The goal of this project is to provide fun for everyone, to train player's memory and to present all car logos from around the world. Intuitive design and consistent navigation will satisfy user needs.


### User stories

With an agile approach I will be focusing on both external and internal clients.

As user I would like to:

- be able to set difficulty level - also in training mode
- see the time needed and flips made
- see various logos each time to make the game more interesting
- quit the game before time is up
- contact car club to submit feedback
- see Car Club address
- easy nav menu
- responsive design for mobile devices

As a website owner I would like to:

 - display my address on Google maps
 - attract users with intuitive design
 - be accessible via contact form




## 1.2 Scope  ❓

The scope will define what features will be implemented into our project based on user stories. For Minimum Viable Product the following features were identified:

- attractive Welcome screen
- intuitive menu
- how to play instructions
- game itself with three levels of difficulty
- timer and a flips counter
- highest score table
- email function
- Google maps location

To be implemented:
- JSON file with car logo url's
- All car logos gallery with basic data about manufacturer



When moving on up to the scope plane, we then ask the question what features based on the information from the strategy (in other words, based on our business goals and our objectives and the idea and the reason behind the product's existences) do we want to include in our design?
What's on the table and what's not, at least for now?
Remember, you can go live with what's called a Minimum Viable Product, an MVP.
And a Minimum Viable Product will contain the essential features that allow the thing that you're building to function.
You may have desirable features that you really want to put in there, but you may not have the time, the skill set, or the resources to do it at that particular stage.

***And the output of that may be the information that gives you enough to determine the scope at the next plane.
You further refine that into the functional specification.



## 1.3 Structure 🚧

Following the user stories I decided to conduct a research on a similar websites to identify suitable architecture and easy navigation for my project. This resulted in consistent simple navbar on top and footer providing requested functions. The content was divided into four main pages: 'Home' page with option to place an order, 'About Us' page introducing the restaurant, 'Menu' page with the meals and prices and 'Contact Us' with contact details.

All content needed to be simple for quick loading and containg nice hero picture or animation engaging with customers and make them browse further. As I was open to any ideas the project started by searching through dozens of pictures. After a while I choosed this lovely picture of [Burger](https://www.pexels.com/photo/hamburger-with-egg-and-vegetable-1251198/). While working on this project I kept checking other webs and changed this idea to more appealing animation.
New challenge to learn was to create a design with wireframing programmes. I came accross [Balsamiq Wireframes](https://balsamiq.com/wireframes/) but I didn't like its sketch based approach so I sticked with [Figma](http://www.figma.com). Instant results in Figma are realistic what helped me while selecting ideal color scheme for my project. Hovewer, after a conversation on Slack with a developers community I believe I will be also using pen & paper on future projects.

Throughout various stages of my project development I changed the company name, logo, hero image and content of pages but I was focusing to stick with initial purpose, main aims and user stories.

So moving then from the scope to the structure, you then start thinking about how our information is structured, how it's logically grouped, the features, the elements, the data, the information.
Remember, a user is only visiting your site for some kind of content. They're looking for some kind of content.

***And then moving on up, getting more concrete, we focus on interaction design.
Interaction design is concerned with consistency of elements and consistency of relationships, the consistency of the relationships of the information discovered and uncovered in the informational design aspect.
It's also concerned with learnability, if something is learnable. Is it intuitive?
And what intuitive means is first-time learning.
Can a user understand and comfortably navigate through a system upon seeing it for the first time?

## 1.4 Skeleton


## Figma Wireframes
### Desktop
![Martin's on Desktop](/img/Figma-desktop.JPG "Martin's on Desktop")

### Tablet
![Martin's on Tablet](/img/figma-tablet.JPG "Martin's on Tablet")

### Mobile
![Martin's on Mobile](/img/figma-mobile.JPG "Martin's on Mobile")

Beyond the structure, we have the skeleton.
Things are getting more defined now.
We're starting to create mock-ups, whether they're on paper or using tools to create prototypes.
So it's concerned with how the information should be implemented.
How will the user navigate through the information and the features?
How will the content relate to each other? What relationships will the content have?
What has priority? What has top priority? What has lower priority?
And based on those priorities, where do we position the content?
How do we navigate to those higher and lower priorities?

***Then moving up to the skeleton, we're concerned with interface design.
That may be prototyping; developing paper-based prototypes or tool based prototypes.
We also start looking at the navigation design.
Where will the placement of a navigation be? What is the order of the navigation, the hierarchy, the priorities? Where is it going to take us?
The information design becomes much more defined at this point. That's the arrangements of the elements that contain that information

## 1.5 Surface

At the beginning I identified color scheme using Adobe Colors https://color.adobe.com/create/image , however I sticked with BS4 colors later as I was happy with the results.

Finally, at the level of the surface, we ask the question what will the product actually look like?
What colors?
What typography are we going to put in place?
What images? What design elements?
What animations, if any? What transitions?
What other effects are going to be in place?
In other words, what will the final product look like?

***And finally, the tasks at the surface level are what the user can do.
How they can interact, what effects are there, what they can click, where they can go to, and also the final version of the information that appears on the screen.


<a href="#index">back to top ☝️</a>
<span id="features"></span>
# 2. Features 👍
## 2.1 Navbar 🏄

- Consistent and responsive navbar on all pages to make the navigation simple. It contains links to all pages and a dropdown menu for faster navigation on About Us page. Underlining links and a rotating logo with restaurant name to enhance design. This can be also used as home page link.

## 2.2 Footer ⚽

- First section of footer with a subscribe button. New window pops up on click where users can enter their email address.

- Second section contains social media icons with cool shaky effect on hover.

- Third section provide additional links to make the navigation even easier and a link to job a portal where the vacancies are advertised.

- Copyright section at the bottom is closing the footer.

## 2.3 Home page 🎪

The 'Home' - index page contains nice backround animation of two pictures and a Welcome greeting and Order button which slides in on opening the page. Welcome greeting has a shaddow for improved readability.

## 2.4 About Us page 👫

The 'About Us' page is divided into three sections each with different background. The first one describes the core elements and principles of a fine dining restaurant.
The middle section presents the staff with pictures and brief description. In both sections pictures zoom in on hover.
The last section is a carousel gallery which shows the interior, food preparation and products.

## 2.5 Menu page 📑

The 'Menu' page contains meals available in restaurant and the prices. Proffesional look was achieved using selelcted fonts and a transparent background.

## 2.6 Contact Us page 📧

The 'Contact Us' page has a detailed information - a phone number,email, address and opening hours. This is followed by a Google map window with restaurant location.
Page also contains Contact us form with required fields and a simple email verification.
The Contact Us form changes to a booking form when booking checkbox is selected. Date and time inputs appear and subject field is removed.

## 2.7 Opportunities for additional features 💰

The following ideas were identified:

- order food for pick up or delivery within the webpage

- recipes / chef's blog

- interactive map including directions from certain location to a restaurant

- section with reviews

These features will need more time and might be implemented later while progressing through the course and learning new skills.

<a href="#index">back to top ☝️</a>
<span id="technologies"></span>
# 3. Used technologies 🔌
## 3.1 Languages 📢

- HTML/HTML5
provides the basic structure of sites

- CSS
provides colors, layouts and fonts for HTML elements

- JavaScript
programming language which enables interactive web pages

## 3.2 Frameworks ➿

- Bootstrap 4
great tool which allows for a quick and responsive design. Bootstrap was used to design navbar, footer.
About Us and Contact Us pages demonstrate the use of its Flex / Grid systems. 

## 3.3 IDE's, Hosting, Frameworks and Image editing. 💻

-  Visual Studio Code - README.md and all code was written in VS Code.

- Git with GitBash - used for version control.

- GitHub - hosting service to save the project in a repository.

- Figma - frameworks.

- GIMP - picture editor.

-TinyPNG.com - used to compress png images.

<a href="#index">back to top ☝️</a>
<span id="testing"></span>
# 4. Testing 💉
## 4.1 Testing tools 💊

- iPad (4th Generation)
 Final results for medium screens and functions were checked on iPad device.

 - OnePlus 6T
Final results for smallest screen width and functions were checked on OnePlus 6T device.

## 4.2 Online tools 🏃

Chrome DevTools - used to see responsive and mobile design previews, applying and optimising CSS rules and targeting HTML elements and their behaviour.

HTML code was checked in W3C validator - https://validator.w3.org/ .
CSS code was checked in W3C validator -  https://jigsaw.w3.org/css-validator/ .
JS code was checked in BeautifyTools - http://beautifytools.com/javascript-validator.php .

## 4.3 Testing User Stories 📉

Following checks were caried out to see if all requirements were met.


- Providing all relevant information - our products, store location and opening time:
    - Our products are presented on a Menu page and location and opening hours are displayed on Contact US page.

- Good looking home page with easy navigation and direct option to order:
    - Welcome text animation and background animation and order button on Home page gives great result. Consistent navbar enables for easy navigation.

- Access throught website for a feedback:
    - Contact Us form implemented on Contact Us page.

- Access web on mobile device:
    - Responsive design was implemented and succesfuly tested.
    
- What meals are available:
    - Menu page added along with prices.
    Page was carefully designed to attract customers.

- How can I apply here:
    - Careers link placed in footer at common location.

- Facebook and Twitter logos:
    - Facebook, Twitter and Instagram with active links in Footer section created.

- Booking feature:
    - Booking available through interactive Contact Us form.

## 4.4 Bugs and issues 🐛

An issue had been identified with responsive design on iPad pro where menu.html page was only taking half of the screen height. This was resolved using VH units in CSS stylesheet.

<a href="#index">back to top ☝️</a>
<span id="deployment"></span>
# 5. Deployment 🌀

I developed this project in VS Code. Code was pushed using GitBash into GitHub repository in my account. This process is described below:

1. Instal VS Code and Git on your computer.
1. Set up a GitHub account create a new repository.
1. Open GitBash and change the current directory to your local project.
1. Use *$ git init -b main* to initialize this directory as your main branch.
1. Code can now be written in VS Code. Changes must be saved before commiting to repository.
1. Use *$ git add .* command to add all files into repository. Files can also be added separately by specifying their names in *git add* command. Files and locations to be ignored can be specified in .gitignore file. 
1. Use *$ git commit -m "First commit"* to commit changes into the repository.
1. Find and copy your GitHub repository URL. This can be found in GitHub repository's 'Quick Setup Page'.
1. Use *$ git remote add origin 'remote repository URL'* to add the URL to your remote repository. This can be verified using *git remote -v* command.
1. Command *$ git add .* must be used again to add files which will be later commited.
1. Use *$ git commit -m " 'what has been done or changed comment here' "* to commit changes to your local repository.
1. Use *$ git push origin main* to push your commits into GitHub repository.
1. Code needs to be commited and pushed regularly. This allows for version control.
1. You can use GitHub to host your website. In GitHub settings, scroll down to GutHub Pages. Select 'Master branch' in drop-down 'Source' menu. This display your website url.

This is not the only way how you can work using local repository. You might find more suitable approach using GitPod or VS Code Git features. I would suggest to search for Git on Slack or Google. There are also tutorials available on YouTube.

This code can be cloned or downloaded. Deployed version of this project is exactly the same as devolper version. This is located in master branch.

<a href="#index">back to top ☝️</a>
<span id="credits"></span>
# 6. Credits 💳
## 6.1 Code Snippets 🧬

- Navigation bar using BS4 template.
    - https://getbootstrap.com/docs/4.0/components/navbar/

- Footer using MDBootstrapcom template.
    - https://mdbootstrap.com/docs/jquery/navigation/footer/

- Subscribe form using w3school.com template.
    - https://www.w3schools.com/howto/howto_js_popup_form.asp

- Gallery carousel using BS4 template.
    - https://getbootstrap.com/docs/4.0/components/carousel/

## 6.2 Media 🎥

-   Logo was created using template at https://www.freelogodesign.org/ .

-   Pexel pictures from https://www.pexels.com/ and https://unsplash.com/ . Authors: Valeria Boltneva, Lucio Panerai, cottonbro, ELEVATE, Andrea Piacquadio, Taryn Elliott, Ketut Subiyanto, Dana Tentis, Pixabay, Gonzalo Guzman, Sanket Sawant, Thimo van Leeuwen.
More pictures were found on https://pxhere.com/ . Icons were downloaded from https://www.pinterest.ie/ . Most pictures and logos were edited and resized.

- Fonts in project are sourced form google fonts.
    - https://fonts.google.com/

- Map in Contact Us is based on Google Maps.
    https://developers.google.com/maps/documentation/javascript/adding-a-google-map

## 6.3 Other references ✌️

This section points to the sites where I found other ideas and help.

- Navbar logo animation.
    - https://stackoverflow.com/questions/16771225/css3-rotate-animation

- Navbar link underlining animation.
    - https://tobiasahlin.com/blog/css-trick-animating-link-underlines

- Shaking social icons.
    - https://www.w3schools.com/howto/howto_css_shake_image.asp

- Footer copyright.
    - https://mdbootstrap.com/docs/jquery/navigation/footer/

- Subcribe form position.
    - https://stackoverflow.com/questions/4463308/position-absolute-div-in-center-of-screen-view
    - https://stackoverflow.com/questions/2005954/center-a-positionfixed-element
    - https://caniuse.com/transforms2d

- Welcome text animation with a css help courtesy of my classmate Miranda.
    - https://github.com/mkthewlis
    - https://css-tricks.com/a-new-way-to-delay-keyframes-animations/

- Back to top button.
    - https://www.w3schools.com/howto/howto_js_scroll_to_top.asp

- Image zoom animation.
    - https://www.w3schools.com/howto/howto_css_zoom_hover.asp

- Transparent forms.
    - https://www.youtube.com/watch?v=OB-75ysZhfY

- How to change calendar and time icon in date/time input.
    - https://www.codegrepper.com/code-examples/css/input+date+icon+color+change

## 6.4 Acknowledgements 🙏

I would like to thank:

- Seun Owonikoko - my mentor, for her guidance and encouragement throughout this project.

- Code Institute staff for excellent work.

- Slack community who helped with some issues and kept me in a good mood every day - especially Jim Morel (@jim.lynx), Simen Daehlin (@Eventyret_mentor), Bim Williams (@Mr_Bim_alumni), Eamonn Smyth (@Eamonn_lead), Kristian Andersen (@kristian andersen)

For any issues related to this project please email me on martinusko@gmail.com
<a href="#index">back to top ☝️</a>


Live project website can be accesed [here](https://martin-itt.github.io/Martin-s-Grill/index.html).

Repository for this project can be accesed [here](https://github.com/Martin-ITT/Martin-s-Grill).
