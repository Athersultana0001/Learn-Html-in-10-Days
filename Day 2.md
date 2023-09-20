# Text Formatting with HTML  📝 

![8. HTML Text Formatting using Heading and Paragraph Elements - HTML -  YouTube](https://i.ytimg.com/vi/WBvGOfC3_HA/maxresdefault.jpg)

## **Objectives:** 🎯

By the end of Day 2, you will:

1.  Understand the importance of text formatting in web content.
2.  Be able to create structured content using headings and paragraphs.
3.  Master text formatting tags for emphasizing and styling text.
4.  Learn how to insert line breaks and horizontal rules.
5.  Discover the purpose and use of HTML comments for documentation.

## **Key Topics for Day 2:** 📋

-   📝 **Working with Headings and Paragraphs:**
    
    -   Learn about HTML headings (`<h1>` to `<h6>`) for creating hierarchical text structure.
    -   Understand how to use paragraphs (`<p>`) to organize and display text content.
-   ✨ **Applying Text Formatting Tags:**
    
    -   Explore text formatting tags like `<strong>`, `<em>`, `<u>`, `<s>`, `<mark>`, and `<code>` to emphasize and style text.
    -   Discover how these tags affect the presentation of your content.
-   🌟 **Using Line Breaks and Horizontal Rules:**
    
    -   Learn how to insert line breaks (`<br>`) to create single-line spacing.
    -   Understand the use of horizontal rules (`<hr>`) for visual separation between content sections.
-   💬 **Adding HTML Comments:**
    
    -   Discover the purpose of HTML comments (`<!-- -->`) for adding notes and documentation to your code.
    -   Learn how to use comments effectively to explain your code to others.

Day 2 will equip you with the knowledge and skills to make your web content not only well-structured but also visually appealing and informative. Let's dive into these text formatting techniques! 🔤

# 📝 Working with Headings and Paragraphs

In the world of HTML, headings and paragraphs are your trusty companions when it comes to structuring and presenting text content. Let's dive deeper into these fundamental elements, adding a touch of emojis to make it more engaging! 🚀📄

## HTML Headings (`<h1>` to `<h6>`) 📚

HTML provides us with six levels of headings, akin to chapters and sub-chapters in a book. Each heading level serves a unique purpose:

-   `<h1>`: The grand title, reserved for the most significant section of your content. It's like the main title of a book.

``` html
<h1>Welcome to the Adventure Blog</h1>
```

`<h2>`: Subheadings under `<h1>`, perfect for dividing your content into major sections. Think of them as the chapters of your adventure.
``` html
<h2>Chapter 1: Exploring the Unknown</h2>
<h2>Chapter 2: Unveiling Hidden Treasures</h2>
```
`<h3>`, `<h4>`, `<h5>`, `<h6>`: These tags are used for finer subordination and creating a hierarchical structure within your content, like sections and subsections in your adventure log.
``` html
<h3>Section 1: The Enchanted Forest</h3>
<h4>Subsection 1: Meeting Magical Creatures</h4>
<h5>Sub-subsection 1: The Wise Old Owl</h5>
```
![Paragraphs and Headings | Basic HTML Elements | Peachpit](https://www.peachpit.com/content/images/chap4_9780136702566/elementLinks/4-2-heading-scale-new_a_alt.jpg)

## Using Paragraphs (`<p>`) 📝

Now, let's talk about the humble `<p>` element. It's your tool for creating structured blocks of text on your web page. Imagine it as the parchment where you record your adventures:

![HTML paragraph tag using p tag For Display of Text](https://tutorialdeep.com/wp-content/uploads/2017/04/paragraphtag.png)

``` html
<p>Deep within the enchanted forest, a world of magic awaited our brave adventurers. The rustling leaves and whispering winds spoke of ancient secrets.</p>
```
## **Key Takeaways:** 🔮

-   HTML headings (`<h1>` to `<h6>`) provide a clear hierarchy for your content, much like the chapters of your adventure.
-   Paragraphs (`<p>`) are your way of organizing and displaying blocks of text, making your story come to life on the web page.

With headings and paragraphs in your toolkit, you're ready to embark on your HTML adventure with structured and engaging content. Next, we'll explore the magical world of text formatting! 🌟

## Example: ✨
Let's create a practical example using HTML headings and paragraphs to structure content for an adventure blog:

``` html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Adventure Blog</title>
</head>
<body>
    <h1>Welcome to the Adventure Blog</h1>

    <h2>Chapter 1: Exploring the Enchanted Forest</h2>
    <p>Deep within the enchanted forest, a world of magic awaited our brave adventurers. The rustling leaves and whispering winds spoke of ancient secrets.</p>

    <h3>Section 1: Meeting Magical Creatures</h3>
    <p>As they ventured deeper, they encountered mystical creatures like the talking animals and the friendly forest spirits. Each encounter was more enchanting than the last.</p>

    <h4>Subsection 1: The Wise Old Owl</h4>
    <p>One day, they met the wise old owl, who shared wisdom passed down through generations. With his guidance, they navigated through the densest parts of the forest.</p>

    <h2>Chapter 2: Discovering Hidden Treasures</h2>
    <p>Their journey led them to hidden treasures buried beneath ancient trees. They unearthed long-forgotten artifacts and uncovered the forest's rich history.</p>
</body>
</html>
```
In this example, we've used HTML headings (`<h1>` to `<h4>`) to create a structured adventure blog. Each heading level signifies a different level of importance and hierarchy within the content. Paragraphs (`<p>`) are used to provide detailed descriptions and stories.

When you view this HTML in a web browser, it will display as a well-structured adventure narrative with clear headings and organized paragraphs. This is just one way you can use headings and paragraphs to structure content on a web page.

#  Applying Text Formatting Tags✍️

![Text Formatting Tags in HTML - Scaler Topics](https://www.scaler.com/topics/images/text-formatting-tags-in-html_thumbnail.webp)

In the enchanting realm of HTML, text formatting tags are like the magical spells that transform ordinary words into eye-catching and expressive content. Let's delve into these formatting tags, adding a sprinkle of emojis for that extra charm! 🌟📝💫

## Emphasizing Text with `<strong>` and `<em>` 🚀

The `<strong>` and `<em>` tags are your allies when it comes to adding emphasis to text. They play distinct roles:

-   `<strong>`: This tag is like a bold declaration, making text **stronger** and more important. It's perfect for highlighting key points.
``` html
<p>Exploring the <strong>ancient ruins</strong> was a thrilling adventure.</p>
```
`<em>`: The `<em>` tag provides a touch of emphasis by making text _italic_. It's often used for **emphasizing** words or phrases.
``` html
<p>The forest was filled with whispers of <em>magic</em> and wonder.</p>
```
## Underlining with `<u>` and Strikethrough with `<s>` ⭐

Sometimes, you need to draw attention to specific words or indicate changes. That's where `<u>` and `<s>` come into play:

-   `<u>`: The `<u>` tag underlines text, making it look like it's _underlined_ on the page.

``` html
<p>Our adventurers crossed the <u>mystical river</u> on a rickety bridge.</p>
```
`<s>`: The `<s>` tag creates a strikethrough effect, ideal for showing **deleted** or **obsolete** content.

``` html
<p>The treasure map led them to a hidden cave, but it was <s>empty</s>.</p>
```
##  **Highlighting Text with `<mark>` and Using Monospace Font with `<code>`** 🌐

Sometimes, you want to **highlight** specific parts of your text or showcase code:

-   `<mark>`: The `<mark>` tag highlights text, making it stand out as if you've **marked** it with a highlighter.
``` html
<p>The most important rule of magic: Always be prepared for the unexpected <mark>✨</mark>.</p>
```
`<code>`: The `<code>` tag is like a window into the world of programming. It displays text in a _monospace_ font, perfect for showcasing code snippets.

``` html
<p>To display "Hello, World!" in Python, you can use the <code>print("Hello, World!")</code> statement.</p>
```
## **Key Takeaways:** ✍️

-   `<strong>`, `<em>`, `<u>`, `<s>`, `<mark>`, and `<code>` are HTML tags that add emphasis and style to text.
-   These tags affect the presentation of your content, making it more engaging and expressive.

With these text formatting tags, your web content will come to life with style and emphasis. Next, let's explore line breaks and horizontal rules to add visual separation! 🌈

## Example:  🌐

Let's use practical examples to showcase how HTML text formatting tags work:
``` html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Text Formatting Example</title>
    <style>
        /* Adding some CSS for styling */
        .highlight {
            background-color: yellow;
        }
    </style>
</head>
<body>
    <h1>Text Formatting Example</h1>

    <p>In this example, we'll explore how to use various <strong>text formatting tags</strong> in HTML to make your content <em>visually appealing</em> and <u>expressive</u>.</p>

    <h2>Emphasizing Text</h2>

    <p>You can use the <strong>&lt;strong&gt;</strong> tag to make text <strong>stronger</strong> and more important. For example, <strong>this text is important</strong>.</p>

    <p>The <em>&lt;em&gt;</em> tag is used for <em>emphasizing</em> words or phrases, making them stand out in <strong>italic</strong>. For instance, <em>magic</em> in the forest.</p>

    <h2>Decoration and Highlighting</h2>

    <p>If you want to <u>underline</u> text, use the <u>&lt;u&gt;</u> tag. For example, <u>this text is underlined</u>.</p>

    <p>For <s>strikethrough</s> effects, utilize the <s>&lt;s&gt;</s> tag. It's useful for indicating <s>deleted</s> or <s>obsolete</s> content.</p>

    <p>The <mark>&lt;mark&gt;</mark> tag highlights specific words, as if you've marked them with a highlighter. For instance, <mark>important point</mark>.</p>

    <h2>Showcasing Code</h2>

    <p>When displaying code, use the <code>&lt;code&gt;</code> tag. It shows text in a <code>monospace</code> font, perfect for code snippets like <code>console.log("Hello, World!");</code></p>
</body>
</html>
```

In this example, we've used various text formatting tags such as `<strong>`, `<em>`, `<u>`, `<s>`, `<mark>`, and `<code>` to emphasize and style text differently. 

When you view this HTML in a web browser, you'll see how each tag affects the presentation of the content, making it visually engaging and expressive. 🌐

# Using Line Breaks and Horizontal Rules 🔍

![[HTML-Tutorial-7] | Heading, Paragraph, Line Break, Word Break, Horizontal  Rule | Web Development - YouTube](https://i.ytimg.com/vi/FJhL8SwS1Jw/sddefault.jpg)

In the world of HTML, sometimes you need to control the flow and separation of content. Line breaks and horizontal rules come to the rescue for creating space and visually separating sections. Let's explore these essential elements with a touch of emojis for added flair!  ✨

## Line Breaks (`<br>`) for Single-Line Spacing 🌈

The `<br>` tag is like a line break in your text, creating a small gap and moving content to the next line. It's handy when you want to add a single-line space between elements:

``` html
<p>This is a <br> line break.</p>
```
**Note:** Unlike most HTML elements, the `<br>` tag doesn't have a closing tag.

## Horizontal Rules (`<hr>`) for Visual Separation 🌐

Horizontal rules are your secret weapon for visually separating content sections. They create a horizontal line across the page, much like a ruler:

``` html
<p>Section 1: Introduction</p>
<hr>
<p>Section 2: Main Content</p>
```
You can customize horizontal rules with CSS to adjust their appearance, such as line thickness and color.

``` html
<hr class="custom-rule">
```

``` css
.custom-rule {
    border: 2px solid #007acc; /* Blue line with 2px thickness */
}
```
## **Key Takeaways:** 📝

-   The `<br>` tag is used for single-line spacing within text or content.
-   Horizontal rules created with the `<hr>` tag visually separate sections of content.

With line breaks and horizontal rules in your HTML toolkit, you have the power to control the spacing and organization of your web page. Now, let's discover how to add meaningful comments to your code! 💬

## Example: ✍️

Let's create a practical example using HTML line breaks (`<br>`) and horizontal rules (`<hr>`) to format and separate content:

``` html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Line Breaks and Horizontal Rules Example</title>
    <style>
        /* Adding some CSS for styling the horizontal rule */
        .custom-hr {
            border: 2px dashed #007acc; /* Blue dashed line with 2px thickness */
            margin: 20px 0; /* Add margin for spacing */
        }
    </style>
</head>
<body>
    <h1>Our Menu</h1>

    <h2>Appetizers</h2>
    <p>Start your meal with our delicious selection of appetizers:</p>
    <ul>
        <li>Mozzarella Sticks</li>
        <li>Spinach Dip</li>
        <li>Bruschetta</li>
    </ul>

    <hr> <!-- Horizontal rule for visual separation -->

    <h2>Main Courses</h2>
    <p>Explore our mouthwatering main courses:</p>
    <ul>
        <li>Grilled Salmon</li>
        <li>Chicken Parmesan</li>
        <li>Vegetable Stir-Fry</li>
    </ul>

    <hr class="custom-hr"> <!-- Custom-styled horizontal rule -->

    <h2>Desserts</h2>
    <p>Save room for our heavenly desserts:</p>
    <ul>
        <li>Chocolate Fondue</li>
        <li>Tiramisu</li>
        <li>Key Lime Pie</li>
    </ul>
</body>
</html>
```
In this example, we've used `<br>` tags to create line breaks within paragraphs for better formatting. Additionally, we've employed `<hr>` tags to visually separate the menu sections. The custom-styled horizontal rule (`<hr class="custom-hr">`) adds a unique touch to the separation. 🎨

When you view this HTML in a web browser, you'll see how line breaks and horizontal rules are used to format and visually organize the content on the page, making it more readable and appealing. 📊

# 💬 Adding HTML Comments

![HTML Comments - An In-Depth Tutorial on How To Use Them](https://ei7sbsqceej.exactdn.com/wp-content/uploads/2021/11/Adding-HTML-comments-300x200.jpg?strip=all&lossy=1&ssl=1)

In the vast world of HTML, communication isn't just with your web page visitors; it's also with fellow developers and your future self. HTML comments, represented by `<!-- -->`, are like hidden notes that let you add context, explanations, and documentation to your code. Let's explore the power of comments with a sprinkle of emojis! 📝

## **Purpose of HTML Comments** 🤓

HTML comments serve multiple essential purposes:

1.  **Documentation**: Comments help you document your code, explaining its purpose, structure, or usage. They're your personal notes in the margins of your codebook.
    
2.  **Debugging**: Comments can be valuable when troubleshooting issues or making changes to your code. They provide insights into your thought process.
    
3.  **Collaboration**: When working on projects with others, comments make it easier to understand and collaborate on the codebase.
    

## **How to Use Comments Effectively** ✨

To create an HTML comment, enclose your comment text within `<!--` and `-->`. Anything within these delimiters is considered a comment and won't be displayed in the web page.

``` html
<!-- This is a comment. It won't be visible in the browser. -->
```
**Examples of Effective Comment Usage:**
``` html
<!-- Header Section -->
<header>
    <h1>My Amazing Website</h1>
    <!-- Navigation Menu -->
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
            <!-- Add more menu items here -->
        </ul>
    </nav>
</header>

<!-- Main Content Section -->
<section>
    <h2>Welcome to my website!</h2>
    <p>This is the main content area.</p>
    <!-- TODO: Add more content -->
</section>
```
## **Key Takeaways:** 📝

-   HTML comments (`<!-- -->`) are hidden notes within your code.
-   They serve the purposes of documentation, debugging, and collaboration.
-   Comments are enclosed within `<!--` and `-->` and are not visible in the browser.

With HTML comments, you can leave your mark on your code, ensuring it's well-documented and understandable to others (or even your future self)!  🤝

## Example: ✍️
Let's create a practical example using HTML comments to document and explain sections of a web page:

``` html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>HTML Comments Example</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>My Portfolio</h1>
        <p>Welcome to my portfolio website.</p>
    </header>

    <!-- Navigation Menu -->
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/projects">Projects</a></li>
            <!-- Add more menu items here -->
        </ul>
    </nav>

    <!-- Main Content Section -->
    <section>
        <h2>About Me</h2>
        <p>I am a web developer passionate about creating beautiful and functional websites.</p>
    </section>

    <!-- TODO: Add Projects Section -->

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 My Portfolio</p>
    </footer>
</body>
</html>
```
In this example, we've used HTML comments (`<!-- -->`) to provide explanations and documentation for different sections of the web page. Comments help readers understand the purpose of each section and what needs to be done (e.g., adding a "Projects" section).

When you view this HTML in a web browser, the comments are not visible to visitors but serve as helpful notes for developers working on the code.📝

# Applications: 💼
1.  📝 **Working with Headings and Paragraphs:**
    
    -   **Application:** Create a personal blog with captivating headings and structured paragraphs to share your adventures or thoughts.
2.  ✨ **Applying Text Formatting Tags:**
    
    -   **Application:** Enhance a restaurant's menu webpage with formatted text to make dishes and descriptions stand out.
3.  🌟 **Using Line Breaks and Horizontal Rules:**
    
    -   **Application:** Design a contact page for a business website with clear separation between contact details and a contact form using horizontal rules.
4.  💬 **Adding HTML Comments:**
    
    -   **Application:** Collaborate on a team project by adding comments to HTML code to explain functions, responsibilities, or future improvements.

These applications bring HTML to life by structuring content, making it visually appealing, and facilitating collaboration among developers. Keep practicing, and you'll be an HTML wizard in no time! 🧙‍♂️

# Summary: 🚀


-   📝 You explored the use of headings and paragraphs in HTML to create structured and organized content.
    
-   🌟 HTML provides six levels of headings  for creating a hierarchical text structure.
-  📄 Paragraphs are represented by the  (`<p>`) tag and are used to group and display blocks of text.
    
-   ✨ You learned to apply text formatting tags like `(<strong>) , (<em>), (<u>), (<s>), (<mark>), and (<code>)` to emphasize and style text.
    
-   🖌️ Text formatting tags help make your content visually appealing and expressive.
    
-   🌈 You discovered how to insert line breaks using the <br> tag to create single-line spacing within text.
    
-   🎨 You can customize the appearance of horizontal rules using CSS.
- 💬 Finally, you explored the purpose of HTML comments and learned how to use them for documentation and code explanation.
    
With this knowledge, you're well on your way to becoming an HTML pro! 🧙‍♂️

# Knowledge test on Text Formatting with HTML  📝

**Which HTML tag is used to create the highest-level heading?** 🌐

-   a) `<header>` 
-   b) `<h1>` 
-   c) `<heading>` 
-   d) `<h6>` 
 
  ✅ Correct Answer: b)

**2. What is the purpose of the `<em>` tag in HTML?** ✨

-   a) It creates a hyperlink. 
-   b) It italicizes text to add emphasis. 
-   c) It defines a paragraph. 
-   d) It makes text bold. 

 ✅ Correct Answer: b)

