# Awesome A2A (Agent-to-Agent Protocol）

> A curated list of resources, tools, libraries, and implementations for Google's Agent-to-Agent (A2A) protocol

## Contents

- [Introduction](#introduction)
- [Official Resources](#official-resources)
- [Protocol Documentation](#protocol-documentation)
- [Implementations](#implementations)
  - [Python](#python)
  - [JavaScript](#javascript)
  - [Rust](#rust)
  - [Other Languages](#other-languages)
- [Tools and Libraries](#tools-and-libraries)
- [Sample Agents](#sample-agents)
- [Tutorials and Guides](#tutorials-and-guides)
- [Articles and Blog Posts](#articles-and-blog-posts)
- [Community Resources](#community-resources)
- [Related Projects](#related-projects)
- [Presentations and Talks](#presentations-and-talks)
- [Contributing](#contributing)

## Introduction

The Agent-to-Agent (A2A) protocol is an open standard initiated by Google designed to enable seamless communication and interoperability between AI agents. Released in April 2025, it provides a standardized method for agents to discover each other's capabilities, negotiate interactions, and coordinate tasks across different frameworks and vendors. A2A is designed to complement other protocols like Anthropic's Model Context Protocol (MCP), acting as a higher-level abstraction specifically for agent-to-agent communication.

## Official Resources

- [GitHub Repository](https://github.com/google/A2A) - Official implementation and documentation of the A2A protocol
- [A2A Documentation](https://google.github.io/A2A/) - Official protocol documentation and guides
- [Official Announcement](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/) - Google's announcement of the A2A protocol

## Protocol Documentation

- [A2A Protocol Specification](https://github.com/google/A2A/blob/main/specification) - JSON specification of the A2A protocol structures
- [Core Concepts](https://github.com/google/A2A/blob/main/README.md) - Explanation of key A2A concepts: Agent Card, Server, Client, Task, Message, Artifact, Streaming, and Push Notifications

## Implementations

### Python

- [A2A Sample Client/Server (Python)](https://github.com/google/A2A/blob/main/samples/python/common) - Reference implementation of A2A client and server in Python
- [A2A CLI (Python)](https://github.com/google/A2A/blob/main/samples/python/hosts/cli/README.md) - Command-line interface for A2A in Python
- [Python A2A](https://medium.com/@the_manoj_desai/meet-google-a2a-the-protocol-that-will-revolutionize-multi-agent-ai-systems-80d55a4583ed) - Production-ready Python implementation

### JavaScript

- [A2A Sample Client/Server (JavaScript)](https://github.com/google/A2A/blob/main/samples/js/src) - Reference implementation of A2A client and server in JavaScript
- [A2A CLI (JavaScript)](https://github.com/google/A2A/blob/main/samples/js/README.md) - Command-line interface for A2A in JavaScript

### Rust

- [a2a-rs](https://github.com/EmilLindfors/a2a-rs) - Complete implementation of the A2A protocol in Rust, supporting both client and server roles with multiple transport options

### Other Languages

*This section will be populated as more implementations become available*

## Tools and Libraries

- [Multi-Agent Web App Demo](https://github.com/google/A2A) - Demo showcasing multi-agent communication via A2A
- [Google ADK](https://developers.googleblog.com/en/agent-development-kit-easy-to-build-multi-agent-applications/) - Agent Development Kit with A2A support

## Sample Agents

- [Currency Converter Agent (LangGraph)](https://github.com/google/A2A/blob/main/samples/python/agents/langgraph/README.md) - A sample A2A server that converts currencies using LangGraph
- [Image Generation Agent (CrewAI)](https://github.com/google/A2A/blob/main/samples/python/agents/crewai/README.md) - A sample A2A server that generates images using CrewAI

## Tutorials and Guides

- [First Look at A2A Protocol](https://medium.com/the-low-end-disruptor/google-a2a-a-first-look-at-another-agent-agent-protocol-cb853aa4d084) - Guide to understanding and using A2A
- [A2A: The Protocol That Will Revolutionize Multi-Agent AI Systems](https://medium.com/@the_manoj_desai/meet-google-a2a-the-protocol-that-will-revolutionize-multi-agent-ai-systems-80d55a4583ed) - Tutorial and introduction to A2A

## Articles and Blog Posts

- [Google's A2A Protocol: The Missing Lingua Franca](https://medium.com/@jenray1986/google-launching-a2a-protocol-the-missing-lingua-franca-for-a-world-of-talking-ai-agents-5e329ec7fec5) - Overview of A2A and its significance
- [Agent-to-Agent Protocol to Break Down AI Silos](https://medium.com/@hxzhouh/google-introduces-agent-to-agent-protocol-a2a-to-break-down-ai-silos-cf456e147944) - Analysis of how A2A addresses AI integration challenges
- [Google's Agent2Agent Open Protocol](https://www.infoworld.com/article/3958032/googles-agent2agent-open-protocol-aims-to-connect-disparate-agents.html) - InfoWorld article on A2A protocol
- [The Future of AI Tooling is Interoperable: MCP and Agent2Agent](https://www.vccafe.com/2025/04/10/the-future-of-ai-tooling-is-interoperable-mcp-and-agent2agent/) - Comparison between MCP and A2A protocols

## Community Resources

- [A2A Discussion on Hacker News](https://news.ycombinator.com/item?id=43631381) - Community discussion about A2A protocol
- [r/modelcontextprotocol](https://www.reddit.com/r/modelcontextprotocol/) - Subreddit with discussions on A2A and MCP

## Related Projects

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) - Complementary protocol to A2A that provides tools and context to agents
- [Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) - Google Cloud's platform with A2A support
- [omega-awesome-a2a](https://github.com/omegalabsinc/omega-awesome-a2a) - Collection of multimodal model resources related to Any-to-Any conversions

## Presentations and Talks

*This section will be populated as presentations become available*

## Contributing

### How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

### Contribution Guidelines

- Ensure your contribution is relevant to the A2A protocol
- Follow the existing format for consistency
- Provide a brief description for each added resource
- Check for duplicates before submitting
- Include proper links and attributions

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.