# Hello, Pages! Theme


### Easy 1-2-3 Publishing

Thanks to the new plugins for easy publishing, namely
Optional Front Matter,
README Index,
Default Layout, and
Titles from Headings
you can now publish pages, that is, static (web)sites
on GitHub without any configuration (that is, `_config.yml`) or
front matter blocks (that is, `---` ... `---`) in your markdown documents
and your README.md will become the index.html front page of your site.

More Info:

- [Publishing with GitHub Pages, now as easy as 1, 2, 3](https://github.com/blog/2289-publishing-with-github-pages-now-as-easy-as-1-2-3) by Ben Balter, Dec 8, 2016

### Relative Links

Thanks to the Relative Links plugin, you can link to markdown source files
and GitHub Pages automatically changes the link to hypertext (.html) when published e.g.


```
[Page Two](two.md)  
        becomes =>
<a href="two.html">Page Two</a>
```

Try it. Follow along to [Page Two](two.md) or to [Page Three](three.md).

More Info:

- [Relative links for GitHub pages](https://github.com/blog/2290-relative-links-for-github-pages) by Ben Balter, Dec 5, 2016



### Live Demo

See a live demo @ [`henrythemes.github.io/hello-pages-theme` »](https://henrythemes.github.io/hello-pages-theme)


### Version 2.0

Note: For a more "advanced" starter theme, see the
[Hello, Pages! Theme V2](https://github.com/henrythemes/hello-pages-theme-v2).
The V2 includes:

- Custom master page layout template in `_layouts` e.g. `page.html`, etc.
- Shared (common) template/page building blocks using `_includes` e.g. `pages.html`, `footer.html`, `github.html`, etc.
- Footer with last built time e.g. `{{ site.time }}` (and Jekyll version e.g. `{{ jekyll.version }}`)
- And more

### More Themes

For more themes in the Hello! series, see:

- [Hello, Jekyll! Theme](https://github.com/henrythemes/hello-jekyll-theme)
- [Hello, Minima! Theme](https://github.com/henrythemes/hello-minima-theme)

For even more themes see the [Dr. Jekyll's Themes](https://drjekyllthemes.github.io) directory.


## Meta

#### License

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The Hello, Pages! theme is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

#### Questions? Comments?

Post them to the [jekyll talk forum](http://talk.jekyllrb.com). Thanks!
