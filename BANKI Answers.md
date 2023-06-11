# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list without answers, courtesy of https://leonnoel.com/100devs/

---

## Table of Contents

1. [Behaviorial](#behavioral)
2. [Technical](#technical-questions)
   - [HTML](#html)
   - [CSS](#css)
   - [Javascript](#javascript)
   - [Javascript General](#javascript-general)
   - [Node](#node)
   - [CS Theory](#cs-theory)
3. [Questions to ask your interviewer](#questions-to-ask-your-interviewer)
4. [Whiteboard](#whiteboard)
5. [Resources](#resources)

---

## Behavioral

Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering begin with "At my last opportunity..." or "At my last company". Don't sell yourself out and say "bootcamp" or "school".

### CAR

- **Cause**
  - Why did you need to take action?
- **Action**
  - Steps you took so solve problem
  - Be positive
  - Don't be humble
- **Result**
  - How are you better?

### Questions

- [x] B1) Give me an example of a project or initiative that you started on your own. What prompted you to get started?

  - **Cause:** During my time at a training agency called 100devs, I began a standalone tutorial project to assist the some of our students in understanding the basics of CRUD app development and CSS styling.
  - **Action:** I saw an opportunity to go beyond the typical CRUD app by incorporating elements from entertainment franchises to generate increased user engagement. Thus, I began production of a full-stack deck building app centered around Pokémon cards. Because Pokémon has a large fan base and is well-known among different age groups, I felt choosing this theme for the app would making it more likely for members of the cohort to explore and interact with the examples and apply what they learned towards their own projects.
  - **Result:** As a result, the cohort was a tremendous success and allowed me to educate others on the vast possibilities of CSS styling and CRUD fundamentals which went on to inspire them to think creatively when developing and designing their own projects. This initiative allowed me to showcase my abilities as a fullstack developer, provide value to users through engaging examples, and demonstrate my creativity in applying technical skills to real-world projects.

- [x] B2) Tell me about a time you had to work on several projects at once. How did you handle this?

  - **Cause:**  Within the freelancing side of my software engineering career, I've often found myself managing multiple client projects concurrently.
  - **Action:** I've handled these substantial workloads by prioritizing each project based on factors such as client deadlines and app complexity. In addition, I provide each client with frequent, organized updates regarding deliverables and timelines in order to set realistic expecations. Throughout the development phase, I will also schedule and break down each project into smaller tasks, which are they allocated to specific time slots. This allows me to make steady progress on all projects through efficient time management.
  - **Result:** As a result, by following these strategies, I've been able to successfully manage multiple projects simultaneously during my freelance web development experience. I've delivered high-quality work, met client expectations, and maintained a professional approach throughout each engagement.

- [x] B3) Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?

  - **Cause:** During my freelance website development work for a client, I encountered a situation where I had not effectively communicated the payment details due to the process of establishing an LLC. As a result, the client kept making checks out to my business name, which I could not cash in my personal name.  
  - **Action:** To compensate for the communication difficulty, I decided to exempt one of the payments that I was owed from the client because I valued our business relationship and didn't want this mishap to cause unnecessary tension throughout the development process.
  - **Result:** By taking these steps, I addressed the communication gap, rectified the payment issue, and provided compensation for the difficulty caused. This helped me retain my client and avoid unnecessary agitation from a misunderstanding. I took ownership of the mistake and used this as a lesson going forward on how to more effectively communicate payment details with future clients.

- [x] B4) Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?

  - **Cause:**  In my current role at CodeStream Studios, I encountered a situation where conflict arose within the team regarding an unreasonable time frame for a large project. Due to an upcoming and improptu meeting with potential clients and stalkeholders, management had requested the completion of said project within a tight deadline that seemed unrealistic given the scope and complexity of the task.
  - **Action:** When I became aware of the timeline set by management, I proactively approached them to express my concerns. I explained the potential risks associated with rushing the project and the possible negative impact on the quality of deliverables. However, despite my efforts to convey the challenges and propose alternatives, I was unable to fully convince management to adjust the timeline. 
  - **Result:** As a result, I buckled down and confirmed with management that I would still give 110% towards the project. I collaborated closely with my team to get a rough prototype ready by the deadline, which was met with appreciation by management. Even though I was unsuccessful in negotiating for more time, this situation taught me the importance being adaptable to situational changes, and to always communicate my disagreements with organized data and research. 

- [x] B5) Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?

  - **Cause:** In a previous project, I encountered a challenging coding problem where a web application was experiencing severe performance issues due to fetching a large amount of data from an external API. The traditional approach of querying the API and rendering all the data on the client side was resulting in significant delays and a poor user experience.
  - **Action:** To tackle this issue, I decided to take a creative and unusual approach by implementing pagination on the API fetch. Instead of retrieving the entire dataset in a single request, I devised a solution where the data would be fetched in smaller chunks or pages. I introduced pagination controls, allowing users to navigate through different pages of data and fetch only the necessary subset of records at a time.
  - **Result:** Implementing pagination on the API fetch yielded remarkable results. The web application's performance improved significantly, as it now retrieved and rendered a smaller portion of data per request. This led to faster loading times, enhanced responsiveness, and an improved user experience overall.

- [x] B6) Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?

  - **Cause:** In a recent freelance website development project, I worked diligently to create a visually stunning and user-friendly website for a client in the real estate industry. However, despite my efforts, the website did not generate the expected level of user engagement and conversions.
  - **Action:** Upon reflection, I identified a few reasons why the desired results were not achieved. Firstly, the project had a tight timeline, which limited the amount of time available for thorough user research and testing. As a result, some design decisions were made without obtaining sufficient user feedback, leading to suboptimal user experiences.
  - **Result:** From this experience, I learned the significance of allocating adequate time for user research and fostering effective communication with clients. I now prioritize thorough user testing, engage in regular client check-ins to align on project goals, and emphasize the importance of realistic deadlines to ensure high-quality deliverables.

- [x] B7) Give an example of an important project goal you reached and how you achieved it.

  - **Cause:** In my role as a frontend developer at CodeStream Studios, we had an important project goal to optimize the loading performance of our learning management system (LMS) to enhance the user experience for students and educators.
  - **Action:** To achieve this goal, I employed several strategies. First, I conducted a sweep of the LMS codebase to identify areas of improvement. I then set about reducing the size of CSS and JavaScript files and implementing lazy loading for non-critical resources, all in order to optimize rendering paths. I also collaborated closely with the backend team to optimize API responses, reduce unnecessary data transfer, and implement server-side rendering for frequently visited pages.
  - **Result:** As a result, we successfully achieved the project goal of significantly improving the loading performance of our LMS. This resulted in a more seamless and efficient learning experience for our users.

- [x] B8) Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way?

  - **Cause:** At my current role with CodeStream Studios, I once encountered difficulty in getting the development team to adopt a new frontend framework for an upcoming project. Despite recognizing the benefits of the framework in terms of productivity and code maintainability, some team members were hesitant to adopt a new technology and preferred sticking to the existing stack.
  - **Action:** To overcome this challenge, I took an approach that focused on collaboration, evidence-based reasoning, and addressing concerns head-on. I organized informal knowledge-sharing sessions where I presented case studies and examples of successful implementation of the framework in other companies. I demonstrated how it could streamline our development process, improve code quality, and increase overall productivity.
  - **Result:** While I couldn't persuade everyone to see things my way initially, the key takeaway from this experience was the importance of building a compelling case supported by evidence, fostering open communication, and addressing concerns empathetically to gradually influence others' perspectives.

- [x] B9) Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?

  - **Cause:**  At a previous job I held for a factoring company, I was placed in charge of a project that was meant to minimize the company’s financial loss due to over-aged invoices. Many of our clients were notorious for submitting shoddy paperwork that would often be rejected by their brokering companies, which led to us not receiving payment.
  - **Action:** To achieve the goals of this project, I proposed a plan to penalize repeat-offending clients with delayed purchasing dates for each time they had paperwork rejected for their truckloads. 
  - **Result:** The plan was a huge success, and as it incentivized a great number of our clients to begin submitting proper paperwork, which then eliminated a large fraction of the over-aged and unpaid invoices our division had been suffering from.

- [x] B10) Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?

  - **Cause:** I once mistakenly authorized the release of a fraudulent load at my previous shipping company, which cost them a sizable amount of money when the client refused to pay for the load post-release.
  - **Action:** Afterwards, I approached my superiors and claimed responsibility for the error. I explained to them how my inexperience with detecting counterfeit invoices led me to making the mistake I did, and I promised I would be much more careful in the future if they would be willing to give me another chance.
  - **Result:** My acting manager at the time reassured me that disciplinary action was unnecessary, because seeing me own my mistake and realizing the severity of it would ensure I never repeated it in the future. I took her message to heart and the extra steps I took going forward to scan for fraudulent loads prevented me from repeating the same mistake throughout my time with the company.

- [x] B11) Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?

  - **Cause:** During my days in ocean freight shipping, my team had recently acquired a new member who had completed his internship with the company. However, because he had been initially trained for a different department, he had great difficulty transitioning into our responsibilities, and often missed his invoicing quotas for the day.
  - **Action:** However, because his intentions to learn and excel at his responsibilities seemed genuine, I chose not to report this case to upper management, and instead opted to assist this team member directly. During downtime, or after I had clocked out for the day, I took the effort to tutor him on his new role and how he could further assist the team by improving his skill-set.
  - **Result:** As a result, this individual became highly adept with his work responsibilities and no longer fell short of the team’s expectations. The time I had committed towards helping him had definitely borne great fruit, and we ended up working closely together for the rest of my duration with the company.

- [x] B12) Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?

  - **Cause:** At my previous workplace, I often had to work under pressure at the end of each month, due to the large influx of client invoices that arrived around said time.
  - **Action:** Repeated exposure to working under these hectic conditions allowed me to develop efficient time management skills so that I could divide and conquer my tasks with sufficient breakpoints in between.
  - **Result:** Each experience built upon the previous to the point where I felt little to no anxiety while working under high pressure conditions. I feel I have become a far more tempered worker as a result.

- [x] B13) Tell me about yourself.

  - I am a highly motivated software engineer with an extensive background in developing both front-end and back-end web applications. I'm skilled in leveraging a wide variety of technologies, such as HTML5, CSS3, JavaScript, React, Node.js, and MongoDB, in order to deliver robust and efficient software solutions. In my current role at CodeStream Studios, I perform the role of a frontend developer, and am tasked with building and maintaining cutting edge UIs that help our teachers access and edit classroom data on a daily basis.

- [x] B14) Tell me about your experience at 100Devs.

  - 100Devs is a software development agency with a training program. I worked on several projects both alone and with teammates to better refine my technical skills. The main tech stack we used were React, Node, Express, and MongoDB.

- [ ] b15) What do you know about our company?

  - **Cause:** 
  - **Action:**
  - **Result:**

- [ ] B16) Why do you want to work for us?


  - **Cause:** 
  - **Action:** 
  - **Result:** 
  

- [ ] B17) Why are you interested in this opportunity?

  - **Cause:** 
  - **Action:** 
  - **Result:** 

