---
title: "Tool Calling in Spring AI 2.0: A Composable, Agentic Architecture"
url: "https://spring.io/blog/2026/06/15/spring-ai-composable-tool-calling"
date: "2026-06-15"
author: "tzolov"
feed_url: "https://spring.io/blog.atom"
---
A technical deep-dive into Spring AI 2.0's redesigned tool-calling system, which lifts the execution loop into the advisor chain as a composable, first-class component. Methods annotated with @Tool expose functionality with auto-generated JSON schemas, a recursive ToolCallingAdvisor manages the execution lifecycle, and a ToolSearchToolCallingAdvisor implements progressive tool disclosure via semantic search that reduces token cost by 34-64% when managing hundreds of tools. Spring AI 2.0 also supports consuming and exposing tools via the Model Context Protocol.
