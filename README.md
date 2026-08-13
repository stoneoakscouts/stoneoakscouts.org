# Stone Oak Scouts website

Jekyll source for [stoneoakscouts.org](https://stoneoakscouts.org).

## Local setup

Use Ruby 3.4 (see `.ruby-version`). [rbenv](https://github.com/rbenv/rbenv) is a
good way to install it.

```
bundle install
bundle exec jekyll serve -l
```

That starts a live-reloading server. Images are not in this repo. They live in
the `stoneoakscouts-images-origin` S3 bucket and are served from
`https://stoneoakscouts.org/images/`. Local preview uses those same URLs, so you
need network access to see logos and photos.

## Layouts

`chrome` is the site shell: header, nav, and footer. Markdown pages should use
`page`, which wraps content in a single 12-column row. If a page needs its own
grid rows, use `chrome` and write the row markup yourself.

## References

* [Jekyll docs](https://jekyllrb.com/docs/)
