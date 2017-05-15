# Frontend Example Code

### Dependencies

- Ruby 2.3
- Middleman 4.2

### Setup

```
git clone git@github.com:stephen-puiszis/frontend-example.git
bundle install
```

### "Running the Server"

Middleman is a static site geneator so there is no server, but in development
the build processes acts like one, using hot-reloading for faster rebuliding:

```
bundle exec middleman sever
```

### Deployment

To create the static site, which does a lot of stuff to optimize for speed
(including minifying html):

```
bundle exec middleman build
```

TODO: Add S3 uploading process
