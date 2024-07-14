# Let's Swim!
## Private swim lessons accommodating special needs and special requests

### Description
The goal of the website is to increase access to swimming lessons by offering private swimming lessons that accommodate special needs or personal, religious or cultural requirements.

The site is aimed at people with some form of disabilty, such as autism, and people whose religious beliefs, cultural background or other personal characteristics cause them to avoid swimming lessons due to barriers such as lack of privacy, a too-overwhelming environment, and so on.

The site-owner is a mother-and-daughters team of certified instructors, and the site informs the user that, while the daughters engage in teaching as a side-job to their studies, the mother provides lessons in her free time to people who lack access in some form, including financial barriers. Such lessons are not necessarily paid. That is, discounts and fee waivers are available, since the primary goal is to increase water safety in the community.

Site-users are offered some reasons why a person should learn how to swim, the most prominent (that it is an important survival skill) listed first. Some statistics about the high level of drowning among children and among autistic people are included, with links to the respective sources, the CDC and Autism Society Florida. Those links open in new tabs. Aria text is included for greater accessibility and states that the links open in new tabs. 

A list of possible accommodations features prominently on the site, as further encouragement for the reluctant student to seek services. The user is there encouraged to contact the site-owner to describe or discuss any other accommodations required.

The tone of the website is friendly and welcoming.

### Features

#### Page
The title of the webpage is shown on the browser tag. Only HTML and CSS are used. The page is fully responsive, mainly using flex properties and a limited number of media queries in CSS. Sections and proper use of headings in the html file give semantic structure to the website. In the head section are included a description of the site, including the location, and keywords to help browsers direct the intended audience to the site. A CSS wildcard selector is used, and some basic styling added there to override some automatic browser styling.

#### Header
The header contains an h1 with an anchor element linked to the home page, as well as a nav bar linked to the different sections of this one-page website. Flex properties were used to make the nav bar wrap under the heading for smaller screen sizes. The nav bar is styled to show horizontally at all times,and a hover feature comes into play on larger screens to indicate when the user hovers over the menu item. The pseudoclass a:hover was used to accomplish this and is applied through a media query. 

/* add images here */

Help with flex properties was obtained from [Flexbox Froggy](https://flexboxfroggy.com/).

For a reminder on how to style the nav list items horizontally, I referred to [W3 Schools](https://www.w3schools.com/css/css_navbar_horizontal.asp).

For a reminder of the correct syntax for using the hover pseudoclass, I referred to the Love Running video Navigation Styling 2 as well as [MDN Web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover). My first solution worked in the browser but failed a validation test, and that is when I consulted MDN.

I resolved an error message the nav elements containing more than one class attribute, with class= used twice, by placing both attributes inside the same set of parentheses.

### Main section

#### Hero section
The hero section features an h2-level headling and an h3-level tagline, appearing prominently against a background of pool water and flanked on both sides by images, one of a child wearing goggles in a pool, and one of a woman wearing a burkini. The heading states the primary offering of private swim lessons, and the tagline alerts the reader to the fact that special accommodations are offered. So right away, both the images and the prominent tagline alert the user to the nature of the intended audience people who have special requirements, or not, as the case may be. The images were styled as circles, with a lighter border to make them stand out against the background and make them slightly resemble bubbles. Originally, there were only 2 such images, but that didn't work well on laptop-sized screens, so another image was added, making the section attractive on all screen sizes, again using flex and media queries.

/* include image here */

The hero section is followed by a section called Why Learn to Swim, described above in the general site description. 

#### About Us section

The About Us section has an anchor tag at its h2 header, enabling the navigation link in the header to function, and the section includes a short description of the site owners and further points to the objective of the website, which is to attract students who may otherwise find it difficult to access swimming lessons, by discussing the site-owner's inspiration for offering the swim lessons. 
In accordance with the site's objective, the most prominent feature of the About Us section is a list of possible accommodations and an invitation, or a call to action, to the user to contact the site owner through the contact form.
The regular business hours appear in a simple table at the bottom of this section.

#### Contact section
Like the About Us section, the Contact section has an anchor tag at its h2 header, enabling the navigation link in the header to function. It includes the location, phone number and email to the business, followed by an invitation to the user to fill out the contact details in the included form. The form consists of three labeled elements, the first a text input box where the user is to enter their name. The second is an email input that accepts only email addresses. That is, it warns the user if an incorrectly formatted text is entered. The third input field is for user comments or questions. It comprised a text-entry field with an additional inside-the-box label stating that the maximum number of characters allowed is 500. The user's text input wraps inside the box.
/* include here source of information for the last feature */

#### Footer
The footer section contains text of the site owner's location and contact details, followed by two icons that represent links to social media. The links open in separate tabs. Aria-labels are included for screen readers, inviting the user to visit the organization on several social media sites and informing them that the link will open in a new tab.






/ * Testing and Validation */

All images that failed to load, showing alt text instead, were removed and, if necessary,  replaced.

Testing for responsiveness was done continually. One of the problems encountered is that the photos on the main page would stack up over the header and outside the background against which they were intended to display.

/*Working on bug to make text in hero div not only center at top of div but into the center of the div, if possible.

###Footer
The footer includes the name of the business, city and country location (as the business is home-based--more detailed location to be included on the contact page), contact details, and two hyperlinked social media icons that open in new table, with aria-labels (for accessibility) inviting the user to visit the business on Facebook and Instagram, respectively. The footer has been made responsive using flex properties, and the height is set to auto to enhance responsiveness.

###Classes Page

This page contains text describing the types of classes offered in terms of class size, ages and levels of ability. It also invites the reader to ask about group swim sessions. This is intentionally left vague because the site owner wants to maintain full owner discretion here, given that the business is run out of a private home. (For the same reason, location information for the business is limited to city and state. It is assumed that browsers will generally direct only U.S. residents to the site.)

A table follows, showing the regular hours of operation, and the reader is informed that requests for lessons outside of those times are welcome.

Although I remembered the structure of the code, I did need to peak back at Code Academy's html unit on tables to ensure I had the right syntax in terms of table, th, and tr. I'm not sure whether a 30-second lookup counts as needing to be credited, but here it is.








###Credits

To make the user's additional comments in the form wrap inside the text box, I use a <textarea> element instead of <input type="text>. I learned this from [W3Schools.com](https://www.w3schools.com/tags/tag_textarea.asp#:~:text=The%20element%20is%20often,attributes%20(or%20with%20CSS).

