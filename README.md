# Let's Swim!
## Private swim lessons accommodating special needs and special requests

### Description
The goal of the website is to increase access to swimming lessons by offering private swimming lessons that accommodate special needs or personal, religious or cultural requirements.

The site is aimed at people with some form of disabilty, such as autism, and people whose religious beliefs, cultural backgrounds or other personal characteristics cause them to avoid swimming lessons due to barriers such as lack of privacy or a too-overwhelming environment.

The site-owner is a mother-and-daughters team of certified instructors, and the site informs the user that, while the daughters engage in teaching as a side-job to their studies, the mother provides lessons in her free time to people who face barriers to learning to swim, including financial barriers. The tone of the website is friendly and welcoming. By including the site owner's personal reasons for teaching private lessons, the reluctant-swim-student user is encouraged to make contact, thus contributing to the site owner's goal of increasing access to swimming lessons and the user's goal of learning to swim.

### Features

#### Page
The title of the webpage is shown on the browser tag. Only HTML and CSS are used. The page is fully responsive, mainly using flex properties and a limited number of media queries in CSS. Sections and proper use of headings in the html file give semantic structure to the website. In the head section are included a description of the site, including the location, and keywords to help browsers direct the intended audience to the site. A CSS wildcard selector is used, and some basic styling is added there to override some automatic browser styling.

#### Header
The header contains an h1 with an anchor element linked to the home page (in this case just the top of the page, as it is a one-page website)

##### The nav bar
 The header also has a nav bar with links to the About Us and Contact sections. Flex properties were used to make the nav bar wrap under the heading for smaller screen sizes. The nav bar is styled to show horizontally at all times,and a hover feature comes into play on laptop and larger screens to indicate when the user hovers over the menu item. The pseudoclass a:hover is used to accomplish this and is applied through a media query. 

/* add images here */

#### The Hero section

The hero section features an h2-level headling and an h3-level tagline, appearing prominently against a background of pool water and flanked on both sides by images, one of a child wearing goggles in a pool, one of two girls happily splashing in a pool in inflatable rings, and one of a woman wearing a burkini. Immediately this gives the user both the impression that swimming is fun and that the site is geared toward people from all walks of life. The heading states the primary offering of private swim lessons, and the tagline alerts the reader to the fact that special accommodations are offered. Thus, together, the h1 heading, the images and the prominent tagline alert the user to the nature of the intended audience, people who have special requirements, or not, as the case may be. The images were styled as circles, with a lighter border to make them stand out against the background and make them slightly resemble bubbles. Originally, there were only 2 such images, but that didn't work well on laptop-sized screens, so another image was added, making the section attractive on all screen sizes, again using flex. Media queries were not required here, but they could easily be used here with the existing flex properties and perhaps an additional image if the owner wished to make the site even more attractive.

/* include image here */

The hero section is followed by a small section called Why Learn to Swim. Site-users are offered some reasons that a person should learn how to swim, the most important (that it is an important survival skill) listed first. Some statistics about the high level of drowning among children and among autistic people are included, with links to their respective sources, the CDC and Autism Society Florida. Those links open in new tabs. Aria labels are included for greater accessibility and state that the links open in new tabs. Icons and bulleted lists with headings help the reader more easily scan the content of the section. Flex properties are used to make the section attractive across all devices, without the need for media queries.

#### About Us section

The About Us section has an anchor tag at its h2 header, enabling the navigation link in the header to function. The section includes a short description of the site owner, and mentions her motivation as one of increasing access to lessons for people who might otherwise face barriers. The intention here is to set the potential student at ease to help them to make the decision to learn to swim. 

The most prominent feature of the About Us section is a bulleted and spaced list of possible **accommodations**, against a dark background with light text to contast with the rest of the page, accompanied by an image of an elderly swimmer and a woman at the edge of a pool, covering her face, looking shy or embarrased. The user is there encouraged to use the site's contact form, or to contact the owner directly, to discuss any other accommodations that might be helpful or required. There is no need for a link to the form at this place in the document because the contact section appears almost directly below the accommodations section, and the header with the nav bar (showing Contact) is always visible. A larger website would want to include a hyperlink here, but it would have appeared somewhat odd here, given that a click would lead to just a small scroll (if any) down the page.

