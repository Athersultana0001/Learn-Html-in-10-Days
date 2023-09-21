#  Working with Links 🔗

## **Objectives:** 💻

-   Understand the importance of hyperlinks in web development.
-   Learn how to create various types of links, including links to web pages, email addresses, and files.
-   Explore best practices for creating accessible and user-friendly links.

## **Key Topics:** 🔗

1.  🔗 **Creating Hyperlinks:**
    
    -   Introduction to the `<a>` (anchor) tag.
    -   How to create clickable text and images.
    -   Specifying the destination URL with the `href` attribute.
2.  🔗 **Linking to Other Web Pages:**
    
    -   Creating links to external websites.
    -   Navigating within the same website using relative URLs.
    -   Using the `target` attribute to control how links open (e.g., in a new tab).
3.  ✉️ **Linking to Email Addresses:**
    
    -   Creating mailto links for email correspondence.
    -   Specifying the recipient's email address in the `href` attribute.
    -   Adding subject lines and body content to email links.
4.  📂 **Linking to Various Types of Files and Documents:**
    
    -   Linking to PDFs, documents, spreadsheets, and other file types.
    -   Ensuring file accessibility and user-friendliness.
    -   Downloadable links vs. in-browser viewing.

By the end of Day 3, you'll have a solid grasp of how to create various types of links in HTML, which is fundamental for building interactive and interconnected web content. 🚀

# 🔗 Creating Hyperlinks

