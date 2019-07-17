
# Mother.MoonBeam | Arts and Crafts

User Centric FE Development Milestone Project - Code Institute

This is a website that I created for my friend as way of showcasing her arts & craft skills. The Site incorporates options for custom designs and also items for sale, also including an about me section. This site stems from the Instagram account and so the website is based on traffic coming from the Instagram page, so it has a mobile first centered design. 

### **Demo:**

A live demo can be found [here](https://brianscan14.github.io/FE-1st-Milestone-Project/index.html)

### **UX:**

The main goal of the site was to direct users to her portfolio where they can see her items for sale, or indeed submit a bespoke order. This was all done while conforming to a simple colour scheme and sheek design.

For the customer, I wanted to give them a relatively simple site to show off her interests/talents/items. Links are provided on all pages which will either bring you to the shop or to contact her for custom orders or enquiries. There are links to blogs for customers to click into and read in a new window, and an about me section was also made with a picture of the individual. These all give the customer a glimpse of the person and her interests, which may entice them to contact her more if they have similar interests. There are also links at the bottom of each page in order to quickly access social media/PayPal platforms.

##### Client Stories

1. Being a new visitor to the website, I want to be able to easily navigate the site and find what I was looking for within one or two clicks.
2. As a new visitor to the site, I want to see more of what was on her social media page and see all the items on offer. 
3. As a new visitor to the site, I want to learn more about the page owner and get to know her interests and hobbies to see if we have anything in common.
4. As a potential client, I want to be able to understand what range of prices the products are going for, and what price I might expect for a bespoke order.
5. As an interested client, I want the order process to be quick and simple. With an easy to fill out contact form  and text area to let me describe what I need.
6. As an interested client, I want to have easy access to social media links to follow her on different platforms.
7. As a returning visitor to the website, i want to be able to subscribe to her feed in order to keep up with all the latest news and stories.

### **Technologies:** 

- Html
- CSS
- Bootstrap 
- jQuery
- Popper.js
- Google Fonts
- FontAwesome

### **Features:**

The navbar changes on this page with regards to screen size to be more mobile user friendly, as a lot of the traffic will be stemming from a link on the Instagram page. Smaller screen devices utilise a collapse button icon to pick the sections for handiness. The logo is placed above the nav items in order to stand out, and the selected tab is ‘active’ to denote to users what page they are currently on. This allows users to recognise the brand and clicking it returns them to the home page.

There is also a footer at the bottom of every page, which highlights when hovered over to the standard light cream/pink colour. These icons symbolise links to social media and also PayPal, the actual private pages were not included for privacy reasons.

##### Home:

At the top of the home page a hero banner is featured which stems across the width of the screen. On the left is an old telly which includes the page logo, and on the right the colour scheme kicks off with some text and a link to the shop. The telly image is removed for smaller screens so as not to be taking up too much scrolling time with unnecessary content that doesn’t entice the user to engage. The direction to purchase items begins straight away on the page.

Below that then there are two sections styled in the colour scheme. These sections provide links to the shop again, and the other to the contact page if they wanted a customer order, these links open on the same page so that a mess isn’t created with redirections.

There is then some more sections which are styled with borders to give the page a bit of style, these show off her interests. Links to blogs are incorporated (the blogs will need to be created by the person) which will give the user a better idea of the individual’s interests and skills.

A photo banner then scrolls across the page on larger screens which showcase the Instagram photos. These photos scale slightly when hovered over, the 1st, 2nd and 3rd photos had to be repeated in order to give the illusion of a continuous carousel as there is no JavaScript functionality.

##### About:

The about section once again carries the same theme as the home page with respect to a full width banner, with the picture on the left of the individual. The right section then incorporates a little bit about the person and what can be found on the page. Links are included in this text to contact her or browse the shop.

There is then a subscribe option included which will add  the user’s email to a mailing list that gets updates when new blogs are added or new items are for sale. The proper email format is required for this so that users don’t fill it in incorrectly.

##### Portfolio:

This page is laid out as a standard ‘shop’ page would be, with a filter on the left and items for sale on the right. When on mobile these filter options become a modal button in order to not take up screen room when un-clicked. The column widths are from bootstrap, 3 on a larger page and 6 on smaller screens. 

The quick view comes on when hovered and will open an image in a new tab, which is desired as the user can see the whole thing as opposed to it being stretched or squashed on a smaller screen. Items also have a shadow around them when hovered which will allow the user to see which one they are on even more.

##### Contact:

The contact page is a standard form which you need to fill in to send an email to the page owner. An email must be entered properly on this form and required was added to the name and text sections also to ensure the form is filled out correctly. A nice shadow feature keeping with the colour scheme is also utilised.

### **Features left to implement**

Adding JavaScript functions to the banner at the bottom of the home page to cycle through the photos would enhance its usability, the buttons allow for a person to ponder on a picture instead of it constantly scrolling. 

I would like to add more content to the shop page, which would give users more to choose from when browsing the page. Also more photos of the items would allow for a better ‘quick view’ function when clicked, JavaScript would also be needed for this.

Adding JavaScript functionality to the filter section on the Portfolio page would improve its user interaction with the page, making it simple for them to swift through different means of filtering the shop items.

### **Testing**

The intended outcome of this site was achieved as I was able to showcase her work and talents while also allowing the user to get know her a bit better. In the about me section they can read a bit about her and her backgrounds along with her interests, while a portrait of her serves as the background. All of her items for sale are easily accessible in the portfolio section and these can then be opened to full screen in a new tab for a closer look. Most links on the sites also encourage the user to either visit the shop or contact her for more bespoke orders. The footer of every page also incorporates a link to her social media accounts.

The contact form needs to be filled out correctly in order for it to work. If an invalid email address is entered then an error will pop up informing you. The ‘required’ attribute is also utilised for email, text and name fields so that if they aren’t filled out correctly it will not submit. The same features are also applied to the subscribe button on the about page to ensure the email is filled out correctly.

Clicking on the logo of the navigation bar will bring you back to the home page at all times in case the user gets misdirected. Using ‘target="_blank"’ on the blogs and the shop items allows for them to be opened in a new window and be and for the user to be fully immersed in them. All links have been tested to ensure that they are pointing in the correct direction.

This site was tested across various browsers and devices. Chrome, Safari, IE and Firefox were tested on laptops, computers, iphones 5 & 7, an ipad and also samsung phones 6 & 8. It was during this testing I realised that the backgrounds of images needed to be changed to the same as the overall background in case it didn't load properly. I also realised that the animated banner wasn't being called correctly for IE page, so this was also corrected.

### **Deployment**
Cloud9 was utilised for this project, changes were committed to git and pushed to GitHub as they were made using this IDE. To deploy this page to GitHub pages from its GitHub repository, you need to:

1. Log in to the GitHub website
2. Select **brianscan14/FE-1st-Milestone-Project** from the repositories.
3. Select setting in the items at the top of the screen.
4. Scroll to Github Pages, click the drop-down menu labelled none and chose Master Branch.
5. The link is now available in the GitHub pages section for the deployed website.

The Development branch and the master branch are matching at the time of submit of the project.

##### To run locally:

1. Follow link to the [project's repository](https://github.com/brianscan14/FE-1st-Milestone-Project.git) on GitHub.
2. Click on 'clone' or 'download' under the repository name.
3. Copy the URL into the clone with HTTPs section.
4. Open git bash in your local IDE in the working directory where you want the cloned directory to be made.
5. Type 'git clone', and paste the URL previously copied, and hit enter.

This will create your clone.

### **Credits**

##### Content

All content in the about me section and home page were written by myself.

##### Media

All pictures were gotten for the Instagram page, the image of the telly was a stock photo which can be found [here](https://www.stockphotobucket.com/).

##### Acknowledgements

The photo banner was obtained with help from WE3 School’s example [here](https://www.w3schools.com/css/css3_2dtransforms.asp) and Tutorial
Republic’s [example](https://www.tutorialrepublic.com/css-tutorial/css3-2d-transforms.php). They were then significantly modified to make the bottom banner for the home page.

##### Disclaimer

This is for educational purposes only.