- [ ] B18) Tell me about your dream job?  What do you really want to do with your career?

  - In my career as a software engineer, my dream job is to work at a large company like yours where I can contribute to meaningful projects and collaborate with a talented team. I have a passion for solving complex problems and enjoy being involved in the entire software development lifecycle, from ideation to deployment.

One aspect of my dream job is the opportunity to work on cutting-edge technologies and innovative projects that push the boundaries of what's possible. I thrive in an environment that encourages continuous learning and allows me to stay up-to-date with the latest trends and advancements in the industry. Your company's reputation for being at the forefront of technological innovation aligns perfectly with my aspirations.

Additionally, I value a company culture that fosters teamwork, open communication, and knowledge sharing. I believe that a collaborative and supportive environment not only enhances productivity but also promotes personal and professional growth. Being part of a diverse and inclusive team that celebrates different perspectives and experiences is crucial to me.

Overall, my dream job is to be part of a dynamic organization where I can continuously learn, contribute my technical skills, collaborate with talented individuals, and make a positive impact on the company's success. I believe that your company's commitment to innovation, culture, and growth perfectly aligns with my long-term career aspirations."

- [x] B19) Tell me a time when you failed.

  - **Cause:** During the start of my freelancing period, I was overly ambitious and advertised website builds I was not completely experienced with developing at the time. 
  - **Action:** As a result, I ended up disappointing my very first client by agreeing with all their demands and over-promising on features I was unable to deliver.
  - **Result:** The entire process taught me the value of learning when to say “No” and to always be honest about my limitations with the people I work with. As I moved forward from this experience, I have stood by the principle of under-promising and over-delivering when possible.

- [x] B20) What do you read on a regular basis?
  - Recently I've been reading various books on Data Structures & Algorithms along with books about different styles of coding architecture.
  - I'll also typically read movie screenplays, self-help books, and cooking guides. I'm a huge fan of our public library system and regularly use it.

- [ ] B21) What's some critical feedback you've gotten recently?

  - **Cause:** Talk less, and listen more. People love to talk about themselves and be listened to, and will value you greatly for lending an ear to them as they share their story.
  - **Action:** 
  - **Result:** 
  

- [ ] B22) Do you have any questions?
- What is the interview process like? What is the timeline?
- What are some of the challenges for the person in this position?
- What is a typical day in this position?
- What is the onboarding process after the offer?
- Are there training programs available?

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [x] T-HTML-1) What does a doctype do?
  - **Explanation:** A doctype tells the browser what version of HTML the document is written in.
  - **Use:** Must be the very first line of code in an HTML document. 
  - **Example:** Modern HTML5 documents use the tag `<!DOCTYPE html>`
  - **Source:** https://www.freecodecamp.org/news/what-is-the-doctype-declaration-in-html/

- [x] T-HTML-2) How do you serve a page with content in multiple languages?
  - **Explanation:** By setting the lang attribute on various elements throughout the page. 
  - **Use:** Translates the text within the attribute’s container into a selected language.
  - **Example:** `<p> French “ <span lang=”fr”> Bonjour </span> “ </p>`
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang

- [x] T-HTML-3) What kinds of things must you be wary of when designing or developing for multilingual sites?
  - **Explanation:**
      - Including the `lang` attribute.
      - How colors are perceived.
      - Language reading direction.
      - Date and currency formats.
      - Allowing users to change the language.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

- [x] T-HTML-4) What are `data-` attributes good for?
  - **Explanation:** They store data private to the page or application.
  - **Use:** Were often used for storing extra data in the DOM, but their use is discouraged now.
  - **Example:** `data-columns=”3”` | `data-index-number=”12314”`
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

- [x] T-HTML-5) Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:**
      - Semantics - Allows you to describe precisely what your content is
      - Multimedia - Making video and audio priority items on the open web.
      - Performance and Integration - Speed optimization
      - Styling - More sophisticated themes
      - Standardization - Building a consensus across all involved web browser stakeholders.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

- [x] T-HTML-6) Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:** Cookies are typically set by a web server and can store data that is read by both the web server and the web browser. Local storage and session storage are only readable by the browser. The difference between the two is their lifetime; localStorage lasts forever, and sessionStorage only lasts for the length of the session.
  - **Use:** All used for client-side storage of strings in key-value pairs.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
  
- [x] T-HTML-7) Describe the difference between `<script>, <script async> and <script defer>`.
  - **Explanation:**
      - <script> HTML parsing is blocked, script is fetched and executed right away.
      - <script async> script fetched in parallel to HTML parsing and executed as soon as it is available.
      - <script defer> script fetched in parallel to HTML parsing and executed when the page has finished parsing.
  - **Use:**
      - `async` is used when the script is independent of any other scripts on the page.
      - `defer` is useful when you need to ensure the HTML is fully parsed before running.
  - **Example:**
      - `async` could be used for analytics scripts.
      - `defer` scripts must not contain `document.write`
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
	
- [x] T-HTML-8) Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:** Placing <link> in the <head> allows for quick “first meaningful paint”. When a page first loads, HTML and CSS are being parsed simultaneously. However, <script> tags block HTML parsing while they are being downloaded and run, which can slow down your page. Thus, placing scripts at the bottom will allow the HTML to be parsed and displayed to the user first.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
	
- [x] T-HTML-9) What is progressive rendering?
  - **Explanation:** Progressive rendering is a technique used to improve the performance of a webpage so that it can render content for display ASAP.
  - **Use:** Improving perceived load time.
  - **Example:** Lazy loading of images, prioritizing visible content, and async HTML fragments.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
	
- [x] T-HTML-10) Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:** When you want to serve different images to users depending on their device display width.
  - **Use:** Sending lower resolution to limit data waste and increase performance or sending larger images to a higher resolution display to enhance the UX.
  - **Example:** `<img srcset =”small.jpg 500w, medium.jpg 1000w, large.jpg 2000w” src=”...” alt=””>`
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions
	
- [x] T-HTML-11) Have you used different HTML templating languages before?
  - **Explanation:** Yes, EJS and HBS. They are more or less the same as each other and provide similar functionality to escape content and provide helpful filters for manipulating the data to be displayed. Most templating engines also allow you to inject your own filters in the event you require custom processing before display.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

### CSS

- [x] T-CSS-1) What is CSS selector specificity and how does it work?
  - **Explanation:** How browsers decide which CSS property values are the most relevant to an element and how to apply them.
  - **Use:** Specificity is a score that is applied to a given CSS declaration, and is determined by the number of each selector type that it calls upon.
  - **Example:** A selector of `#id .class tag` would have 111 points, as id’s count for 100, classes count for 10, and tags count for 1.
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity
	
- [x] T-CSS-2) What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  - **Explanation:** “Normalize” alteres the default styles of various browsers to match each other. “Reset” will remove a browser’s default styles so you are starting from scratch.
  - **Use:** Using one or the other is done so that websites can remain visually consistent across different browsers. I prefer CSS normalize because of its style presets.
  - **Example:**

Normalize:

```css
/**
 * Correct the font size and margin on `h1` elements within `section` and
 * `article` contexts in Chrome, Firefox, and Safari.
 */

h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
```
	
Reset:

```css
html,
body,
h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
  padding: 0;
}
```
   
  - **Source:** https://elad.medium.com/normalize-css-or-css-reset-9d75175c5d1e
	
- [x] T-CSS-3) Describe floats and how they work.
  - **Explanation:** They are a positioning property where an element that is floated will be removed from the flow of the page and affect elements around it. `.clearfix` hacks are used to fix parent elements which collapse to zero height due to containing only floated elements.
  - **Use:** Floats were used prior to flex and grid to organize pages in a more flexible way.
  - **Example:** You can float three `<div>` elements left and give them widths of 33% each to create three columns with equal width.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-4) Describe z-index and how stacking context is formed.
  - **Explanation:** Z-index allows you to stack elements above or below one another to affect their visibility. Stacking context is formed by the parent-child relationship of nested elements, and the order of elements in the DOM.
  - **Use:** Giving a planet image with a transparent background a higher z-index so that it appears in front of a dark-colored background with a lower z-index.
  - **Example:** 
   `#planet {
      position: relative;
      z-index: 1
   }`
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-5) Describe BFC (Block Formatting Context) and how it works.
  - **Explanation:** A BFC is an HTML box that satisfies one or more of the following conditions:
      - The value of float is not ‘none’.
      - The value of position is neither static nor relative.
      - The value of display is table-cell, table-caption, inline-block, flex, or inline-flex, grid, or inline-grid.
      - The value of overflow is not visible. 
  - **Use:** Knowing how to establish a block formatting context is crucial, because otherwise, the containing box will not contain floated children.
  - **Example:** Without forming a BFC, you might end up with the contents of a float that end up being taller than the content beside it.
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context
	
- [x] T-CSS-6) What are the various clearing techniques and which is appropriate for what context?
  - **Explanation:**
      - Empty `div` method
      - Clearfix method
      - `overflow: auto` or `overflow: hidden` method
  - **Use:** `.clearfix` is likely the most efficient method to use on a general basis due to its short construction time and lack of clipping issues compared to the overflow methods.
  - **Example:**
      - `<div style=”clear:both;”></div>`
      - `.cleafix:after {
		content: ‘ ‘;
		visibility: hidden;
		display: block;
		height: 0;
		clear: both;
		}`
      - Overflow: Parent will establish a new BFC and expand to contain its floated children.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-7) Explain CSS sprites, and how you would implement them on a page or site.
  - **Explanation:** CSS sprites combine multiple images into one. To implement them, you would use a sprite generator and apply the proper CSS for it. Each image would have its own corresponding CSS class and background properties, which are placed in the elements which require them. 
  - **Use:** Commonly used for icons. 
  - **Source:** https://css-tricks.com/css-sprites/
- [x] T-CSS-8) How would you approach fixing browser-specific styling issues?
  - **Explanation:** By writing browser-specific CSS code, using a library like Bootstrap, and also by using a normalizer or reset CSS. My personal preference would be to use a combination normalize/reset style sheet.
  - **Use:** Safari and IE have different default fonts, which means the font on any given site can change when viewed with either browser.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-9) How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:**
	- Graceful degradation - Building an app for modern browsers while ensuring it remains functional in older browsers.
	- Progressive enhancement - Building an app for a base level of user experience, but adding functional enhancements when a browser supports it.
	- @support tag in CSS to test whether certain features are supported.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-10) What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:**
	- Make width and height both 0 for the content.
	- Position outside the screen.
	- Indent the text by -9999px.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-11) Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:** I have used floats and flex. I prefer flex because it feels more modernized and customizable, and has substantial browser support. I have been slightly exposed to CSS Grid Layout, but am still learning how to properly implement its `grid` property.
  - **Source:** https://www.flux-academy.com/blog/how-to-use-a-grid-in-web-design
	
