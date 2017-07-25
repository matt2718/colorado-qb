# Colorado Quiz Bowl

The main point of this website is to consolidate information on quiz bowl in Colorado, and provide an authoritative resource for players and coaches.

The site is at http://coloradoqb.org. It's not finished yet, so I've configured it to prevent indexing by search engines. When we're ready to release, I'll update `robots.txt`, post a link to it somewhere, and let Google work its magic.

## How this site is built

The site is based on [Jekyll](https://jekyllrb.com/), with a modified version the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme. Jekyll has the advantage of working really well with GitHub Pages, so we can manage our site using Git and all of the beautiful, graph-theory-based distributed version control goodness that it provides (which is probably overkill, but should make it easy to keep track of changes and manage multiple contributors).

Because we're using Jekyll, pages can be written in Markdown, so pretty much anyone can contribute, even if they don't know HTML (though they will need to learn Git). You can still use HTML, but you probably won't need to, given how convenient Markdown is.

## How to add pages

I'd recommend looking through the Jekyll documentation, just so you have some idea how this is set up.

Pages are stored in the `_pages` directory, usually in subfolders. Just copy a template from a page that already exists, change the front matter (title and permalink) and content, and you're good to go. If you want to insert a link to your page on the sidebar, add an entry to `_data/navigation.yml`.

If you want to insert a blog post, just shove it in the `_posts` directory. Make sure you format the filename the way Jekyll requires.
