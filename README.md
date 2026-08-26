# Pi Memorization Game

A simple browser-based game for practicing the digits of π, originally built for Gage.

## Features

- Practice π in configurable chunks of digits
- Start from a specific digit index
- Use the Hint button to reveal the next digit progressively
- Track the digits entered correctly during the current run
- Works as a single static HTML page with no build step or dependencies

## Run locally

Open `index.html` in any modern web browser.

No installation, package manager, server, framework, or other ceremony is required. Humanity occasionally gets one right.

## How it works

The game stores a sequence of π digits directly in `index.html`. Enter the requested number of digits and submit them. Correct answers advance the current position; an incorrect answer shows the expected digits and resets the run.

The challenge settings let you change the starting index and the number of digits entered per round.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
