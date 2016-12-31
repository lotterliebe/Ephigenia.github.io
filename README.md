Run local jekyll Server

    JEKYLL_ENV=development bundle exec jekyll serve

test production state:

    JEKYLL_ENV=production jekyll serve

Enable unpublishd, draft and future posts:

    bundle exec jekyll server --unpublished --drafts --future
