<h1 align="center">
  <br>
  <img src="https://olivia-ai.org/img/icons/olivia-with-text.png" alt="Olivia's character" width="300">
  <br>
</h1>

<h4 align="center">💁‍♀️ Your new best friend</h4>

<p align="center">
  <a href="https://goreportcard.com/report/github.com/olivia-ai/olivia"><img src="https://goreportcard.com/badge/github.com/olivia-ai/olivia"></a>
  <a href="https://godoc.org/github.com/olivia-ai/olivia"><img src="https://godoc.org/github.com/olivia-ai/olivia?status.svg" alt="GoDoc"></a>
  <a href="https://app.fossa.io/projects/git%2Bgithub.com%2Folivia-ai%2Folivia?ref=badge_shield"><img src="https://app.fossa.io/api/projects/git%2Bgithub.com%2Folivia-ai%2Folivia.svg?type=shield"></a>
  <br>
  <img src="https://github.com/olivia-ai/olivia/workflows/Docker%20CI/badge.svg">
  <img src="https://github.com/olivia-ai/olivia/workflows/Format%20checker/badge.svg">
</p>

<p align="center">
  <a href="https://olivia-ai.org">Website</a> —
  <a href="https://olivia-ai.org/chat">Chat online</a> —
  <a href="https://olivia-ai.org/blog">Blog</a> —
  <a href="https://olivia-ai.org/changelog">Changelog</a> —
  <a href="#getting-started">Getting started</a> —
  <a href="https://trello.com/b/azB6r2IC/olivia">Projects</a> —
  <a href="#contributors">Contributors</a> —
  <a href="#license">License</a>
</p>

## Getting started
### Installation
#### Docker

<p align="center">
  <img alt="docker installation" height="100" src="https://i.imgur.com/5NDCfF3.png">
</p>

Pull the image from GitHub Packages
```bash
$ docker pull docker.pkg.github.com/olivia-ai/olivia/olivia:latest
```

Then start it
```bash
$ docker run -d -p 8080:8080 docker.pkg.github.com/olivia-ai/olivia/olivia:latest
```

You can just use the websocket of Olivia now.

To stop it, get the container id:
```bash
$ docker container ls
```
```bash
CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS              PORTS                    NAMES
311b3abb963a        olivia              "./main"            7 minutes ago       Up 7 minutes        0.0.0.0:8080->8080/tcp   quizzical_mayer
```

and stop it
```bash
$ docker container stop 311b3abb963a 
```

The app will automatically check for `res/training.json` file which contains the save of the neural network.
By default when you clone the repository from Github you have a stable save.
If you want to train a new model just delete this file and rerun the app.

#### GitHub
<p align="center">
  <img height="100" src="https://i.imgur.com/RRPoP69.png">
</p>

Clone the project via GitHub:

```bash 
$ git clone git@github.com:olivia-ai/olivia.git
```

Then download the dependencies
```bash
$ go mod download
```

And run it
```bash
$ go run main.go
```

## Contributors

<p align="center">
  <img alt="docker installation" height="85" src="https://i.imgur.com/6xr2zdp.png">
</p>
  
### Code Contributors
Thanks to the people who contribute to Olivia. 

[Contribute](CONTRIBUTING.md)
<a href="https://github.com/olivia-ai/olivia/graphs/contributors"><img src="https://opencollective.com/olivia-ai/contributors.svg?width=890&button=false" /></a>

### Financial Contributors
Become a financial contributor and help Olivia growth. 

[Contribute](https://opencollective.com/olivia-ai/contribute)

#### Individuals
<a href="https://opencollective.com/olivia-ai"><img src="https://opencollective.com/olivia-ai/individuals.svg?width=890"></a>

#### Organizations
Support Olivia with your organization. 
Your logo will show up here with a link to your website. 

<a href="https://opencollective.com/olivia-ai/organization/0/website"><img src="https://opencollective.com/olivia-ai/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/1/website"><img src="https://opencollective.com/olivia-ai/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/2/website"><img src="https://opencollective.com/olivia-ai/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/3/website"><img src="https://opencollective.com/olivia-ai/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/4/website"><img src="https://opencollective.com/olivia-ai/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/5/website"><img src="https://opencollective.com/olivia-ai/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/6/website"><img src="https://opencollective.com/olivia-ai/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/7/website"><img src="https://opencollective.com/olivia-ai/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/8/website"><img src="https://opencollective.com/olivia-ai/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/olivia-ai/organization/9/website"><img src="https://opencollective.com/olivia-ai/organization/9/avatar.svg"></a>


## License

<p align="center">
  <img src="https://i.imgur.com/9Xxtchv.png" height="90">
</p>

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Folivia-ai%2Folivia.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Folivia-ai%2Folivia?ref=badge_large)

<p align="center">
  <img width="60" src="https://olivia-ai.org/img/icons/olivia.png">
<p>

<p align="center">
  Made with ❤️ by <a href="https://github.com/hugolgst">Hugo Lageneste</a>
</p>

![Olivia's wave](https://olivia-ai.org/img/background-olivia.png)