**3. Which tag is used to create a line break in HTML?** 🌈

-   a) `<br>` 
-   b) `<lb>` 
-   c) `<line-break>` 
-   d) `<break-line>` 

  ✅ Correct Answer: a)

**4. What does the `<strong>` tag do in HTML?** 🖌️

-   a) It makes text italic. 
-   b) It creates a hyperlink. 
-   c) It makes text bold. 
-   d) It defines a paragraph. 

✅ Correct Answer: c)

**5. What does the `<u>` tag in HTML stand for?** 🔗

-   a) Unordered list 
-   b) Underline 
-   c) URL 
-   d) Unbold 

 ✅ Correct Answer: b)

**6. Which HTML tag is used to create a marked or highlighted text?** 🎯

-   a) `<highlight>` 
-   b) `<mark>` 
-   c) `<bold>` 
-   d) `<emphasize>` 

 ✅ Correct Answer: b)

**7. How can you create a second-level heading in HTML?** 📄

-   a) `<h1>` 
-   b) `<h2>` 
-   c) `<h3>` 
-   d) `<h4>` 

✅ Correct Answer: b)

**8. Which tag is used to insert a horizontal rule for visual separation in HTML?** 🚀

-   a) `<line>` 
-   b) `<separator>` 
-   c) `<rule>` 
-   d) `<hr>` 

 ✅ Correct Answer: d)

