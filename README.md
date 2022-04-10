<img src="https://www.insidedms.com/img/logo.svg" alt="Digital Mind Solution Logo">

# Create Proper Markup in HTML Documents


## The images below shows how to do markup in a correct way


>correct is on the left side, incorrect on the right side


<img src="https://raw.githubusercontent.com/squteronsquter/create-html-as-meaningful-markup-documents-and-not-just-visual-representation-page/main/assets/img/html-markup-done-right.jpg">

```
<!-- Important Notice! if you omit <DOCTYPE> the browser or robots crawling the internet may try to read it as a legacy format and misinterpret your document
https://html.spec.whatwg.org/#the-html-element -->
<!DOCTYPE html>

<!-- The root of your html (markup language) which contains all other element
https://html.spec.whatwg.org/#the-html-element -->
<html lang="en">

<!-- <head> element is very important as it contains metadata (data about other data) of your page:
https://html.spec.whatwg.org/#the-head-element -->

<head>
    <meta charset="UTF-8">
    <!-- title is important for many reasons. One of them being search engines index the other eg. the text that will appear in the favorite websites when someone bookmarks your page
    https://html.spec.whatwg.org/#the-title-element -->
    <title>Gray Monk's blog on SEO - Search Engine Optimization aka how to get your blog posts to the top of search
        results.</title>
</head>
<!-- <body> is the container of your documents content. It is also a sectioning root.
    https://html.spec.whatwg.org/#the-body-element -->

<body>

<!-- <main> element represents the dominant content of the document 
There may bo no more than one main element on a page. main element cannot be part of any element, it must be the the child of either <body> element or <div> which is the child of a body element. https://html.spec.whatwg.org/#the-main-element
-->
<main>
    <!-- headings
    https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements 
https://html.spec.whatwg.org/#heading-content -->
    <h1>How to get your blog posts at the top of search results</h1>
    <!-- A <section> element represents a generic section of a document, it usually is a thematic group with its own heading
            https://html.spec.whatwg.org/#the-section-element -->
    <section>
        <!-- heading might be implicit or explicit. When before a section it implies that it is the heading related to the section below. When iside a section it explicitly says that it is the heading of that section -->
        <h2>Gray Monk</h2>
        <!-- The p element represents a paragraph. While paragraphs are usually represented in visual media by blocks of text that are physically separated from adjacent blocks through blank lines, a style sheet or user agent would be equally justified in presenting paragraph breaks in a different manner, for instance using inline pillcrows (¶). 
        https://html.spec.whatwg.org/#the-p-element -->
        <p>
            Coder, Web Developer, UX Designer, blogger, instructor.
        </p>
        <!-- definition lists are value data pair associations for robots/computers to understand what it is - just a semicolon between data and value is not enough https://html.spec.whatwg.org/#the-dl-element -->
        <dl>
            <dt>Website</dt>
            <dd>insidedms.com</dd>
            <dt>Phone</dt>
            <dd>+48500100100</dd>
            <dt>Twitter</dt>
            <dd>@_graymonk_</dd>
        </dl>
    </section>
    <!-- <article> is a self contained complete, composition in a document, which can by itself be a separate document eg. a blog post 
    https://html.spec.whatwg.org/#the-article-element -->
    <article>
        <!-- header is an element intended to contain sections heading (h1-h6 elements)
        https://html.spec.whatwg.org/#the-header-element -->
        <header>
            About Me
        </header>
        <p>
            Hi! I am Gray Monk and I am happy to have you as a reader of my blog on SEO. Read the blog calmly when you
            can
            focus on reading, without any distractions. Try to implement the rules I am writing about in your own future
            projects.
        </p>
        <!-- <aside> is an element which could be considered related but separate from the content surrounding it, eg. sidebar could be placed in aside element.Do not think about visual representation of that aside element, think about it as marking up content eg. for future functionality when agents will be able to read it in a different voice or print it as a footnote or even something else.
                https://html.spec.whatwg.org/#the-aside-element -->
        <aside>
            <p>
                Human face of the digital world.
                Digital marketing deserves an utterly human touch to be able to breathe new ideas into people.
            </p>
        </aside>
        <!-- The <footer> element represents a footer for its nearest ancestor sectioning content or sectioning root element. A footer
        typically contains information about its section such as who wrote it, links to related documents, copyright data, and
        the like. https://html.spec.whatwg.org/#the-footer-element -->
        <footer>
            Contact me
        </footer>
    </article>
    <!-- another self container section just as an items in the Table of Contents Index -->
    <section>
        <h2>Services</h2>
        <!-- list elements
        https://html.spec.whatwg.org/#the-ul-element
        https://html.spec.whatwg.org/#the-ol-element
        https://html.spec.whatwg.org/#the-li-element-->
        <ul>
            <li>Web Development</li>
            <li>App Development</li>
            <li>Marketing Consulting</li>
            <li>SEO Analyses and Audits</li>
            <li>UX/UI Design</li>
            <li>Content Writing and Curation</li>
            <li>Email Marketing</li>
            <li>Social Media Planning and Strategy</li>
            <li>Brand Creation and Re-Branding</li>
        </ul>
    </section>
    <!-- and another of in the Table of Contents List -->
    <section>
        <h2>Skills</h2>
        <ul>
            <li>
                <h3>HTML</h3>
                <p>Markup content with semantic HTML
                </p>
            </li>
            <li>
                <h3>CSS</h3>
                <p>Layout and visual content representation on various devices
                    JavaScript
                    Making content more reactive</p>
            </li>
            <li>
                <h3>PHP</h3>
                <p>Making websites work with backends eg. databases
                </p>
            </li>
            <li>
                <h3>Golang</h3>
                <p>Creating fast apps with extended functionality using compiled language which can be run on any
                    operating
                    system
                    or device or agent.
                </p>
            </li>
        </ul>
    </section>
    <!-- another block of sections to complete the Table of Contents -->
    <section>
        <h2>Work history</h2>

        <h3>Graphic Designer</h3>
        <p>Worked with top Polish and International Brands form the publishing and travel industries.</p>

        <h3>Web Developer</h3>
        <p>Warsaw based interactive agency with leading Polish brands from telecommunication, furniture as well as
            international cosmetics and hotel brands
        </p>

        <h3>Own Interactive Agency</h3>
        <p>Supporting clients ranging from an International Industrial Automation Systems producer from Germany
            through a Polish business consulting entity working for to WSE (Warsaw Stock Exchange) listed companies,
            Italian
            Lifestyle magazine, Polish Health & Beauty magazine, Regional HoReCa and Bakery shops
            wholesale company, Medical Clinic in Dublin (Republic of Ireland) and a couple of others.
        </p>
    </section>
    <section>
        <h2>Portfolio</h2>

               <table>
            <caption>My Active Projects List (Selection)
            </caption>
            <thead>
                <tr>
                    <th>Project Name
                    <th>Services Provided
                    <th>Technology Used
                    <th>Scope of Support
            <tbody>
                <tr>
                    <th>art fo BEAUTY - online magazine
                    <th>built website
                    <th>PHP CSS JavaScript
                    <th>VPS administration, supporting editors, functionality enhancements
                <tr>
                    <th>Sklep art fo BEAUTY - e-Commerce website
                    <th>built website
                    <th>PHP CSS JavaScript
                    <th>VPS administration, supporting editors, functionality enhancements
                <tr>
                    <th> Kongresy art fo BEAUTY - Events website
                    <th>built website
                    <th>PHP CSS JavaScript
                    <th>VPS administration, supporting editors, functionality enhancements
                <tr>
                    <th> Witalne Inspiracje - Lifestyle website
                    <th>built website
                    <th>PHP CSS JavaScript
                    <th>VPS administration, supporting editors, functionality enhancements
                <tr>
                    <th>Estetica Polska - online magazine
                    <th>built website
                    <th>PHP CSS JavaScript
                    <th>VPS administration, supporting editors, functionality enhancements
                <tr>
                    <th>Fundacja Rozwoju Regionów - Charity Foundation website
                    <th>re-built website and moved to VPS
                    <th>Hugo, GoLang, CSS, Javascript
                    <th>I work for free as developer, VPS administrator, supporting editors, functionality enhancements


                <tr>
                    <th>A.J. Motyl - corporate website
                    <th>built website
                    <th>PHP CSS JavaScript
                    <th>VPS administration, supporting editors, functionality enhancements
                <tr>
                    <th>Oferta A.J. Motyl - e-Commerce website
                    <th>built website
                    <th>Python, React JS, CSS, Javascript
                    <th>VPS administration, supporting editors, functionality enhancements


                <tr>
                    <th>Materiality - corporate website in PL & ENG
                    <th>built website
                    <th>PHP CSS Javascript
                    <th>Hosting administration, supporting editors, functionality enhancements

                <tr>
                    <th>FSR (Fundacja Standardów Raportowania) - corporte website
                    <th>built website
                    <th>PHP CSS Javascript
                    <th>Hosting administration, supporting editors, functionality enhancements
                <tr>
                    <th>Mailing Server System for 3 major clients - mass mailing on own mailing servers
                    <th>built mailing system based on PHPlist
                    <th>PHP CSS Javascript
                    <th>Hosting administration, sending campaigns on daily basis
        </table>
    </section>
    <section>
        <h2>Testimonials</h2>
        <!-- <blockquote> element. The blockquote element represents a section that is quoted from another source.
                    https://html.spec.whatwg.org/#the-blockquote-element -->
        <blockquote>
            <p>We have been working together over the last six years launching many successful projects.</p>
        </blockquote>
        <blockquote>
            <p>Gray Monk has helped us with revitalizing our websites and keeping our online presence in very good shape
                over many years now.</p>
        </blockquote>
        <blockquote>
            <p>
                Gray Monk is an experienced consultant who helped us numerous times to streamline our brand
                communication
                strategies.
            </p>
        </blockquote>
        <blockquote>
            <p>We work with Gray Monk on daily basing to make our e-commerce business reach its targets.</p>
        </blockquote>
    </section>
    <section>
        <!-- <address> element: The address element represents the contact information for its nearest article or body element ancestor. If that is the body element, then the contact information applies to the document as a whole.
        https://html.spec.whatwg.org/#the-address-element -->
        <h2>Mailing Address</h2>
        <address>
            <p>
                Digital Mind Solutions LTD
                Office 265b, 182-184 High Street North,
                London E6 2JA,
                United Kingdom
            </p>
        </address>

    </section>
    <footer>
        <!-- <address> element: The address element represents the contact information for its nearest article or body element ancestor. If that is the body element, then the contact information applies to the document as a whole.
        https://html.spec.whatwg.org/#the-address-element -->
        <address>
            <p>
                To introduce yourself or require more details
                <a href="mailto:hello@insidedms.com">say "Hello"</a>.
            </p>
        </address>
        <p><small>© copyright 2022 Digital Mind Solutions</small></p>
    </footer>

    <!-- Tabular data: The <table> element represents data with more than one dimension, in the form of a table.

The table element takes part in the table model. Tables have rows, columns, and cells given by their descendants. The rows and columns form a grid; a table's cells must completely cover that grid without overlap.
https://html.spec.whatwg.org/#the-table-element -->

</main>
</body>

</html>

```
