# Required Practices for Web Assignments 2017-2018

In teaching web design as an academic subject, we need standards by which we can judge your work. What follows is based on actual W3C standards and industry ‘best practices’. Although these are often broken in the commercial work environment, it doesn’t mean that they are not best practices. Whilst working for us your work is required to conform to these practices. When out in the real world you will be able to make your own judgement about what to use and what to ignore, but at least you will know why you have come to your decision.

A classic example is the title attribute. On most elements this attribute is not necessary. However, by us insisting you use the title attribute when relevant on links (i.e. expanding on 'About' in a menu) you can hone your skills in writing a relevant title (and not just repeating the link text). Then when you do need to use them on real projects you will understand the context and you know what is required. 

Likewise, missing out an alt description for an image doesn’t mean that the image won’t display. However, learning to write good alt text will considerably improve the user experience for screen reader users. And validating your HTML and CSS not only makes you look more professional, it also helps you ensure your coding is future proof, correct and fit for purpose.

Richard Eskins & Derren Wilson


## Homepage	
The homepage of your site must be called index.html 	A submission that fails to conform will lose marks.

## Validation	
All web pages submitted must validate. Work should usually be validated to HTML 5. Use of other standards should be agreed with the tutor. A submission that fails to validate (any page) will lose marks.

## Disclaimer	
All pages must carry our disclaimer that includes a link to the W3C Validator. Client work for final year projects are exempt.	A submission that fails to use the disclaimer will lose marks.

## HTML5	
HTML5 must be implemented using the best practices from XHTML. 
This includes:
a.	All elements lower case
b.	Quote all attributes
c.	All attributes lower case.
d.	Closing all elements that have a closing tag, e.g. <li></li>	For ‘self closing’ elements such as meta, img or br there is no need for the closing /> in HTML5. For example <br> Is fine, rather than <br />.

## Semantic mark-up
Follow the rules for semantic mark-up. Use tags as intended. Only one `<h1>` for the main heading and `<h2>` to `<h6>` for sub-headings or section headings.

Use <p> for paragraphs. E.g. don’t place a paragraph in a heading just to enlarge the font.	Non-semantic coding (any page) will lose marks.

## Clean mark-up	
Space out / indent your mark-up for easy reading and error detection. If you use CSS pre-processors like Sass or LESS or minify CSS talk to the tutors. We need access to the original files to be able to feedback on your working practices.	Cluttered mark-up will lose marks.

## Commented mark-up	
Use comments in your HTML and CSS to indicate sections, functions, features etc.	Commented mark-up will gain marks. Comments for the sake of comments won't.
 
## CSS	
All elements of design should be delivered via CSS. You should not use ‘old’ (or deprecated) elements such as the <font> tag. CSS should be delivered by one or more external stylesheets. Internal and inline styles should be an exception, explained with a comment.

CSS should be validated to spot mistakes.	A submission that fails to use external CSS will lose marks.

Excess, unused CSS will lose marks.

## Page <title>	
The homepage title should reflect and set a context for the whole site. What we do, who we are, where we are?

Titles for sub-pages should continue this theme, but reflect the actual page content/purpose first (function first).	A submission that has missing or weak titles will lose marks.

## Meta Keywords	
Meta Keywords should make use of any specific (standout) words or phrases relating to the site/business/product. Avoid generic words.	A submission that has missing or limited keywords will lose marks.

## Meta Description	
Meta Description, in particular on the homepage is a chance to sell your site/business/product when listed on Google in 65 characters. Description for sub-pages should reflect content of that individual page (and the overall site/business/product) when possible.	A submission that has a missing or weak description will lose marks.

## Alt text	
All images (unless fluff or decoration) should have descriptive alt text. Images that have no importance (fluff) should have null alt text (`alt=""`). Images containing text should replicate the text in the alt attribute when possible.	A submission that fails to include descriptive alt text for all relevant images will lose marks.

Consider what sort of images should be added with an `<img>` tag and which ones should be added using CSS `background-image`.

## Image captions	
Consider the use of captions with images (if your design allows). Use the `figure` and `figcaption` tags. 	Do not repeat alt text in a caption. Either add to/enhance the alt description in your caption, or have a null alt.

