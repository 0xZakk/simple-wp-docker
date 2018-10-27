# Simple WordPress Development with Docker

Leverage [Docker](https://www.docker.com) and
[Composer](https://getcomposer.org) to create a simple dev environment for
building WordPress sites.

## Getting Started

These instructions will get you a copy of the project up and running on your
local machine for development and testing purposes.

### Prerequisites

Before you can get started with using this starter, you'll need to install and
set up both Docker Compose and Composer:

* [Install Docker Compose](https://docs.docker.com/compose/install/)
* [Download Composer](https://getcomposer.org/download/)

### Installing

Once both of the above are installed and set up, you can install the
dependencies in [`composer.json`](./composer.json):

```sh
composer install
```

Then, to get the project running, all you have to do is build and setup the
project using Docker Compose:

```sh
docker-compose up
```

This command may take a minute to run. But afterwards, you should be able to
navigate to [`localhost:8080`](http://localhost:8080) and see the WordPress
5-minute install screen:

![](https://user-images.githubusercontent.com/4991553/47607183-d68dec00-d9ea-11e8-8cd6-7656e43b4c47.png)

## Deployment

To deploy a site built with this site, you can either deploy this container
project and run it using the default WordPress image or you can deploy the theme
and plugins directory using any method you'd like.

## Built With

* [WordPress](https://wordpress.org/) - For building easy-to-manage websites
* [Docker](https://www.docker.com) - Easy virtual environment management
* [Composer](https://getcomposer.org/) - Dependency management for PHP

## Contributing

Please read
[CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for
details on the process for submitting pull requests to us.

## Authors

* **Zakk Fleischmann** - *Creator, Maintainer* - [zkf.io](https://zkf.io)

See also the list of
[contributors](https://github.com/your/project/contributors) who participated in
this project.

## License

This project is licensed under the MIT License - see the
[LICENSE.md](LICENSE.md) file for details

