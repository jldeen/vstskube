![Let's Chat Greylock](http://i.imgur.com/0a3l5VF.png)
![Screenshot](http://i.imgur.com/C4uMD67.png)
A self-hosted chat app for small teams or big Gal by [Security Compass][seccom].



## Features and Stuff

* BYOS (bring your own server)
* Persistent messages
* Multiple rooms
* Private and password-protected rooms
* New message alerts / notifications
* Mentions (hey @you/@all)
* Image embeds / Giphy search
* Code pasting
* File uploads (Local / [Amazon S3][s3] / [Azure][azure])
* Transcripts / Chat History (with search)
* XMPP Multi-user chat (MUC)
* 1-to-1 chat between XMPP users
* Local / [Kerberos][kerberos] / [LDAP][ldap] authentication
* [Hubot Adapter][hubot]
* REST-like API
* Basic i18n support
* MIT Licensed


## Deployment 

For installation instructions, please use the following links:

* [Local installation][install-local]
* [Docker][install-docker]
* [Heroku][install-heroku]
* [Vagrant][install-vagrant]

## Support & Problems

We have a [troubleshooting document][troubleshooting], otherwise please use our
[mailing list][mailing-list] for support issues and questions.


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue
guidelines][contributing] and search for existing and closed issues. If your
problem or idea is not addressed yet, [please open a new issue][new-issue].


## Documentation

Let's Chat documentation is hosted in the [wiki]. If there is an inaccuracy in
the documentation, [please open a new issue][new-issue].


## Contributing

Please read through our [contributing guidelines][contributing]. Included are
directions for opening issues, coding standards, and notes on development.

Editor preferences are available in the [editor config][editorconfig] for easy
use in common text editors. Read more and download plugins at
<http://editorconfig.org>.


## License

Released under [the MIT license][license].


[wiki]: https://github.com/sdelements/lets-chat/wiki
[troubleshooting]: https://github.com/sdelements/lets-chat/blob/master/TROUBLESHOOTING.md
[mailing-list]: https://groups.google.com/forum/#!forum/lets-chat-app
[tracker]: https://github.com/sdelements/lets-chat/issues
[contributing]: https://github.com/sdelements/lets-chat/blob/master/CONTRIBUTING.md
[new-issue]: https://github.com/sdelements/lets-chat/issues/new
[editorconfig]: https://github.com/sdelements/lets-chat/blob/master/.editorconfig
[license]: https://github.com/sdelements/lets-chat/blob/master/LICENSE
[ldap]: https://github.com/sdelements/lets-chat-ldap
[kerberos]: https://github.com/sdelements/lets-chat-kerberos
[s3]: https://github.com/sdelements/lets-chat-s3
[seccom]: http://securitycompass.com/
[hubot]: https://github.com/sdelements/hubot-lets-chat
[azure]: https://github.com/maximilian-krauss/lets-chat-azure
[install-local]: https://github.com/sdelements/lets-chat/wiki/Installation
[install-docker]: https://registry.hub.docker.com/u/sdelements/lets-chat/
[install-heroku]: https://github.com/sdelements/lets-chat/wiki/Heroku
[install-vagrant]: https://github.com/sdelements/lets-chat/wiki/Vagrant





![Let's Chat Greylock](https://codefresh.io/wp-content/uploads/2017/03/lets-chat.png)


This tutorial is based on Let’s Chat [app].

https://github.com/jldeen/demochat

### Let’s Chat is self-hosted chat app for small teams or big

This tutorial will walk you through the process of adding the following :


* Build step - that will build Docker image for your Let’s Chat app

* Push to registry step - that will push your image to Docker Hub

* Unit Test step - A freestyle step that runs the unit test of the demo chat after the build 

* Composition step - This step will create and launch a composition.

So, the first thing you need to do is :

## Fork the repo  

Enter the following link and fork Let’s Chat app!: ```https://github.com/jldeen/demochat```


## About Containers 101

[Containers 101](https://www.meetup.com/Containers-101-meetup/) is online/offline meetup group based in Mountain View that provides guides and helps developers work with Containers. Created by [Codefresh](https://codefresh.io/) which provides environments for every commit, Docker CI and CD, and an embedded registry. 

[Join Containers 101](https://www.meetup.com/Containers-101-meetup/)
Learn more about [Codefresh](https://codefresh.io/)

