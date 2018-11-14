---
layout: mmu-list-page
title:  Required Practices for Web Projects
summary: Read this before you make a website!
---

# Required Practices for Web Projects

 <h1>Required Practices for Web Assignments 2018&#8211;2019</h1>

        <div class="box">
            <p>In teaching web design as an academic subject, we need standards by which we can judge your work.</p>
            <p>What follows is based on actual W3C standards and industry ‘best practices’. Although these can be
                broken in the commercial work environment for good reasons, it doesn’t mean that they are not best
                practices. Whilst working for us your work
                is required to conform to these practices. When out in the real world you will be able to make your own
                judgement about what to use and what to ignore, but at least you will know
                <strong>why</strong> you have come to your decision.</p>

            <p>A classic example is the title attribute. On most elements this attribute is not necessary. However, by
                us insisting you use the title attribute when relevant on links (i.e. expanding on 'About' in a menu)
                you can hone your skills in writing
                a relevant title (and not just repeating the link text). Then when you do need to use them on real
                projects you will understand the context and you know what is required.</p>

            <p>Likewise, missing out an alt description for an image doesn’t mean that the image won’t display.
                However, learning to write good alt text will considerably improve the user experience for screen
                reader users. And validating your HTML and CSS
                not only makes you look more professional, it also helps you ensure your coding is future proof,
                correct and fit for purpose.</p>

            <p>&#8212; Richard Eskins &amp; Derren Wilson</p>
        </div>
        <h2>Homepage</h2>

        <p>The homepage of your site must be called
            <code>index.html</code>. A submission that fails to conform will lose marks.</p>

        <h2>Validation</h2>

        <p>
            <a href="https://validator.w3.org/">All web pages submitted must validate</a>. Work should usually be
            validated to HTML5. Use of other standards should be agreed with the tutor. A submission that fails to
            validate (any page) will lose marks.</p>

        <h2>Disclaimer</h2>

        <p>All pages must carry our disclaimer that includes a link to the W3C Validator. Client work for final year
            projects are exempt. A submission that fails to use the disclaimer will lose marks.</p>

        <h2>HTML5</h2>

        <p>HTML5 must be implemented using the best practices from XHTML.</p>

        <p>This includes:</p>
        <ul>
            <li>All elements lower case</li>
            <li>Quote all attributes</li>
            <li>All attributes lower case</li>
            <li>Good
                <br />
                <code>&lt;a href="index.html"&gt;Back to homepage&lt;/a&gt;</code>
            </li>
            <li>Poor
                <br />
                <code>&lt;A HREF=index.html&gt;Back to homepage&lt;/A&gt;</code>
            </li>
            <li>Closing all elements that have a closing tag, e.g.
                <code>&lt;li&gt;&lt;/li&gt;</code>. For ‘self closing’ elements such as
                <code>meta</code>,
                <code>img</code> or
                <code>br</code> there is no need for the closing
                <code>/&gt;</code> in HTML5. For example
                <code>&lt;br&gt;</code> is fine, rather than
                <code>&lt;br /&gt;</code>.</li>

        </ul>
        <p>Use our <a href="html-template.html">HTML template</a> as a starting point for your documents. The language
            is set <code>&lt;html lang="en-gb"&gt;</code>. Adjust to match the main language of your site if different
            to British English.

</html>
</p>

<h2>Semantic mark-up</h2>

<p>Follow the rules for semantic mark-up. Use tags as intended. Only one
    <code>&lt;h1&gt;</code> for the main heading and
    <code>&lt;h2&gt;</code> to
    <code>&lt;h6&gt;</code> for sub-headings or section headings.</p>

<p>Use
    <code>&lt;p&gt;</code> for paragraphs. E.g. don’t place a paragraph in a heading just to enlarge the font.
    Non-semantic coding (any page) will lose marks.</p>

<p>Use elements such as <code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;aside&gt;</code>, <code>&lt;footer&gt;</code>
    to provide a semantic structure to your documents rather than the older practice of <code>&lt;div&gt;</code>. Use
    the <code>&lt;main&gt;</code> element to indicate your primary content area. This can be subdivided (if required)
    using <code>&lt;section&gt;</code> or <code>&lt;article&gt;</code>.</p>

<p>For small sites you may apply styles directly to these semantic elements. However, we recommend (as encouraged by
    our friend <a href="https://twitter.com/csswizardry">@CSSwizardry</a>) that classes are applied for greater
    flexibility and future proofing.
</p>

<h2>Clean mark-up</h2>

