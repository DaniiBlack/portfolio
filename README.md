## Project Requirements

### Content:
1. Include at least one profile picture. 🍎
2. Include biography (at least 100 words). 🍎
3. ~~Include a functional contact form.~~ ✅
4. ~~Have a section dedicated to listing projects you have worked on (there are many projects to add throughout this course!).~~ ✅
5. ~~Links to external sites, e.g. GitHub and LinkedIn.~~ ✅

### Technical:
1. ~~Have at least 2 web pages.~~ ✅
2. ~~Be deployed on GitHub pages.~~ ✅
3. ~~Implements responsive design principles.~~ ✅
4. ~~Uses semantic HTML.~~ ✅
**Bonus**
- ~~Have different styles for 
- - ~~ active ~~ ✅
- - ~~ hover ~~ ✅
- - focus states. 🍎
- Use JavaScript to add some dynamic elements to your site. 🍎

### Submission
**Please submit the following:**
1. A link to your website.
2. A document containing a link to your repository.
3. Create a "screenshots" folder in the repository, containing screenshots that show:
   1. The different pages and features of your website on;
      1.  mobile
      2.  tablet
      3.  desktop screen sizes 
      4.  (multiple screenshots per page and screen size).
   2. The different features of your site, e.g. if you have hover states, take a screenshot that shows that.

[steps to submit linked here](https://shecodes.thinkific.com/courses/take/she-codes-plus-sydney-22-23/assignments/38847850-project-portfolio-website)

------------------------------------------------

#### Nav
**Start with semantic html**
1. Header ✅
   1. h1 ✅
   2. Nav ✅
      1. List <ul><li></li></ul> ✅
         1. Anchor ✅
**Style**
1. remove li dots ✅
2. remove underline, blue etc, make them pretty ✅
**Add nav dropdown**
1. Add a button above the list (inside nav) ✅
2. style the button so its `display: none` ✅
3. Add an MQ for `max width 600`. ✅
   1. inside mq, style button to `display: block` ✅
   2. inside mq, style your list items to be `display:none` ✅
   3. ~~on `hover` state for button, set `display:block` again on list items~~

**Right and left align the nav**

- at full width, nav is on the left 
- at half and less, nav is at the top
  - this is when burger appears 
  - when click on burger; nav dropdown is aligned to the right

1. 


**Hamburger menu svg**

**TODO**
* nav on left with logo as header
  * TODO: design logo
* nav at top, logo chnages to name. Hamburger on the right 
* when hampurger selected, then dropdown is on right.
  * create hamburger svg


**Notes / checklist** 
- Ensure when page is smaller and nav has been selected, that nav does not disappear lol 
- ensure nav is always set and will not move when hovered over (right especially)

----------------

### Flex box version of your page!!

#### CSS

##### Body
1. ~~Make Body display flex~~
2. ~~on main add the following stuff~~
   1. vertical-align: top // this puts it up the top of the space
   2. margin: 10px // play with this one just make it a little less crowded
   3. flex-grow: 1 // make it fill remaining space
3. ~~Inside media query change flex-direction to column~~
##### Header
1. ~~Set display to flex~~
2. ~~Make flex direction column~~
3. ~~Add min-width: 200px (or similiar)~~
4. ~~Inside media query make flex-direction row~~
##### H1
1. add some styling, add a little margin like 10-20 🍏
##### Nav
1. Add a little padding if you want 🍏
2. ~~Inside media query set margin-left: auto (This aligns it to the right in flex box)~~
##### Button stuff (Back to how it was)
1. ~~Display none~~
2. ~~Media query display block~~
3. Add somes styling, make it into a burger? 🍏

### HTML
1. Wrap your two lists in a div with a class "nav-content"

### CSS
#### header
1. set the height to 100vh; ✅
2. set the position to sticky; ✅
3. set top to 0; ✅ 🍎
4. set  background-color to white; ✅
5. inside media query set height to 50px (or more) ✅ 🍎
#### nav
1. set display flex ✅
2. set flex-grow 1 ✅
3. inside media query set flex-grow 0 ✅
#### nav-content 
1. set display flex ✅
2. set flex-direction to column ✅
3. set flex-grow to 1 ✅
4. Inside media query 
    1. change the ul to .nav-content ✅
    2. change the nav:hover ul to nav:hove .nav-content ✅
#### socials     
1. set display to flex (this makes them next to each other) ✅
2. set margin-top to auto ✅
3. ~~target social li elements and give them some padding like padding-right 5px~~
   
4. TODO [Additionally, if you really want to be specific, you can toggle your button’s text between 'Open Menu’ and 'Close Menu’ with JavaScript.](http://web-accessibility.carnegiemuseums.org/code/navigation/)


##### List stuff
1. ~~Style CSS to remove the underline/blue/dot points on list~~
2. ~~Remove padding and margin on ul (It has padding by default so set them to 0)~~
3. ~~Inside media query on ul~~
    1. ~~Set display none~~
    2. ~~Set position absolute (This makes it float over stuff)~~
    3. ~~Set a background-color white~~ and add some poadding 🍏
4. ~~on "nav:hover ul" set display to block~~ ✅










### Misc TODO
- use javascript to make the navigation move over when screen is smaller
- menu when floating right:
- - Button, A11y standards? UI should only drop-down menu when hover over button. Sort out styling and to use type=button or role=button?
- - Links/icons to socials, to be inline
- - menu ui to be wider, maybe to the bottom of the page, adjusting the content to not be cut-off when toggling menu open and closed 
- - ensure semantic a11y html re. toggle/ open/closed (using javascript let screen reader know if the menu is opened or closed)
- - name to be logo when nav floating left and name when nav floating right.

#### Accessibility 
- dt; dd; dl tags?! To use or not to use? On the button to descrbe it is nav/menu?
- scope out making menu button a checkbox instead of button.

#### Contact form 
- too high on page 
- style button more
- look at design for full-page 
- ensure mobile-view is ok 
- re-configure a new form in the website thing.


