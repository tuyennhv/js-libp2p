js-libp2p-tcp
===============

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![Build Status](https://travis-ci.org/diasdavid/js-libp2p-tcp.svg?style=flat-square)](https://travis-ci.org/diasdavid/js-libp2p-tcp)
![](https://img.shields.io/badge/coverage-%3F-yellow.svg?style=flat-square)
[![Dependency Status](https://david-dm.org/diasdavid/js-libp2p-tcp.svg?style=flat-square)](https://david-dm.org/diasdavid/js-libp2p-tcp)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard)

![](https://raw.githubusercontent.com/diasdavid/abstract-connection/master/img/badge.png)
![](https://raw.githubusercontent.com/diasdavid/abstract-transport/master/img/badge.png)

> Node.js implementation of the TCP module that libp2p uses, which implements
> the [interface-connection](https://github.com/diasdavid/interface-connection)
> interface for dial/listen.

## Description

`libp2p-tcp` in Node.js is a very thin shim that adds the support to dial to a
`multiaddr`. This small shim will enable libp2p to use other different
transports.

## Example

```js
```

outputs

```
```

## Installation

### npm

```sh
> npm i libp2p-tcp
```

## API

```js
const Tcp = require('libp2p-tcp')
```

### var tcp = new Tcp()

...

### tcp.dial(multiaddr, options)

...

### tcp.createListener(multiaddrs, handler, callback)

...

### tcp.close(callback)

...

### tcp.filter(multiaddrs)

...

## License

MIT
