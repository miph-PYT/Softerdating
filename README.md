Softer Dating website: https://www.softerdating.dk

## Events
Edit only `events.js` between events. The English and Danish homepages and the blog posts all read from it.

## Blog (softerdating.dk/blog/)
Posts are markdown files in the `_posts` folder.

1. Copy `_drafts/post-template.md` into `_posts/`.
2. Rename it `YYYY-MM-DD-short-url-name.md` (the part after the date becomes the web address).
3. Fill in title, description and language, write the post, commit.

GitHub Pages builds it in a few minutes. The post then shows up on /blog/, in the "From the blog" section of
both homepages (that section stays hidden until the first post exists), in /sitemap.xml and in the RSS
feed at /blog/feed.xml. Every post ends with a box showing the next event from `events.js`.

### Cross-posting to Medium
After a post is live, go to medium.com → your profile → Stories → **Import a story**, and paste the post's
softerdating.dk address. Medium copies it and marks softerdating.dk as the original, so Google gives
your site the credit.
