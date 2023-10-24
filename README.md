# Loreweaver

[<img alt="github" src="https://img.shields.io/badge/maintenance%20status-actively%20developed-brightgreen?style=for-the-badge&labelColor=555555&logo=github" height="20">](https://github.com/snowmead/loreweaver)
[<img alt="github" src="https://img.shields.io/badge/github-snowmead/loreweaver-8da0cb?style=for-the-badge&labelColor=555555&logo=github" height="20">](https://github.com/snowmead/loreweaver)
[<img alt="crates.io" src="https://img.shields.io/crates/v/loreweaver.svg?style=for-the-badge&color=fc8d62&logo=rust" height="20">](https://crates.io/crates/loreweaver)
[<img alt="docs.rs" src="https://img.shields.io/badge/docs.rs-loreweaver-66c2a5?style=for-the-badge&labelColor=555555&logo=docs.rs" height="20">](https://docs.rs/loreweaver)
[<img alt="build status" src="https://img.shields.io/github/actions/workflow/status/snowmead/loreweaver/rust.yml?branch=main&style=for-the-badge" height="20">](https://github.com/snowmead/loreweaver/actions?query=branch%3Amain)

Loreweaver is a flexible out-of-the-box library designed to interact with ChatGPT, with an emphasis on managing long conversations exceeding the maximum token limit of a model, ensuring a continuous and coherent user experience.

> Check out the official [Loreweaver Discord Bot](https://github.com/snowmead/loreweaver-discord-bot) purpously built based on this library!

## Implementation

This library is a rust implementation of [OpenAI's Tactic](https://platform.openai.com/docs/guides/gpt-best-practices/tactic-for-dialogue-applications-that-require-very-long-conversations-summarize-or-filter-previous-dialogue) for handling long conversations with ChatGPT that span beyond a GPT model's maximum context token limit.

Once a certain threshold of context tokens is reached, the library will summarize the entire conversation and begin a new conversation with the summarized context appended to the system instructions.

The library is designed to be as flexible as possible, allowing you to easily integrate it into your own projects.

## Use Cases

- **Text-Based RPGs:** Crafting coherent and persistently evolving narratives and interactions in text-based role-playing games.

- **Customer Support Chatbots:** Developing chatbots that remember past user interactions and provide personalized support.

- **Educational Virtual Tutors:** Implementing AI tutors that remember student interactions and tailor assistance accordingly.

- **Healthcare Virtual Assistants:** Creating healthcare assistants that provide follow-up advice and reminders based on past user health queries.

- **AI-Driven MMO NPC Interactions:** Enhancing MMO experiences by enabling NPCs to have contextually relevant interactions with players based on past encounters.

## How to Use

Follow the [crate level documentation](https://docs.rs/loreweaver/latest/loreweaver/) for a detailed explanation of how to use the library.

## Contribution

If you are passioniate about this project, please feel free to fork the repository and submit pull requests for enhancements, bug fixes, or additional features.

## License

Loreweaver is distributed under the MIT License, ensuring maximum freedom for using and sharing it in your projects.