![Hyperlink là gì? Tại sao hyperlink lại quan trọng với SEO?](https://news.bnn.vn/wp-content/uploads/2020/11/hyperlink-la-gi-5.jpg)

Hyperlinks, often referred to as links, are what make the web an interconnected network of resources. They allow users to seamlessly navigate between web pages, access external content, and interact with online resources. In HTML, hyperlinks are created using the `<a>` (anchor) tag.

## Introduction to the `<a>` (Anchor) Tag

The `<a>` tag is the foundation of creating hyperlinks in HTML. Here's how it works:

``` markdown
<a href="URL">Link Text</a>
```

-   `<a>`: This is the opening tag of the anchor element.
-   `href`: The `href` attribute specifies the destination URL (Uniform Resource Locator) to which the link should point.
-   `"URL"`: Replace this with the actual URL you want to link to.
-   `Link Text`: This is the text that will be displayed as the clickable link.

## How to Create Clickable Text and Images 🖱️

You can create hyperlinks using both text and images. Here's how:

**Clickable Text:**
``` markdown
Click <a href="https://example.com">here</a> to visit our website.
```
In this example, the text "here" becomes a clickable link that directs users to "[https://example.com](https://example.com/)" when clicked.

**Clickable Images:**
``` markdown
<a href="https://example.com">
  <img src="image.jpg" alt="Description">
</a>
```
In this example, the entire image becomes a clickable link. When users click the image, they are taken to "[https://example.com](https://example.com/)."

## Specifying the Destination URL with the `href` Attribute 📄

The `href` attribute is the heart of every hyperlink. It defines where the link will take the user. Here are some common use cases:

**Linking to an External Website:**
``` markdown
<a href="https://www.example.com">Visit Example.com</a>
```
In this case, clicking the link takes users to the external website "[https://www.example.com](https://www.example.com/)."

**Linking to Another Page on Your Website:**
``` markdown
<a href="about.html">Learn About Us</a>
```
Here, the link directs users to the "about.html" page within your website.

**Linking to Email Addresses (Mailto Links):**
``` markdown
<a href="mailto:info@example.com">Contact Us</a>
```
This creates a "mailto" link that, when clicked, opens the user's default email client with the "[info@example.com](mailto:info@example.com)" address pre-filled.

**Linking to Various Types of Files and Documents:**
``` markdown
<a href="document.pdf">Download PDF</a>
```
By mastering the `<a>` tag and understanding how to utilize the `href` attribute, you can create diverse and engaging hyperlinks in your web pages, connecting users to valuable resources and information across the internet. 🌐

## Example: 🚀

Here's the practical example of creating a hyperlink in HTML: 🔗
``` markdown
Click 🌐 <a href="https://www.example.com">here</a> to visit our website.
```
In this example:

-   🌐 `Click` is the text that users will see as the hyperlink.
-   `<a>` is the anchor tag used to create the hyperlink.
-   `href` is the attribute that specifies the destination URL, which in this case is "[https://www.example.com](https://www.example.com/)."
-   `here` is the clickable text. When users click "here," they will be taken to the "[https://www.example.com](https://www.example.com/)" website.

This code creates a simple text hyperlink that, when clicked, directs users to the specified website. 😊


# 🔗 Linking to Other Web Pages 

![How to link one page to another page in HTML | How to link 2 HTML files  together - YouTube](https://i.ytimg.com/vi/GmzUr4Tdeb0/mqdefault.jpg)

Hyperlinking to external web pages and managing navigation within your own website is crucial for creating a cohesive online experience. In HTML, you can achieve this through various techniques:

## Creating Links to External Websites 🚀

To link to an external website, you simply provide the full URL within the `href` attribute:
``` markdown
<a href="https://www.example.com">Visit Example.com</a>
```

-   This link directs users to the "[https://www.example.com](https://www.example.com/)" website when clicked.

## Navigating Within the Same Website Using Relative URLs 🌐

Relative URLs are used to link to pages within the same website. They are relative to the current location of the HTML file. For example:
``` markdown
<a href="about.html">Learn About Us</a>
``` 
-   This link navigates to the "about.html" page, assuming it's within the same website's directory structure.

## Using the `target` Attribute to Control How Links Open 🔗

The `target` attribute allows you to specify how linked content is displayed. Common values include:

-   `_blank`: Opens the link in a new browser tab or window.
-   `_self`: Opens the link in the same tab or window (default behavior).
-   `_parent`: Opens the link in the parent frame or window (if applicable).
-   `_top`: Opens the link in the full body of the current window (breaks out of frames).

Example:
``` markdown
<a href="https://www.example.com" target="_blank">Visit Example.com in a New Tab</a>
```
-   This link opens "[https://www.example.com](https://www.example.com/)" in a new browser tab.

By understanding how to link to external websites, navigate within your own website, and control link behavior with the `target` attribute, you gain the ability to create a seamless and user-friendly browsing experience for your website's visitors. 🌐

## Example: 📚
Here's a practical example of linking to another web page within the same website using a relative URL: 📄
``` markdown
Explore our 📚 <a href="about.html">About Us</a> page to learn more about our mission and values.
```
In this example:

-   📚 `Explore` is the text that users will see as the hyperlink.
-   `<a>` is the anchor tag used to create the hyperlink.
-   `href` is the attribute that specifies the destination URL, which is "about.html" in this case. This is a relative URL, assuming the "about.html" page is within the same website's directory structure.
-   `About Us` is the clickable text. When users click "About Us," they will be taken to the "about.html" page on the same website.

This code creates a link that navigates users to the "About Us" page within your website. 🌐

# 📧 Linking to Email Addresses

![Mailto links in emails and how to use them in email signatures](https://www.mail-signatures.com/wp-content/uploads/2020/09/Complete-guide-to-mailto-link_Blog-image.png)

Linking to email addresses in HTML allows you to create clickable email links that users can click to send an email. This is often done using the `mailto:` scheme.

## Creating Mailto Links for Email Correspondence 📩.

To create a mailto link, you use the `<a>` (anchor) tag, just like with regular hyperlinks, but with the `href` attribute set to the email address preceded by `mailto:`.

``` markdown
<a href="mailto:contact@example.com">Send an Email</a>
```

-   📧 `Send an Email` is the text users will see as the link.
-   `<a>` is the anchor tag.
-   `href` specifies the destination URL using the `mailto:` scheme, followed by the email address.

## Specifying the Recipient's Email Address in the `href` Attribute 📩.

You can also specify the recipient's email address directly in the `mailto:` link:
``` markdown
<a href="mailto:contact@example.com">Contact Our Team</a>
```
-   This link will open the user's default email client with "[contact@example.com](mailto:contact@example.com)" as the recipient.

## Adding Subject Lines and Body Content to Email Links 📧

You can pre-fill subject lines and even the email body by adding them to the `mailto:` link:
``` markdown
<a href="mailto:contact@example.com?subject=Hello%20There&body=I%20have%20a%20question">Email Us</a>
```
-   📬 `Email Us` is the link text.
-   `subject=Hello%20There` sets the subject line to "Hello There." Note that spaces are encoded as `%20."
-   `body=I%20have%20a%20question` pre-fills the email body with "I have a question."

This code creates a clickable email link that, when clicked, opens the user's default email client with the specified email address, subject line, and body content. It's a convenient way for users to contact you via email. 🚀

## Example: ✍️

Let's create a practical example of creating a mailto link for email correspondence: 📩
``` markdown
Have questions? 📬 <a href="mailto:contact@example.com?subject=Questions%20About%20Our%20Services&body=Hello%20Team,%0A%0AI%20have%20some%20questions%20regarding%20your%20services.%20Can%20you%20provide%20more%20information%3F">Email Us</a>
```
**In this example:**

-   📬 `Email Us` is the link text users will see.

-   `<a>` is the anchor tag used to create the hyperlink.

-   `href` specifies the destination URL using the `mailto:` scheme, followed by the email address "[contact@example.com](mailto:contact@example.com)."

-   `subject=Questions%20About%20Our%20Services` sets the subject line to "Questions About Our Services," with spaces encoded as `%20`.
- `body=Hello%20Team,%0A%0AI%20have%20some%20questions%20regarding%20your%20services.%20Can%20you%20provide%20more%20information%3F` pre-fills the email body with a greeting and questions. Line breaks are represented by `%0A`.

When users click "**Email Us**," it opens their default email client with the specified email address, subject line, and pre-filled body content, making it easy for them to reach out with inquiries. 📧🚀


# 📂 Linking to Various Types of Files and Documents

![How do I link files from different folders in HTML? - Stack Overflow](https://i.stack.imgur.com/RP9Ds.png)

In HTML, you can create links to various types of files and documents, providing your website visitors with access to downloadable resources. Here's how you can do it:

## Linking to PDFs, Documents, Spreadsheets, and More 📂

To link to files and documents, you use the same `<a>` (anchor) tag as with regular hyperlinks. However, instead of specifying a web page URL, you specify the path to the file on your server:

``` markdown
<a href="documents/document.pdf">Download PDF</a>
```
-   📂 `Download PDF` is the text users will see as the hyperlink.
-   `<a>` is the anchor tag.
-   `href` specifies the path to the file, which is located in a "documents" folder on your server.

This code creates a link that allows users to download the "document.pdf" file.

## Ensuring File Accessibility and User-Friendliness 📄

When linking to files, it's essential to consider accessibility and user-friendliness:

-   Provide clear and descriptive link text to inform users about the file they are about to download.
-   Ensure the linked file format is widely supported to accommodate different users and devices.
-   Consider adding file size information if files are large.
-   Use appropriate icons or labels to indicate the file type (e.g., PDF, DOC, XLS) next to the link.

## Downloadable Links vs. In-Browser Viewing 🔗

Depending on the user's browser and file type, linked files may open in the browser or trigger a download. For example:

-   PDFs often open in the browser if the user has a PDF viewer plugin.
-   Documents like DOC or XLS files may trigger downloads.

To force a download, you can use the `download` attribute:
``` markdown
<a href="documents/document.pdf" download>Download PDF</a>
```
This ensures that the linked file is always downloaded rather than displayed in the browser.

By understanding how to link to various file types, ensuring accessibility, and providing a user-friendly experience, you can make valuable resources and documents readily available to your website's visitors. 🚀

## Example: ✍️

Here's a practical example of linking to a PDF document for download: 🚀
``` markdown
Explore our annual report for 2023! 📈 <a href="documents/annual_report_2023.pdf" download>Download PDF</a>
```
In this example:

-   📈 `Download PDF` is the text users will see as the hyperlink, indicating that they can download the annual report.
-   `<a>` is the anchor tag used to create the hyperlink.
-   `href` specifies the path to the PDF file, which is located in a "documents" folder on your server.
-   `download` is the attribute that ensures the linked PDF is downloaded rather than displayed in the browser.

When users click "**Download PDF**," it triggers the download of the "annual_report_2023.pdf" file, allowing them to access and save the document to their device. 📂

# Applications: 💼


### 🔗 Working with Links

1.  **Creating Hyperlinks 🌐**
    
    -   **Scenario**: Building a personal blog website and linking to a favorite tech news website.
    -   **Application**: Use the `<a>` tag with the `href` attribute to create a hyperlink to the tech news website. Users can click on it to visit the site.
2.  **Linking to Other Web Pages 🏠**
    
    -   **Scenario**: Creating a navigation menu with links to different sections of your website.
    -   **Application**: Use relative URLs to link to other pages within your website. Customize the navigation by specifying the `href` attribute accordingly.
3.  **Linking to Email Addresses (Mailto Links) ✉️**
    
    -   **Scenario**: Building a contact page for a business website, allowing users to send inquiries via email.
    -   **Application**: Create "mailto" links using the `<a>` tag with the `href` attribute set to "mailto:" followed by the business email address. Users can click to compose emails directly.
4.  **Linking to Various Types of Files and Documents 📂**
    
    -   **Scenario**: Offering downloadable resources like PDFs, lecture notes, and spreadsheets on an educational website.
    -   **Application**: Use the `<a>` tag to create links to these files, allowing students to download the resources. Ensure clear labeling and file format indicators for user convenience.

### Ensuring Accessibility and User-Friendliness

5.  **Accessibility Considerations ♿**
    
    -   **Scenario**: Designing a website for a nonprofit organization with a focus on accessibility.
    -   **Application**: Ensure that your hyperlinks have descriptive text, use meaningful link text, and consider using aria-labels and role attributes to improve accessibility for users with disabilities.
6.  **File Size Information 📏**
    
    -   **Scenario**: Providing downloadable design files on a portfolio website and informing users about file sizes.
    -   **Application**: Add file size information next to the download links to help users anticipate the download duration based on their internet connection.
7.  **Icons for File Types 📁**
    
    -   **Scenario**: Creating a library website with links to downloadable eBooks in different formats.
    -   **Application**: Use file type icons (e.g., PDF, EPUB) next to the links to clearly indicate the file format, making it easier for users to choose the right format.

### Downloadable Links vs. In-Browser Viewing

8.  **Forcing Downloads 📥**
    -   **Scenario**: Hosting important legal documents on a website that should always be downloaded and not viewed in the browser.
    -   **Application**: Use the `download` attribute in your `<a>` tags to ensure that linked files (e.g., PDFs, Word documents) are always downloaded, regardless of the user's browser settings.

These applications demonstrate how to use HTML to create a seamless and user-friendly browsing experience, with added emojis for an engaging touch. 🌐

# Summary: 🚀
1.  🌐 **Creating Hyperlinks**
    
    -   Introduced the `<a>` (anchor) tag for creating hyperlinks.
    -   Explored how to create clickable text and images.
    -   Specified the destination URL using the `href` attribute.
2.  🏠 **Linking to Other Web Pages**
    
    -   Learned to link to external websites.
    -   Navigated within the same website using relative URLs.
    -   Explored the `target` attribute for controlling link behavior.
3.  ✉️ **Linking to Email Addresses (Mailto Links)**
    
    -   Created mailto links for email correspondence.
    -   Specified the recipient's email address in the `href` attribute.
    -   Added subject lines and body content to email links.
4.  📂 **Linking to Various Types of Files and Documents**
    
    -   Linked to PDFs, documents, spreadsheets, and more.
    -   Emphasized file accessibility and user-friendliness.
    -   Discussed downloadable links vs. in-browser viewing.
5.  ♿ **Accessibility Considerations**
    
    -   Focused on creating accessible hyperlinks with descriptive text.
    -   Ensured meaningful link text for improved user experience.
    -   Considered accessibility attributes for users with disabilities.
6.  📏 **File Size Information**
    
    -   Provided users with file size information for large downloads.
    -   Enhanced user transparency regarding download durations.
7.  📁 **Icons for File Types**
    
    -   Used file type icons to visually indicate file formats.
    -   Improved user comprehension and selection of the right format.
8.  📥 **Forcing Downloads**
    
    -   Explored how to force downloads using the `download` attribute.
    -   Ensured certain files are downloaded rather than viewed in the browser.

Day 3 equipped you with the skills to create effective hyperlinks, link to various types of content, consider accessibility, and enhance user-friendliness. These techniques are fundamental for building engaging and accessible websites. 🌐

#  🔗 **Working with Links and Documents MCQs**

1.  Which HTML tag is used to create hyperlinks? 🔗
    
    -   a) `<link>` 
    -   b) `<a>` 
    -   c) `<href>` 
    -   d) `<url>` 
    
       **Correct Answer**: b) `<a>` ✅
2.  What does the `href` attribute specify in an anchor tag (`<a>`)? 📝
    
    -   a) File type 
    -   b) Destination URL 
    -   c) Hyperlink text 
    -   d) Link behavior 
    
       **Correct Answer**: b) Destination URL 🌐
3.  To link to an external website, what should you include in the `href` attribute? 🌍
    
    -   a) Website name 
    -   b) Absolute URL 
    -   c) Relative URL 
    -   d) Email address 
    
       **Correct Answer**: b) Absolute URL 🌍
4.  How can you navigate within the same website using links? 🏠
    
    -   a) By using absolute URLs 
    -   b) By using relative URLs 
    -   c) By using mailto links 
    -   d) By using anchor tags 
    
       **Correct Answer**: b) By using relative URLs 🏠
5.  What does the `target="_blank"` attribute value do in an anchor tag? 🔄
    
    -   a) Opens the link in the same tab 
    -   b) Opens the link in a new tab 
    -   c) Redirects to the homepage 
    -   d) Disables the link 
    
       **Correct Answer**: b) Opens the link in a new tab 🚀
6.  Which type of link is used for email correspondence? ✉️
    
    -   a) Hyperlink 
    -   b) Mailto link 
    -   c) Document link 
    -   d) Download link 
    
       **Correct Answer**: b) Mailto link ✉️
7.  What should the `href` attribute value in a mailto link start with? ✉️
    
    -   a) `mail:` 
    -   b) `mailto:` 
    -   c) `email:` 
    -   d) `contact:` 
    
       **Correct Answer**: b) `mailto:` ✉️
8.  How can you pre-fill the subject line in a mailto link? ✉️
    
    -   a) Using the `mail-subject` attribute 
    -   b) By appending `?subject=` to the `href` 
    -   c) By using a separate `<subject>` tag 
    -   d) Subject lines cannot be pre-filled 
    
       **Correct Answer**: b) By appending `?subject=` to the `href` ✉️
9.  What attribute can you use to force a file download when linking to a file? 📥
    
    -   a) `download` 
    -   b) `force-download` 
    -   c) `file-download` 
    -   d) `download-link` 
    
       **Correct Answer**: a) `download` 📥
10.  How can you make your links more accessible to users with disabilities? 📝
    
      -   a) Use vague link text 
      -   b) Avoid using alt text for images 
      -   c) Use descriptive link text 
      -   d) Disable keyboard navigation 
    
       **Correct Answer**: c) Use descriptive link text 📝
11.  What is the purpose of the `rel` attribute when linking to files (e.g., PDFs)? 🖋️

-   a) It sets the file type 
-   b) It specifies the file format 
-   c) It defines the link text 
-   d) It indicates how the linked file should be related 

   **Correct Answer**: d) It indicates how the linked file should be related 🌐

12.  In HTML, what does the `download` attribute do when used in an anchor tag? 📥

-   a) Opens the link in a new tab 
-   b) Triggers a file download 
-   c) Redirects to the homepage 
-   d) Disables the link

   **Correct Answer**: b) Triggers a file download 📥
 
13.  How can you indicate the file type next to a download link for better user understanding? 🚀

-   a) Use the `<filetype>` tag 
-   b) Add an emoji 
-   c) Include file type in the link text 
-   d) Use the `type` attribute 

   **Correct Answer**: c) Include file type in the link text 📄

14.  Which value of the `target` attribute opens a link in a new browser tab or window? 🚀

-   a) `_self` 
-   b) `_blank` 
-   c) `_parent` 
-   d) `_top` 

   **Correct Answer**: b) `_blank` 🚀

15.  When should you use a relative URL for linking to another web page within the same website? 🏠

-   a) When linking to external websites 
-   b) When linking to email addresses 
-   c) When linking within the same website 
-   d) When linking to downloadable files

   **Correct Answer**: c) When linking within the same website 🏠

16.  What should you do to ensure that large file downloads are user-friendly? 📏

-   a) Provide no information 
-   b) Display file sizes in kilobytes only 
-   c) Show file size information next to download links 
-   d) Offer multiple download links for the same file 

   **Correct Answer**: c) Show file size information next to download links 📏

17.  Which attribute should you use to specify that a file should be downloaded rather than displayed in the browser? 🌐

-   a) `view` 
-   b) `download` 
-   c) `display` 
-   d) `force-download` 

  **Correct Answer**: b) `download` 📥

18.  What is the purpose of the `href` attribute in an anchor tag? 📝

-   a) It defines the link text 
-   b) It specifies the link's destination URL 
-   c) It sets the link's color and font 
-   d) It controls link behavior 

   **Correct Answer**: b) It specifies the link's destination URL 🌐

19.  Which HTML tag is used to create a hyperlink? 🔗

-   a) `<link>` 
-   b) `<a>` 
-   c) `<anchor>` 
-   d) `<url>` 

   **Correct Answer**: b) `<a>` 🌐

20.  What does a `mailto` link enable users to do? ✉️
   -   a) Play videos 
      -   b) Send emails 
      -   c) Download files 
      -   d) Open external websites 
    
   **Correct Answer**: b) Send emails ✉️



"Great job on Day 3! You've mastered the art of linking in HTML, whether it's to web pages, email addresses, or various file types🎉. Now, let's dive into more exciting topics on Day 4. 
Get ready to explore forms, user input, and interaction with your web pages. Let's keep the learning journey going!" 🚀
