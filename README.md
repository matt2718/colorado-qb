# Colorado Quiz Bowl

The main point of this website is to consolidate information on quiz bowl in
Colorado, and provide an authoritative resource for players and coaches. The site can be found at http://coloradoqb.org.

## How this site is built

The site is based on [Jekyll](https://jekyllrb.com/), with a modified version
the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.
Jekyll has the advantage of working really well with GitHub Pages, so we can
manage our site using Git and all of the beautiful, graph-theory-based
distributed version control goodness that it provides (which is probably
overkill, but should make it easy to keep track of changes and manage multiple
contributors).

## How to add pages

Because we're using Jekyll, pages can be written in Markdown, so pretty much
anyone can contribute, even if they don't know HTML. Contributors will need to
[learn Git](https://git-scm.com/book/en/v2), but this should be relatively easy.
You can still use HTML, but given how convenient Markdown is, you probably won't
need to.

I'd recommend looking through the Jekyll documentation, just so you have some
idea how this is set up.

Pages are stored in the `_pages` directory, usually in subfolders. Just copy a
template from a page that already exists, change the front matter (title and
permalink) and content, and you're good to go. If you want to insert a link to
your page on the sidebar, add an entry to `_data/navigation.yml`.

If you want to insert a blog post, just shove it in the `_posts` directory. Make
sure you format the filename the way Jekyll requires.

## Style Guide

When writing for this site, try to adhere to the following conventions:

* In the interest of consistency, "quiz bowl" should always be 2 words.
  "Quizbowl" should only be when quoting (e.g. "as Bob once wrote, 'Quizbowl is
  awesome!'") or in proper names (e.g. "Missouri Quizbowl Alliance").

* Unless otherwise specified, "quiz bowl" refers to pyramidal quiz bowl, **not**
  Knowledge Bowl or Science Bowl. History Bowl, however, **is** considered quiz
  bowl because most of the game is pyramidal.

* Quiz bowl is a common noun; don't capitalize it. It refers to a type of game
  and is not tied to any single organization. Specific formats like Science
  Bowl, History Bowl, and Knowledge Bowl (tied to the DOE, NHBB, and Academic
  Hallmarks respectively) should be capitalized.

* Never write in first person singular. You are writing on behalf of Colorado
  Quiz Bowl; if you need to speak in the first person, use "we".

* When referring to an *non-specific* person, use they/them/their. I'm not
  trying to force my views about gender-neutral language on anyone else; I'd
  just like a consistent writing style. No one wants a site that uses "he" in
  one part, "she" in another, "he/she" in a third, and "they" in a fourth.

* Use Oxford commas (e.g. "Colorado, Idaho, and Utah" instead of "Colorado,
  Idaho and Utah"). I know this is a contentious issue, but again, it's about
  consistency.

* When you link to another page on this site, do not include the domain name.
  `[rules](/info/rules/)` is right. `[rules](http://coloradoqb.org/info/rules/)`
  is wrong. This is because:
  *  It makes the site harder to preview locally before pushing changes, as
     clicking on links will take you to the public version.
  *  If we ever move the site to a different domain, or if another quiz bowl
     organization bases their site on ours, the links will have to be re-written
     manually.
  
* I recommend limiting your line width to 80 characters for ease of editing, but
  this part isn't super important.