<p>Space out / indent your mark-up for easy reading and error detection. If you use CSS pre-processors like Sass or
    LESS or minify CSS talk to the tutors. We need access to the original files to be able to feedback on your working
    practices. Cluttered mark-up
    will lose marks.</p>

<h2>Commented mark-up</h2>

<p>Use comments in your HTML and CSS to indicate sections, functions, features etc. Commented mark-up will gain marks.
    Comments for the sake of comments won’t.</p>

<h2>CSS</h2>

<p>All elements of design should be delivered via CSS. You should not use ‘old’ (or deprecated) elements such as the
    <code>&lt;font&gt;</code> tag. CSS should be delivered by one or more external stylesheets. Internal and inline
    styles should be an exception, explained with a comment.</p>

<p>
    <a href="https://jigsaw.w3.org/css-validator/">CSS should be validated</a> to spot mistakes. A submission that
    fails to use external CSS will lose marks.</p>

<p>Excess, unused CSS will lose marks.</p>

<h2>Page
    <code>&lt;title&gt;</code>
</h2>

<p>The homepage title should reflect and set a context for the whole site. What we do, who we are, where we are?</p>

<p>Titles for sub-pages should continue this theme, but reflect the actual page content/purpose first (function first).
    A submission that has missing or weak titles will lose marks.</p>

<h2>Meta Keywords</h2>

<p>Meta Keywords should make use of any specific (standout) words or phrases relating to the site/business/product.
    Avoid generic words. A submission that has missing or limited keywords will lose marks.</p>

<pre><code class="html">&lt;meta name=&quot;keywords&quot; content=&quot;keywords, about, your, site&quot; /&gt;</code></pre>

<h2>Meta Description</h2>

<p>Meta Description, in particular on the homepage, is a chance to sell your site/business/product when listed on
    Google in 65 characters. Description for sub-pages should reflect content of that individual page (and the overall
    site/business/product) when
    possible. A submission that has a missing or weak description will lose marks.
</p>

<pre><code class="html">&lt;meta name=&quot;description&quot; content=&quot;Add your meta description&quot; /&gt;</code></pre>

<h2>Alt text</h2>

<p>All images (unless fluff or decoration) should have descriptive alt text. Images that have no importance (fluff)
    should have null alt text (
    <code>alt=&quot;&quot;</code>). Images containing text should replicate the text in the alt attribute when
    possible. A submission that fails to include descriptive alt text for all relevant images will lose marks.</p>

<p>Consider what sort of images should be added with an
    <code>&lt;img&gt;</code> tag and which ones should be added using CSS
    <code>background-image</code>.</p>

<h2>Image captions</h2>

<p>Consider the use of captions with images (if your design allows). Use the
    <code>figure</code> and
    <code>figcaption</code> tags. Do not repeat alt text in a caption. Either add to/enhance the alt description in
    your caption, or have a null alt.</p>

<h2>Title attribute for links</h2>

<p>Not always necessary in the real world but for you to hone your writing skills we expect title attributes when
    applicable on links. Enhance, don’t replicate link text. Especially effective on menu links (that have short link
    text). On the flip side, do
    not add the title attribute to random elements. It is pointless. DO NOT confuse the title attribute for the alt
    attribute.</p>

<h2>Link text</h2>

<p>Think about your link text. Don’t use or repeat descriptions such as ‘read more’ or ‘click here’. They tell the user
    nothing, are bad for accessibility. Good link text has SEO benefits. A submission that fails to include descriptive
    link text will lose
    marks.
</p>

<h2>Images as links</h2>

<p>Use the alt text to describe the location of the link. The link element doesn’t need a title attribute. A submission
    that fails to use the alt text this way will lose marks.</p>

<h2>Accessibility</h2>

<p>We are looking for your site to have
    <a href="https://www.w3.org/TR/WCAG21/">conformance to WCAG 2.1</a>.
    <strong>Your web site must be accessible!</strong>
</p>
<p>Students should use <a href="">WebAIM's WCAG 2 Checklist</a> to review their work as part of an accessibilty audit
    before submitting coursework.</p>
<p>A submission that fails to conform to applicable WCAG 2.0 standards will lose marks.</p>

<p>The <a href="http://www.bbc.co.uk/guidelines/futuremedia/accessibility/html/">BBC's HTML Accessibility Standards
        website</a> contains a wealth of information and examples.</p>


<h2>Image optimisation</h2>

