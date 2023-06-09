# ZenYoga
The ZenYoga website provides comprehensive information about a serene yoga studio located in the heart of Glasgow, Scotland. It caters to both experienced yogis and beginners, offering a detailed class schedule for the entire week and vivid descriptions and images of the peaceful surroundings.

There is also a simple Contact Page where users can submit their name and email address if interested in signing up for the variety of yoga classes. 

![zenyoga mockup](/assets/images/screenshots/zenyoga-mockup.png)

## Features
### Exisiting Features
#### Navigation Bar
- The fully responsive navigation bar, featured on both pages, includes links to the Logo, About, Timetable, Yoga Styles, and Sign-up page. 
- It is identical on both pages, ensuring easy navigation for users.
 
![zenyoga navigation bar](/assets/images/screenshots/zenyoga-header.png)

#### Landing Page Image
- The landing page features a photograph with overlaid text, providing a clear overview of the website's offerings - yoga. 
- This section is designed to introduce users to ZenYoga and grab their attention with an eye-catching cover-message.

![zenyoga landing page image](/assets/images/screenshots/zenyoga-firstpage.png)

#### About Section
- This section aims to provide users with dynamic information about the benefits of practicing yoga. Additionally, it highlights the location (Glasgow) and emphasizes the well-lit and naturally-lit studio. 
- The section also delivers a warm and friendly greeting, welcoming individuals of all yoga levels.

![zenyoga about section](/assets/images/screenshots/zenyoga-about.png)

#### Timetable
- In this section, users can find a clear and concise schedule for the week's ZenYoga classes. The schedule includes information on each class's start time and style/level. 
- Additionally, a navigation link is conveniently located underneath, allowing users to easily access the sign-up section.

![zenyoga timetable](/assets/images/screenshots/zenyoga-timetable.png)

#### Footer
- The footer section of ZenYoga's website provides convenient links to their relevant social media sites, which open in a new tab for seamless navigation. 
- By utilizing the footer, users are encouraged to stay connected with ZenYoga through their social media platforms, adding value to their overall website experience.

![zenyoga footrer](/assets/images/screenshots/zenyoga-footer.png)

#### Second Landing Page Image
- The second landing page of the yoga studio website showcases a captivating photograph with overlaid text that conveys a clear message of inclusivity, emphasizing that yoga is for everyone. 
- The bold text results in an attention-grabbing design, sure to captivate and engage users.

![zenyoga second landing page image](/assets/images/screenshots/zenyoga-secondpage.png)

#### Yoga Styles
- This section aims to provide a concise and clear overview of the various types of yoga classes offered by ZenYoga, facilitating easy readability of information.

![zenyoga yoga styles](/assets/images/screenshots/zenyoga-yogastyles.png)

#### Sign Up
- This is the sign-up page for users to input their contact information effortlessly. 
- The layout is intentionally kept clear and simple, and is complemented by an image featuring the friendly faces of the ZenYoga team.

![zenyoga sign up](/assets/images/screenshots/zenyoga-signup.png)

### Features Left to Implement
- Gallery

## Testing
- I have tested the functionality of this page across multiple web browsers, including Chrome, Firefox, and Safari.
- After using the DevTools device toolbar, I have confirmed that this page is responsive, visually appealing, and fully functional on all standard screen sizes.
- I have verified that the main sections of the page - the navigation, about, timetable, yoga styles, and contact us - are all presented in a clear and understandable manner.
- I have verified that the yoga timetable found on the first page is easily readable.
- I can confirm that the form on this page is fully functional. The form mandates entries in all fields and only accepts valid email addresses in the email field and the submit button also works.

### Bugs
#### Solved Bugs
- While I tested the input form for the email, it did not intially request that it should be written in an email format. I fixed this by adding an email input type: <b> \<input type="email"> </b>
- The social media links in the first page of the footer was initally not working. I then realised it was because I had missed <b> \</a> </b> after the link to the sign up section at the bottom of the timetable. 
- The Poppins font that I found from Font Awesome initally did not work with Chrome or Firefox. This was fixed when I removed this tag <b> \<meta http-equiv="X-UA-Compatible" content="IE=edge"></b>
- I had intially placed the <b>\<footer></b> element outside of the <b>\<body></b> element which caused some performace issues when I deployed the website. This was fixed when I realised the issue and placed the <b>\<footer></b> element inside of the <b>\<body></b> element.

### Validator Testing

#### HTML
- No Errors were found when passing through the official [W3C validator](https://validator.w3.org/#validate_by_input)
#### CSS
- No Errors were found when passing though the official [W3C validator](https://jigsaw.w3.org/css-validator/)

#### Accessibility 
 - I confirmed that the colours and fonts chosen are easy to read and accessible by running them through Lighthouse in Devtools.

![lighthouse in devtools](/assets/images/screenshots/zenyoga-lighthouse.png)

### Unfixed Bugs
No unfixed bugs

## Deployment
After preparing the site for deployment, the next step was to host it on GitHub pages. I followed these steps to deploy:

- Go to the Settings tab of the Github Repository.
- Under the code and automation section, I navigate to the Pages section.
- In Github Pages, I select the main branch to deploy the page.
- After selecting the main branch, the page will refresh and display a link to confirm the successful deployment.

The live link can be found here -  https://annieross10.github.io/ZenYoga/

## Credits
### Content
- The icons in the footer and links were taken from [Font Awesome](https://fontawesome.com/)
- The font for the website was taken from [Google Fonts](https://fonts.google.com/)
- The instructions to create keyframes for CSS was taken from [This Youtube Tutorial](https://www.youtube.com/watch?v=SgmNxE9lWcY&ab_channel=SlayingTheDragon)

 ### Media
- The image yogaimage is taken from [unsplash](https://unsplash.com/s/photos/yoga-studio)
- The images yogaimagetwo, yogaeimagethree and yogaimagefour were taken from [Pexels](https://www.pexels.com/)
