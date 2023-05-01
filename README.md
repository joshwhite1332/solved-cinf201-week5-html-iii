Download Link: https://assignmentchef.com/product/solved-cinf201-week5-html-iii
<br>
Last week, we learned about validation and why it matters for our HTML. This week, we will learn about metatags and how they are used to provide further information about our HTML documents. We’ll also review some best practices for making our web pages usable/accessible.




<h2>Project Proposal</h2>

Overall, you need to make sure you are explaining your work as much as possible. For the wireframes that means using headings/labels to make your potential layout more understandable. For the style tile, you should include colors, fonts, adjectives and anything else that’s visual to convey a look/feel. The needs assessment will be used to explain everything as a whole.




<strong>Previous Participation Questions/Responses </strong>These are the participation questions from last week:

<u>https://forms.gle/Dtu8w1EoPMrkZEPq7</u>




This link has the responses to the fun question from last week. Feel free to look over the responses from myself and your peers.  <u>https://docs.google.com/spreadsheets/d/1QLoQzbO-</u>

<u>Er7ARIECl0aPvY1lKUyZTdYeuwsn4g0XEAk/edit?usp=sharing</u>




<strong>What’s Due? </strong>

<ul>

 <li>Participation Questions (4)</li>

 <li>SEO &amp; Accessibility Review (CW/HW)</li>

 <li>Project Proposal (9/30 at midnight)</li>

</ul>




<h1>HTML Final Review (Lecture/Class Activity)</h1>

<h2>HTML Validation Review</h2>

Last week, we learned about HTML and discussed the basics of getting our documents up to standard. This week, I’ll go over the previous assignment and how we can use the validator to discover/fix errors.




I will be opening last week’s assignment in Brackets. Feel free to follow along with me as I describe the process for fixing most of the problems in the assignment.




<h2>Search Engine Optimization</h2>

SEO involves building your website in a way that allows for it to be found more easily by search engines when a user makes a query for information. If a user does a search for “lions,” a search engine will pull up relevant results from pages which have information about lions. These pages would have keywords, links, and other materials related to lions which help them rank higher than other pages.




With the proper implementation of SEO, you can give your website a better chance of appearing on the first few pages of search results. Users typically don’t go beyond a page or two in the search, so it’s very important to get your page ranked as highly as possible.




There are a few methods for achieving quality SEO on your website. Some of them are related to the performance of the website while others are related to the content on the website. Websites that aren’t responsive are generally ranked lower than those that work on multiple devices/screen sizes. As for content, using appropriate keywords and structuring your information well helps your page become more findable. If other websites link to your website, that generally will improve its SEO.




Here are some ways to address SEO on a website:

<ul>

 <li>Using appropriate keywords/phrases</li>

 <li>Having relevant content</li>

 <li>Including links to other related sources</li>

 <li>Having other pages link to your website</li>

 <li>Usage of title and meta tags</li>

 <li>Good performance on any device</li>

</ul>




<h2>Metatags in HTML</h2>

These tags are used to provide information about the HTML document that cannot be conveyed or represented by other HTML elements such as link, script, style, or title. The information in these tags is typically used by search engines, browsers, and screen readers.

Metatags almost always go inside of the &lt;head&gt; tag of an HTML document and do not have ending tags. The ones listed in the examples below are some that I have used in our assignment/examples files as well. This is not an exhaustive list but these are the ones you should include in your pages for this course.

<u>Examples</u>

&lt;meta charset=”utf-8″&gt; – This defines the character set for the HTML document.

&lt;meta http-equiv=”X-UA-Compatible” content=”IE=edge”&gt; – This is important to include if you plan on supporting earlier versions of Internet Explorer (IE). It will tell the browser to use the latest version of IE available on that person’s browser. It should be one of the first tags in your &lt;head&gt; tag.

&lt;meta name=”description” content=””&gt; – This is used to describe the content that will be found in the HTML document.

&lt;meta name=”viewport” content=”width=device-width, initial-scale=1″&gt; – This is used to help your content scale to the user’s device. It should always be included as leaving it out will result in your page displaying weirdly on smaller screen resolutions. <u>Additional Reading</u>

