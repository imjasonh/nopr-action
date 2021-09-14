# No Pull Requests

This repo contains a GitHub Actions workflowtestteststes to automatically close all Pull Requests opened on the repo.

![Image of self-closing box](http://i.imgur.com/wQdS8RJ.gif)

Some projects don't accept Pull Requests. Maybe they have their own contribution processes. Maybe they hate freedom. Either way, GitHub doesn't provide a way to disable pull requests officially.

So I wrote this.

Using this workflow, you can effectively disable pull requests for your repo on GitHub. When pull requests are disabled, any time a new one is opened it will immediately be closed by the bot.
