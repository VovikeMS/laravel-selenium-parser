# Laravel Selenium Parser

Web application to easily parse content of third party sites.

## Local

```bash
$ cp .env.example .env
$ docker-compose up -d
$ ./cmd composer install
$ ./cmd npm install
$ ./cmd npm run dev
$ ./cmd php artisan key:generate
$ ./cmd php artisan migrate
```

## API

### GET /api/products?page={page}

Fetch all products using pagination.

- `{page}` - current pagination page

### GET /api/products/{id}

Fetch specific product.

- `{id}` - id of specific product


## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