<ul>

 <li><u>https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta</u></li>

 <li><u>https://moz.com/blog/the-ultimate-guide-to-seo-meta-tags</u></li>

 <li><u>https://moz.com/beginners-guide-to-seo</u> (There is a lot of great content here, but scroll down the page to Chapter 1 for a brief explanation of SEO)</li>

 <li><u>https://developers.google.com/search/docs/advanced/guidelines/webmaster-guidelines</u> (This is specific to ranking well on Google – not required reading but interesting)</li>

</ul>

<strong> </strong>

<h2>Usability/Accessibility in HTML</h2>

These two concepts are different but have many overlapping ideas. In terms of web development, usability refers to our page’s ease-of-use. We can build features to aid users and prevent confusion with our content. With accessibility, we want users to have access to our content and be able to navigate it without issue. Look at the examples below which are based on an imaginary ball to gain a better understanding of these concepts.




Usable but not accessible: A ball in good condition but located on a high shelf where you can’t reach it. In this case, people could play with the ball, but some might not be able to get to it.




Accessible but not usable: A ball on a short table where everyone can reach it, but it has holes in it. In this case, everyone can reach the ball, but no one can play with it since it is broken.




Not usable or accessible: A broken ball on a high shelf. In this case, the ball can’t be reached by some people, and even if they could reach it, they couldn’t use it since it is broken.




Usable and accessible: Everyone can reach the ball and it is in good condition so it can be used as well.




It is important to build your website to be as accessible and usable as possible. After all, your goal is to get a lot of traffic coming to your website. If your pages aren’t easy to navigate or lack some of the accessibility and usability features I mention below, it will result in a lower rate of visitors to those pages. Think about the times you’ve visited a page that loaded slowly or had intrusive popups or features which hindered your ability to use that page. You may have left the page immediately or decided to not use the site again after that instance.




There are many ways to incorporate usability and accessibility in your pages. I’ve included a basic list to get you started with thinking about the different ways a web page can be enhanced. This list isn’t exhaustive, and some parts aren’t related to HTML specifically, but it’s useful for reviewing before publishing any pages.




<ul>

 <li>Use alternative text with images</li>

 <li>Identify page language using the lang attribute on the html tag</li>

 <li>Use HTML to convey meaning and structure</li>

 <li>Use labels with forms</li>

 <li>Structure content appropriately</li>

 <li>Include appropriate roles for elements (aria roles)</li>

 <li>Make all interactive elements keyboard accessible</li>

 <li>Use a “skip to main” button</li>

 <li>Use easily identifiable and accurate links</li>

 <li>Ensure color contrast is high</li>

 <li>Don’t use flashing or blinking elements</li>

 <li>Don’t use HTML tables for layout</li>

 <li>Give users enough time to read content in slideshows or other interactive items</li>

 <li>Optimize content so pages load quickly</li>

</ul>




<h1>SEO &amp; Accessibility Review (CW/HW)</h1>

<strong><u>There are two parts to this assignment.</u></strong> You’ll do a search on a topic and then use the findings for two separate write-ups. You should view the page source and look through the head tag of the document to see the meta tags. Also, check the title tags and general content as far as keywords and headings. I’ve included instructions/questions for each part. You don’t have to answer every question, but additional details will enable you to provide a more complete picture of each website/search term used.




<h2>Part 1</h2>

Perform a search in a browser on a topic of your choice. After getting search results, look through the various websites on the very first page. Also, visit some websites that are located after a few pages of results. To do this, scroll to the very bottom of the search results page and select a higher page number. The first red “o” lets you know which results page you are on currently. In both images below, I am on the very first results page. Once you are done looking through a few websites, try to answer some of the questions listed in the next paragraph.




Google Chrome










Microsoft Edge







How do the websites on the first page compare to the websites in later results pages? Are their differences in what different search engines display? Did your search term appear in the websites ranked lower in the search results? Are there any keywords that you’ve seen repeated across the websites? Why do you think one website is ranked higher than another? Do the websites appear to have an information hierarchy of some sort? What information seems to be the most important? How can you tell? Are semantic tags being used? If not, what are some tags (if any) that you feel should be used on the page? What meta tags are being used?




