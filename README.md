# Awesome Frontend Resources 👓🖌️

<p align="center">
    <img width="300" src="./logo.png" alt="logo of awesome-vite repository"/>
    <br />
    <br />
</p>

> 🧠 A **personal** curated list of awesome things related to Front-end development - HTML, CSS, JS and more. 

Note that this is still a Work-In-Progress 🚧👷‍♂️ as I have stored links and bookmarks probably for the last 5 years. I will try to update & support the list semi-often.

<br />
<p align="center">
	<a href="notes/What-And-Why.md">What is this and why?</a>&nbsp;&nbsp;&nbsp;
	<a href="notes/Contribution.md">Want to add to the list?</a>&nbsp;&nbsp;&nbsp;
</p>

<br />

## Other Awesome lists
- [Awesome: Awesome lists about all kinds of interesting topics ](https://github.com/sindresorhus/awesome)
- [Awesome HTML: A curated list of awesome HTML5 resources](https://github.com/diegocard/awesome-html5)
- [Awesome CSS: A curated contents of amazing CSS](https://github.com/awesome-css-group/awesome-css)
- [Awesome Vue: A curated list of awesome things related to Vue.js ](https://github.com/vuejs/awesome-vue)
- [Awesome Vite: A curated list of awesome things related to Vite.js ](https://github.com/vitejs/awesome-vite)
- [Awesome React: A collection of awesome things regarding React ecosystem ](https://github.com/enaqx/awesome-react)

<br />
<br />

# ![](https://img.shields.io/badge/resource-HTML-orange) HTML
- [W3S - HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp) - What is Semantic HTML and why use it
- [Semantics - HTML, CSS, JS](https://developer.mozilla.org/en-US/docs/Glossary/Semantics) - Examples on semantics
- [MDN - h1–h6: The HTML Section Heading elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements#problems_solved_by_html5) - Documentation and examples on using headings in HTML
- [MDN - HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) - This page lists all the HTML elements by groups
- [Kevin Powell - 5 important HTML concepts for beginners](https://www.youtube.com/watch?v=HJ0-fUJ-2F0)
- [Kevin Powell - The most common HTML mistake that I see](https://www.youtube.com/watch?v=NexL5_Vdoq8)
- [`<article>` vs. `<section>`: How To Choose The Right One](https://www.smashingmagazine.com/2022/07/article-section-elements-accessibility/) - A pretty in-depth take on the forever question `div` vs `section` vs `article`.
    - > I gave my usual answer: think of `<article>` not just as a newspaper article or a blog post, but as an article of clothing — a discrete entity that can be reused in another context. So your trousers are an article, and you can wear them with a different outfit; your shirt is an article and can be worn with different trousers; your knee-length patent leather stiletto boots are an article (you wouldn’t wear just one of them, would you?).
    - Does grouping this content play a role that may help explain my document structure? If it does not, then I can use a div. If it does, play a role and proceed to consider if the role matches a section or an article. What role does it play in my document structure? Is the content of this group thematically related such that it helps to understand the outline of my document? If it is, then it is possibly a section. Is the content of this group one that contains content that I can take out and redistribute to other pages while it does not totally tie to my document theme and outline? If it is, then it is possibly an article.
- [Div divisiveness](https://www.scottohara.me/blog/2022/01/20/divisive.html) - Why `div`s aren't evil & why any overexaggerating is bad. Also a lot of good examples where you should and should probably not use `div`.
    - By representing nothing, a `<div>` is free to be anything. A `<div>` is essentially chaotic neutral and can easily pivot between valid and invalid use, per the whim of the developer that uses it.
    - Use semantic HTML. Use semantic HTML as a default. Just maybe also don’t worry so much about if other people aren’t using semantic HTML if what they’ve built doesn’t actually result in accessibility issues? Or, if calling out the lack of semantic HTML, be very specific about what the actual problem is. The semantics of HTML are not just about accessibility. They’re useful for other tools that consume HTML, and can be far easier to understand for fellow developers modifying markup than a sea of never-ending `<div>`s.
    - Remember, `<div>`s are meant to represent nothing. They can be made into just about anything… just don’t make them into soup.


<br />
<br />

# ![](https://img.shields.io/badge/resource-CSS-blue) CSS


- [caniuse.com](https://caniuse.com/) 
- [CSS-Tricks - What are CSS Modules and why do we need them?](https://css-tricks.com/css-modules-part-1-need/)
- [CSS-Tricks - Should I Use Source Maps in Production?](https://css-tricks.com/should-i-use-source-maps-in-production/)
- [Smashing Mag - Flexbox use cases](https://www.smashingmagazine.com/2018/10/flexbox-use-cases/) - Flexbox vs Grid
- Centering in CSS 
  - [CSS Tricks - Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/)
  - [Stephanie Eckles' - The Complete Guide to Centering in CSS](https://moderncss.dev/complete-guide-to-centering-in-css/)
- [A List Apart - Axiomatic CSS and Lobotomized Owls](https://alistapart.com/article/axiomatic-css-and-lobotomized-owls/)
- [CSS-Tricks - A Complete Guide to CSS Media Queries ](https://css-tricks.com/a-complete-guide-to-css-media-queries/)


<br />

## "Modern" CSS
- Flexbox
  - [CSS-Tricks - A Complete Guide to Flexbox ](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [MDN Basic - concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
  - [Test CSS Flexbox Rules](https://flexbox.help/)
  - [Flexbox Froggy](https://flexboxfroggy.com/)
  - [Flex Box Adventure](https://codingfantasy.com/games/flexboxadventure)
  - [Flexbox Playground](https://flexbox.tech/)
  - [Common CSS Flexbox Layout Patterns with Example Code](https://tobiasahlin.com/blog/common-flexbox-patterns/)
- Grid
  - [CSS-Tricks - A Complete Guide to Grid ](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [MDN - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- Min, Max, Clamp
  - [Web.dev - three logical CSS functions to use today](https://web.dev/min-max-clamp/) 
  - [ModernCSS - Practical Uses of CSS Math Functions: calc, clamp, min, max](https://moderncss.dev/practical-uses-of-css-math-functions-calc-clamp-min-max/)
- Fluid Typograhy
  - [CSS-Tricks - Simplified Fluid Typography ](https://css-tricks.com/simplified-fluid-typography/)
  - [ModernCSS - Generating `font-size` CSS Rules and Creating a Fluid Type Scale](https://moderncss.dev/generating-font-size-css-rules-and-creating-a-fluid-type-scale/)

<br />

## SASS / SCSS
- [Stop using @import with Sass | @use and @forward explained](https://www.youtube.com/watch?v=CR-a8upNjJ0)

<br />

## Snippets. Latouts. Patterns. Components.
- [SmolCSS](https://smolcss.dev/) - Minimal snippets for modern CSS layouts and components
- [CSS Layouts](https://csslayout.io/) - Popular layouts and patterns made with CSS

<br />

## Utilities
- [A Modern CSS Reset](https://piccalil.li/blog/a-modern-css-reset/) or the classic [meyerweb](https://meyerweb.com/eric/tools/css/reset/)
- Vendor Prefixes
  - [What are Vendor Prefix](https://developer.mozilla.org/en-US/docs/Glossary/Vendor_Prefix)
  - [Autoprefixer: A Postprocessor for Dealing with Vendor Prefixes in the Best Possible Way ](https://css-tricks.com/autoprefixer/)
  - Autoprefixer: [NPM package](https://github.com/postcss/autoprefixer) or [online](https://autoprefixer.github.io/)

<br />

## Methodologies & naming conventions
- [BEM](http://getbem.com/)
- [BEMIT: Taking the BEM Naming Convention a Step Further](https://csswizardry.com/2015/08/bemit-taking-the-bem-naming-convention-a-step-further/)
- [SMACSS](http://smacss.com/)
- [OOCSS](http://oocss.org/)
- [Atomic CSS](https://acss.io/)
- [Cube CSS](https://cube.fyi/)

<br />

## CSS Minification/Compression
- [Benchmarks](https://goalsmashers.github.io/css-minification-benchmark/)
- [cssnano](https://github.com/cssnano/cssnano)
- [csso](https://github.com/css/csso)
- [clean-css](https://github.com/clean-css/clean-css)



<br />
<br />

# ![](https://img.shields.io/badge/resource-JS-yellow) JS

## React
- [Robin Wieruch](https://www.robinwieruch.de/blog/) - bery good articles for React, Node and JS/TS in general
- [Kent C Dodds](https://kentcdodds.com/blog) - a log of articles and knowledge on JS testing

<br />
<br />

# ![](https://img.shields.io/badge/resource-Performance-green) Performance
- [My web performance journey with Nuxt, Storyblok & Netlify ](https://www.dawntraoz.com/blog/my-web-performance-journey-with-nuxt-storyblok-netlify/) - though it says Nuxt, there are a lot of important general points and topics you can discover here; specific packages and alternatives are shared
- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - Very good and detailed lesson on why and how to use responsive images. Covers both `srcset` & `picture`
- 

<br />
<br />

# ![](https://img.shields.io/badge/resource-General-9cf) General
- [Design Patterns](https://refactoring.guru/design-patterns)
- [Refactoring](https://refactoring.guru/refactoring)

<br />
<br />

# ![](https://img.shields.io/badge/resource-Courses-violet) Courses - general

<br />
<br />

# ![](https://img.shields.io/badge/resource-Creators-brightgreen) Creators (in no specific order)
- Kevin Powell - [Youtube](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) - CSS, SASS, HTML
- Traversy Media - [YouTube](https://www.youtube.com/c/TraversyMedia) - Crash Courses on everything Front-end related 
- peruvianidol (Mike Aparicio) - [twitch](https://www.twitch.tv/peruvianidol) & [Youtube](https://www.youtube.com/c/MikeAparicio75) - 11ty, Design Systems, CSS
- Jason Lengstorf / Learn With Jason - [YouTube](https://www.youtube.com/c/Lengstorf) & [website](https://www.learnwithjason.dev/) - Discussions with different developers, showcasing wide range of frameworks and ideas; Web, JS, React, Vue, etc.
- Coding Garden - [twitch](https://www.twitch.tv/codinggarden) & [Youtube](https://www.youtube.com/channel/UCLNgu_OupwoeESgtab33CCw) - JS, Vue, React, Node, Web technologies
- Stephanie Eckles - [twitch](https://www.twitch.tv/5t3phdev) & [website](https://thinkdobecreate.com/)- CSS, a11y, design systems

<br />
<br />

# ![](https://img.shields.io/badge/resource-Assets-informational) Assets (icons, colors, images, etc.)
- [Reddit - Websites I use for free svg Illustrations](https://www.reddit.com/r/webdev/comments/eejh52/websites_i_use_for_free_svg_illustrations/?%24deep_link=true&correlation_id=a1ddfb22-4fb5-4cc8-baba-43e2e8aa4558&ref=email_digest&ref_campaign=email_digest&ref_source=email&utm_content=post_title&utm_medium=digest&utm_name=top_posts&utm_source=email&utm_term=day&%243p=e_as&%24original_url=https%3A%2F%2Fwww.reddit.com%2Fr%2Fwebdev%2Fcomments%2Feejh52%2Fwebsites_i_use_for_free_svg_illustrations%2F%3F%24deep_link%3Dtrue%26correlation_id%3Da1ddfb22-4fb5-4cc8-baba-43e2e8aa4558%26ref%3Demail_digest%26ref_campaign%3Demail_digest%26ref_source%3Demail%26utm_content%3Dpost_title%26utm_medium%3Ddigest%26utm_name%3Dtop_posts%26utm_source%3Demail%26utm_term%3Dday&_branch_match_id=544492509236131805)
- [undraw - illustrations](https://undraw.co/illustrations)
- [iconfinder](https://www.iconfinder.com/)

<br />
<br />

# ![](https://img.shields.io/badge/resource-Hosting-lightgrey) Free hosting
- [Netlify](https://www.youtube.com/watch?v=bjVUqvcCnxM)
- [Netlify Forms](https://www.youtube.com/watch?v=6ElQ689HRcY)
- [Clouflare Pages + GitHub](https://www.youtube.com/watch?v=MTc2CTYoszY)

<br />
<br />

# ![](https://img.shields.io/badge/resource-Emails-yellowgreen) Newsletters
- [JavaScript Weekly](https://javascriptweekly.com/)
- [Frontend Focus](https://frontendfoc.us/)
- [React Status](https://react.statuscode.com/)
