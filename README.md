# API in the right way

This project is a small example of a REST API, built on good development practices.

## Features

* Implements [Fractal](https://fractal.thephpleague.com/)
* [Coming soon] Documentation with [Swager](https://swagger.io/docs/)
* The architecture tends to [DDD](https://en.wikipedia.org/wiki/Domain-driven_design)
* [Single action Controllers](https://laravel.com/docs/5.7/controllers#single-action-controllers)
* [Coming soon] Code coverage by tests with [PHPUnit](https://phpunit.de/)
* Docker for dev environment with [Ambientum](https://github.com/codecasts/ambientum)


## Installation

Use the package manager [composer](https://getcomposer.org) to install it.

```bash
# At the root of the project.
composer install
```

## Usage

You can run this project easily on your machine with [Docker](https://docs.docker.com/), you will also need the [Docker Compose](https://docs.docker.com/compose/).

```bash
# At the root of the project.
./bin up -d # Ready! The API is already available at http://localhost :)
./bin down  # Drop containers.
./bin composer update # Use the composer package manager.
./bin artisan # Use the Laravel command line.
./bin vendor/bin/phpunit # PHPUnit
# OR
./bin ls -l # Run any command inside the container.
```

> All this was very easy thanks to the beautiful work done in this project [codecasts/ambientum](https://github.com/codecasts/ambientum)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## Authors
* [Edilson Cichon](https://github.com/cichondev)

## License
[MIT](https://choosealicense.com/licenses/mit/)