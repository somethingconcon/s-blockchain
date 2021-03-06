# s-blockchain
[![Build Status](https://travis-ci.org/sungjk/s-blockchain.svg?branch=master)](https://travis-ci.org/sungjk/s-blockchain)

Minimal and Simple blockchain implementation in Scala with Netty

## API Endpoint Reference
| METHOD | ENDPOINT | USAGE | DESCRIPTION |
|--------|----------|-------|-------------|
| GET | /mine | mine by running proof of work mining to validate new blocks  |
| GET | /chain | return the chain stored in the current node |
| GET | /nodes | get the list of nodes participating in the mining |
| POST | /messages/new | add a new message to the current node |
| POST | /nodes/join |  join the block chain |


## Getting Started

```shell
$ sbt "project app" run
```

### Prerequisites

* **Make sure you have Scala installed:**

````shell
$ brew install scala
````

Or visit [http://www.scala-lang.org/download/](http://www.scala-lang.org/download/) for alternative ways.

* **Install Scala Build Tool:**

```shell
$ brew install sbt
```

Or visit [http://www.scala-sbt.org/download.html](http://www.scala-sbt.org/download.html) to see more.

## Built With

* [Netty](http://netty.io/) - Binds the core library to a Netty channel handler and provides an embedded server.
* [json4s](http://json4s.org/) - Provides extractors for working with jsonp and transforming json request bodies.

## Authors

* **Jeremy Kim** - *Initial work* - [sungjk](https://github.com/sungjk)

See also the list of [contributors](https://github.com/sungjk/s-blockchain/contributors) who participated in this project.

# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
