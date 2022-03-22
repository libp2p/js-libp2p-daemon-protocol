# js-libp2p-daemon-protocol

<a href="http://libp2p.io/"><img src="https://img.shields.io/badge/project-libp2p-yellow.svg?style=flat-square" /></a>
<a href="http://webchat.freenode.net/?channels=%23libp2p"><img src="https://img.shields.io/badge/freenode-%23libp2p-yellow.svg?style=flat-square" /></a>
<a href="https://discuss.libp2p.io"><img src="https://img.shields.io/discourse/https/discuss.libp2p.io/posts.svg" /></a>
<a href="https://waffle.io/libp2p/libp2p"><img src="https://img.shields.io/badge/pm-waffle-yellow.svg?style=flat-square" /></a>

> Contains the protobuf definitions of the communication protocol for libp2p daemons

## Install

```
npm i @libp2p/daemon-protocol
```

## Usage

For a full list of options, you can run help `jsp2pd --help`.
Running the defaults, `jsp2pd`, will start the daemon and bind it to a local unix socket path.
Daemon clients will be able to communicate with the daemon over that unix socket.

As an alternative, you can use this daemon with a different version of libp2p as the one specified in `package.json`. You just need to define its path through an environment variable as follows:

```sh
export LIBP2P_JS=./../../js-libp2p/src/index.js
```

## Contribute

This module is actively under development. Please check out the issues and submit PRs!

## License

Licensed under either of

 * Apache 2.0, ([LICENSE-APACHE](LICENSE-APACHE) / http://www.apache.org/licenses/LICENSE-2.0)
 * MIT ([LICENSE-MIT](LICENSE-MIT) / http://opensource.org/licenses/MIT)