The regular business hours appear in a simple **table** at the bottom of this section, but with a white background, to maintain the prominence of the accommodations section.

#### The Contact section

Like the About Us section, the Contact section has an anchor tag at its h2 header, enabling the navigation link in the header to function. This section includes the location, phone number and email to the business, followed by an invitation to the user to fill out the contact details in the included form. 

The form consists of three labeled elements, the first a text input box where the user is to enter their name. The second is an email input that accepts only email addresses. That is, it warns the user if an incorrectly formatted text is entered. The third input field is for user comments or questions. It comprises a text-entry field with an additional inside-the-box label stating that the maximum number of characters allowed is 500. The user's text input wraps inside the box. Finally, the required fields (name and email) work as intended.

/* include here source of information for the larger text box feature */

#### Footer
The footer section contains text of the site owner's location and contact details, followed by two icons that represent links to social media. The links open in separate tabs. Aria labels are included for screen readers, inviting the user to visit the organization on several social media sites and informing them that the link will open in a new tab.


### Features Left to Implement

A telephone-number input field is the first feature that should be implemented, with radio button to indicate whether the phone number is to a fixed or mobile phone.

A checklist allowing the site-user to include more information, rather than having to type it in a field, would increase user experience significantly. The checklist should include the user's preferred mode of communication.

A radio-button list could also be included to help the site owners narrow down whether the mother or the daughters might be the best to answer the user's eventual query.
The site could be updated to include more information about different types of local resources for the target audience.

### Testing

#### Validator Testing
The html and CSS files were tested and passed with no errors or warnings in the [W3C (Jigswa) validator](https://validator.w3.org/) and in the [W3C CSS validator](https://jigsaw.w3.org/css-validator/), respectively.

The website was opened on a PC laptop, a large screen (PC), an iPhone 12xPro, and a Samsung Z Flip 4, and it looked good on all of those devices. I used Chrome's dev tool to continually check the site for responsiveness at all sizes, and the site looks good on all screen sizes.

The navigation and social media links (and the overall site responsivity) were tested in Chrome, Mozilla Firefox, Microsoft Edge, Safari, Opera and IOS (iPhone), and all worked as it should.

Lighthouse scores were good: 
![Lighthouse](vscode-local:/Screenshot%202024-07-15%20223055.png)



#### Bugs Encountered

### Deployment

### Credits

#### Content
Statistics on drowning in children were obtained from the Centers for Disease Prevention and Control, or the [CDC](https://www.cdc.gov/media/releases/2024/s0514-vs-drowning.html#:~:text=Over%204%2C500%20people%20died%20due,this%20latest%20Vital%20Signs%20report).
Statistics on drowning among autistic people were obtained from [Autism Society Florida](https://www.autismfl.org/drowning-prevention), who were quoted directly by the American Red Cross.

#### Media
All images were downloaded from Pexels.com and have links in the alt text in the html files, except for one background image, which was from Pexels as well and was contributed there by Julie Aagaard.

#### Help with Code
My mentor suggested, and I used, for the form submit and reset buttons, a particular shadow-box styling from GetCSSscan.com.

Help with flex properties was obtained from [Flexbox Froggy](https://flexboxfroggy.com/).

For a reminder on how to style the nav list items horizontally using flexbox, I referred to [W3 Schools](https://www.w3schools.com/css/css_navbar_horizontal.asp).

For a reminder of the correct syntax for using the hover pseudoclass, I referred to the Love Running video Navigation Styling 2 as well as [MDN Web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover). My first solution worked in the browser but failed a validation test, and that is when I consulted MDN.







### Footer
The footer includes the name of the business, city and country location (as the business is home-based--more detailed location to be included on the contact page), contact details, and two hyperlinked social media icons that open in new table, with aria-labels (for accessibility) inviting the user to visit the business on Facebook and Instagram, respectively. The footer has been made responsive using flex properties, and the height is set to auto to enhance responsiveness.

### Credits

To make the user's additional comments in the form wrap inside the text box, I use a textarea element instead of an input type="text. I learned this from [W3Schools.com](https://www.w3schools.com/tags/tag_textarea.asp#:~:text=The%20element%20is%20often,attributes%20(or%20with%20CSS).

All images that failed to load, showing alt text instead, were fixed (usually a typographical error somewhere) or removed and replaced.