**9. What's the purpose of using HTML comments (<!-- -->) in your code?** 💬

-   a) To create clickable links 
-   b) To make text bold 
-   c) To add documentation and explanations to your code 
-   d) To insert images 

 ✅ Correct Answer: c)

**10. Which HTML tag is used to define a paragraph?** 📝

-   a) `<para>` 
-   b) `<p>` 
-   c) `<paragraph>` 
-   d) `<text>` 

  ✅ Correct Answer: b)

**11. To emphasize text in HTML, which tag should you use?** ✨

-   a) `<italic>` 
-   b) `<emphasis>` 
-   c) `<em>` 
-   d) `<bold>` 

   ✅ Correct Answer: c)

**12. How many levels of headings are available in HTML?**

-   a) 4
-   b) 5
-   c) 6
-   d) 7

   ✅ Correct Answer: c)

**13. What does the `<s>` tag in HTML represent?** 🚫

-   a) Strong text
-   b) Superscript text
-   c) Strikethrough text 
-   d) Subscript text

  ✅ Correct Answer: c)

**14. In HTML, what tag is used to create an ordered list?** 📋

-   a) `<ul>` 
-   b) `<li>` 
-   c) `<ol>` 
-   d) `<dl>` 

   ✅ Correct Answer: c)

**15. Which HTML tag is used to create a hyperlink?** 🔗

