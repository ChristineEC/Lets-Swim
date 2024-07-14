# Let's Swim!
## Private swim lessons accommodating special needs and special requests

### Description
The goal of the website is to increase access to swimming lessons by offering private swimming lessons that accommodate special needs or personal, religious or cultural requirements.

The site is aimed at people with some form of disabilty, such as autism, and people whose religious beliefs, cultural background or other personal characteristics cause them to avoid swimming lessons due to barriers such as lack of privacy, a too-overwhelming environment, and so on.

The site-owner is a mother-and-daughters team of certified instructors, and the site informs the user that, while the daughters engage in teaching as a side-job to their studies, the mother provides lessons in her free time to people who lack access in some form, including financial barriers. Such lessons are not necessarily paid. That is, discounts and fee waivers are available, since the primary goal is to increase water safety in the community.

Site-users are offered some reasons why a person should learn how to swim, the most prominent (that it is an important survival skill) listed first.

The list of possible accommodations features prominently on the site, as further encouragement for the reluctant student to seek services.

The tone of the website is friendly and welcoming.

### Features

#### Header
The header contains an h1 with an anchor element linked to the home page, as well as a nav bar linked to the different sections of this one-page website. Flex properties were used to make the nav bar wrap under the heading for smaller screen sizes. The nav bar is styled to show horizontally at all times,and a hover feature comes into play on larger screens to indicate when the user hovers over the menu item. The pseudoclass a:hover was used to accomplish this and is applied through a media query. 

Help with flex properties was obtained from [Flexbox Froggy](https://flexboxfroggy.com/).

For a reminder on how to style the nav list items horizontally, I referred to [W3 Schools](https://www.w3schools.com/css/css_navbar_horizontal.asp).

For a reminder of the correct syntax for using the hover pseudoclass, I referred to the Love Running video Navigation Styling 2 as well as [MDN Web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover). My first solution worked in the browser but failed a validation test, and that is when I consulted MDN.

I resolved an error message concerning the nav elements containing more than one class attribute, with class= used twice, by placing both attributes inside the same set of parentheses.





###Main Section - Homepage

The main section of the home page has a simple, bold and easy to read headline and tag, announcing the nature of services and intended audience. This is followed by a section with a water background and collage of photos depicting swimmers of all ages and cultural backgrounds, as well as images encouraging acceptance of differences, including one for autism. Further text details the business's broader objective of inclusion and inviting the user to visit the activities page for more details about the business's offerings.

Originally, the headline and tag were placed against the water background, but this required a lighter container box for purposes of visibility, and it was felt that this feature did not work well on the slimmest mobile phones. Therefore, it was decided to keep the headings section separate at the top. Moving the water background to the images section also helped with the styling of the images. These were set to flex flow (row), and they looked better on a wide variety of devices with a background instead of the default white. A more experienced developer with more time could simply have the images in a row, with the user able to use an arrow to make scroll horizontally through the images.

All images that failed to load, showing alt text instead, were removed and, if necessary, replaced.

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