## Title attribute for links	
Not always necessary in the real world but for you to hone your writing skills we expect title attributes when applicable on links. Enhance, don’t replicate link text. Especially effective on menu links (that have short link text).	On the flip side, do not add the title attribute to random elements. It is pointless. DO NOT confuse the title attribute for the alt attribute.

## Link text	
Think about your link text. Don’t use or repeat descriptions such as ‘read more’ or ‘click here’. They tell the user nothing, are bad for accessibility. Good link text has SEO benefits.	A submission that fails to include descriptive link text will lose marks.

## Images as links	
Use the alt text to describe the location of the link. The link element doesn’t need a title attribute.	A submission that fails to use the alt text this way will lose marks.

## Accessibility	
[Conformance to WCAG 2.0](https://www.w3.org/TR/WCAG20/). __Your web site must be accessible!__	

A submission that fails to conform to applicable WCAG 2.0 standards will lose marks.
 
## Image optimisation	

All images must be optimised for the web. If relevant, crop to remove un-necessary elements of your pictures. Resize the physical dimensions of each image to fit the page design. DO NOT resize images with the height & width attributes only.	A submission that fails to optimise all images will lose marks.
You should strive to get image file sizes as small as possible.

Aim for a balance between quality and file size.

## Version control	
We will be encouraging the use of [version control tools such as github](https://education.github.com/pack) in coursework. This is an ‘essential skill’ for the digital industries for a variety of roles, not just techies.	Using version control is a great way to back up your work and you progress through a project.

You can also use for team work for multiple contributions.

## Media	
All text, images, audio and movies should be the student’s own, original work or belong to your client. Use of library items must be credited. You can use creative commons materials if allowed under the relevant licence.	Use of other people’s work may lead to charges of plagiarism.

Credit is given for original images – not for stock or library images.

## Files & Folders	
* Filenames – no spaces, dashes or underscores to separate words, no caps, relevant names. `DSC 10344.jpg ` should be `drone-takeoff.jpg`.
* Folders – relevant file/folder structure.	Poor file names and/or file/folder structure will lose marks. Even if you have only a few images or a single CSS file it is worth creating a folder for them to keep everything organised.

## Design	
Page design including layout, positioning, use of space, colour and typography.	Good design will gain credit. Design is often the element that lifts excellent work (quality coding and content) into the highest marking bands.

## Usability
Providing the user with ‘a good experience’.	User centred designs with high usability will gain credit.

## Text	
All text must be original unless quoted or provided by a client. Use of other people’s work may lead to charges of plagiarism.

## Grammar	
All text should be spell checked and grammar checked.	A submission that includes typing errors and/or bad grammar cannot attain a mark of excellent.

## Coding	
All coding must be original. If you have used scripts or code from tutorials or such in your work you must always credit using comments.

Use of other people’s work may lead to charges of plagiarism.

## Forms	
Forms can be processed using services such as [formspree.io](http://formspree.io/)

All forms must be accessible and highly usable.
 
## Frameworks for layout
Use of pre-created CSS layout solutions (frameworks or templates) is not acceptable unless specified in class or agreed with tutors.

You are learning to code. Create your own grids and layouts.	There are downsides to many grid solutions including bloated code. If your code is bloated (full of unnecessary mark-up and CSS) you will lose marks.

Coursework using predefined solutions may be disqualified.

## CSS pre-processors & compression
Use of CSS pre-processors & compression in coursework must be agreed with tutors.

You may be required to provide access to the original CSS.

Whilst we encourage learning to use these tools you should aim to develop your CSS skills first.

## JavaScript	
Use of JavaScript is encouraged. Make sure you know what you are using. Do not just cut and paste lumps of code. Be careful of using predefined script without knowing how it really functions. Prefer solutions that use 'progressive enhancement' - no inline javascript. Check your website still works with JavaScript turned off, even if the functionality isn't available.

Good implementation will gain credit and as you guessed it, poor implementation will lose credit.

## PHP	
As with JavaScript. Use, but within your limits. As above.

## Other technologies	
There are numerous new technologies being developed for the web almost daily. We encourage you to experiment; to try out some of the latest tools and techniques in your work. Discuss with tutors.	Good implementation will gain credit. Poor implementation will be a disaster and could cause much pain!

Always be prepared to 're-wind' when things don't work. Version control can help with this.

