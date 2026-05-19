# YewChat 💬

> Source code for [Let’s Build a Websocket Chat Project With Rust and Yew 0.19 🦀](#)

## Install

1. Install the required toolchain dependencies:
   ```npm i```

2. Follow the YewChat post!

## Branches

This repository is divided to branches that correspond to the blog post sections:

* main - The starter code.
* routing - The code at the end of the Routing section.
* components-part1 - The code at the end of the Components-Phase 1 section.
* websockets - The code at the end of the Hello Websockets! section.
* components-part2 - The code at the end of the Components-Phase 2 section.
* websockets-part2 - The code at the end of the WebSockets-Phase 2 section.

# TUTORIAL 3

## Experiment 3.1

![img.png](img.png)

Explanation: > To run the original WebChat application, I had to set up two separate environments. First, I cloned and ran the NodeJS WebSocket server which listens for incoming connections on port 8080 and handles broadcasting messages. Second, I cloned the Rust-based Yew frontend. Because Yew compiles Rust into WebAssembly (WASM), the client-side code leverages wasm-bindgen to communicate with standard Web APIs (like WebSockets and DOM manipulation) directly from Rust. When the frontend is served and opened in the browser, the user first interacts with a Login component. Upon entering a nickname, the app transitions to the Chat component, establishes a WebSocket connection to the NodeJS server, and allows the user to send and receive real-time messages in a graphical web interface.