- [x] T-CSS-12) Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:** Yes. It was to adjust the content displayed based on the user’s screen size.
  - **Use:** Re-organizing certain `<div>` and `<section>` elements on a site to be more aesthetic and functional if the user switches from a desktop to a mobile device.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-13) Are you familiar with styling SVG?
  - **Explanation:** Yes. It has advantages over other image formats such as JPG and GIF, such as:
	- Able to be created and edited with any text editor.
	- SVG images are scalable.
	- SVG graphics do not lose quality upon being resized or zoomed.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-14) Can you give an example of an `@media` property other than screen?
  - **Explanation:** There are 4  types of @media properties:
	- All - for all media type devices
	- Print - for printers
	- Speech - for screen-readers that “read” the page out loud.
	- Screen - for computer screens, tablets, phones, etc
  - **Example:**
	```
	@media print { 
	     body { 
		color: black
	     }
	}
	```
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-15) What are some of the "gotchas" for writing efficient CSS?
  - **Explanation:** Avoid key selectors that are tag and universal selectors. Since they match a large number of elements, browsers become overworked as they have to determine if the parents are a match. Also, avoid writing styles that change the layout. Be aware of the CSS properties which trigger reflow, repaint and compositing. Everything should have a single class.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-16) What are the advantages/disadvantages of using CSS preprocessors?
  - **Explanation:**
	- Pros:
		- CSS is made more maintainable.
		- Easy to write nested selectors.
		- Mixins to generate repeated CSS.
	- Cons:
		- Requires tools for preprocessing.
		- Re-compilation time can be slow.

  - **Example:** Sass, Post-CSS, Less
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-17) Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:**
	- Likes:
		- Being able to split files and nest selectors is very efficient.
	- Dislikes:
		- Sass requires frequent re-compilation when switching between node versions.
		- Less uses variable names prefixed with @, which can be confused with native CSS keywords such as @media, @import, etc.
  - **Source:** [https://www.frontendinterviewhandbook.com/css-questions/](https://adamsilver.io/blog/the-disadvantages-of-css-preprocessors/)
	
- [x] T-CSS-18) How would you implement a web design comp that uses non-standard fonts?
  - **Explanation:** Use `@font-face` and define `font-family`.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-19) Explain how a browser determines what elements match a CSS selector.
  - **Explanation:** Browsers match selectors from right to left. They filter out elements in the DOM based on the key selector and go up its parent element to find matches
  - **Example:** `p span` locates all `<span>` elements and works its way up until it finds a `<p>` element. 
  - **Source:**
- [x] T-CSS-20) Describe pseudo-elements and discuss what they are used for.
  - **Explanation:** A keyword added to a selector that lets you style a specific part of the element.
  - **Example:** `span: first-line` | `button: hover` 
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements
	
- [x] T-CSS-21) Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:** Everything inside a web-page is a box. There are several components that comprise a box model, such as padding, border, and margin. The size of an overall element is directly affected by the box element.
  - **Use:** The standard box model calculates box size by taking a specified height and width, then adding the padding and border. To change to the alternative box model, however, you would set `box-sizing: border box`, which allows you to set the box size with height and width.
  - **Example:** Content box (default), border box, etc
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model
	
- [x] T-CSS-22) What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation:** It changes how the height and width of elements are calculated, compared to content-box. Changes the parameters of border and padding to not affect the overall sizing of the element.
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#the_alternative_css_box_model
	
- [x] T-CSS-23) What is the CSS `display` property and can you give a few examples of its use?
  - **Explanation:** CSS display defines whether an element is treated as a block or inline element, as well as the layout used for its children, such as flow layout, grid, or flex.
  - **Example:**
	- Block - takes up the whole line in the block’s direction.
	- Inline - elements can be laid out beside one another.
	- Inline-block - allows you to place block elements side by side.
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/display
	
- [x] T-CSS-24) What's the difference between `inline` and `inline-block`?
  - **Explanation:** Inline-block allows you to set a width and height on the element, unlike inline alone. Inline-block also allows you to set margin and padding on all sides, whereas for inline, you can only set margin and padding on the left and right sides.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-25) What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Explanation:**
	- Relative - The element’s position is adjusted relative to itself without changing layout, and allows the use of Z-index on said element.
	- Fixed - The element is removed from the flow of the page and set at a specific position, and doesn’t move when the page is scrolled.
	- Absolute - The element is removed from the flow of the page and positioned based off of the top of the DOM content. It is not affected by other elements, and can be placed exactly where you want on the DOM.
	- Static - Default position; element flows into the page as it normally would.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-26) What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  - **Explanation:** Bootstrap and Tailwind. I like them as they are.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-27) Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:** Yes, to Flexbox. I find it far more efficient than using floats because of enhanced customization and sizing options.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-28) Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:** 
	- A responsive website will respond by adapting its size and/or other functionalities based on the user’s screen size.
	- Mobile-first websites will cater their design to mobile devices first, and then add responsive rules for other screen sizes afterwards.
  - **Example:**
```css
.my-class {
  font-size: 12px;
}

@media (min-width: 600px) {
  .my-class {
    font-size: 24px;
  }
}
```
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-29) How is responsive design different from adaptive design?
  - **Explanation:**
	- Responsive design - A fluid website that can look good on any device. ie. A ball growing or shrinking to fit through several different hoops.
	- Adaptive design - Detects the type of device used and delivers a pre-set layout for that device. ie. Several different balls to use depending on the hoop size.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-30) Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:** Retina is just a marketing term to refer to high resolution screens with a pixel ratio bigger than 1. In order to have crisp, good-looking graphics that make the best of retina displays we need to use high resolution images whenever possible. However using highest resolution images will have an impact on page load times.
  - **Use:** To overcome this problem, we can use responsive images, as specified in HTML5 with the `srcset` attribute.
  - **Example:**
  ```html
  <img
    src="/images/test-1600.jpg"
    srcset="/images/test-400.jpg 400w, /images/test-800.jpg 800w, /images/test-1200.jpg 1200w"
  />
  ```
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/
	
- [x] T-CSS-31) Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Explanation:** `translate()` is more efficient than absolute positioning because it uses GPU, rather than CPU, which results in shorter paint times for smoother animations.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

### Javascript

- [x] T-JS-1) Explain event delegation
  - **Explanation:** Event delegation is the practice of adding event listeners to a parent element instead of its descendents. The listener will be affected by triggered events on the descendent elements due to the parent-child relationship.
  - **Use:** When you want some code to run when the user interacts with any one of a large number of child elements.
  - **Example:**
```html
<div id="container">
  <div class="tile"></div>
</div>
<script>
  container.addEventListener('click', (event) => (event.target.style.backgroundColor = bgChange()));
</script>
```
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#event_delegation
	
- [x] T-JS-2) Explain how `this` works in JavaScript
  - **Explanation:** `this` references an object. When inside of a constructor function or class it will reference the object on instantiation.
  - **Use:** It is used to assign properties and values to an object on instantiation.
  - **Example:**
```javascript
class MyThing {
  constructor(passThisIn) {
    this.passThisIn = passThisIn;
  }
}
```
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
	
- [x] T-JS-3) Explain how prototypal inheritance works
  - **Explanation:** When a property is accessed on an object, but said property does not exist within said object, it moves up the chain to see if its parent objects contain said property so it can call upon them.
  - **Use:** It can help reduce redundant code.
  - **Example:**
```javascript
function Parent() {
  this.name = 'Parent';
}
Parent.prototype.greet = function () {
  console.log('Hello from ' + Parent.name);
};
const child = Object.create(Parent.prototype);
child.cry = function () {
  console.log('waaaaaahhhh!');
};
child.cry();
// waaaaaahhhh!
child.greet();
// hello from Parent
console.log(child.constructor);
// ƒ Parent() {
// this.name = 'Parent';
// }
console.log(child.constructor.name);
// 'Parent'
```	
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions
	
- [x] T-JS-4) What do you think of AMD vs CommonJS?
  - **Explanation:** Historically CommonJS was used in the back-end and runs synchronous and AMD was used in the front-end and runs asynchronous.
  - **Use:** CJS has been used in node.js for a while.
  - **Source:** https://dev.to/iggredible/what-the-heck-are-cjs-amd-umd-and-esm-ikm
	
- [x] T-JS-5) Explain why the following doesn't work as an IIFE (Immediately Invoked Function Expression): `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:** The parser reads it as two seperate statements. First the function declaration `function foo(){ }` and then a blank function call attempt `();` The best way to fix this would be to add another set of parenthesis wrapping the function declaration `(function foo(){ })()` This changes it from a function declaration to a function expression.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions
	
- [x] T-JS-6) What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:**
    - `null`: the value is intentionally absent (points to nothing in memory).
    - `undefined`: not yet assigned a value or not yet declared.
    - `undeclared`: improperly declared without let/const/var
  - **Use:** null can be used to assign the primitive value of null to a variable. undeclared throws an error where as null and undefined can be checked with a conditional
  - **Example:** `null` and `undefined` can be checked using strict equality `===`. Undeclared will throw it's own error so you could use `try...catch`
  - **Source:** https://www.30secondsofcode.org/articles/s/javascript-undeclared-undefined-null
	
- [x] T-JS-7) What is a closure, and how/why would you use one?
  - **Explanation:** Closure allows you to use an outer function’s scope (go into a parent, grandparent function, etc.) from within an inner function. In JavaScript a closure is created every time a function is created.
  - **Use:** It allows you to combine data with the function that will operate on that data. It is similar to OOP.
  - **Example:**
```javascript
function init() {
  var name = 'Mozilla'; // name is a local variable created by init
  function displayName() {
    // displayName() is the inner function, a closure
    alert(name); // use variable declared in the parent function
  }
  displayName();
}
init();
```	
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
	
- [x] T-JS-8) Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:** `.forEach()` executes a callback function on each element, but does not return a value. `.map()` executes a callback function on each element and "maps" the result to a new array. The new array is returned.
  - **Use:** If you need the result and don't want to mutate the original array, use map. If you only need to iterate over the array then forEach can be used.
  - **Example:**
    `.forEach()`:

```javascript
const a = [1, 2, 3];
const doubled = a.forEach((num, index) => {
  // Do something with num and/or index.
});
// doubled = undefined
```

`.map()`:

```javascript
const a = [1, 2, 3];
const doubled = a.map((num) => {
  return num * 2;
});
// doubled = [2, 4, 6]
```
- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-9) What's a typical use case for anonymous functions?
  - **Explanation:** They can be used in IIFEs to contain some code within a local scope so that its variables do not leak to the global scope.
  - **Use:** Essentially when you don't need a named function and the function is bound to some other action.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-10) How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:** Single directional data flow, similar to the one used in React.
  - **Source:** https://www.theodinproject.com/lessons/node-path-javascript-es6-modules
	
- [x] T-JS-11) What's the difference between host objects and native objects?
  - **Explanation:** 
	
	- Native objects are ones that are part of the JavaScript language, such as string, math, object, function, etc.
	- Host objects are provided by the runtime environment (browser) such as window, XMLHTTPRequest, etc.
  - **Example:** Some native objects are `String`, `Math`, `RegExp`, and `Object`. A couple of host objects are `window` and `console`
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-12) What is the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation & Use:**
    - `function Person(){}` is likely being used as a constructor.
    - `var person = new Person()`is instantiating a new Person object as person.
    - `var person = Person()` is not correct and would likely return undefined. To create a new instance you would need to use the `new` operator as above.
  - **Example:**

