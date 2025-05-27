# koog-ai-chat-with-tools-demo

[Koog](https://docs.koog.ai/) is a Kotlin-based framework designed to build and run AI agents entirely in idiomatic Kotlin. It lets you create agents that can interact with tools, handle complex workflows, and communicate with users.

The framework offers two main approaches:

Simple API: A high-level, user-friendly interface that lets you quickly create single-run agents with minimal configuration.
AI Agent: A more flexible, full-featured framework for building custom agents with advanced capabilities.


The Simple API provides an easy way to create and run AI agents. It offers an interface that lets you create single-run agents with customizable tools and configurations.

A single-run agent processes a single input and provides a response. This agent can return either a message or a tool result. The tool result is returned if the tool registry is provided to the agent.

Model used: `gemini-2.0-flash`
website: https://aistudio.google.com/apikey