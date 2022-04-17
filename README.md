# ms-one 
        First milestone project at Code Institute showcasing a responsive website using vanilla HTML5 and CSS3.

# FlexGrid Yoga - a website for a personal yoga instructor. 

## project outline:
<hr>

        I decided to work from one of the pre-defined project suggestions because  I wanted to put myself in a scenario where I create a website for a client that does not share my personal interest or design preferences. For me this meant a greater challange and what I can imagine is a more life like scenario in web development.



## end user goals  : 

>Typical users are interested in getting involved with online-classes and tutorship in yoga.

- ### __The typical end user wants to:__

  -  know more about site and yoga instructor
  - be able to subscribe to news coming from community regarding techniques and upcoming yoga sessions
  - get a hint about what is expected inside the paid members area
  - be able to sign up and become a full member, attending live- and pre recorded -yoga sessions
  - connect to community on social medias


- ### __a typical returning user wants to:__
  - sign in to their account and conduct yoga sessions.

## site owners goals:
>site owner wants to inspire potential end users who wants to learn yoga and market the benefits of yoga and let users connect with her community and sign up to engage in live and pre-recorded yoga sessions.

- ### __in short, the site owner wants to:__

  - educate new site visitors about herself
  - give breif overview of the benefits of yoga
  - let new users sign up to newsletter to keep them in the loop of what is happening in the community
  - let users know how they can engage in social media.
  - let existing users log in to view the paid-for content

<hr>

# Approach 

## Design and Content
        My goal as a webdeveloper was to create a clutter free minimalistic website. Since the Website is Yoga / mindfullness oriented, I wanted the information provided to have lots of breathing room and the animation on elements to be somewhat slower than on a normal website to make it feel calm and relaxing. I also wanted the colors to be positive. For the color scheme I was inspired by different colors of yoga mats.


>         I decided that the best way to adress the users and site owners needs was to device the website into two main parts.
>
>1.  __an index page__ <br> 
        the main page, with a single page layout style where the site owner could present herself and the users could get to learn more about her and about yoga. 
>2. __a members page__ <br>
        where existing users could sign in and a new user could choose to sing up and become a full member. I wanted this to be a separate page since it mostly contains of form elements and a separate page for this would reduce clutter on the website, making it look and feel cleaner
>>      Since the header is a users first impression of the site, it felt especially important to get this section right. I wanted it to have the least amount of different colors and the information to be clear with lots of breathing room.
>
>>     As you progressed down on the page I wanted more colors to mix in to give a positive vibe near the join-section where the user takes some kind of action. 
>
>>     Elements such as images and forms was created with round soft shapes to feel relaxing while the text-boxes was designed square to break off and give contrast.

___
### __The index page consist of five sections:__ 

<details>
  <summary>
  <b>1.1 Header - an inspiering welcome</b> 
  <hr>
  </summary> 


        This is the section of the website a user is presented to. I wanted it too look clean and relaxing.
> __Contains the following elements:__
> -  an inspiering __background image__ 
> -  __navigation menu__  that lets the user jump to the different sections
>
> - __a welcome heading__ -in this case the website's name -FlexGrid Yoga 
>        instead of having a logo in the navigation bar
> -  __a textbox__ with a welcome text 
> 
> - a __call-to-action button__ that takes the user to the join us page where 
>       the user can choose to subscribe to a newsletter through a form or click 
>       a link to go to the sign-up form and become a full paying member. 
>
>
      I gave this page enough space to give breathing room to all elements presented, but also made it small enough to let user hint the sections below to encourage a scroll down.
</details>

<details>
 <summary>
 <b>1.2 About section  - introduction to the tutor.</b>
 <hr>
 </summary>

        This first section will let the users know who the site owner / instructor is through a breif presentation. 
> __Contains the following elements:__  
> - introduction __text-area__
> - selfie __image__ 
>>     I argue that this section has the highest informative priority since there are many different online yoga classes out there, and the first impression a user gets from the instructor herself is a key differentiator from other similar sites.
>
>>      I wanted the design to follow the same pattern as the rest of the site. so I created a light box-shaddow around the elements and gave the the section a lot of breathing space to go with the relaxed theme. Image element is round  while the information is square to give contast and be less distractive from the text.
</details>

<details> 
 <summary> 
 <b>1.3 Benefits section - six benefits of yoga. </b>
 <hr>
 </summary>

        The second section informs the users of som of the benefits of yoga, the goal with this is to inspire users interest in the subject. I wanted to do this with a card design that looked good and was easy to both design and reuse. 

> __Contains the following elements:__
> - a section __heading__
> - six different __cards__ that each explains one unique benefit of yoga.
>>       To make this section a bit more interesting, I created a floating effect by moving the cards ever so slightly upwards and added more box-shadow when the user hovers the pointer over the them with the mouse. 
>>        
>>     I made the hover effect slower to feel more relaxing.
</details>