```javascript
function Person(name) {
  this.name = name;
}

var person = Person('John');
console.log(person); // undefined
console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

var person = new Person('John');
console.log(person); // Person { name: "John" }
console.log(person.name); // "john"
```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-13) What's the difference between `.call()` and `.apply()`?
  - **Explanation:** They are both used to invoke functions, but the difference is in how they take arguments. `.call()` takes them as comma-separated values and `.apply()` takes them as an array.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-14) Explain `Function.prototype.bind`.
  - **Explanation:** Creates a new function that, when called, has its `this` keyword set to the provided value.
  - **Use:** It binds the value of `this` in methods of classes you want to pass into other functions. Frequently performed with React components.
  - **Example:**

```javascript
function getMonthlyFee(fee){
  var remaining = this.total - fee;
  this.total = remaining;
  return this.name +' remaining balance:'+remaining;
}
	
var rachel = {name:'Rachel Green', total:500};

//bind
var getRachelFee = getMonthlyFee.bind(rachel, 90);
//deduct
getRachelFee();//Rachel Green remaining balance:410
getRachelFee();//Rachel Green remaining balance:320
```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-15) When would you use `document.write()`?
  - **Explanation:** It is considered dangerous, and its use is not encouraged. It can clear the entire document and replace its content with a given parameter value.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-16) What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:** 
	
    - **Feature Detection:** Working out whether a browser supports a certain block of code, and running different code depending on whether it does, so that the browser can provide a working experience rather crashing/erroring in some browsers.
    - **Feature Inference:** Checks for a feature just like feature detection, but uses another function because it assumes it will also exist. Feature Detection is the better approach.
    - **UA String:** A browser-reported string that allows the network protocol peers to identify various properties of the system. It's tricky to parse and can be spoofed so it's best to avoid this method.
  - **Example:** Using feature detection:

```javascript
if ('geolocation' in navigator) {
  // Can use navigator.geolocation
} else {
  // Handle lack of feature
}
```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-17) Explain Ajax in as much detail as possible.
  - **Explanation:** Ajax (asynchronous JavaScript and XML) is a set of web development techniques using many web technologies on the client side to create asynchronous web applications. With Ajax, web applications can send data to and retrieve from a server asynchronously (in the background) without interfering with the display and behavior of the existing page.
  - **Use:** By decoupling the data interchange layer from the presentation layer, Ajax allows for web pages, and by extension web applications, to change content dynamically without the need to reload the entire page. In practice, modern implementations commonly use JSON instead of XML, due to the advantages of JSON being native to JavaScript.
  - **Example:** The `fetch` API is typically used nowadays for asynchronous communication.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-18) What are the advantages and disadvantages of using Ajax?
  - **Advantages:**
    - Better interactivity. New content from the server can be changed dynamically without the need to reload the entire page.
    - Reduce connections to the server since scripts and stylesheets only have to be requested once.
    - State can be maintained on a page. JavaScript variables and DOM state will persist because the main container page was not reloaded.
  - **Disadvantages:**
    - Dynamic webpages are harder to bookmark.
    - Does not work if JavaScript has been disabled in the browser.
    - Some webcrawlers do not execute JavaScript and would not see content that has been loaded by JavaScript.
    - JavaScript will have to be parsed and executed on the browser, and low-end mobile devices might struggle with this.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-19) Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:** JSONP (JSON with Padding) is a method commonly used to bypass the cross-domain policies in web browsers because Ajax requests from the current page to a cross-origin domain is not allowed.
  - **Use:** JSONP can be unsafe as it can do everything else JavaScript can so you need to trust the provider of data. These days, CORS is the recommended approach and JSONP is seen as a hack.
  - **Example:**

```html
<!-- https://mydomain.com -->
<script>
  function printData(data) {
    console.log(`My name is ${data.name}!`);
  }
</script>

<script src="https://example.com?callback=printData"></script>
```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-20) Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:** Yes. I have used handlebars(hbs) when I was picking up MVC architecture to split my code into multiple files and directories.
  - **Source:** https://reactjs.org/docs/introducing-jsx.html
	
- [x] T-JS-21) Explain "hoisting".
  - **Explanation:** Hoisting is the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to execution of the code. Think of it as moving the code up to the top. Note that the assignment stays where it is despite this.
  - **Use:** Hoisting allows functions to be safely used in code before they are declared.
  - **Example:**

```
eat()  //this hoisting works b.c it's a function declaration below

function eat(){
  console.log('eat')
 }
```
  - **Source:** https://developer.mozilla.org/en-US/docs/Glossary/Hoisting
	
- [x] T-JS-22) Describe event bubbling.
  - **Explanation & Use:** When an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestors. The most deeply nested element that caused the event is called a target element, accessible as event.target.
  - **Example:**

```html
<style>
  body * {
    margin: 10px;
    border: 1px solid blue;
  }
</style>
<form onclick="alert('form')">
  FORM
  <div onclick="alert('div')">
    DIV
    <p onclick="alert('p')">P</p>
  </div>
</form>
```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
	
- [x] T-JS-23) What's the difference between an "attribute" and a "property"?
  - **Explanation & Use:** Attributes are defined on the HTML markup but properties are defined on the DOM. An attribute is the initial state when rendered in the DOM. A property is the current state.
  - **Example:**

```javascript
const input = document.querySelector('input');
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello
```

Notice how the property updates after adding "World" to the input.

```javascript
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello World!
```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-an-attribute-and-a-property
	
- [x] T-JS-24) Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:** Extending a built-in/native JavaScript object means adding properties/functions to its prototype. While this may seem like a good idea at first, it is dangerous in practice. Imagine your code uses a few libraries that both extend the Array.prototype by adding the same contains method, the implementations will overwrite each other and your code will break if the behavior of these two methods is not the same.
  - **Use:** The only time you may want to extend a native object is when you want to create a polyfill, essentially providing your own implementation for a method that is part of the JavaScript specification but might not exist in the user's browser due to it being an older browser.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/#why-is-extending-built-in-javascript-objects-not-a-good-idea
	
- [x] T-JS-25) What is the difference between window `load` event and document `DOMContentLoaded` event?
  - **Explanation:** The DOMContentLoaded event is fired when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading. window's `load` event is only fired after the DOM and all dependent resources and assets have loaded.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/#difference-between-document-load-event-and-document-domcontentloaded-event

- [x] T-JS-26) What is the difference between `==` and `===`?
  - **Explanation:** == checks for value equality while === checks for value and data type equality
  - **Use:** == should generally be avoided unless for null or undefined
  - **Example:**

```javascript
1 == '1'; // true
1 == [1]; // true
1 == true; // true
0 == ''; // true
0 == '0'; // true
0 == false; // true
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-27) Explain the same-origin policy with regards to JavaScript.
  - **Explanation:** The same-origin policy is a critical security mechanism that restricts how a document or script loaded by one origin can interact with a resource from another origin. This policy prevents a malicious script on one page from obtaining access to sensitive data on another web page through that page's Document Object Model.
  - **Source:** https://en.wikipedia.org/wiki/Same-origin_policy

- [x] T-JS-28) Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5] `
  - **Example:**

```javascript
function duplicate(arr) {
  return arr.concat(arr);
}
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-29) Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:** "Ternary" means "composed of three parts", as the expression accepts 3 operands. First, a condition followed by a question mark (?), then an expression to execute if the condition is truthy followed by a colon (:), and finally the expression to execute if the condition is falsy.
  - **Use:** Can simplify code over if...else statements.
  - **Example:**

```javascript
const age = 26;
const beverage = age >= 21 ? 'Beer' : 'Juice';
```

- **Source:** https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator

- [x] T-JS-30) What is "use strict";? what are the advantages and disadvantages to using it?

  - **Explanation:** 'use strict' is a statement used to enable strict mode to entire scripts or individual functions. Strict mode is a way to opt into a restricted variant of JavaScript. Overall, I think the benefits outweigh the disadvantages, and I never had to rely on the features that strict mode blocks. I would recommend using strict mode.
  - **Use:**

    - Advantages:

      - Makes it impossible to accidentally create global variables.
      - Makes assignments which would otherwise silently fail to throw an exception.
      - Makes attempts to delete undeletable properties throw an exception (where before the attempt would simply have no effect).
      - Requires that function parameter names be unique.
      - this is undefined in the global context.
      - It catches some common coding bloopers, throwing exceptions.
      - It disables features that are confusing or poorly thought out.

    - Disadvantages:
      - Many missing features that some developers might be used to.
      - No more access to function.caller and function.arguments.
      - Concatenation of scripts written in different strict modes might cause issues.

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/#what-is-use-strict-what-are-the-advantages-and-disadvantages-to-using-it

- [x] T-JS-31) Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  - **Example:**

```javascript
function fizzBuzz() {
  for (let i = 1; i <= 100; i++) {
    if (i % 5 === 0 && i % 3 === 0) {
      console.log(i, 'FizzBuzz');
    } else if (i % 3 === 0) {
      console.log(i, 'Fizz');
    } else if (i % 5 === 0) {
      console.log(i, 'Buzz');
    }
  }
}
```


- [x] T-JS-32) Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  - **Explanation:** Every script has access to the global scope, and if everyone uses the global namespace to define their variables, collisions will likely occur. Use the module pattern (IIFEs) to encapsulate your variables within a local namespace.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-33) Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:** `load` fires when the entire page is finished loading (HTML, CSS, Scripts, etc.). You might want to use `DOMContentLoaded` which fires when the DOM is loaded, but before stylesheets, scripts, etc. are loaded.
  - **Use:** It depends on the context, but perhaps there is some non-blocking resource that is a large file which you would wait to load until the entire page is done.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/
  - **Source:** https://www.geeksforgeeks.org/difference-between-domcontentloaded-and-load-events/

- [x] T-JS-34) Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:** SPA's render the page client side instead of server side. The server sends the initial page, but subsequent changes to the page do not initiate a page refresh. The data on the page is typically updated via an AJAX request which is then used to dynamically update the page via JavaScript.
  - **Use:** A reason to use a SPA is that it feels more responsive to the user, fewer HTTP request are made so assets don't have to be downloaded multiple times and there is a clear separation between client and server. As long as the API is the same either side can be modified without affecting the other. Some downsides would be heavier initial page load, additional server config needed and SEO can be more difficult. To overcome the SEO problem you could render your pages server side or use a service such as Prerender.
  - **Source:** https://github.com/grab/front-end-guide

- [x] T-JS-35) What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:** I've used Promises extensively as they are a main component in modern asynchronous JavaScript. They are used for operations that will produce a resolved value in the future. I haven't used polyfills much as they aren't required much these days.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-36) What are the pros and cons of using Promises instead of callbacks?

  - **Pros:**
    - Avoid callback hell
    - Easy to write sequential asynchronous code that is readable with `.then()`.
    - Easy to write parallel asynchronous code with `Promise.all()`.
    - With promises, these scenarios which are present in callbacks-only coding, will not happen:
      - Call the callback too early
      - Call the callback too late (or never)
      - Call the callback too few or too many times
      - Fail to pass along any necessary environment/parameters
      - Swallow any errors/exceptions that may happen
  - **Cons:**
    - Slightly more complex code (debatable).
    - Older browsers may require a polyfill.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/


- [x] T-JS-37) What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Advantages:**
    - Adds some syntatic sugar allowing you to write shorter code.
    - Static types may be available which helps for large projects that need to be maintainable.
    - Discourages JavaScript anti-patterns.
  - **Disadvantages:**
    - Requires a build/compile step.
    - Another language to learn so requires additional training for developers new to the project.
    - Less resources due to smaller communities.
    - Behind the latest features of the up to date ECMAScript standards.
    - Debugging may be difficult if mapping from compiled to pre-compiled code is not done well.
  - **Example:** Some more well known examples of these types of languages are CoffeeScript and TypeScript.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#what-are-some-of-the-advantagesdisadvantages-of-writing-javascript-code-in-a-language-that-compiles-to-javascript

- [x] T-JS-38) What tools and techniques do you use debugging JavaScript code?
  - **Explanation & Use:** I typically will watch variables as they change over time to make sure they are carrying the correct values or states. The three most common tools I use are:
    - Browser Devtools (Typically Chrome & Firefox)
    - `console.log`
    - `debugger` statement
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#what-tools-and-techniques-do-you-use-for-debugging-javascript-code

- [x] T-JS-39) What language constructions do you use for iterating over object properties and array items?
  - **Objects:**
    - `for...in` loops: When I don't need to access properties that are non-enumerable and that are keyed by Symbols.
    - `Object.keys()`: Only when I need to access the enumerable properties.
    - `Object.getOwnPropertyNames()`: When I need to access all properties.
  - **Arrays:**
    - `for` loops: I use them when I need to iterate through the array in steps larger than one.
    - `forEach()`: I use it when I don't need to reference the index as it requires less code.
    - `for...of` loops: I use them when I might need to `break` from the loop.
  - **Sources:**
    - https://www.frontendinterviewhandbook.com/javascript-questions#what-language-constructions-do-you-use-for-iterating-over-object-properties-and-array-items
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys

- [x] T-JS-40) Explain the difference between mutable and immutable objects.
  - **Explanation:** A mutable object is an object whose state can be modified after it is created. An immutable object is an object whose state cannot be modified after it is created.
  - **Use:** Immutable objects make it easier to detect changes, make programs less complicated to think about and sharing is easy with references. If immutable objects are setup incorrectly though it could lead to poor performance due to multiple copies being made.
  - **Example:** To make an object immutable you could `Object.freeze()` which prevents new properties from being added and existing properties from being altered or removed.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-41) Explain the difference between synchronous and asynchronous functions.
  - **Explanation:** Synchronous functions are blocking while asynchronous functions are not. In synchronous functions, statements complete before the next statement is run. In this case, the program is evaluated exactly in order of the statements and execution of the program is paused if one of the statements take a very long time.
  - **Use:** Note that JavaScript is synchronous and it's actually the browser and Node.js that's actually asynchronous (think callbacks and promises)
  - **Example:**

```javascript
function f1() {
  // Some code   //synchronous
}
function main() {
  console.log('main');
  setTimeout(f1, 0); // async, with a callback of f1 function
  f2();
}
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/


