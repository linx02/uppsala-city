# Uppsala City

Uppsala City is a site that hopes to provide useful information for tourists wanting to visit Sweden.
The website is targeted to people interested in visiting Uppsala and will provide info surrounding the history of the city aswell as tips for tourist attractions.

# Features

## Existing features

* Navigation bar
    - Featured and identical on all three pages, fully responsive navigation bar with logo and clickable links.
    - Will allow users to easily navigate thorughout the site without having to use the browsers back and forward buttons.

![Navigation bar](https://github.com/linx02/uppsala-city/blob/main/media/navigationbar.png)

* Landing page image
    - The landing image is a photograph of Uppsala City, which the site revloves around.
    - Features a text overlay welcoming the user to the site

![Landing page image](https://github.com/linx02/uppsala-city/blob/main/media/landingpage_image.png)

* Landing page content
    - Provides information of famous people from the city
    - Designed to not be heavy and easy for users to digest

![Landing page content](https://github.com/linx02/uppsala-city/blob/main/media/landingpage_content.png)

* Map
    - An interactive map of the city
    - Allows users to easily explore the city via google maps

![Map of Uppsala City](https://github.com/linx02/uppsala-city/blob/main/media/map.png)

* Link to next page
    - Encourages users to further explore the page using a clickable link

![Link to next page](https://github.com/linx02/uppsala-city/blob/main/media/calltoaction.png)

* Footer
    - Footer to mark the end of the page

![Footer](https://github.com/linx02/uppsala-city/blob/main/media/footer.png)

# See & Do page

The purpose of the See & Do page is to provide users with tips for tourist attractions with images and descriptive text.

* See & Do page video
    - Lets user watch recorded footage of the city
    - Video is played muted and allows all controls

![Video of Uppsala city](https://github.com/linx02/uppsala-city/blob/main/media/video.png)

* Tourist attraction images with descriptive text
    - Provides users with high resolution images of some of the tourist attractions of the city.
    - Gives users context to the images

![Images of Uppsala gothic cathedral and botanic garden](https://github.com/linx02/uppsala-city/blob/main/media/touristattraction_images.png)
![Image context](https://github.com/linx02/uppsala-city/blob/main/media/touristattraction_text.png)

* Link to next page

![Link to next page](https://github.com/linx02/uppsala-city/blob/main/media/calltoaction2.png)

# Contact page

The contact page provides a way for users to contact the page author. It is not working and only there for design purposes.

* Contact page image
    - Another image of the city

![Image of Uppsala city](https://github.com/linx02/uppsala-city/blob/main/media/contactpage_image.png)

* Contact form
    - Allows users to contact page author. Not working

![Contact form](https://github.com/linx02/uppsala-city/blob/main/media/contactform.png)

## Testing

 - I have tested the responsiveness of the website using Googles DevTools aswell as visiting the github link through my phone. The website should be fully responsive on all devices.
 - I have tested the links to all pages and they work as they should.
 - I have tested that the footer link opens in a new tab which was a requirement in the Learning Outcomes.

 On smaller screen sizes the layout of the page changes to a more column-structured layout suitable for scrolling.

### Bugs i found

 When working on the responsiveness I came across alot of issues.

 - Whitespace on the right-side of the screen on smaller devices
 - text spilling out of divs and overlapping other elements
 - Images becoming stretched or too small on smaller device screens

 All of these were solved using flexboxes, media queries and responsive units such as rems, ems, vh, vw, % instead of absolute units such as px.

- When deploying project to github pages I found that pieces of my css styling and none of my images were loading

This was resolved by removing the first forward slash in all of the file paths.

### Validator testing

- HTML
    - Errors saying section tags being unnecessary.
        This was resolved by changing them to divs.
    - Errors with iframe styling and attributes
        This was resolved by removing all attributes and styling in seperate CSS file.

- CSS
    - No errors were returned

### Unfixed bugs

No known bugs are left unfixed

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://linx02.github.io/uppsala-city/index.html

## Credits

### Content

- Map
    - The interactive map is provided by Google

- Text
    - Text for image context is generated with ChatGPT

### Media

- Images
    - All images are from google images

- Video
    - Video is downloaded from YouTube. Link: https://youtu.be/5bmT5XvkmZo