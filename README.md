# fun-home-town-html

For this challenge you need to demonstrate your HTML and CSS skills by building a site about your home town / favourite place. You should show your ability to setup a project on github as well as creating and linking the relevant html and css files. Your site should be:

- **responsive** - it should be functional at different screen sizes
- **accessible** - it should employ good practises for those using alternative means to access the website, i.e. screen readers
- **readable** - it should be readable, not least for potential employers who might want to view the source code of your site
- **attractive** - it should look good!

...and it should have...

- a home page
- at least 2 additional pages containing information on your chosen place
- what you have on your pages is up to you, feel free to get creative
- a way to navigate around the different pages of your site

## Steps

1. Before you start any work on your portfolio site please watch the following videos:
2. Create your own GitHub repo for this task. Clone it to your computer.
3. Create a structure inside this folder to hold your website assets. There's a guide on how to do this on [MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files).
4. Build your site! We suggest starting with the basic HTML structure, then bringing in CSS and any other JavaScript when you are happy with the content.
5. Remember to add and commit your changes frequently as you work.
6. When you're ready to show the world, you might want to look at [GitHub Pages](https://pages.github.com/) as a solution for deploying.

## Resources

Below are some extra resources on HTML and CSS that you may find useful.

### Responsive Design

Nowadays most visits to websites are made on mobile and tablet devices. This means people are viewing sites on a range of different screen sizes, and we need to make sure our site looks attractive and provides a good user experience across all devices. Responsive design is the process of designing and building our sites with this in mind. There are a few concepts and features in CSS that you should get to know to help with this:

- The use of **relative units** when we specify sizes and positions with CSS. There is a short section on the [% unit](http://learnlayout.com/percent.html) on LearnLayout. Read this article on [Relative Units](https://thecssworkshop.com/lessons/relative-units) and maybe try some out on Codepen.

- The use of **media queries**. Media Queries allow us to specify particular styling to be applied at specific ranges of screen sizes, giving us extra control over where we position things and how we size elements and typefaces on different sized devices. There is a short section on the [Media Queries](http://learnlayout.com/media-queries.html) on LearnLayout. Also read this [CSS Tricks Guide to Media Queries](https://css-tricks.com/css-media-queries/) and experiment on Codepen.

- The **flexbox** layout model has been around since the early 2010s, and was created with responsiveness in mind. It is very commonly used now to handle alignment across one direction, and is worth getting on top of. The [MDN basic concepts walkthrough](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) is an excellent introduction, then the [CSS Tricks guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) is a great reference. Kill some time and learn some flexbox with [Flexbox Froggy](https://flexboxfroggy.com/) and [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies).

- Finally, the new kid on the block is **CSS grid**. It has been supported on all major browsers since the end of 2017, and is becoming more and more widely implemented. Whereas flexbox is focused on handling elements across one dimension, you can think of CSS Grid as a mapping tool across two dimensions. Again, your major references should be [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout) and [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/). But [Grid Garden](http://cssgridgarden.com/) is a fun introductory game too.

### Accessibility

Accessibility, commonly referred to a 'a11y' in the tech world, refers to making tech available to as many people as possible, regardless of any disability or impairment. You can read a summary of the aims and legal imperatives we must subscribe to as developers on [W3C](https://www.w3.org/standards/webdesign/accessibility).

One thing you can do from the start is ensure you are using 'semantic HTML' - or the right element for the right occasion - here's an [overview](https://internetingishard.com/html-and-css/semantic-html/). For example, a `<p>` tag represents a **p**aragraph, so that's what it should be used for, because this has implications not only for those read your code, but for [screen readers](https://24ways.org/2017/accessibility-through-semantic-html/) and [SEO optimisation](https://www.inboundnow.com/html5-semantic-elements-mean-seo/) amongst other things.

[Axe](https://www.deque.com/axe/) is an accessibility auditing tool available as an extension on [Chrome](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/axe-devtools/). It will give you some detailed feedback on accessibility issues your website might have - try using it on some popular websites and see where they fall short!

### CSS

Another consideration on larger projects is adopting a naming convention for your CSS classes that is readable and flexible. You might not be doing something on a scale where you reap the benefits, but this would be a good opportunity to explore good practices: consider implementing the [BEM syntax](http://getbem.com/introduction/) in your page.

### Additional Resources

- [fontawesome.io](http://fontawesome.io/) for icons
- [devicon](http://konpa.github.io/devicon/) for some lovely tech icons in particular
- [google fonts](https://fonts.google.com/) for easily implementable fonts