- [x] T-JS-42) What is event loop? What is the difference between call stack and task queue?
  - **Explanation:** The event loop is a single-threaded loop that monitors the call stack and checks if there is any work to be done in the task queue. If the call stack is empty and there are callback functions in the task queue, a function is dequeued and pushed onto the call stack to be executed.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-43) Explain the differences on the usage of foo between `function foo() {}` and `var foo = function() {}`
  - **Explanation:** The former is a function declaration while the latter is a function expression.
  - **Use:** The function declaration is hoisted and can therefore be accessed from anywhere, whereas the function expression can only be accessed after it's been defined.
  - **Example:**
  
  ```javascript
  console.log(name('Curtis')) // can be accessed before initialization (hoisted)

   function name (str){ // function declaration
      return str
   }

   console.log(nameTwo('Curtis')) // cannot be accused before initialization (not hoisted)

   const nameTwo = function (str) { // expression
      return str
   }
   ```
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/

- [x] T-JS-44) What are the differences between variables created using `let`, `var` or `const`?
  - **Explanation:** Variables declared using the var keyword are scoped to the function in which they are created, or if created outside of any function, to the global object. let and const are block scoped, meaning they are only accessible within the nearest set of curly braces (function, if-else block, or for-loop).
  - **Use:** var is hoisted and can be redeclared, whereas let and const cannot be redeclared. let and var can be reassigned, but const cannot be.
  - **Example:**

```javascript
if (true) {
  var thing1 = 'bar';
  let thing2 = 'baz';
  const thing3 = 'qux';
}

// var declared variables are accessible anywhere in the function scope.
console.log(thing1); // bar
// let and const defined variables are not accessible outside of the block they were defined in.
console.log(thing2); // ReferenceError: baz is not defined
console.log(thing3); // ReferenceError: qux is not defined
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions/


- [x] T-JS-45) What are the differences between ES6 class and ES5 function constructors?
  - **Explanation & Example:** Simple constructors are fairly similar in length and ease of use. The main difference in the constructor comes when using inheritance. If we want to create a Student class that subclasses Person and add a studentId field, this is what we have to do:

```javascript
// ES5 Function Constructor
function Student(name, studentId) {
  // Call constructor of superclass to initialize superclass-derived members.
  Person.call(this, name);

  // Initialize subclass's own members.
  this.studentId = studentId;
}

Student.prototype = Object.create(Person.prototype);
Student.prototype.constructor = Student;

// ES6 Class
class Student extends Person {
  constructor(name, studentId) {
    super(name);
    this.studentId = studentId;
  }
}
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#what-are-the-differences-between-es6-class-and-es5-function-constructors


- [x] T-JS-46) Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
  - **Explanation & Use:** It simplifies the syntax needed to create functions and `this` is lexically bound meaning it uses `this` from the code that contains the arrow function.
  - **Example:** Notice that you do not need to `.bind(this)` for the below to work.

```javascript
var obj = {
  id: 42,
  counter: function counter() {
    setTimeout(() => {
      console.log(this.id);
    }, 1000);
  },
};
```

- **Source:** https://www.freecodecamp.org/news/when-and-why-you-should-use-es6-arrow-functions-and-when-you-shouldnt-3d851d7f0b26/


- [x] T-JS-47) What advantage is there for using the arrow syntax for a method in a constructor?

  - **Explanation & Use:** The main advantage is that the value of `this` gets set at the time of the function creation and can't change after that. This is helpful in React class components when for example you may pass a click handler down into a child component as a prop.
  - **Example:**

  ```javascript
  const Person = function (firstName) {
    this.firstName = firstName;
    this.sayName1 = function () {
      console.log(this.firstName);
    };
    this.sayName2 = () => {
      console.log(this.firstName);
    };
  };
  const john = new Person('John');
  const dave = new Person('Dave');

  john.sayName1(); // John
  john.sayName2(); // John

  // The regular function can have its 'this' value changed, but the arrow function cannot
  john.sayName1.call(dave); // Dave (because "this" is now the dave object)
  john.sayName2.call(dave); // John

  john.sayName1.apply(dave); // Dave (because 'this' is now the dave object)
  john.sayName2.apply(dave); // John

  john.sayName1.bind(dave)(); // Dave (because 'this' is now the dave object)
  john.sayName2.bind(dave)(); // John
  ```

  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#what-advantage-is-there-for-using-the-arrow-syntax-for-a-method-in-a-constructor


- [x] T-JS-48) What is the definition of a higher-order function?
  - **Explanation:** A higher-order function is any function that takes one or more functions as arguments, which it uses to operate on some data, and/or returns a function as a result.
  - **Use:** To abstract some operation that is performed repeatedly.
  - **Example:** The classic example of this is `map`, which takes an array and a function as arguments. map then uses this function to transform each item in the array, returning a new array with the transformed data.
  - **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#what-is-the-definition-of-a-higher-order-function

- [x] T-JS-49) Can you give an example for destructuring an object or an array?
  - **Explanation:** Destructuring is an expression that enables a convenient way to extract properties from Objects and values from Arrays and place them into distinct variables.
  - **Use:** It's a more concise way to assign values to variables and can be particularly handy when passing function arguments.
  - **Example:** An example of destructing a simple object:

```javascript
// Variable assignment
const o = { p: 42, q: true };
const { p, q } = o;

console.log(p); // 42
console.log(q); // true
```

- **Source:**

  - https://www.frontendinterviewhandbook.com/javascript-questions#can-you-give-an-example-for-destructuring-an-object-or-an-array
  - https://betterprogramming.pub/why-i-find-javascripts-destructuring-so-useful-7be41d9ba609


- [x] T-JS-50) ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
  - **Explanation:** Template literals are a way to do string interpolation, or to include variables in a string.
  - **Use:** It is simpler and more readable than using concatenation methods prior to ES2015.
  - **Example:**

```javascript
// Prior to ES2015
'Hi, my name is ' + person.name + ' and I am ' + person.age + ' years old!';

// Using template literals
`Hi, my name is ${person.name} and I am ${person.age} years old!`;
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#es6-template-literals-offer-a-lot-of-flexibility-in-generating-strings-can-you-give-an-example


- [x] T-JS-51) Can you give an example of a curry function and why this syntax offers an advantage?
  - **Explanation:** Currying is a pattern where a function with more than one parameter is broken into multiple functions taking a single parameter each that, when called in series, will accumulate all of the required parameters one at a time.
  - **Use:** This technique can be useful for making code written in a functional style easier to read and compose.
  - **Example:**

```javascript
// regular function
function sum3(x, y, z) {
  return x + y + z;
}

// curried version
function sum3(x) {
  return (y) => {
    return (z) => {
      return x + y + z;
    };
  };
}
```

- **Source:**

  - https://www.frontendinterviewhandbook.com/javascript-questions#can-you-give-an-example-of-a-curry-function-and-why-this-syntax-offers-an-advantage
  - https://hackernoon.com/currying-in-js-d9ddc64f162e


- [x] T-JS-52) What are the benefits of using spread syntax and how is it different from rest syntax?
  - **Explanation:** Spread syntax is used to "unpack" data from an array, while rest syntax is the opposite and is used to put data into an array.
  - **Use:** When coding in a functional paradigm it is easier to create copies of arrays or objects with spread syntax versus using `Object.create`, `slice`, or a library function. Rest syntax is useful when used as a function parameter where there will be an arbitrary number of arguments.
  - **Example:**

```javascript
// Copying an object
const person = {
  name: 'Todd',
  age: 29,
};

const copyOfTodd = { ...person };
```

- **Source:** https://www.frontendinterviewhandbook.com/javascript-questions#what-are-the-benefits-of-using-spread-syntax-and-how-is-it-different-from-rest-syntax


- [x] T-JS-53) How can you share code between files?
  - **Explanation:** With ES6 modules via the `import ... export` syntax. Prior to ES6 modules you could use Asynchronous Module Definition for the client side scripts or CommonJS for server side scripts.
  - **Use:** To better organize and abstract code bases.
  - **Example:**

```javascript
// file square.js
export { name, draw, reportArea, reportPerimeter };

