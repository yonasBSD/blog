# Create your own blog now!

[CLICK ON FORK BUTTON](https://github.com/rochacbruno/make-me-a-blog/fork) and name your fork `blog`.

Then edit the `marmite.yaml` with your own information. (IMPORTANT! change the `url:..` field to match your own repo)

Commit and see the Github Actions building a blog for you.

This blog is generated with [marmite](https://rochacbruno.github.io/marmite/)


## Building locally

```console
$ git clone git@github.com:YOURUSER/blog.git
$ cd blog
```

```console
$ cargo install marmite
```

```console
$ marmite . site
Site generated at: /site/
```

Learn more on [marmite](https://rochacbruno.github.io/marmite/)

