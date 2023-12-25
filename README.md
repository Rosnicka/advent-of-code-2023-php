# advent-of-code-2023-php
https://adventofcode.com/2023/

## Composer
To run composer via docker use something like:
`docker run --rm -v ${pwd}:/app composer -V`

## PHP
Run PEST Tests
`docker run -v "${pwd}:/usr/src/myapp" -w /usr/src/myapp php:8.1-cli php ./vendor/bin/pest`