-   a) `<a>` 
-   b) `<link>` 
-   c) `<hlink>` 
-   d) `<hyper>` 

   ✅ Correct Answer: a)

**16. How do you add a comment in HTML?** 💬

-   a) `// This is a comment`
-   b) `/* This is a comment */`
-   c) `<!-- This is a comment -->` 
-   d) `# This is a comment`

   ✅ Correct Answer: c)

**17. What is the purpose of the `<code>` tag in HTML?** 💻

-   a) It defines a code block.
-   b) It makes text bold.
-   c) It italicizes text.
-   d) It displays text as code. 

  ✅ Correct Answer: d)

**18. Which tag creates a custom-styled horizontal rule in HTML?** 🌈

-   a) `<custom-line>` 
-   b) `<rule>` 
-   c) `<hr class="custom-hr">` 
-   d) `<separator>` 

   ✅ Correct Answer: c)

**19. In HTML, how do you create a third-level heading?** 🏗️

-   a) `<h2>` 
-   b) `<h3>` 
-   c) `<h1>` 
-   d) `<h4>` 

  ✅ Correct Answer: b)

**20. What is the purpose of HTML's `<mark>` tag?** 🖼️

-   a) To add a background color to text 
-   b) To create clickable links 
-   c) To highlight or mark text 
-   d) To insert images 

   ✅ Correct Answer: c)

