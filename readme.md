<img src="https://github.com/kkamara/useful/raw/main/MainClass.png" alt="MainClass.png" width=""/>

# PhP Docker Skeleton

(2020) Get started with PHP and Docker.

* [Installation](#installation)

* [Usage](#usage)

* [Not Using Docker?](#not-using-docker)

* [Misc.](#misc)

* [Contributing](#contributing)

* [License](#license)

## Installation

* [PHP](https://herd.laravel.com/)
* [Composer](https://getcomposer.org/)

If you're using Docker make sure you have [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) installed.

```bash
# composer install
composer i
```

## Usage

```bash
# to run on first time
docker-compose up --build
# to run in background
docker-compose up --build -d
# to run when file-changes have been made
docker-compose up
```

<a name="not-using-docker"></a>
#### Not Using Docker?

```bash
composer start -- -f=foo --bar=baz
```

## Misc.

[PHP Docker Skeleton](https://github.com/kkamara/php-docker-skeleton).

[NodeJS Docker Skeleton](https://github.com/kkamara/nodejs-docker-skeleton).

[Python Docker Skeleton](https://github.com/kkamara/python-docker-skeleton).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)