<p>All images must be optimised for the web. If relevant, crop to remove un-necessary elements of your pictures. Resize
    the physical dimensions of each image to fit the page design. DO NOT resize images with the height &amp; width
    attributes only. A submission
    that fails to optimise all images will lose marks. You should strive to get image file sizes as small as possible.</p>

<p>Aim for a balance between quality and file size.</p>

<h2>Version control</h2>

<p>We will be encouraging the use of
    <a href="https://education.github.com/pack">version control tools such as github</a> in coursework. This is an
    ‘essential skill’ for the digital industries for a variety of roles, not just techies. Using version control is a
    great way to back up your
    work and you progress through a project.</p>

<p>You can also use for team work for multiple contributions.</p>

<h2>Media</h2>

<p>All text, images, audio and movies should be the student’s own, original work or belong to your client. Use of
    library items must be credited. You can use creative commons materials if allowed under the relevant licence. Use
    of other people’s work may
    lead to charges of plagiarism.</p>

<p>Credit is given for original images &#8211; not for stock or library images.</p>

<h2>Files &amp; Folders</h2>

<ul>
    <li>
        <p>Filenames &#8211; no spaces, dashes or underscores to separate words, no caps, relevant names.
            <code>DSC 10344.jpg</code> should be
            <code>drone-takeoff.jpg</code>.</p>
    </li>
    <li>
        <p>Folders – relevant file/folder structure. Poor file names and/or file/folder structure will lose marks. Even
            if you have only a few images or a single CSS file it is worth creating a folder for them to keep
            everything organised.
        </p>
    </li>
</ul>

<h2>Design</h2>

<p>Page design including layout, positioning, use of space, colour and typography. Good design will gain credit. Design
    is often the element that lifts excellent work (quality coding and content) into the highest marking bands.
</p>

<h2>Usability</h2>

<p>Providing the user with ‘a good experience’ is important. User centred designs with high usability will gain credit.
    Websites with complex or misleading interactions may loose marks.</p>

<h2>Text</h2>

<p>All text must be original unless quoted or provided by a client. Use of other people’s work may lead to charges of
    plagiarism.
</p>

<h2>Grammar</h2>

<p>All text should be spell checked and grammar checked. A submission that includes typing errors and/or bad grammar
    cannot attain a mark of excellent.</p>

<h2>Coding - Originality</h2>

<p>Any snippets of code used from tutorials or libraries should be clearly referenced within your coding.
    Implementation for example of lines and lines of CSS that you only part use will lose you marks. Use other people’s
    code sparingly and efficiently.
    Choose code that isn't obsolete or over engineered for the task you need it to do. Over use of other people’s code,
    even if referenced, may lead us to ask ‘what have you done’ or accusations of plagiarism.</p>

<h2>Forms</h2>

<p>Forms can be processed using services such as
    <a href="http://formspree.io/">formspree.io</a>
</p>

<p>All forms must be accessible and highly usable.</p>

<h2>Frameworks for layout</h2>

<p>Use of pre-created CSS layout solutions (frameworks or templates) is not acceptable unless specified in class or
    agreed with tutors.</p>

<p>You are learning to code. Create your own grids and layouts. There are downsides to many grid solutions including
    bloated code. If your code is bloated (full of unnecessary mark-up and CSS) you will lose marks.</p>

<p>Coursework using predefined solutions may be disqualified.</p>

<h2>CSS pre-processors &amp; compression</h2>

<p>Use of CSS pre-processors &amp; compression in coursework must be agreed with tutors.</p>

<p>You may be required to provide access to the original CSS.</p>

<p>Whilst we encourage learning to use these tools you should aim to develop your CSS skills first.</p>

<h2>JavaScript</h2>

<p>Use of JavaScript is encouraged. Make sure you know what you are using. Do not just cut and paste lumps of code. Be
    careful of using predefined script without knowing how it really functions. Prefer solutions that use 'progressive
    enhancement' - no inline
    javascript. Check your website still works with JavaScript turned off, even if the functionality isn't available.
</p>

<p>Good implementation will gain credit and as you guessed it, poor implementation will lose credit.</p>

<h2>PHP</h2>

<p>As with JavaScript. Use, but within your limits. As above.</p>

<h2>Other technologies</h2>

<p>There are numerous new technologies being developed for the web almost daily. We encourage you to experiment; to try
    out some of the latest tools and techniques in your work. Discuss with tutors. Good implementation will gain
    credit. Poor implementation
    will be a disaster and could cause much pain!</p>

<p>Always be prepared to 're-wind' when things don't work. Version control can help with this.</p>

s