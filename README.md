![screenshot](./photos/splash-image.png)

This is a Connect Four game built on React. Two players will be able to use this game.

A version of this game built in Vanilla JavaScript. You can find it [here](https://github.com/Brandoncyu/connect4-vanilla).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

What things you need to install the software and how to install them

* fork and clone this repository

### Installing

Install the Node dependencies:

```shell
run npm install
```

Start the react development server:

```shell
npm start
```

## Key Features

When the game begins, you will be presented with a board that is empty. The player number and color will be on the status bar on the right.

![screenshot](./photos/empty.png)

Click the column you want to put your first piece in. It will then populate in the lowest row. The status bar will then toggle to the next player, who can then make his or her move.

![screenshot](./photos/first-move.png)

You can keep going until there is a winner. You can win by having four or more in a row horizontally, vertically, or diagnoally. When it happens, the status bar will update on the right, denoting the winner. You will not be able to make any more moves on the board.

![screenshot](./photos/splash-image.png)

If you fill up an entire column, you can still click on the same column, but you will not be able to fill it up anymore. The player will not toggle to the next one.

![screenshot](./photos/full-column.png)

When the game is over, you can hit the "Reset Game!" button on the status bar. This will empty out the board and start with the first player once again. You can also do this mid-game as well.

## Built With

* [JavaScript](https://www.javascript.com/) - The language
* [Bootstrap](https://bootstrap.com/) - The css framework used
* [React](https://reactjs.org/) - Frontend library

## Contributing

Please send me a message for details on our code of conduct, and the process for submitting pull requests.

## Author

* **Brandon Yu** - *Initial work* - [Brandoncyu](https://github.com/Brandoncyu)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
