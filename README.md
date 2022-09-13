<h1>Welcome to Two Dogs!</h1>
<p>Two Dogs is a blog site that hopes to bring light-hearted and entertaining content by showcasing events in the life of the Two Dogs - Wreckless Eric and Baby Jim. It includes stories, images and videos about what they get up to in their day-to-day life.
Responsive Mockup</p>
<br>

<h2>Features</h2>
<p>The first release of the Two Dogs site includes several vital features which are detailed below. Future releases should include additional features as outlined in the 'Features Left to Implement' section below.</p>
<br>

<h3>Existing Features</h3>
<strong>Navigation Bar</strong>
<p>Featured on all pages, this fully responsive navigation includes links to the landing page, the meet page, the tails blog page, the gallery and the blog sign up page. It is exactly replicated across the site to ensure consistency for the user.</p>

<p>The navigation allows users to browse the site from any page without having to use the back button on their device.</p>
Nav Bar screenshot
<br>

<strong>The landing page image</strong>
<p>The landing page opens up to an image of the two dogs, enticing the user to explore the site further and find out more about them. The image has a slight zoom to help focus the user on the call-to-action, beginning their journey on the site.</p>

<p>Also on this page, users can find a teaser for the blog in the form of the latest blog post and some additional information on the breeds of the dogs.</p>
Landing Page image
<br>

<strong>The Footer</strong>
<p>**The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user.
The footer is valuable to the user as it encourages them to keep connected via social media</p>
Footer screenshot
<br>

<strong>Meet page</strong>
<p>**This section will allow the user to see exactly when the meetups will happen, where they will be located and how long the run will be in kilometers. This section will be updated as these times change to keep the user up to date.</p>
Meet screenshot
<br>

<strong>Tails Blog</strong>
<p>Intro</p>
Tails screenshot
<br>

<strong>Gallery</strong>
<p>**The gallery will provide the user with supporting images to see what the meet ups look like.
This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together.</p>
Gallery
<br>

<strong>The Sign Up Page</strong>
<p>**This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address.</p>
Sign Up screenshot
<br>

<strong>Sign up form</strong>
<p>The sign up form, housed on the sign up page, allows users to quickly identify their interest in receving a periodical blog to their email inbox with information about the two dogs.</p>
screenshot
<br>

<h3>Features Left to Implement</h3>
<ul>
    <li>CMS for adding and organising blog posts and image/video content</li>
    <li>Automated emails to subscribed users with optional daily, weekly or monthly updates</li>
    <li>Comments and social sharing on blogs</li>
    <li>Option to utilise dynamic image sizes at different screen sizes</li>
</ul>
<br>

<h2>Testing</h2>
<p>Throughout the development of this site, testing was carried out on different devices using the developer tools on multiple browsers including Chrome, Firefox and Microsoft Edge. This was repeated at the final testing phase of the project but also included additional browsers including Safari and Opera at this stage.</p>

<p>It is worth noting that as Apple has suspended support for Safari on Windows devices, testing for this browser was conducted using the free <a href="https://www.lambdatest.com/">LambdaTest tool</a> which may limit the accuracy of the tests.</p>

