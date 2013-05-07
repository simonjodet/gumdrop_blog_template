***
{
    "title":"Welcome on Gumdrop's blog template",
    "date":"1970-01-01",
    "layout":"post.twig"
}
***
It features:
  
* a default look based on [Bootstrap](http://twitter.github.io/bootstrap/),
* a command-line tool to create blog posts,
* a pagination for the home page with Ajax loading and "infinite scrolling",
* a basic Ajax search engine,
* an [Atom feed](atom.xml),
* a [site map](sitemap.xml).

First you should edit `sitemap.xml.twig` to replace `http://your-blog.com/` by your blog's URL.

You should also edit `atom.xml.twig` to replace `http://your-blog.com/` by your blog's URL and set your blog's title, your name and email.

And finally you should look into `_layout/default.twig` to change the footer, header and other stuff. Obviously, it's better if you have some knowledge of HTML, CSS and JavaScript.

This post's content is in `posts/1970-01-01-welcome-on-gumdrop-s-blog-template.markdown`.

Its skeleton was generated using a small command-line helper:

    ./_tools/create_post

It was then further edited using the Markdown syntax. You can delete it or edit it as you want.

Please refer to [Gumdrop's documentation](http://gumdropapp.com/documentation.htm) for more information in Gumdrop's usage.