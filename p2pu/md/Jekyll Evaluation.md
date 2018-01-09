# Jekyll Evaluation

I'm busy changing my own blog over to Jekyll, I'll put my thoughts and questions here to help us:

*   The default Markdown renderer sucks, put 'markdown: redcarpet' in _config.yml
*   Featured images need to be defined in the header
*   How do you do tag/category pages?
*   How do you do site.url for local testing and deployment?
*   Managing asset paths can be tricky if you have to account for a possible baseurl (like when you are hosting on github pages
*   How does Jekyll handle different languages?
*   Jekyll templates are good at working with the front matter (what you put in the top) but what you put in the body of a page/post is mostly just processed by markdown and supports a few tags/filters. This means you can't really lay out the content of a page/post with the templating system
*   front matter variables only passed to immediate template (layout)
*   Are there any good documentation for liquid templates?
*   Difficult to order lists
*   for courses: it makes the idea of static content much stronger - difficult to change content - assumption is that the course creator will not continue to edit the course
*   Jekyll goes far, but not far enough wrt simplicity. I don't really know why they distinguish between pages and posts?