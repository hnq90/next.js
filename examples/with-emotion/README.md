[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/zeit/next.js/tree/master/examples/with-emotion)

# Example app with [emotion](https://github.com/tkh44/emotion)

## How to use

Download the example [or clone the repo](https://github.com/zeit/next.js):

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/master | tar -xz --strip=2 next.js-master/examples/with-emotion
cd with-emotion
```

Install it and run:

```bash
npm install
npm run dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

This example features how to use [emotion](https://github.com/tkh44/emotion) as the styling solution instead of [styled-jsx](https://github.com/zeit/styled-jsx).

We are creating three `div` elements with custom styles being shared across the elements. The styles includes the use of pseedo-selector and CSS animations.


This is based off the with-glamorous example.