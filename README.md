my-twitters
===========

A list of Twitter followers and followings (output from t)

### Scripts

To create the `followers.log` run:

    $ t followers --sort=since > followers.log

To create the `followings.log` run:

    $ t followings --sort=since > followings.log

Or to automatically push it to twitter run `myTwitter`:

    $ sh myTwitter

### Why

First, why not? Second, this is an easy way to keep track of the changes in your
Twitter Follower and Following lists which is not easily done.

### Thanks

I want to thank [sferik](https://github.com/sferik) for creating [t](https://github.com/sferik/t), an amazing commandline application for
Twitter. I also want to thank [malvosenior](https://news.ycombinator.com/user?id=malvosenior) who gave me this idea exactly from a
recent [Hacker News thread about t](https://news.ycombinator.com/item?id=8384643).