<details>
 <summary>
  <b>1.4 Join Section - join community and newsletter</b>
  <hr>
 </summary> 
  <hr>

        New users might be hesitant to become a full paying member on the first visit. So in order for the site owner to keep users in the loop, and in order to let new users connect and learn more about the future content and what value it would bring to them, they have an option to join a newsletter where the site owner has the potential to reach interested visitors in the future via email.

> __Contains the following elements:__
> - a __text-box__ containing information on what _value_ signing up could bring new users.  
> - a __link__ directing interested users to the sign up form on the _Members page_.
> - a __form__ that could feed an emailing list database. this form contains following information:
>   - __First name__ _required_
>   - __Last name__ 
>   - __Email__ _required_
>   - __Submit button__
>
>>      In order to make this section feel clean yet have the sufficiant support for screen readers, the legends and labels are placed off screen using css. Placeholders show the user what is expected in the form-fields.
</details>

<details>
<summary>
<b>1.5 footer - links to social media </b>
<hr>
</summary>

        The footer and the end of the website is held as simple as possible in order to make more important elements on the website stand out.
       
> __Contains the following elements__ 
> - List of __links to social media__ pages.
> - __Copy right text__ for the website. ( in this case my own name since this is an excersise.)
</details> 

___

### __The Members page consist of three sections:__ 

<details>
<summary>
<b>2.1 Header - Sign in </b>
<hr>
</summary>

        The header on the members page is the same as on the index page. but the welcome text box and the website name heading is replaced with a login form.
       
> __Contains the following elements__ 
> - a __fieldset legend__
> - __log-in__ form for existing users form contains the following form-elements:
>   - __Email__ _required_
>   - __Password__ _required_
>   - __Submit button__ that submits the form and could validate the user to log in.
>
>>     Just like on the join section of the index page, the labels are not displayed but still accessable for screen readers and assistive technology for users who need it. 
</details> 

<details>
<summary>
<b>2.2 Sign-up section - create an account </b>
<hr>
</summary>

         In this section the user gets is faced with the option to become a paying member of the website and gain full access to its content.
       
> __Contains the following elements__ 
> - __information box__ with the following sub-elements:
>   - __heading__ letting user know what it costs
>   - __text__ explaining the offer
>   - __video element__ using an iframe with embedded youtube content that the user can interact with.
> - account creation __form__ containing the following sub-elements:
>   - an _Account Creation_ __fieldset__ with 3 input fields create the new account.
>   - A __detail > summary__ element styled to look like a button that reviels the _payment_ part of the form 
>   - a _Payment Card_ __fieldset__ to fill in the payment details
>   - a _Billing_ __fieldset__ that let the user fill in the billing adress for the payment. 
>
>>      the video element in the information box let's the user get a hint of what to expect as a paying member. The video runs on youtube using iframe and youtubes sharing feature using embedded code.
>
>>      The payment details button could have been executed in a more elegant way using javascript but since I limited myself to pure html and css, styling the summary element to look like a button was the solution I came up with.
</details> 

<details>
<summary>
<b>2.3 footer - links to social media </b>
<hr>
</summary>

        The footer on the members page is identical to the one on the index page to provide users with concistancy. 
       
</details> 

Sign in and Sign Up will be a separate page called "members". <br> 
This page let existing users log in with it's user credidentials and new users sign up to the paid-section of the site. 
It will consist of one form for existing members to log in, and another form to sign up where you create log in details and provide payment information.

Apart from the form there will also be a free yoga session video. the video is intended to let users know what to expect if they signup as well inspire them to do so. 



these people will be credited if I use their images from freepik
<a href='https://www.freepik.com/vectors/flower'>Flower vector created by rawpixel.com - www.freepik.com</a>
<a href='https://www.freepik.com/vectors/yoga-studio'>Yoga studio vector created by pch.vector - www.freepik.com</a>
<a href='https://www.freepik.com/photos/yoga-nature'>Yoga nature photo created by jcomp - www.freepik.com</a>
<a href='https://www.freepik.com/vectors/open-air'>Open air vector created by pikisuperstar - www.freepik.com</a>

how to ease everything on hover:
https://stackoverflow.com/questions/41267357/css-ease-in-and-out-on-hover

using media queries:
https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

styling input fields:
https://www.w3schools.com/css/css_form.asp

hiding elemens off screen so that they dont take up screen realestate when they have visibility:hidden property set to them:

https://stackoverflow.com/questions/6746649/how-can-i-hide-an-element-off-the-edge-of-the-screen


adding script to bottom of the page:
https://stackoverflow.com/questions/38407962/when-to-use-the-script-tag-in-the-head-and-body-section-of-a-html-page#:~:text=Put%20your%20functions%20in%20the,not%20interfere%20with%20page%20content.&text=If%20your%20is%20not%20placed,of%20the%20element.


center an image from html through css
https://www.w3schools.com/howto/howto_css_image_center.asp

smooth-scrolling:
https://gomakethings.com/smooth-scrolling-links-with-only-css/

hamburger menu:
found this burger menu method, imported it and modified it to suit this website.
https://codepen.io/alvarotrigo/pen/wvrzPWL

benfits of yoga:
https://www.hopkinsmedicine.org/health/wellness-and-prevention/9-benefits-of-yoga