// file index.js
import { name, draw, reportArea, reportPerimeter } from './modules/square.js';
```

- **Source:**

  - https://www.frontendinterviewhandbook.com/javascript-questions#how-can-you-share-code-between-files
  - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules


- [x] T-JS-54) Why might you want to create static class members?
  - **Explanation:** Static class members are properties and methods that do not change.
  - **Use:** You would use them for properties that stay the same throughout the application and every instance of the object needs to know that property. They could also be used for utility functions so they can be called without instantiating any object.
  - **Source:** https://stackoverflow.com/questions/21155438/when-to-use-static-variables-methods-and-when-to-use-instance-variables-methods

### Javascript General


- [x] T-JSGeneral-1) Can you name two programming paradigms important for JavaScript app developers?
  - OOP and Functional Programming are the most often used. OOP allows inheritance via different "classes". Functional is pure-functions without side effects.
  - **Source:** https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95

- [x] T-JSGeneral-2) What is functional programming?
  - **Explanation:** Using pure functions with no side effects to compose your program.
  - **Use:** You avoid mutable data and shared states and instead make use of simple functions. It makes the code more predictable.
  - **Example:** Instead of having a function with two parameters that does two tasks, you break it into two functions. Each function would have a single parameter and do a single task.
  - **Source:** https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95

- [x] T-JSGeneral-3) What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:** Classical instances inherit from class "templates" and create sub-class relationships. They are typically instantiated via constructor functions or the class keyword. Prototypal instances inherit directly from other objects and typically instantiated via factory functions or the `Object.create()` method.
  - **Use:** It's generally considered better practice to use Prototypal inheritance for a few reasons:
    - Protoypes are more flexible than classes
    - The abstraction is only a single level deep
    - It's less verbose than using classical inheritance
  - **Source:**
    - https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95
    - https://dev.to/crishanks/classical-vs-prototypal-inheritance-2o5a

- [x] T-JSGeneral-4) What are the pros and cons of functional programming vs object-oriented programming?
  - **Explanation:**
	- FP: Avoids bugs related to shared state, due to lack of multiple functions competing for the same resources. A downside with FP is that it reduces readability of code due to abstract specifications and large compositions.
	- OOP: Easy to understand the basic concept of objects and easy to interpret the meaning of method calls. However, it depends on shared state, which can lead to undesirable behavior such as race conditions.
  - **Source:**

- [x] T-JSGeneral-5) What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation:**
    - Two-way data: UI fields are bound to model data dynamically. When a UI field changes, the model data changes with it and vice-versa. Side effects can occur.
    - One-way data: The model is the single source of truth. Changes in the UI signal user intent to the model (or “store” in React). Only the model has the access to change the app’s state. The effect is that data always flows in a single direction. It is deterministic meaning no side effects will occur.
  - **Use:** React is a popular framework which uses one-way data flow. Angular on the other hand uses two-way data binding.
  - **Source:** https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95

- [x] T-JSGeneral-6) What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:** It allows you to run blocking code outside of the single thread so that the program can continue to run while it waits for the blocking code to complete. Javascript is synchronous by nature, but the runtime (browser or node) has an event loop which allows developers to write asynchronous programs.
  - **Use:** It is important for user interfaces, where you are waiting for user input, and for network requests, where you are waiting for some data back from a server.
  - **Example:** Using `async...await` and `fetch` to fetch resources from an API is a common implementation of async programming.
  - **Source:** https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95

### Node


- [x] T-Node-1) What is Node.js? Where can you use it?

  - Node.js is a single-threaded, open-source, cross-platform runtime environment used to build server-side and networking applications. It uses event-driven, non-blocking I/O architecture, which makes it efficient and suitable for real-time applications.
  - **Source:** https://kinsta.com/knowledgebase/what-is-node-js/


- [x] T-Node-2) Why use Node.js?

  - **Explanation:** It uses fewer resources and memory because it is single threaded, it has wide adoption with many open source pacakages available, it is multi-platform and it simplifies the full stack as you can use just one language: Javascript.
  - **Use:** It's best used for real time applications that aren't data intensive. For programs that require more data processing a multi-threaded language like Java is a better choice.
  - **Source:** https://kinsta.com/knowledgebase/what-is-node-js/


- [x] T-Node-3) What are the features of Node.js?

  - **Explanation:** Node.js is a single-threaded, but highly scalable, system that uses JavaScript as its scripting language. It uses asynchronous, event-driven I/O instead of separate processes or threads. It can achieve high output via single-threaded event loop and non-blocking I/O.
  - **Source:**


- [x] T-Node-4) How do you update NPM to a new version in Node.js?

  - **Explanation:** With Mac or Linux systems it is rather easy just type the command `npm install -g npm@latest` into the terminal to update npm. With Windows it's a little more complex as you will need to either modify the Window's installation PATH or remove the npm files from the nodejs install directory then update npm in the terminal.
  - **Source:** https://docs.npmjs.com/try-the-latest-stable-version-of-npm

- [x] T-Node-5) Why is Node.js Single-threaded?

  - **Explanation:** Node.js is single-threaded for async processing. By doing async processing on a single-thread under typical web loads, more performance and scalability can be achieved instead of the typical thread-based implementation.
  - **Source:** https://www.simplilearn.com/tutorials/nodejs-tutorial/nodejs-interview-questions

- [x] T-Node-6) Explain callback in Node.js.

  - **Explanation:** A callback function is called after a given task. All APIs of Node are written to support callbacks.
  - **Use:** Callbacks allow other code to be run in the meantime and prevents any blocking. Being an asynchronous platform, Node.js heavily relies on callback.
  - **Source:** https://www.simplilearn.com/tutorials/nodejs-tutorial/nodejs-interview-questions

- [x] T-Node-7) What is callback hell in Node.js?

  - **Explanation:** This is a big issue caused by coding with complex nested callbacks. Imagine each and every callback takes an argument that is a result of the previous callbacks. In this manner, The code structure looks like a pyramid, making it difficult to read and maintain. Also, if there is an error in one function, then all other functions get affected.
  - **Use:** This should be avoided.
  - **Example:**

  ```callback hell
  fs.readdir(source, function (err, files) {
    if (err) {
      console.log('Error finding files: ' + err)
    } else {
      files.forEach(function (filename, fileIndex) {
        console.log(filename)
        gm(source + filename).size(function (err, values) {
          if (err) {
            console.log('Error identifying file size: ' + err)
          } else {
            console.log(filename + ' : ' + values)
            aspect = (values.width / values.height)
            widths.forEach(function (width, widthIndex) {
              height = Math.round(width / aspect)
              console.log('resizing ' + filename + 'to ' + height + 'x' + height)
              this.resize(width, height).write(dest + 'w' + width + '_' + filename, function(err) {
                if (err) console.log('Error writing file: ' + err)
              })
            }.bind(this))
          }
        })
      })
    }
  })   //note this long line of stacking brackets is often a tell of callback hell
  ```

  - **Source:**

- [x] T-Node-8) How do you prevent/fix callback hell?

  - **Explanation:** One of the most common ways is to use promises (an object that represents the eventual completion or failure of an async operation and its value). Once each step is finished and we have our value, we can run then() method to call the async callback or if it fails we can catch an error. We could also just keep our code shallow and modularize (make each block of code do one thing only).
  - **Example:**

  ```promises and then() method
  houseOne()
  	.then(data=>console.log(data)
  	.then(houseTwo)
  	.then(data=>console.log(data)
  	.then(houseTwo)
  ```

  - **Source:** https://www.geeksforgeeks.org/what-is-callback-hell-in-node-js/

- [x] T-Node-9) Explain the role of REPL in Node.js.

  - **Explanation:** The Node.js Read-Eval-Print-Loop (REPL) is an interactive shell that processes Node.js expressions. The shell reads JavaScript code the user enters, evaluates the result of interpreting the line of code, prints the result to the user, and loops until the user signals to quit.
  - **Use:** The REPL is bundled with with every Node.js installation and allows you to quickly test and explore JavaScript code within the Node environment without having to store it in a file. Entering "node" in the terminal starts the REPL
  - **Example:**

  ```promises and then() method
  sammy@b6755984:~$ node     //press enter on "node" to get ">", indicating the start
  Welcome to Node.js v14.19.0.
  Type ".help" for more information.
  > 2+2    //used REPL to evaluate simple math
  4
  ```

  - **Source:** https://www.digitalocean.com/community/tutorials/how-to-use-the-node-js-repl

- [x] T-Node-10) Name the types of API functions in Node.js.

  - **Explanation:** There are two types; **Asynchronous**, Non-blocking functions and **Synchronous**, Blocking functions
  - **Example:** Asynchronous examples would be emails and online forums. Synchronous examples would be instant messaging and video calls.
  - **Source:** https://www.geeksforgeeks.org/types-of-api-functions-in-node-js/

- [x] T-Node-11) What are the functionalities of NPM in Node.js?

  - **Explanation:** NPM serves two main purposes; being an online repository of open-source Node.js projects and a command line utility for interacting with said repository.
  - **Use:** Typically it is used to install packages, manage versions and manage project dependencies.
  - **Source:** https://nodejs.org/en/knowledge/getting-started/npm/what-is-npm/

- [x] T-Node-12) What is the difference between Node.js and Ajax?

  - **Explanation:** Node.js and Ajax are the advanced implementations of JavaScript. They each serve entirely different purposes.
  - **Use:** Ajax is primarily designed for dynamically updating a particular section of a page’s content, without having to update the entire page. Meanwhile, Node.js is used for developing client-server apps.
  - **Source:**

- [x] T-Node-13) What are “streams” in Node.js? Explain the different types of streams present in Node.js.

  - **Explanation:** Streams are objects that enable you to read data or write data continuously.
  - **Use:** There are four types of streams:
    - Readable – Used for reading operations
    - Writable − Used for write operations
    - Duplex − Can be used for both reading and write operations
    - Transform − A type of duplex stream where the output is computed based on input
  - **Source:** https://www.simplilearn.com/tutorials/nodejs-tutorial/nodejs-interview-questions

- [x] T-Node-14) Explain chaining in Node.js.

  - **Explanation:** It is a mechanism where the output of one stream is connected to another stream, creating a chain of multiple stream operations.
  - **Source:**

- [x] T-Node-15) What are Globals in Node.js?

  - **Explanation:** Node.js Global Objects are the objects that are available in all modules. Global Objects are built-in objects that are part of the JavaScript and can be used directly in the application without importing any particular module.
  - **Use:** Common built-in modules, functions, strings and objects used widely in Node.
  - **Example:** setTimeout() is a global function used to run a callback after at least x milliseconds:

```javascript
function printHello() {
  console.log('Hello World!');
}
//call printHello() after 2 seconds
setTimeout(printHello, 2000);
```

- **Source:** https://www.tutorialspoint.com/nodejs/nodejs_global_objects.htm

- [x] T-Node-16) What is Event-driven programming?

  - **Explanation:** Event-driven programming is used to synchronize the occurrence of multiple events and to make the program as simple as possible. The basic components of event-driven programming are:
	- A callback function (ie. an event handler) is called when an event is triggered.
	- An event loop that listens for event triggers and calls the corresponding event handler for that event.
  - **Source:**

- [x] T-Node-17) What is Event loop in Node.js? And How does it work?

  - **Explanation:** The Event loop handles all async callbacks. We can attach listeners to events, and when a said event fires, the listener executes the callback we provided.
  - **Use:** Whenever we call `setTimeout`, `http.get` and `fs.readFile`, Node.js runs the operation and continues to run other code without waiting for the output. When the operation is finished, it receives the output and runs our callback function. All the callback functions are queued in an loop, and will run one-by-one when the response has been received.
  - **Source:** https://vigowebs.medium.com/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678

- [x] T-Node-18) What is the purpose of `module.exports` in Node.js?
  - **Explanation:** In Node.js, a module encapsulates all related code into a single unit of code by moving all relevant functions into a single file.
  - **Use:** You may export a module with the `module.exports` function, which lets it be imported into another file using `require`
  - **Source:** https://www.simplilearn.com/tutorials/nodejs-tutorial/nodejs-interview-questions

- [x] T-Node-19) What is the difference between Asynchronous and Non-blocking?

  - **Explanation:** **Asynchronous** literally means not synchronous. HTTP requests which are asynchronous, means we are not waiting for the server response. The program continues with other code blocks and deals with the server response when it is received. The term **Non-Blocking** is widely used with I/O. For example non-blocking read/write calls return with whatever they can do and expect caller to execute the call again. Read will wait until it has some data and put the calling thread to sleep.

- **Source:** https://vigowebs.medium.com/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678

- [x] T-Node-20) What is Tracing in Node.js?

  - **Explanation:** Tracing provides a mechanism to collect tracing information generated by V8, Node core and userspace code in a log file.
  - **Use:** Tracing can be enabled by passing the `--trace-events-enabled` flag when starting a Node.js application. The set of categories for which traces are recorded can be specified using the `--trace-event-categories` flag followed by a list of comma separated category names. By default the `node` and `v8` categories are enabled. Log files can be opened in the `chrome://tracing` tab of Chrome.
  - **Source:** https://vigowebs.medium.com/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678

- [x] T-Node-21) How will you debug an application in Node.js?

  - **Explanation:** Typically using the `debugger` utility and `console.log()`. I would place `debugger` statements in the code wherever I would like a breakpoint inserted and then run the script with node and `debug` enabled.
  - **Source:** https://vigowebs.medium.com/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678

- [x] T-Node-22) Difference between `setImmediate()` and `setTimeout()`?

  - **Explanation:** setImmediate() is to schedule the immediate execution of callback after I/O (input/output) event callbacks and before setTimeout and setInterval. setTimeout() is to schedule execution of a one-time callback after delay milliseconds. both are async.
  - **Use:** Inside an I/O cycle, the setImmediate() should execute before setTimeout({},0).
  - **Example:**

  ```// timeout_vs_immediate.js
  const fs = require('fs');

  fs.readFile(__filename, () => {
    setTimeout(() => {
      console.log('timeout');
    }, 0);
    setImmediate(() => {
      console.log('immediate');
    });
  });
  ```

  - **Source:** https://dev.to/ynmanware/setimmediate-settimeout-and-process-nexttick-3mfd

