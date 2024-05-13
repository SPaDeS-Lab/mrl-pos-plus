# MRL-PoS Blockchain

A custom MRl-POS blockchain implemented with Go.

## Installation

First, download and install Go from [here](https://go.dev/dl/). Open this project in any code editor and install the third party dependencies.

```bash
go get github.com/joho/godotenv
go get github.com/davecgh/go-spew/spew
```

## Configuring environment variables

Clone the `.env.example` file and rename it to `.env`. You can also change the address port you want to run. By default it will start using port 9000.

## Running the project

First start the TCP server

```bash
go run .
```

Then for connecting a new node/validator, open a new terminal and run the following command

```bash
nc localhost 9000
```

## License

[GNU](https://www.gnu.org/licenses/)
