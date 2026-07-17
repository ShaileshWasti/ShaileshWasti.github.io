# How to apply these changes to your local repo

Your repo: /Users/shaileshwasti/Desktop/gitALL/ShaileshWasti.github.io

## 1. Copy these changed/new files over your local ones (same relative paths):
- _config.yml                  (site title fixed)
- _sass/_variables.scss        (new accent color, was drab grey #7a8288 -> now #2c5f7c)
- _data/navigation.yml         (nav trimmed to just "Research")
- _pages/about.md              (added CV button + research summary placeholder)
- _pages/research.md           (NEW — was missing, causing your "Research" nav link to 404)

## 2. Delete these placeholder/orphaned files from your local repo:
  _posts/2012-08-14-blog-post-1.md
  _posts/2013-08-14-blog-post-2.md
  _posts/2014-08-14-blog-post-3.md
  _posts/2015-08-14-blog-post-4.md
  _posts/2199-01-01-future-post.md
  _talks/2012-03-01-talk-1.md
  _talks/2013-03-01-tutorial-1.md
  _talks/2014-02-01-talk-2.md
  _talks/2014-03-01-talk-3.md
  _publications/2010-10-01-paper-title-number-2.md
  _portfolio/portfolio-1.md
  _portfolio/portfolio-2.html
  _teaching/2014-spring-teaching-1.md
  _pages/publications.md
  _pages/teaching.html
  _pages/talks.html
  _pages/talkmap.html
  _pages/portfolio.html

(You can do this fastest from Terminal, inside your repo folder:)

cd /Users/shaileshwasti/Desktop/gitALL/ShaileshWasti.github.io
rm -f _posts/2012-08-14-blog-post-1.md _posts/2013-08-14-blog-post-2.md _posts/2014-08-14-blog-post-3.md _posts/2015-08-14-blog-post-4.md _posts/2199-01-01-future-post.md
rm -f _talks/2012-03-01-talk-1.md _talks/2013-03-01-tutorial-1.md _talks/2014-02-01-talk-2.md _talks/2014-03-01-talk-3.md
rm -f _publications/2010-10-01-paper-title-number-2.md
rm -f _portfolio/portfolio-1.md _portfolio/portfolio-2.html
rm -f _teaching/2014-spring-teaching-1.md
rm -f _pages/publications.md _pages/teaching.html _pages/talks.html _pages/talkmap.html _pages/portfolio.html

## 3. Still to do (need your real info — I left placeholders):
- _pages/about.md: fill in the real 1-sentence research summary (marked with [ ])
- _pages/research.md: replace "Electricity Markets" section with your real topics + real papers,
  add/remove subheadings as needed
- files/CV.pdf: add your real CV PDF (About page links to /files/CV.pdf)
- files/paper1.pdf, paper2.pdf, paper3.pdf: replace with your real paper PDFs, or remove the links
  in research.md if you'd rather link to a journal/DOI page instead

## 4. Commit and push
cd /Users/shaileshwasti/Desktop/gitALL/ShaileshWasti.github.io
git add -A
git commit -m "Refresh site: fix broken Research page, trim nav, remove placeholder content, update accent color"
git push