- [x] T-Node-23) What is `process.nextTick()`?

  - **Explanation:** Every time the event loop takes a full trip, we call it a tick. When we pass a function to process.nextTick(), we instruct the engine to invoke this function at the end of the current operation, before the next event loop tick starts. process.nextTick() is actually faster
  - **Use:** Calling setTimeout(() => {}, 0) will execute the function at the end of next tick, much later than when using nextTick() which prioritizes the call and executes it just before the beginning of the next tick.
  - **Example:**

  ```
  process.nextTick(() => {
    // do something
  });
  ```

  - **Source:** https://nodejs.dev/learn/understanding-process-nexttick

- [x] T-Node-24) What is package.json? What is it used for?

  - **Explanation:** All npm packages contain a file, usually in the project root, called package.json - this file holds various metadata relevant to the project. It's a central repository of configuration for tools, for example. It's also where npm and yarn store the names and versions for all the installed packages.
  - **Use:** This file is used to give information to npm that allows it to identify the project as well as handle **the project's dependencies**. It can also contain other metadata such as a project description, the version of the project in a particular distribution, license information, even configuration data - all of which can be vital to both npm and to the end users of the package. The package.json file is normally located at the root directory of a Node.js project.
  - **Source:** https://nodejs.org/en/knowledge/getting-started/npm/what-is-the-file-package-json/

- [x] T-Node-25) What is libuv?
  - **Explanation:** `libuv` is a multi-platform support library with a focus on asynchronous/non-blocking I/O. It was developed mainly to be used by Node.js, but it is also used by other libraries such as Luvit, Julia, pyuv, etc.
  - **Use:** It provides mechanisms to handle file systems, DNS, networks, child processes, pipes, and more. Some features of `libuv` are:
	- Full-featured event loop backed by epoll, kqueue, IOCP, event ports.
	- Asynchronous file and file system operations.
	- Child processes.
	- File system events.
  - **Source:**
	
- [x] T-Node-26) What are some of the most popular modules of Node.js?
  - **Explanation:**
	- Express
	- Async
	- Browserify
	- Socket.io
	- Bower
  - **Source:**
	
- [x] T-Node-27) What is `EventEmitter` in Node.js?
  - **Explanation:** EventEmitter is a class that holds all the objects that can emit events.
  - **Use:** Whenever an object from the EventEmitter class throws an event, all attached functions are called upon synchronously.
  - **Source:** https://www.simplilearn.com/tutorials/nodejs-tutorial/nodejs-interview-questions

### CS Theory 

- [x] T-CSTheory-1) What is recursion and give an example using javascript?
- **Explanation:** Recursion is when a function calls itself within its own body. Besides the recursive call, it should always have a base case which stops it from calling itself to prevent infinite loops.
- **Use:** Recursion is made for solving problems that can be broken down into smaller, repetitive problems. It is especially good for working on things that have many possible branches and are too complex for an iterative approach.
- **Example:** A classic example is computing a factorial given a number `num`:

```js
function factorial(num) {
  if (num === 1) {
    return num;
  }
  return num * factorial(num - 1);
}
```

**Source:** https://developer.mozilla.org/en-US/docs/Glossary/Recursion

- [x] T-CSTheory-2) What are types?

  - **Explanation:** Types, also called data types, each have a unique set of rules/instructions of what can and can't be done with it.
  - **Use:** Types are necessary so that the computer knows how to handle data when trying to do an operation with it.
  - **Example:** A few data types that are shared by most programming language are:
    - Boolean (ex. true or false)
    - String ("hello world")
    - Float (3.1415)
  - **Source:** https://www.youtube.com/watch?v=A37-3lflh8I

- [x] T-CSTheory-3) What are data structures?

  - **Explanation:** Data structures is storage that is used to store and organize data. It is also a way of arranging data on a computer in such a way that it can be updated and accessed efficiently.
  - **Use:** Data structures are not only used for processing, retrieving, and storing data, but also organizing the data into more readable ways.
  - **Example:** There are many types of data structures, all classified as either linear or non-linear. The following are some examples:
    - Linear Static Data Structures (Arrays)
    - Linear Dynamic Data Structures (Queue, Stack, Linked List)
    - Non-linear Data Structures (Tree and Graphs)
  - **Source:** https://www.geeksforgeeks.org/data-structures/

- [x] T-CSTheory-4) What is an algorithm?

  - **Explanation:** In literal terms, an algorithm is a set of rules to be followed in calculations or other problem-solving opterations or a procedure for solving a mathematical problem in a finite number of steps that frequently by recursive operations.
    In other words, an Algorithm refers to a sequence of finite steps to solve a particular problem.
  - **Use:** Algorithms can be used for many things such as building a solution by searching all available solutions, searching, and sorting.
  - **Example:**
    - Breadth First Search Algorithm
    - Recursive Algorithms
    - Brute Force Algorithms
  - **Source:** https://www.geeksforgeeks.org/introduction-to-algorithms/

- [x] T-CSTheory-5) What is scope / lexical scope in javascript?

  - **Explanation:** Scope refers that the accessibility of variables, depending on where they are declared in the code they are “visible” and thus can be called. Lexically scoped variables can only be called from within the block of code they are defined, generally speaking inside of a function.
  - **Use:** It is used to avoid scope pollution, or unwanted invoking of variables
  - **Source:**

- [x] T-CSTheory-6) What is polymorphism?

  - **Explanation:** Polymorphism is a concept of Object-oriented programming(OOP) Paradigm that provides a way to perform a single action in different ways.
  - **Use:** It provides an ability to call the same method on different JavaScript objects
  - **Example:**

  ```javascript
  class A {
    display() {
      console.log('A is invoked');
    }
  }

  class B extends A {}

  class C extends A {
    constructor() {
      super();
    }

    //overrides the display function of A and hence behaves differently
    display() {
      console.log('C is invoked');
    }
  }
  var b = new B();
  var c = new C();
  b.display(); //output: :"A is invoked"
  c.display(); //Output: "C is invoked"
  ```

  - **Source:**https://www.javatpoint.com/javascript-oops-polymorphism, www.stackOverflow.com

- [x] T-CSTheory-7) What is encapsulation?

  - **Explanation:** A tenet of OOP, it is the wrapping up of data under a single unit, those being variables, and functions acting on those variables. In JS this is accomplished with objects and constructor functions
  - **Use:** Its main benefit is it allows your code to be more readable, and robust against errors.
  - **Example:**

  ```javascript
  class Person {
    #name = 'Nathan';

    getName() {
      return this.#name;
    }

    setName(name) {
      this.#name = name;
    }
  }
  ```

  - **Source:**https://www.javatpoint.com/javascript-oops-encapsulation

- [x] T-CSTheory-8) What is a Linked List?

  - **Explanation:**
    It is a linear data structure similar to an array, except that elements are not stored on a particular memory location or index but instead represent separate objects containing a reference to the next item on the list
    Elements (commonly called nodes) contain two items: the data and the link to the next node. The data can be of any type.
    In a linked list, the head refers to the first node of the list. Null refers to the last node of the list. If the list is empty, the head is null.
    There are 3 Types: Singly, Doubly and Circular Linked List.
  - **Use:** The DOM, Blockchains, Prototypal Inheritance, Image Viewer, Music Payer and Previous And Next Page...
  - **Example:**

  ```javascript
  const linkedList = {
      head: {
          value: 1
          next: {
              value: 2
              next: {
                  value: 12
                  next: {
                      value: 4
                      next: null
                      }
                  }
              }
          }
      }
  };
  ```

  - **Source:** Implementing A Linked List https://www.freecodecamp.org/news/implementing-a-linked-list-in-javascript/

