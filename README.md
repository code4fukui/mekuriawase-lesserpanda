# mekuriawase-lesserpanda

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, web-based memory matching game (mekuriawase) featuring adorable lesser pandas. Flip the cards to find matching pairs and test your memory! The game board is dynamically generated using open data.

## Demo

**Play the game here: https://code4fukui.github.io/mekuriawase-lesserpanda/**

## Features

-   **Dynamic Card Generation:** Game cards are created on-the-fly from a remote CSV file of lesser panda data.
-   **Memory Challenge:** A classic 16-card (8-pair) matching game.
-   **Clear Time Tracking:** Your time is recorded and displayed in an alert upon successful completion.
-   **Replayable:** A "Retry" button lets you shuffle the cards and play again.
-   **Zero-Installation:** Runs entirely in your web browser with no setup required.

## How to Play

1.  Open the [demo link](https://code4fukui.github.io/mekuriawase-lesserpanda/).
2.  Click on any two cards to flip them over.
3.  If the lesser pandas on the cards match, they will stay face-up.
4.  If they don't match, they will flip back over after a short delay.
5.  The goal is to match all pairs as quickly as possible.

## Running Locally

To run this project on your own machine, simply clone the repository and open `index.html` in a web browser.

```bash
git clone https://github.com/code4fukui/mekuriawase-lesserpanda.git
cd mekuriawase-lesserpanda
# Open index.html in your browser
```

An internet connection is required to fetch the lesser panda data and the necessary JavaScript libraries (`shuffle.js`, `CSV.js`).

## Data Source

This game uses photos and information from the [lesserpanda-opendata](https://github.com/code4fukui/lesserpanda-opendata) project, a collection of open data about lesser pandas.

## Acknowledgements

This project is a fork and adaptation of the original "めくりあわせ" (Mekuriawase) game created by [Taisuke Fukuno (福野泰介)](http://fukuno.jig.jp/757).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.