In your write-up, be sure to include the search terms exactly as you used them and briefly mention the websites you compared. This will allow me to perform the same exact search and check for results. You should write at least two paragraphs on the search term, the websites, the features you found, and how they compare to each other.




<h2>Part 2</h2>

Pick one website from the first page of your results and one website from a page beyond the 5<sup>th</sup> page of results and compare their usability/accessibility in at least two paragraphs. Specifically, I’d like you to consider some of the following ideas:




<ul>

 <li>Which website is more usable/accessible in your opinion? Why?</li>

 <li>Are the sites easy to use?</li>

 <li>How is the information architecture?

  <ul>

   <li>Does a clearly established hierarchy exist? o Can you tell where the main navigation is?

    <ul>

     <li>How do they handle their navigation on smaller screens? Can you use your keyboard to navigate the websites? (try to press tab) • Do the websites work well on a mobile device?</li>

    </ul></li>

   <li>Are the buttons and links easy to tap? What about input boxes?</li>

  </ul></li>

 <li>Is the color contrast high enough?</li>

 <li>Do the websites let you accomplish the tasks they say they will?</li>

 <li>Can you identify the website’s purpose from the homepage?</li>

</ul>

Use various web tools to aid your evaluation and look at the checklist/PowerPoint document provided with today’s lecture notes.

<ul>

 <li><u>https://webaim.org/resources/contrastchecker/</u> (plug in color values)</li>

 <li><u>https://wave.webaim.org/</u> (copy and paste link)</li>

</ul>

Google has a built-in accessibility audit (inspect the page, go to the “Audits” tab all the way to the right. Uncheck everything except “Accessibility” and then click “Generate Report”




Your write-up is <strong>due September 30<sup>th</sup> at 6pm. </strong>To submit the work for this exercise, go to

Blackboard à Course Materials à Lecture Notes for this week’s class. You can also visit the “Assignments” folder and the submission area will be titled “SEO &amp; Accessibility Review.” <strong><u>You</u> <u>must submit a Word document or something else I can open</u></strong>. The work submitted will be evaluated based on the rubric explained below.




<strong><u>SEO &amp; Accessibility Review – 10pts</u> </strong>

<ul>

 <li>Part 1: 5pts o Did you include your search term(s)/websites checked?

  <ul>

   <li>Length of write-up o Quality of content:

    <ul>

     <li>Relevant discussion of website terms</li>

     <li>Compared at least two websites</li>

    </ul></li>

   <li>Part 2: 5pts o Did you mention the websites you evaluated?

    <ul>

     <li>Length of write-up o Were specific items about the website mentioned?</li>

     <li>Did you evaluate the websites based on the criteria mentioned in lecture notes?</li>

    </ul></li>

  </ul></li>

</ul>




<h1>Participation Questions 9/23</h1>

To receive credit for participation in today’s class, please answer all the questions in the Google Form linked below. If you don’t want to answer the final question (fun), simply put N/A (not applicable) for your answer and that will count.




<h2>This Week’s Participation Questions: <u>https://forms.gle/W6dBh1R4NCAfwN7T8</u></h2>




<strong>Previous Participation Questions/Responses </strong>These are the participation questions from last week:

<u>https://forms.gle/Dtu8w1EoPMrkZEPq7</u>




This link has the responses to the fun question from last week. Feel free to look over the responses from myself and your peers.  <u>https://docs.google.com/spreadsheets/d/1QLoQzbO-</u>

<u>Er7ARIECl0aPvY1lKUyZTdYeuwsn4g0XEAk/edit?usp=sharing</u>




<h1>Next Week</h1>

We will learn about Cascading Style Sheets (CSS) and how they can be used to add some personality to our web pages. Go through the following links to get an idea of how CSS can be implemented on a web page.

<ul>

 <li><u>https://www.htmldog.com/guides/css/</u> – CSS Beginner Tutorial only</li>

 <li><u>https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS</u></li>

 <li><u>https://www.tutorialspoint.com/css/css_syntax.htm</u> – Specific syntax examples</li>

</ul>