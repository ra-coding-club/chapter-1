# Chapter 1 Practice

**Read [What’s in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML) and answer the following questions below.**

### Questions

Sample Question 1: The ______ of an HTML document is the part that is not displayed in the web browser when the page is loaded. 

1. What is the head's job?

2. **Quote the article** to explain the difference between the `<title>` element and the `<h1>` element. 

3. Write the code for specifying your document's character encoding.

4. Many `<meta>` elements include `name` and `content` attributes. Explain what those two attributes are.

5. The humble ______, which has been around for many years, was the first icon of this type, a 16 x 16 pixel icon used in multiple places.

6. The ______ element always goes inside the head of your document.

7. *True or False?* - The `<script>` element does not have to go in the head. *Explain why or why not by quoting the article.*

8. What four-letter attribute sets the primary language of the document?

9. *True or False?* - There's a lot more you can do in here, but an exhaustive tour would be boring and confusing at this stage, and we just wanted to give you an idea of the most common things you'll find in there for now!

**Read [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals) and answer the following questions below.**

10. Why do we need semantics?

11. **Quote two sentences of the article** and explain the difference between ordered and unordered lists.

12. Summarize in complete sentences the **emphasis and importance** section of the article.

**Read [Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure) and answer the following questions below.**

13. Define the **5** basic sections of a document.

14. Explain non-semantic wrappers.

**Read [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started) and answer the following questions below.**

Sample Question 2: HTML (Hypertext Markup Language) is not a programming language; it is a ______ ________ used to tell your browser how to structure the web pages you visit.

15. *True or False* - Tags in HTML are case-sensitive

16. Explain the **4** main parts of a typical element.

17. You can put elements inside other elements too — this is called _______.

18. Explain the difference between block-level elements and inline elements.

19. What is the *only* example of an empty element in the article.

20. _________ contain extra information about the element which you don't want to appear in the actual content. 

21. Why is it advised to always include the attribute quotes?

22. If you've used one type of quote in your HTML, you (**can**/**can't**) include the other type of quote without causing any problems.

23. List the **6** main elements/tags that make up the anatomy of an HTML document.

24. What is the **one-word answer** for why to use a lot of whitespace?

25. In order to use `<`, `>`, `"`, `'`, and `&` in our HTML document, we have to use _________ __________.

26. Copy the following line of code, but now you have to **comment it out**: ````<p>Please comment this element out.</p>````

27. *True or False* - HTML and CSS don't go very well together, as you'll soon discover.

### Answers
Type your answers here:

Sample Answer 1: *head*

1. The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page <title>, links to CSS (if you choose to style your HTML content with CSS), links to custom favicons, and other metadata (data about the HTML, such as the author, and important keywords that describe the document.)

2. We've already seen the `<title>` element in action — this can be used to add a title to the document. This however can get confused with the `<h1>` element, which is used to add a top level heading to your body content — this is also sometimes referred to as the page title. But they are different things! The `<h1>` element appears on the page when loaded in the browser — generally this should be used once per page, to mark up the title of your page content (the story title, or news headline, or whatever is appropriate to your usage.)
The `<title>` element is metadata that represents the title of the overall HTML document (not the document's content.)

3. `<meta charset="utf-8">`

4. `name` specifies the type of meta element it is; what type of information it contains. `content` specifies the actual meta content.

5. favicon

6. `<link>`

7. True. The `<script>` element does not have to go in the head; in fact, often it is better to put it at the bottom of the document body (just before the closing `</body>` tag), to make sure that all the HTML content has been read by the browser before it tries to apply JavaScript to it (if JavaScript tries to access an element that doesn't yet exist, the browser will throw an error.)

8. lang

9. True!

10. One of HTML's main jobs is to give text structure and meaning (also known as semantics) so that a browser can display it correctly.

11. Unordered lists are used to mark up lists of items for which the order of the items doesn't matter. Ordered lists are lists in which the order of the items does matter.

12. In human language, we often emphasise certain words to alter the meaning of a sentence, and we often want to mark certain words as important or different in some way. HTML provides various semantic elements to allow us to mark up textual content with such effects.

13. (1) Header, (2) navigation bar, (3) main content, (4) sidebar, (5) footer.

14. Sometimes you'll come across a situation where you can't find an ideal semantic element to group some items together or wrap some content. Sometimes you might want to just group a set of elements together to affect them all as a single entity with some CSS or JavaScript. For cases like these, HTML provides the `<div>` and `<span>` elements. You should use these preferably with a suitable class attribute, to provide some kind of label for them so they can be easily targeted.

Sample Answer 2: 
