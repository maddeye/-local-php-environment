# My local php dev environment

## How to setup

Clone this repo and cd into it:

```bash
git clone git@github.com:maddeye/local-php-environment.git
cd local-php-environment
```

Start docker compose:

```bash
docker-compose up -d
```

Start developing within the _app_ folder.

Open your browser on _http://localhost:3000_.

## Stop the environment

Stop docker compose:

```bash
docker-compose down
```

## Tipp

Use the _index.php_ file only as an entry point and develop your code outside of the public folder!
