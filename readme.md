# Custom Runnable Pipeline

This project is a small experiment where I tried to understand how the "Runnable concept works internally". Instead of using the built-in implementation from libraries like LangChain, I wrote my own basic version from scratch.

The goal of this project was not to build a full framework, but to learn how different components of an LLM pipeline connect and execute step by step.

## What this project shows

* How a runnable pipeline can be created manually
* How different steps in a chain pass data to the next step
* A simple structure similar to prompt → model → output parser
* Basic idea of chaining operations together

## Why I made this

While working with LLM tools, I realized that many abstractions hide the actual execution flow. I wanted to see what happens underneath, so I implemented a small runnable system myself.

This helped me understand things like:

* how inputs move through a pipeline
* how chaining works
* how different components interact

## Project Structure


runnable-from-scratch
│
├── runnable.ipynb      # main notebook with the implementation
└── README.md




## Notes

This is mainly a learning project. The implementation is intentionally simple so the core idea of runnables is easy to follow.


