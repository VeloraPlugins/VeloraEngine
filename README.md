# VeloraEngine

VeloraEngine is the shared core library for Velora Paper plugins. It provides common utilities, command helpers, configuration tooling, messaging support, coroutine integration, and other reusable systems used across the Velora plugin ecosystem.

Its purpose is to reduce duplicated code between plugins and provide a clean, consistent development base for Velora-powered Minecraft servers.

A core goal of VeloraEngine and the Velora plugin ecosystem is to be built around a fully async-first approach wherever possible. Our aim is to keep plugins modern, efficient, and scalable by moving heavy work away from the main server thread while still remaining safe and compatible with Paper.

## Features

- Shared Paper plugin base utilities
- Common command framework integration
- Configuration helpers and serializers
- Messaging and component utilities
- Coroutine-friendly plugin support
- Async-first development philosophy
- Reusable internal systems for Velora plugins

## Notes

- VeloraEngine is a dependency/library project for other Velora plugins
- It is not designed to be a standalone gameplay plugin
- Server owners should only install it when required by another Velora plugin
- Velora plugins are designed with an async-first mindset wherever possible

## Support

For support, questions, or bug reports, please open an issue in this repository or join our Discord support server.

**Discord:** https://discord.gg/UEW3AJnMqx
