
![image](/assets/images/news-title-header.png) <br>

---

[THE NEWS](https://annaweronica.github.io/european-news-service/)

---

<h1>UX</h1>

**Aim:** <br>
To get updated with the lastest news from choosen countries and within six categories.

**Target audience:**<br>
The user who is interested in latest news from *Country* within *Category*.<br>
The user can choose the *Country* among:
- Sweden as default country, 
- Poland, 
- United Kingdom
- Ireland
- France

>The list of the countries is a subject to be extented. <br>

There are six categories for each *Country* to choose from: 
- Latest news (all categories together)
- Business
- Entertainment
- Health
- Science
- Sports
- Technology

**Layout:**<br>
Simple, clean and easy to read and navigate.<br>

**Styling:**
- Font: Abril+Fatface and PT+Serif referring to old-fashion yellow pages newspapers.
- Color: 
    - for header soft-coffe color to not distructed the user from the main purpose.
    - for main content white to make the news clean and easy to read.

**The structure of the news**

- The title of the news
- The image
- Description

![Structure of the news](/assets/images/news-structure.png)

The original news source opens in a new tab of the browser.

**The user path:** <br>
The default settings while opening the webpage:
- *Country*: *Sweden*
- *Category*: *Latest news* (all categories for *Country*) <br>

>*Latest news* section contains all news from different categories together.<br>
>By default clicling on any *Country* only (without selecting *Category*) it will open the *Latest news* section.<br>

The user must scroll down to read the news.<br>

To open the link to the original news source the user can click either on:
- Title of the news
- Image/broken image

The user can be back to the top of the webpage either:
- by clicking on any *Country*
- by clicking on any *Category*
- by clicking on a *Go up* button on the right bottom of the webpage

**Optional paths:** <br>

- *Country: Sweden* -> *Category: Health* -> *Category: Science* -> <br>
- *Country: France* -> *Category: Science* -> <br>
- *Country: Poland* -> *Category: Science* -> *Category: Health* -> <br>
- *Country: Ireland* -> *Category: Health* -> *Category: Latest News*<br>

>Following the logic:

>- The user can click on the *Country* to see *Latest news* from *Sweden* and choose *Category* *Health* and then change the *Category* for *Science* <br>
>- Then the user can change the *Country* for *France* but he will automatically stay in the last *Category* which is *Science*
>- If he changes the *Country* for *Poland* he will still automatically stay within the same last choosen *Category* which is *Science* 

staying within the *Catogory* *Science* the user can change the *Country* for Sweden and he will stay within the same *Category* (just different *Country*)
- To be back to the *Lastest News* for *Country* the user can click on *Lastest News* section

Wireframe for browser, iPod and iPhone view:<br>
![Browser, iPod, iPhone view](/assets/wireframes/all-view.png)

USER STORIES
- As a user I want to see news from the default country as I open the webpage.
- As a user I want to be able to choose from which country I want to read the news from.
- As a user I want to get news by default from all categories for choosen country.
- As a user I want to be able to choose the news category for choosen country.
- As a user I want to move from the category to the same category but changing the country.
- As a user I want to be back from choosen category to all latest news by clicking on *Lastest news*.
- As a user I want to have the header minimalized while scrolling down.
- As a user I want to see on which element I hover the mouse.
- As a user I want to see a no-image if there is not image available.
- As a user I want to see a broken image icon if the image is availe but no displayed.

<h1>Features</h1>

**Existing features:**
- Shrinking header
- Select *Country*
- Select *Category*
- Going back to the top webpage
- Hover on the clickable elements of the webpage.
- Swedish flag as an icon in the browser tab title

**Future features to implement**
- Search news input
- Language translations
- Weather-widget for the country on *Country* click
>   - The developer made an attempt to implement the weather widget and succeced.
>   - It has been removed due to crashing the webapage. It was not optimal.
>   - The widget was taken from [darksky.net](https://darksky.net/widgets/small)<br>
>   ![widget](/assets/images/widget.png)

<h1>Technologies</h1>

HTML/HTML5<br>
CSS/CSS3<br>
JavaScript<br>

**Frameworks:**<br>
Bootstrap<br>

**External sources imported to the project:**

BootstrapCDN<br>
popper.js<br>
Google fonts<br>
Font awesome<br>

**Online IDE:**<br>
GitPod

**Hosting service:**<br>
GitHub

**Knowledgeable resources which supported the Developer during her work:**

- [w3school](https://www.w3schools.com/js/default.asp)
- [stackoverflow](https://stackoverflow.com/)
- [Code Institute lerning materials](https://courses.codeinstitute.net/program/FullstackWebDeveloper)


**External code sources implemented and modified:**
- [stickey header](https://www.w3schools.com/howto/howto_js_sticky_header.asp)
- [scroll top](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp)
- [stickey footer](https://startbootstrap.com/snippets/sticky-footer-flexbox/)

<h1>Testing</h1>

**HTML Validator**
- No errors or warnings to show. However:
    > Please note: there is a workaround to avoid a warning *article without the heading*: <br>
    > `<article class="col-lg-4 wide-column col content-wide">`<br>
	>					`<h1>News</h1>`<br>
	>					`<div id="main-content">`<br>
	>					`</div>`<br>
	>				`</article>`<br>
    > To avoid another warning: *empty heading* in the `<h1>` in the `<article>` had to be added.<br>
    > `<h1>News</h1>` is not visible on the webpage due to top margin on the main content.

**CSS Validator**
- No Error Found.

**JS Hint**<br>
- Metrics:

There are 9 functions in this file.<br>
Function with the largest signature take 2 arguments, while the median is 0.<br>
Largest function has 21 statements in it, while the median is 4.<br>
The most complex function has a cyclomatic complexity value of 5 while the median is 1.<br>

Two unused variables:
	- latestNews
	- news_query<br>
There are called in HTML.<br>

<h2>Manual Testing</h2>

Webpage and its responsiveness was tested on follwoing browsers:

| Chrom     | FireFox   | Edge      | Internet Explorer |
| --------- | ----------| --------- | ------------------|
| supported | supported | supported | not supported     |


<h2>TESTING THE FEATURES</h2>

1. Selecting the *Country* 
2. Selecting the *Category*
3. Clicking on the *Go up* button
4. Shrinking header
5. Hover on the clickable elements of the webpage.
6. Swedish flag as an icon in the browser tab title

**All the features were tested on all size devices and bugs weere detected**

<h2>TESTING USER STORIES</H2>

1. As a user I want to see news from the default country as I open the webpage.
2. As a user I want to be able to choose from which country I want to read the news from.
3. As a user I want to get news by default from all categories for choosen country.
4. As a user I want to be able to choose the news category for choosen country.
5. As a user I want to move from the category to the same category but changing the country.
6. As a user I want to be back from choosen category to all latest news by clicking on *Lastest news*.
7. As a user I want to have the header minimalized while scrolling down.
8. As a user I want to see on which clickable elements I hover the mouse.
9. As a user I want to see a no-image if there is not image available.

    ![no-image available](/assets/images/no-image-available.png)

10. As a user I want to see a broken image icon if the image is available but no displayed.

    ![available image but not displayed](/assets/images/image-not-displayed.png)

**All User Stories were tested on all size devices and bugs were not detected.**

<h1>Deployment</h1>
The webpage is hosted on github with one master branch: [https://github.com/annaweronica/european-news-service](https://github.com/annaweronica/european-news-service)

Commends below were made as the work incrementation was made progressively and prevented from any code incrementation loss.

- git add .
- git commit -m "name"
- git push

<h2>GitHub Pages</h2>

**To deploy a website on GitHub Pages, follow these steps:**

1. Go to [GitHub repository](https://github.com/annaweronica/european-news-service)
2. Click on Settings
3. Scrolling down you will find GitHub Pages
4. Click on the Source dropdown menu
5. Select master branch
6. Should appear a green message saying *Your site is published at* [https://annaweronica.github.io/european-news-service/](https://annaweronica.github.io/european-news-service/)

**To create a local development repository, follow these steps:**

1. Go to [GitHub repository](https://github.com/annaweronica/european-news-service)
2. Click on the Clone or download
3. Click the check list icon on the right of the newly opened window to clone the repository using HTTPS
4. Open Terminal
5. Change the current working directory to the location where you want the cloned directory to be made
6. Type git clone and paste the URL you copied in step 3 and run the command


<h1>Credits</h1>
Anna have joined Code Institue to leran as much as she can from the best teachers, tutors and mentors so she believs she will have the opportuinity to find the job as Developer after graduation of CI programme.
<br>

**Inspiration**<br>
[tvn24](https://tvn24.pl/)

<h2>Content</h2>

[API](https://newsapi.org/)<br>
All flag icons made by <a href="https://www.flaticon.com/authors/roundicons" title="Roundicons">Roundicons</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a><br>
[No photo image](https://www.freeiconspng.com/downloadimg/23483)<br>
The wireframe was made on the [balsamiq cloud](https://balsamiq.cloud/sxgoi9m/projects)

**Thank you**<br>
@Xav @Kevin for support during the project<br>
@Anna for inspiration on readme.md 

---

Enjoy!