- [x] T-CSTheory-1) What is a Doubly Linked List?

  - **Explanation:** It is pretty much the same as a linked list, only each node also has a pointer to the previous node and also has a null head pointer. It makes it easier to traverse the nodes and delete items, though they require more space, and take longer due to the extra pointers.
  - **Use:** They are used in stacks, hash tables, and binary trees.
  - **Example:**

  ```javascript
  const morningRoutine = {
    value: 'Make Bed',
    previous: null,
    next: {
      value: 'Drink Tea',
      previous: `<REFERENCE TO NODE MAKE BED>`,
      next: {
        value: 'Brush Teeth',
        previous: `<REFERENCE TO NODE DRINK TEA>`,
        next: null,
      },
    },
  };
  ```

  - **Source:** https://www.geeksforgeeks.org/doubly-linked-list/

- [x] T-CSTheory-9) What is a Queue?

  - **Explanation:** A Queue is a linear structure which follows a particular order in which the operations are performed. The order is First In First Out (FIFO).
  - **Use:** Queue is used when things don't have to be processed immediately, but have to be processed in First In First Out order like Breadth First Search.
  - **Example:** The Event Loop Model prioritizes all the Jobs in a Job Queue.
  - **Source:** https://www.geeksforgeeks.org/queue-data-structure/

- [x] T-CSTheory-10) What is a Stack?

  - **Explanation:** A Stack is a linear data structure which follows a particular order in which the operations are performed. The order is LIFO(Last In First Out).
  - **Use:** Stacks are used to implement functions, parsers, expression evaluation, and backtracking algorithms.
  - **Example:** The Event loop uses call stack. Every time a script or function calls a function, it's added to the top of the call stack. Every time the function exits, the interpreter removes it from the call stack.
  - **Source:** https://www.geeksforgeeks.org/stack-data-structure/

- [x] T-CSTheory-11) What is a Hash Table?

  - **Explanation:** Also known as a hash map or dictionary, is a data structure that implements a set data type, in a structure that can map keys to values. In JS you can create them with objects as they offer an easy way to make key/value pairs. When a key is passed into the table the corresponding value is returned.
  - **Use:** Hash tables are used in all manner of tasks, the most common however would be password verification
  - **Example:**

  ```javascript
  function test() {
    var map = {
      m1: 12,
      m2: 13,
      m3: 14,
      m4: 15,
    };
    alert(map['m3']);
  }
  ```

  - **Source:** https://www.geeksforgeeks.org/hashing-data-structure/

- [x] T-CSTheory-12) What is a Heap?

  - **Explanation:** They are binary tree-based data structures, Heaps come in one of two forms min-heaps, and max-heaps, the only difference between the two, min and max, is that the root node in max-heap is the biggest key working down, and min is the reverse, this must be recursively true for all sub-trees in that binary tree.
  - **Use:** Heaps are generally used in priority queues. or to order statistics
  - **Example:**

  ```
            10
          /     \
       15         30
     /    \      /    \
   40      50  100     40
          min heap

            100
          /     \
       40         50
     /    \     /     \
   10      15  50      40
          max heap
  ```

  - **Source:** https://www.geeksforgeeks.org/heap-data-structure/?ref=lbp

- [x] T-CSTheory-13) What is a Trie?

  - **Explanation:** It is a type of tree data structure, they are used to store associate arrays where the keys are usually strings. They are often compared to hash tables, though some key differences are that.
    Nodes in the tree do not store keys, instead, they each store parts of keys, traversing down from the root node to a leaf allowing you to build the key as you progress, they also don't need to be a value at every node. Values are typically only associated with leaf nodes.
  - **Use:** They are typically used for auto-complete.
  - **Example:**

  ```
                       root
                    /    \    \
                    t    a     b
                    |    |     |
                    h    n     y
                    |    |  \  |
                    e    s  y  e
                 /  |    |
                 i  r    w
                 |  |    |
                 r  e    e
                         |
                         r
  ```

  - **Source:** https://www.geeksforgeeks.org/trie-insert-and-search/

- [x] T-CSTheory-14) What is a Tree?

  - **Explanation:** Trees are non-linear data structures, they organize data hierarchically. They are a collection of nodes, that are linked via branches, each node branches to its child nodes. They are possibly the most commonly used data structure. You can think of it as a family tree, or company structure, branching down from the root node (CEO) to child nodes (managers) and terminating at leaf nodes(entry level employees)
  - **Use:** The DOM, file management, and even machine learning decision-based algorithms.
  - **Source:** https://www.programiz.com/dsa/trees

- [x] T-CSTheory-15) What is a Binary Search Tree?

  - **Explanation:** A binary search tree, or "ordered binary tree" is a type of binary tree where the nodes are arranged in order: for each node, all elements in its left subtree are less than the parent node, and all the elements in its right subtree are greater than the parent node.
  - **Use:** They are used to implement dictionaries, implement multilevel indexing in DBs. as well as Implementing search algorithms.
  - **Example:**

  ```
            5
          /   \
        3      6
       /  \      \
     1     4      9

  ```

  - **Source:** https://www.geeksforgeeks.org/binary-search-tree-data-structure/?ref=gcse

- [x] T-CSTheory-16) What is a Disjoint Set?

  - **Explanation:** Disjoint-set is a data structure that keeps track of a elements broken down into sets, of which each set is unique. It is useful for keep track or elements as you can compare sets to see what set they belong to. They are two main functions used on these sets, being union and find.
  - **Use:** The uses for this data structure are compilers and symbolic computation
  - **Source:** https://www.oodlestechnologies.com/blogs/understanding-disjoint-set-and-their-use-cases-in-computer-science/#:~:text=1It%20is%20used%20to,used%20in%20Maze%20generation%20problems

- [x] T-CSTheory-17) What is a Bloom Filter?

  - **Explanation:** It is a probabilistic data structure that is execptionally space-efficient , it is used to check to see if an element is a member of a set. A common use case is checking the availability of a username, this approach is far more efficient than alternative solutions, however, since it is probabilistic it can return false positives so it is not suitable for mission-critical tasks. It is important to note that although it can give a false positives it is not possible to return a false negative.
  - **Use:** This used to be used in search engines, and currently has found use in blockchain technology
  - **Source:** https://www.geeksforgeeks.org/bloom-filters-introduction-and-python-implementation/?ref=gcse

- [x] T-CSTheory-18) Demonstrate Bubble Sort and explain when you might use it?

  - **Explanation:** A bubble sort algorithm is an algorithm that sorts an array by comparing two adjacent elements and swaps them if they are not in the intended order. Order can be anything like increasing order or decreasing order.
  - **Use:** It is generally considered a bad practice to implement this in most situations, though it is easy to implement so for a first-pass solution, on a small data set it can find use.
  - **Example:**

  ```javascript
  function bblSort(arr){
    for(let i = 0; i < arr.length; i++){
      // Last i elements are already in place
      for(let j = 0; j < ( arr.length - i -1 ); j++){
        // Checking if the item at the present iteration
        // is greater than the next iteration
        if(arr[ j ] > arr[ j +1 ]){
          // If the condition is true then swap them
          let temp = arr[ j ]
          arr[ j ] = arr[ j + 1]
          arr[ j+1] = temp
        }
      }
    }
  ```

  - **Source:** https://www.geeksforgeeks.org/bubble-sort/?ref=gcse

- [x] T-CSTheory-19) Demonstrate Insertion Sort and explain when you might use it?

  - **Explanation:** Insertion sort is a simple sorting algorithm that builds the final sorted array/list one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.
  - **Use:** It is very efficient in smaller data sets, especially if they are already mostly sorted.
  - **Example:**

  ```javascript
  function insertionSort(inputArr) {
    let n = inputArr.length;
    for (let i = 1; i < n; i++) {
      // Choosing the first element in our unsorted subarray
      let current = inputArr[i];
      // The last element of our sorted subarray
      let j = i - 1;
      while (j > -1 && current < inputArr[j]) {
        inputArr[j + 1] = inputArr[j];
        j--;
      }
      inputArr[j + 1] = current;
    }
    return inputArr;
  }
  ```

  - **Source:** https://www.geeksforgeeks.org/insertion-sort/?ref=g

- [x] T-CSTheory-20) Demonstrate Merge Sort and explain when you might use it?

  - **Explanation:** Merge sort is a sorting algorithm that uses the “divide and conquer” concept. Given an array, we first divide it in the middle and we get 2 arrays. We recursively perform this operation, until we get to arrays of 1 element. After divinding into its smallest units it starts merging the elements again based on their size.
  - **Use:** It is one of the most respected sorting algorithms. Merge sort is more efficient and works faster than quick sort in case of larger array size or datasets.
  - **Example:**

  ```javascript
  const _mergeArrays = (a, b) => {
    const c = [];
    while (a.length && b.length) {
      c.push(a[0] > b[0] ? b.shift() : a.shift());
    }
    // if we still have values, let's add them at the end of `c`
    while (a.length) {
      c.push(a.shift());
    }
    while (b.length) {
      c.push(b.shift());
    }
    return c;
  };

  const mergeSort = (a) => {
    if (a.length < 2) return a;
    const middle = Math.floor(a.length / 2);
    const a_l = a.slice(0, middle);
    const a_r = a.slice(middle, a.length);
    const sorted_l = mergeSort(a_l);
    const sorted_r = mergeSort(a_r);
    return _mergeArrays(sorted_l, sorted_r);
  };
  ```

  - **Source:** https://www.geeksforgeeks.org/merge-sort/?ref=gcse

- [x] T-CSTheory-21) Demonstrate Quicksort and explain when you might use it?

  - **Explanation:** Quicksort is an in-place sorting algorithm. it is still a widely used algorithm for sorting. It picks an element as a pivot and partitions the given array around the picked pivot. There are many different versions of quickSort that pick pivot in different ways. When implemented well, it can be somewhat faster than merge sort and about two or three times faster than heapsort.
  - **Use:** It is used pretty much everywhere that doesnt require a stable sort.
  - **Example:**

  ```javascript
  function quicksort(array) {
    if (array.length <= 1) {
      return array;
    }

    let pivot = array[0];
    let left = [];
    let right = [];

    for (let i = 1; i < array.length; i++) {
      array[i] < pivot ? left.push(array[i]) : right.push(array[i]);
    }

    return quicksort(left).concat(pivot, quicksort(right));
  }

  let unsorted = [23, 45, 16, 37, 3, 99, 22];
  let sorted = quicksort(unsorted);

  console.log('Sorted array', sorted);
  ```

  - **Source:** https://www.geeksforgeeks.org/quick-sort/?ref=gcse

## Questions to ask your interviewer

1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?
7. If Bob's Burgers hired me today how would you know in a year's time that I was the right fit?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

## Whiteboard

When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time 😉)

- **Parameters**
  - Inputs
  - Ask questions
    - Will it always be a number?
    - Will it ever be negative?
    - Any gotchas?
- **Returns**
  - Ask questions
    - Do you want it returned or is a console.log better?
    - Should I pass a whole array of solutions back or just a single solution?
- **Examples**
  - Show a couple black box examples, aka test cases
    - I pass in these arguments and get these results, is that correct?
  - Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
  - Write pseudocode of each of the steps

## Resources:

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