**21. Which HTML tag is used for emphasized text in a way that it changes its tone?** 🖌️

-   a) `<strong>` 
-   b) `<em>` 
-   c) `<italic>` 
-   d) `<code>` 

  ✅ Correct Answer: b)

**22. How can you create a fourth-level heading in HTML?** 🏗️

-   a) `<h2>` 
-   b) `<h4>` 
-   c) `<h5>` 
-   d) `<h6>` 

   ✅ Correct Answer: b)

**23. What is the purpose of the `<u>` tag in HTML?**

-   a) It defines a URL.
-   b) It underlines text to indicate a hyperlink.
-   c) It makes text bold.
-   d) It creates a horizontal rule.

   ✅ Correct Answer: b)

**24. To create a hyperlink in HTML, what tag should you use?** 🔗

-   a) `<link>` 
-   b) `<a>` 
-   c) `<url>` 
-   d) `<hyperlink>` 

  ✅ Correct Answer: b)

**25. How do you customize the appearance of horizontal rules in HTML using CSS?**

-   a) You can't customize horizontal rules.
-   b) By changing the width property.
-   c) By adding a custom class to the `<rule>` tag.
-   d) By using the `<hr style="...">` tag with inline styles.

 ✅ Correct Answer: c)


Congratulations on completing Day 2 of our "Learn HTML in 10 Days" course! 🎉

Today, you delved into the world of HTML text formatting, headings, paragraphs, line breaks, horizontal rules, and the invaluable use of HTML comments. You've acquired essential skills to structure and style your web content, making it both visually appealing and well-documented.

As you continue your HTML journey, remember that practice is key. Keep experimenting with what you've learned today, and don't hesitate to explore the vast possibilities that HTML offers.

Tomorrow, on Day 3, we'll venture into the exciting realm of working with hyperlinks and creating lists and tables. Get ready to take your HTML skills to the next level! 🚀