<p>For all testing, each page was reviewed across the following criteria;
<ul>
    <li>Layout and positioning (ie is everything where it's expected to be on all devices)</li>
    <li>Functions (ie buttons, links, inputs, etc)</li>
    <li>Features (ie image rendering, form fill and submission, etc)</li>
    <li>Consistency, convention and expectation (ie does it allow affordance to the user)</li>
</ul>
</p>

<p>
During initial testing, more efficient ways to approach the html structure and css of this site were dicovered and an attempt was made to improve it. This resulted in large changes than expected, such as the move to using styled sections over individually targeted elements, and required additional fixes and testing before release.</p>
<br>

Additionally, the sight was evaluated by Google's Lighthouse and Page Speed tools. The results were as follows.

<strong>Lighthouse</strong>
<ul>
    <li>Performance - </li>
    <li>Accessibility - </li>
    <li>Best Practices - </li>
    <li>SEO - </li>
</ul>
<br>

<strong>Page Speed</strong>
<ul>
    <li>Mobile - </li>
    <li>Desktop - </li>
</ul>
<br>

<h3>Validator Testing</h3>
<strong>HTML</strong>
<p>In the first round of html validator testing, button tags and section/article tags were found to be used incorrectly. In addition, there were a small number of open tags and unnecessary tags that needed to be addressed.</p>

<p>The second round, conducted after implementing the new structure,...</p>

<p>The third and final round returned no errors for this project.</p>
<br>

<strong>CSS</strong>
<p>In the first round of css validator testing, some unclosed attributes were found. This highlighted that these attributes that were unecessary to the output of the code and were removed.</p>

<p>The second round, conducted after implementing more efficient css,...</p>

<p>The third and final round returned no errors for this project.</p>
<br>

<h2>Unfixed Bugs</h2>
<strong>Images</strong>
<p>Unfortunately image rendering falls short of expectation as on different screen sizes images present differenty. Although efoorts were taken to reduce the impact with additional css and properly prepared files, not all images on the Two Dogs site are currently optimised for every screen. In particular, the hero image on the landing page has provided a challenge and should be addressed in future iterations of this site.</p>
<br>

<strong>404 Error</strong>
<p>Due to the limitations of GitHub, a custom 404 page has not been implemented. However, one has been developed along side the project for release and is ready to be implemented when applicable.</p>
<br>

<h2>Deployment</h2>
<p>**This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)
**The site was deployed to GitHub pages. The steps to deploy are as follows:
**In the GitHub repository, navigate to the Settings tab
 **From the source section drop-down menu, select the Master Branch
**Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
**The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html</p>
<br>

<h2>Credits</h2>
<h3>Code</h3>
<p>The code from this project was implemented by the project owner, Louise Stanley. Additional help, guidance and solutions were also used from the below sources.</p>
<br>

<strong>Code Institute - Love Running Walkthrough Project</strong>
    <ul>
    <li><a href="https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/6fd29d155c3b42248ff57bae32978a4b/">Creating the Hero Image</a> for the hero image and text on the landing page</li>
    <li><a href="https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/637be1a2e3b84b25aa33f3ab4d98603c/">Creating the Header</a> for the main nav initial structure</li>
    <li><a href="https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/12ba169db7b34b82b137edd825af6a02/">Creating the Club Ethos</a> for the circle containers of the dog profiles on the Meet page</li>
    <li><a href="https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/e6d4cda2bc08458ba94d2092be9bad3a/">Site Footer</a> for the social media links on the footer</li>
    </ul>

<strong>W3Schools</strong>
    <ul>
    <li><a href="https://www.w3schools.com/howto/howto_css_custom_checkbox.asp">How TO - Custom Checkbox</a> for styling the checkboxes on the sign up form</li>
    <li><a href="https://www.w3schools.com/howto/howto_css_blog_layout.asp">How TO - Blog Layout</a> for the structure of the blog and image gallery</li>
    </ul>

<strong>Slider Revolution</strong>
    <ul>
    <li><a href="https://www.sliderrevolution.com/resources/styling-radio-buttons/">Styling Radio Buttons with CSS</a> for styling the radio buttons on the sign up form</li>
    </ul>
<br>

<h3>Content</h3>
<p>Although the content is unique, the project including layout, features and readme file were guided by the Code Institute <a href="https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSSE_PAGPPF+2021_Q2/courseware/66cf361c769a41d496f5001fae6f9be7/3b5cd5dc8313462aa5975a3c9b9a1a3c/">Portfolio 1 Assessment Guide</a>.</p>

<p>All written content was provided by the project owner, Louise Stanley.</p>
<br>

<h3>Media</h3>
<p>Images and videos were generated by Louise Stanley with the exception of the background image for the About Breeds section. Please see content creator information below.
<ul>
    <li>
    Photo by <a href="https://unsplash.com/@hannah15198?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hannah Lim</a> on <a href="https://unsplash.com/s/photos/breeds?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
    </li>
</ul>
</p>