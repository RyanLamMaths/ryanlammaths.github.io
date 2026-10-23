# Ryan Lam — Academic Pages

This is the WordPress content from https://ryanlamhk.wordpress.com/, migrated into the actual [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template. The upstream MIT license is retained in `LICENSE`. Conversion is helped by ChatGPT.

## Content

- 8 original pages and 24 complete blog posts, with original publication dates and routes.
- All 10 public comments and pingbacks, original categories/tags, images, downloadable files and embedded presentation video.
- Original wording is retained, including historical references to WordPress. WordPress advertisements, tracking, admin controls and theme styling are omitted.
- Mathematical expressions are migrated from WordPress equation images to their original TeX and rendered with the template's MathJax support.
- 73 available site-owned downloads and images are copied to their original `/wp-content/uploads/...` paths. External links, including the current Google Drive CV and YouTube video, remain external. One obsolete WordPress CV file already returned 404; that link now points to the current Google Drive CV linked from the original About page.
- The WordPress contact form and email subscriptions still open the original WordPress service. Email and a local RSS feed are also available. New comments are not collected by this static website; existing public comments are archived.

## Edit and run

Install Ruby 3.3 or newer and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Edit `_pages/*.html` for pages, `_posts/*.html` for posts, `_data/navigation.yml` for navigation, and `_config.yml` for your profile and site URL. The HTML content uses YAML front matter, as supported by Jekyll. New content may also use Markdown files.

To produce a static site:

```sh
JEKYLL_ENV=production bundle exec jekyll build --destination dist
```


## Migration records

`migration/inventory.json` records every imported page and post. `migration/assets.json` records each copied file, its original URL, byte count and SHA-256. The original public API responses and sitemap are retained there for comparison and future editing. These files are excluded from the generated website. `migration/template-commit.txt` identifies the upstream template revision. `migration/validation.json` records content, links, equation and file-hash checks. Browser visual QA was unavailable in the build environment. No private posts, drafts or WordPress account data were accessed.
