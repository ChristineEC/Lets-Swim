#Swim with Chrissy

##Private swim lessons

### Description







###Features

####Header
The header contains an H1 with an anchor element linked to the home page, as well as a nav bar linked to the different pages of the website. Flex properties were used to make the nav bar wrap under the heading for smaller screen sizes. The nav bar was further styled to show horizontally, then stack when wrapped, and the list style was set to none. The pseudoclass a:hover was applied to the nav bar to indicate when the user hovers over the menu item.

The code for horizontally centering the logo (text) and the nav using line-height was taken from the Love Running Navigation Styling 2 video. Help with flex properties was obtained from [Flexbox Froggy](https://flexboxfroggy.com/).

For a reminder on how to style the nav list items horizontally, I referred to [W3 Schools](https://www.w3schools.com/css/css_navbar_horizontal.asp).

For a reminder of the correct syntax for using the hover pseudoclass, I referred to the Love Running video Navigation Styling 2 as well as [MDN Web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover). My first solution worked in the browser but failed a validation test, and that is when I consulted MDN.

I resolved an error message concerning the nav elements containing more than one class attribute, with class= used twice, by placing both attributes inside the same set of parentheses.



####Main

The main section of the home page has a simple, bold and easy to read headline and tag, announcing the nature of services and intended audience. This is followed by a section with a water background and collage of photos depicting swimmers of all ages and cultural backgrounds, as well as images encouraging acceptance of differences, including one for autism. Further text details the business's broader objective of inclusion and inviting the user to visit the activities page for more details about the business's offerings.

Originally, the headline and tag were placed against the water background, but this required a lighter container box for purposes of visibility, and it was felt that this feature did not work well on the slimmest mobile phones. Therefore, it was decided to keep the headings section separate at the top. Moving the water background to the images section also helped with the styling of the images. These were set to flex flow (row), and they looked better on a wide variety of devices with a background instead of the default white. A more experienced developer with more time could simply have the images in a row, with the user able to use an arrow to make scroll horizontally through the images.



####Footer
The footer includes the name of the business, city and country location (as the business is home-based--more detailed location to be included on the contact page), contact details, and two hyperlinked social media icons that open in new table, with aria-labels (for accessibility) inviting the user to visit the business on Facebook and Instagram, respectively. The footer has been made responsive using flex properties, and the height is set to auto to enhance responsiveness.








