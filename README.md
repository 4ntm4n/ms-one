# FlexGrid Yoga

![FlexGrid on different screen sizes and devices](assets/img/readme/Screenshot%20from%202022-04-18%2011-50-26.png)

 [__Have a look on your own device__](https://4ntm4n.github.io/ms-one/index.html)


## Project outline

>Typical users are interested in getting involved with online-classes and tutorship in yoga.

- __The typical end user wants to:__

  -  know more about site and yoga instructor
  - be able to subscribe to news coming from community regarding techniques and upcoming yoga sessions
  - get a hint about what is expected inside the paid members area
  - be able to sign up and become a full member, attending live- and pre recorded -yoga sessions
  - connect to community on social medias


- __a typical returning user wants to:__
  - sign in to their account and conduct yoga sessions.


>site owner wants to inspire potential end users who wants to learn yoga and market the benefits of yoga and let users connect with her community and sign up to engage in live and pre-recorded yoga sessions.

- __in short, the site owner wants to:__

  - educate new site visitors about herself
  - give breif overview of the benefits of yoga
  - let new users sign up to newsletter to keep them in the loop of what is happening in the community
  - let users know how they can engage in social media.
  - let existing users log in to view the paid-for content.


## Approach

### Design Approach

The design of the website is created with the benefits of yoga in mind. the text should be easy to read and not be distracted by design elements around it. the design features are created to feel relaxed positive and light

__Design features__
- Elements that contain no text are __soft and rounded__.

  - Text areas are __square and light__ to stand out from the rest of the website and enhance readability. 

  - initially the colors are __few and muted__, as you progress down the site __more colors__ are mixed in to keep visitors curious and __enhance positivity__.

  - Elements have a __lot of space__ around them to feel more relaxed. 

  - Elements that have animations are __slow and subtle__ to make elements feel __relaxing__.

__Fonts__

> __'Fredoka One'__ is a round blocky font that is chosen for the headings on the webpage to blend in with the overall design language.

> Paragraghs, buttons, and other small text areas have the font set to __helvetica__ with a fallback of _Arial_ to maximize readability while not being a distraction from the rest of the website. 

__Colors__
> The choice of colors are inspired by different colors of yoga mats. these colors are often pastel, so they have been altered slightly along the way to enhance contrast and readability.

__Animations__
> animations that take place when a user interacts with certain elements on the website are designed to be slightly slower than on an avarage website to induse a relaxing feeling, which in turn connects back to the overall design approach.

___
### Technical Approach

In order to make the website less cluttered and reduce the amount of scrolling the website is built on two main pages. 

1. > __an index page__ <br> 
        the main page, with a single page layout style where the site owner could present herself and the users could get to learn more about her and about yoga. 
2. > __a members page__ <br>
        where existing users can sign in and a new user can choose to sing up and become a full member. 


__Framework__
>This website does not take advantage of any framework. Since this is a small project the it instead takes advantage of CSS3's newly added feature of CSS-grids to create rows for each section. Each section is then made into a flexbox.

>__this approach has 2 main advantages:__
> 1. it removes unnessary code from framwork, which can enhance loading speeds.
> 
> 2. using CSS-grids reduses the amount of divs in the html which makes the syntax more clean and better for screen readers and assistive technologies.

__Responsive design__
> This website is created with a mobile first approach.
>
> Mobile phones usually have less processing power than a tablet, laptop and desktop. By having the CSS load up the mobile design first,  the website renders faster on mobile phones since it can ignore styling that is specified lower down in the style.css document that only applies to larger screens.
> 
>On larger screens, each section takes advantage of the full width of the screen it is being displayed on. But the content inside each section is limited to a width of 1000px. This makes the website look more unified across larger screens and creates a better user experience since the user will have access to all the websites information within 1000px and do not have to pan the head to read.

___

## Website Features

> ### Header

The header is designed to be large enought to give breathing room to its elements and feel relaxed, while still hint that there are information visible below that you can scroll to.


![header section of FlexGridYoga](assets/img/readme/Screenshot-index-header.png)

 __Contains the following elements:__
 -  an inspiering __background image__ 
 -  a fixed, responsive __navigation menu__  

 - __a welcome heading__  with the company name
  
 -  __a textbox__ with an introduction text 
 
 - a __call-to-action button__ that takes the user to the join us page where 
       the user can choose to subscribe to a newsletter through a form or click a link to go to the sign-up form and become a full paying member. 

__What it accomplish:__
1.  let users know more about the website.
2.  give users a shortcut to join section.       
3.  give the user a way to navigate around the site. 

___
> ### About Section - instructor presentation

In the about section, the yoga instructor get a chance to introduce herself. This section is set higher in the infromation hirarchy than the other sections below since the _instructor_ really is what sets one community appart from anothers.

![About section of FlexGridYoga](assets/img/readme/Screenshot-index-about.png)


 __Contains the following elements:__  
 - introduction __text-area__
 - selfie __image__ 

__What it accomplish:__
1.  Let users get to know the instructor.
2.  Let site owner diffirentiate herself from competitors       

___
> ### Benefits section - Why yoga?

This section informs the users of som of the benefits of yoga.

The goal with this is to inspire users interest in the subject. This is done with six interactive cards, each presenting one unique benefit you gain from doing yoga.

![Benefits section of FlexGridYoga](assets/img/readme/Screenshot-index-benefits.png)

 __Contains the following elements:__
 - a section __heading__
 -  interactive and responsive __cards__

__What it accomplish:__
1.  Educate users on the benefits of engaging in yoga.
2.  Give site owner a tool to inspire her visitors.
3.  Make website a bit more interactive.

___
> ### Join Section - first step to get involved

New users might be hesitant to become a full paying member on the first visit. So in order for the site owner to keep users in the loop, and in order to let new users connect and learn more about the future content and what value it would bring to them, they have an option to join a newsletter where the site owner has the potential to reach interested visitors in the future via email.

![Join section of FlexGridYoga](assets/img/readme/Screenshot-index-join.png)



 __Contains the following elements:__
 - a responsive __text-box__ containing information on what _value_ signing up could bring new users.  
 - a __link__ directing interested users to the sign up form on the _Members page_.
 - a responsive __form__ that could feed an emailing list database. this form contains following information:
   - __First name__ _required_
   - __Last name__ 
   - __Email__ _required_
   - __Submit button__

__What it accomplish:__
1.  Educate users on the benefits of engaging in yoga.
2.  Give site owner a tool to inspire her visitors in the future.

__Design feature:__
>Input labels are placed off screen using CSS. The users can't see them, but the screen readers can. Making the section looking clean while keeping functionality. Placeholders shows the user what is expected in the form-fields.
>
>By mixing different vivid colors in the background image, the join section becomes positive and fun to inspire user to commit.
___
>  ### Members page header

The header inherits most of the styling from the index page. but the welcome text box and the website name heading is replaced with a login form.

Existing users can sign in to the website here.

![header on members page of FlexGridYoga](assets/img/readme/Screenshot-members-login.png)
       
__Contains the following elements__ 
- a __fieldset legend__
- __log-in__ form for existing users form contains the following form-elements:
- __Email__ _required_
- __Password__ _required_
- __Submit button__ that submits the form and could validate the user to log in.

__What it accomplish:__
1. > gives existing users an easy way to log in to their accounts.

__Design feature:__
 >Just like on the join section of the index page, the labels are not displayed but still accessable for screen readers and assistive technology for users who needs it. 
___
> ### Members page - sign up section

In this section the user gets is faced with the option to become a paying member of the website and gain full access to its content.

![sign up section on members page of FlexGridYoga](assets/img/readme/Screenshot-members-signup.png)

__Contains the following elements__ 
- __information box__ with the following sub-elements:
   - __heading__ letting user know what it costs
   - __text__ explaining the offer
   - __video element__ using an iframe with embedded youtube content that the user can interact with.
- __account creation form__ containing the following sub-elements:
   - an _Account Creation_ __fieldset__ with 3 input fields create the new account.
   - A __detail > summary__ element styled to look like a button that reviels the _payment_ part of the form 
   - a _Payment Card_ __fieldset__ to fill in the payment details
   - a _Billing_ __fieldset__ that let the user fill in the billing adress for the payment.

__What it accomplish:__
1.  Give users an idea of what is behind the paywall.
2.  Give site owner a way to promote the paid-for content.
3.  Let users create a members account.
4.  Let users poivide payment details to become full members.

__Technical Feature:__
>the video element in the information box let's the user get a hint of what to expect as a paying member. The video runs on youtube using iframe and youtubes sharing feature using embedded code which gives the user full controll over play, pause, volume and playing speed functionalities.
___
> ### Footer - Social media links

The footer and the end of the website contains links to the website's social media platforms.

![Footer of FlexGridYoga](assets/img/readme/Screenshot-index-footer.png)


     
 __Contains the following elements__ 
 - List of __links to social media__ pages.
 - __Copy right text__ for the website. ( in this case my own name since this is an excersise.)

__Section Goal:__
1.  Let users connect to website's social media platforms
2.  Give site owner a way to promote her community on social media.

__Design feature:__
> The footer area is designed to be as clean and minimal as possible yet have enough contrast to be clear ans readable.
> animations on the elements has been removed to reduce distractions from the rest of the the website. the mouse still indicate these icons are links through the pointer-change. 
___
### Features Left to Implement

Herea are some ideas that could further improve this website:
- Flip over cards with more information of yoga benefits on the backside
- Members login inside the fixed nav-bar for faster login for existing users.
- Gallery page from social media showcasing the commuinity
___
## Testing 

Here follows some picure of the website on mobile and tablet to show the website might appear on smaller screens than in the feature section.



### __Mobile full page:__
>![full mobile page](assets/img/readme/testing/mobile-full-index.png)
>> this is how the index page looks like on mobile
>>
>> You can for example see that the benefits section __cards__ is shrunken in size and that the join form __input fields__ are diplayed in a column, rather than in a row.

>![full mobile page](assets/img/readme/testing/mobile-full-members.png)
>> this is how the members page looks like on mobile
>>
>> Every element is centered. and the information box that was split into two parts in the sign-up section is now looking like one solid box.


### __Mobile Navigation:__
>![full mobile page](assets/img/readme/testing/mobile-index-header.png)
>> On mobile, the navigation menu is replaced with a hambuger button.
>>
>>This is what the mobile navigation looks like closed.

>![mobile navigation open](assets/img/testing/../readme/testing/mobile-nav-open.png)
>> When you click the burger menu button, this is what the navigation menu looks like open.
>>
>> You can also see that when open the menu, the menu bar disapears, and the burger icon is animated to become an X.


>![mobile navigation open](assets/img/testing/../readme/testing/mobile-nav-button.png)
>> When you click a button in the menu, it takes you to the correlating section.
>>
>> you close the menu by pressing the X.

### __Video Elements__

>![Video element from youtube](assets/img/testing/../readme/testing/mobile-members-signup1.png)
>> Here you can see the video element that is dispalyed in the sign-up section of the members page.
>> This video is implemented using an iframe element and embedded code from youtube. 
>>
>> This video works the same way it would on youtube.com, meaning the video will only play if the user intends it to. The user also has full control over actions such as play, pause, full screen view, video quality and sound.
>>
>> Since the video is embeded using iframes, this is like watching youtube from within this website, meaning the creator of what ever video is embedded will get credited by youtube in terms of view counts etc. It can there for also work as a link to a site owners potential youtube page.
>>> __important note:__
>>>
>>>This video is for mockup reasons only to display what an embedded video would look like on this page and should be replaced by the site owners own video uploaded to youtube. All credit goes to the creator and creators account:
>>>
>>>_Name of account:_ 
>>>
>>> [__Boho Beautiful Yoga__](https://www.youtube.com/channel/UCWN2FPlvg9r-LnUyepH9IaQ)
>>>
>>> _Link to video used:_
>>>
>>> https://www.youtube.com/watch?v=CiaD3jP0YhA

### __form field validation__

>![form field being validated](assets/img/testing/../readme/testing/form-field-validation.png)
>> form fields are validated by html 5.
>> All form fields are also type specific if applicable, meaning if a forn field expects an email adress, its input will not be accepted as valid if it is missing a correct email formating. 
>>
>> in this example you can see an email form being validated because the form field is set to "required".

### __Lighthouse results:__
>![form field being validated](assets/img/testing/../readme/testing/lighthouse-report.png)
>>_Performance_, _Accessibility_ adhearance, _SEO_ and _Best Practices_ have been tested with the inbuild lighthouse tester in chrome developer tools. 
>>
>>These are the results.

### __Validator tests__

To extend the validation of the HTML and CSS, external validators from w3c has been checking the code as well.

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)


### Unfixed Bugs

>__What?__
>> background of fixed menu bar disapears.
>>
>>![navigation bug](assets/img/readme/testing/bugs/bug1.png)
>
>__When?__
>>When user is on a desktop browser and resizes the viewport so small that the hamburger menu appears. If the hamburger menu is then clicked to be opened and the viewport is enlarged so that the "normal" navigation menu appears again.
>
>__Why?__
>> This is due to the fact that the menu is made with pure CSS and uses a transparent checkbox on top of the hamburger icon. When the checkbox is checked, the menu is toggled, and the navigation bar disapears. If it is left checked, and the viewport enlarged, the menu will disapear but the checkbox will remain checked. This means that all styling that is applied when the checkbox is checked also will remain until you physically uncheck the checkbox.
>
>__Solution__
>> 1. You can redesign the menu so that it covers the entire screen, and remove the animation that removes the nav-bar. (This creates some other UX issues).
>>
>> 2. You could re-create the hamburger menu using a method that involves javascript. (This is arguably the best solution but N/A for this project.)

___
## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

>You can visit the live website form any device by following this link:
>
>https://4ntm4n.github.io/ms-one/index.html


## Credits 
In this section I want to give crdits to resourses I have used when creating this website.

### __Technical__
>Here I want to give credit to the resourses I have used that gave me enough knowledge in html and css in order to build this website.

> #### __Code Institute__
> Since I am a full stack developer student at code institute most of my fundamental programming skills and essential knowledge in html and css comes from here: 
>>https://codeinstitute.net

> #### __Codecademy__ - _Intermediate CSS track_
>On Codecademy.com I took a course in intermediate CSS after finnishing the course material on Code Institute. Here I learned about flexbox in CSS and also CSS inbuilt grid functionality that I used to create rows for each section of this website.
>>Here is a link to the track on codecademy:
>> https://www.codecademy.com/learn/learn-intermediate-css
>
>> here is a link to project I made to teach myself flexbox:
>>https://github.com/4ntm4n/Tea-cozy/blob/main/README.md

>#### __tips and tricks__ 
>Here I will are some things I picked up after googling and reading forums
>
>__smooth-scrolling in CSS:__
>>https://gomakethings.com/smooth-scrolling-links-with-only-css/
>
>__center an image from html through CSS:__
>> https://www.w3schools.com/howto/howto_css_image_center.asp
>
>__adding script to bottom of the page:__
>>https://stackoverflow.com/questions/38407962/when-to-use-the-script-tag-in-the-head-and-body-section-of-a-html-page#:~:text=Put%20your%20functions%20in%20the,not%20interfere%20with%20page%20content.&text=If%20your%20is%20not%20placed,of%20the%20element.
>
>__styling input fields:__
>>https://www.w3schools.com/css/css_form.asp
>
>__hamburger menu:__
>
>found this burger menu method, imported it and modified it to suit this website.
>>https://codepen.io/alvarotrigo/pen/wvrzPWL
>
>__using media queries:__
>>https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries
>
>__how to ease everything on hover:__
https://stackoverflow.com/questions/41267357/css-ease-in-and-out-on-hover


### __Content__
In terms of text content, almost everything has been invented by myself on the fly as I saw fit and can be viewed as relevant mockup text that should be replaced by the site owners own words if this site ever were to be commercially used.

> #### __Benefits of yoga__
> The cards in the benefits section have six different benefits of yoga presented on them, these benefits were inspired by this article.
>> https://www.hopkinsmedicine.org/health/wellness-and-prevention/9-benefits-of-yoga

### __Fonts and icons__
> - Fonts for text and heading has been imported through [Google Fonts](https://fonts.google.com/)
>> 
> - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)


### __Media__

In this section you can see where the media elements on the website comes from and who created them.

> __flower pictures that are used for the benefits cards:__
>https://www.freepik.com/free-vector/yoga-mind-quote-vector-template-social-media-post-set_20266489.htm#query=flower%20yoga%20pose&position=0&from_view=search
>>created by rawpixel.com and availabel on https://freepik.com/


> __background of sign-up section on members page:__
>https://www.freepik.com/free-vector/people-practicing-yoga_9176176.htm#query=yoga%20studio&position=33&from_view=keyword
>>Created by pch.vector and available on https://freepik.com/


> __background of join section on index page__
>https://www.freepik.com/free-vector/open-air-yoga-class-concept_9892525.htm#query=yoga&position=2&from_view=author
>>created by pikisuperstar and available on https://freepik.com/


> __Selfie image in the about section on index page__
> https://www.freepik.com/free-photo/woman-yoga-mat-relax-park-young-sporty-asian-woman-practicing-yoga-doing-headstand-exercise-working-out-wearing-sportswear-pants-top_14625823.htm#query=yoga%20nature%20headstand&position=0&from_view=search
>> Image by jcomp and available on https://freepik.com/


> __background image in header on index and members page__
> 
>> bought from adobestock photos and available on https://adobestock.com/

>__video element in sign-up section on members page__
>
>As mentioned in the testing area: _This video is for mockup reasons only_ to display what an embedded video would look like on this page and should be replaced by the site owners own video uploaded to youtube. All credit goes to the creator and creators account. 
>
>By viewing the video on this website, you are watching the creators channel on youtube through the iframe and youtube's embedded code.
>
>>_Name of account:_
>>
>>__Boho Beautiful Yoga__
>
>>_Link to video used:_
>>
>>https://www.youtube.com/watch?v=CiaD3jP0YhA
___

### Some final words from the developer

Thank you for taking the time to read through this website documentation.

This project is the first of five milestone projects in a full stack developer course that I have enrolled through [Code Institute](https://codeinstitute.net).

- There are many ways to approach a project like this, but in this case I wanted to:
  
  - __A__: limit myself to __pure__ html and CSS since this is a course in those topics and I was curious to see how much could be done without using any javascript to create front end functionality. 
  
  - __B__: __not use__ any framework to aid me in class creation, grid functionality and design.

  - __C__: Work from a __pre-defined__ project suggestion (in this case yoga / mindfullness) to further challange myself and create a, what I can imagine, more life like scenario for a web developer where you put yourself in a clients shoes and work with a topic that is not always aligning with personal interests.



>FlexGrid Yoga - a study in webdevelopment
>
>By Anton Askling 2022