# Bibit Reksadana API

API to get Indonesian mutual funds data. All data are retrieved from [Bibit Reksadana](https://bibit.id/reksadana.html) page.

## Installation

You'll need a [Vercel](https://vercel.com/home) account and [Vercel CLI](https://vercel.com/download) to run this API.

```bash
# Clone the repository
$ git clone git@github.com:risan/bibit-reksadana.git

# Install dependencies
$ npm install

# Spin up vercel development
$ vercel dev
```

Checkout [bibit-reksadana.vercel.app](https://bibit-reksadana.vercel.app/) for API documentation.

## How to use

```bash
https://bibit-reksadana.vercel.app/api?buy_from_bibit=true&search=Sucor&page=1&per_page=10&types=fixed_income&sharia=false&usd=false&sort_by=return_1y&sort_direction=asc

https://bibit-reksadana.vercel.app/api?
buy_from_bibit=true
search=Sucor
page=1
per_page=10
types=fixed_income
sharia=false
usd=false
sort_by=return_1y
sort_direction=asc

```
