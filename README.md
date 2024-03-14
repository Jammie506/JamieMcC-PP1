![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Love Swimming!

Love Swimming is a website that aims to provide a smooth and friendly way for people to start swimming, improve their skills or just make new friends. The site will be primarily targeted towards adults living and working in and around Dublin City Centre. The site will allow users to join tailor-made classes to begin lessons or to improve their fitness and swimming abilities.

The site will also allow users to set up their own “Community Meets”, allowing for the growth of the community into more specialized training sections for all abilities and styles. Love Swimming will also be useful for swimmers to progress their skills in the water to their desired level, whether this would be to join a more competitive team to compete in races or simply to feel more confident in the water on holidays.


## Features

* Navigation Bar
    * In place at the top of all pages, this allows users to easily navigate the entire site without the need to use external controls, such as the browser “Previous Page” or “Back” button.
    * The simplistic design of the Navigation Bar clearly outlines all that is available for visitors to the site, both on Mobile and Desktop.
    * The Navigation Bar has been designed to automatically hide using CSS on smaller screens, to be replaced with a menu icon, in order to prevent visual overcrowding.

* Home Page
    * The home page includes a large “Hero Image” that draws the user’s attention, encouraging them to remain on the site.
    * The use of bright colours also served to catch the user’s attention by creating a visually appealing page.
    * On large screens the page is laid out in such a way that users can see some of the content below the hero image, encouraging them to scroll to read it. This can increase the amount of time that the user remains on the site.

* Benefits of Swimming
    * This section outlines some of the reasons that users may be interested in joining the club.
    * The various and wide-ranging information should help to encourage a wider audience of people to become interested in the club.

* Meet Ups & Community Meets
    * This page allows users to see what option they have for attending a club meet for a specific purpose, such as for general training or as a way to attend more focused training.
    * The “Community Meets” section allows users to explore training sessions created by members of the wider Love Swimming community.
    * The “Community Meets” section allows users to explore training sessions created by members of the wider Love Swimming community.

* Social Media Section
    * On each page, located in the footer of each page allows users to find the club in alternate places outside If the primary website. This can help encourage them to incorporate the club into their social life, increasing attendance.
    * As the links to social media are pinned to the bottom of each page, they remain unobtrusive yet easily accessible for all site users.

* Gallery 
    * Page contains images of past club events to give new and existing members a chance to see what the club is about and what they have been involved in previously.
    * This page has value as it allows viewers to see what the team organises and establish if it is something that they would be interested in overall.

## Features to be Implemented

* Competitions Page
    * The competitions page will collate any local or regional competitions into a single location for simmers, this will allow them to easily see all upcoming competitions. 
    * This page will specifically work as a directory for all upcoming events, linking users out to external pages while also providing information on how to enter the competitions as part of the Love Swimming team.

## Testing

* A majority of the testing for this website was conducted using the Responsive Screen Size tool within Google Chrome’s dev mode. This allowed me to ensure that the design elements all worked across different simulated screen sizes. This also allowed for stress testing of the site by rapidly changing the size of the screen.
* The site was deployed via GitHub Pages to ensure that there were no issues that occurred between the initial development stage and the full launch of the page. Some issues were encountered during this phase and were thus resolved.
* The site was tested across multiple devices, including an iPhone 12 Pro Max and a Samsung device. The latter of these revealed an issue with the Community Meet form where the form itself overflowed the backing image. This issue was then was then resolved by matching the maximum height of the form to the height of the image.
* An issue was found in testing where the Community Event button did not scale in the same method as the rest of the meetups. This issue was resolved by adding the “Flex Grow” property to all links within the “times” class on the page. This also ensures that any further buttons that need to be added to the page will match the existing styling be default.

## Validator Testing

* HTML
    * No errors were found when testing through the [W3C validator] (https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)

* CSS
    * No errors were found when testing through the [Jigsaw validator] (https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

## Unfixed Bugs

* No unresolved bugs were found at this point during testing

## Deployment 

* The site was deployed to GitHub pages. The steps to deploy are as follows: 
    * In the GitHub repository, navigate to the Settings tab
    * From the source section drop-down menu, select the Master Branch
    * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://jammie506.github.io/JamieMcC-PP1/

## Credits

* The initial layout and concept of the page was taken from the Code Institute “Love Running” project, however, it was altered both in content and building to ensure that it was sufficiently different. This included adding new content and changing some of the styles for the overall page.
* Some additional information on HTML and CSS syntax was found using Web3 School website (https://www.w3schools.com/)

## Media

* All media and images for this site were found via unsplash.org. A full list of image attributions can be found [here] (notes.txt)
    

    
    
    
    

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 20 2023:** Update Python version to 3.9.17.

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
