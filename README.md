# Awesome WebMCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for **WebMCP** — the W3C browser-native standard that lets websites expose structured tools directly to AI agents via `navigator.modelContext`.

WebMCP was launched as a W3C Draft Community Group Report on **February 10, 2026** and shipped as an early preview in **Chrome 146 Canary** behind the `chrome://flags/#enable-webmcp-testing` flag.

---

## Contents

- [Official Resources](#official-resources)
- [Specification & Explainers](#specification--explainers)
- [SDKs & Libraries](#sdks--libraries)
- [Chrome Extensions & DevTools](#chrome-extensions--devtools)
- [Demos & Examples](#demos--examples)
- [Tutorials & Guides](#tutorials--guides)
- [Videos](#videos)
- [Articles & Blog Posts](#articles--blog-posts)
- [X (Twitter) Threads](#x-twitter-threads)
- [Platform Integrations](#platform-integrations)
- [Tools & Utilities](#tools--utilities)

---

## Official Resources

- [WebMCP Early Preview – Chrome for Developers](https://developer.chrome.com/blog/webmcp-epp) — Official Chrome blog announcing the early preview in Chrome 146 Canary.
- [When to use WebMCP and MCP – Chrome for Developers](https://developer.chrome.com/blog/webmcp-mcp-usage) — Official Chrome blog post explaining when to choose WebMCP (ephemeral browser interactions) versus MCP (persistent server-side needs).
- [W3C WebMCP Spec](https://webmachinelearning.github.io/webmcp/) — Official W3C Draft Community Group Report (Web Machine Learning Community Group).
- [webmachinelearning/webmcp](https://github.com/webmachinelearning/webmcp) — The official spec repository on GitHub.
- [WebMCP Inspector – Chrome Web Store](https://chromewebstore.google.com/detail/webmcp-inspector/ddmnodehiebeklbngpeeghmcohomfimd) — Official Chrome extension to test and inspect WebMCP tools on any page.

## Specification & Explainers

- [WebMCP updates, clarifications, and next steps](https://patrickbrosset.com/articles/2026-02-23-webmcp-updates-clarifications-and-next-steps/) — Detailed update by Patrick Brosset (Microsoft Edge team), one of the spec co-authors.
- [WebMCP: Official W3C Standard for AI Agent Browser Interaction](https://webmcp.link/) — Community landing page with spec overview.
- [WebMCP in 2026: Which Browsers Support navigator.modelContext?](https://dev.to/ai-agent-economy/webmcp-in-2026-which-browsers-support-navigatormodelcontext-complete-compatibility-status-1oe4) — Browser compatibility status overview on DEV Community.
- [Choose the right AI protocol: WebMCP vs MCP](https://x.com/ChromiumDev/status/2032460022265827793) — Chrome for Developers explanation of when to use WebMCP (ephemeral browser) vs MCP (persistent server-side).

## SDKs & Libraries

- [WebMCP-org/npm-packages](https://github.com/WebMCP-org/npm-packages) — NPM packages for MCP-B: transport layers, React hooks, and browser tools for the Model Context Protocol.
- [@mcp-b/react-webmcp](https://www.npmjs.com/package/@mcp-b/react-webmcp) — React hooks for exposing tools via WebMCP in React apps.
- [@mseep/webmcp](https://www.npmjs.com/package/@mseep/webmcp) — Lightweight WebMCP implementation for the browser.
- [MiguelsPizza/WebMCP](https://github.com/MiguelsPizza/WebMCP) — Bringing the power of MCP to the web; one of the early polyfill implementations.
- [keak-ai/webmcp-core](https://github.com/keak-ai/webmcp-core) — Auto-generate WebMCP tool definitions for any existing website.
- [GoogleChromeLabs/webmcp-tools](https://github.com/GoogleChromeLabs/webmcp-tools) — Official Chrome Labs tooling for WebMCP development.

## Chrome Extensions & DevTools

- [WebMCP – Model Context Tool Inspector](https://chromewebstore.google.com/detail/webmcp-model-context-tool/gbpdfapgefenggkahomfgkhfehlcenpd) — Inspect, monitor, and execute tools exposed via `navigator.modelContext`; shows full JSON schema and lets you run tools from the DevTools panel.
- [beaufortfrancois/model-context-tool-inspector](https://github.com/beaufortfrancois/model-context-tool-inspector) — Source code for the Model Context Tool Inspector Chrome extension.
- [WebMCP-org/chrome-devtools-quickstart](https://github.com/WebMCP-org/chrome-devtools-quickstart) — Minimal quickstart demo for using Chrome DevTools MCP with WebMCP tools.
- [Chrome DevTools (MCP) for your AI agent – Chrome for Developers](https://developer.chrome.com/blog/chrome-devtools-mcp) — Official blog post introducing the Chrome DevTools MCP server that lets coding agents (Claude, Cursor, Copilot, Gemini) control and inspect a live Chrome instance.
- [ChromeDevTools/chrome-devtools-mcp – GitHub](https://github.com/ChromeDevTools/chrome-devtools-mcp) — Official Chrome DevTools MCP server that gives AI coding assistants access to network analysis, console logs, performance tracing, and browser automation via Puppeteer.
- [Web MCP: Browser MCP Service – Chrome Web Store](https://chromewebstore.google.com/detail/web-mcp-browser-mcp-servi/acdlpjcmkabbmhpibedepbfdankiagoc) — Chrome extension that exposes browser automation capabilities as an MCP server, enabling AI agents to control the browser directly.

## Demos & Examples

- [WebMCP-org/examples](https://github.com/WebMCP-org/examples) — Production-ready MCP-B browser-native MCP implementation examples.
- [WebMCP-org/webmcp-sh](https://github.com/WebMCP-org/webmcp-sh) — Web-based MCP playground for testing and developing MCP servers and clients in the browser.
- [Halmob Contact Page – Live WebMCP Example](https://halmob.com/contact) — Real-world contact form with WebMCP implemented; AI agents on Chrome 146+ can discover and submit it via both declarative and imperative pathways.
- [nearform/web-agents – GitHub](https://github.com/nearform/web-agents) — Agents in the browser combining WebMCP and Chrome's Prompt API to demonstrate how a local on-device model can interact with page-level WebMCP tools.

## Tutorials & Guides

- [WebMCP Tutorial: Building Agent-Ready Websites With Chrome's New Standard – DataCamp](https://www.datacamp.com/tutorial/webmcp-tutorial) — Practical step-by-step tutorial covering both the declarative (HTML) and imperative (JS) APIs.
- [How to Make Your Website Agent-Ready With WebMCP – ivanturkovic.com](https://www.ivanturkovic.com/2026/02/23/webmcp-tutorial-make-website-agent-ready/) — Beginner-friendly walkthrough for making a website WebMCP-ready.
- [How to make your website agent-ready with Google's Web MCP – LogRocket](https://blog.logrocket.com/google-web-mcp/) — Practical implementation guide from the LogRocket engineering blog.
- [Test WebMCP Tools with Chrome Model Context Inspector – MCPcat](https://mcpcat.io/guides/test-webmcp-tools-model-context-inspector/) — Guide to testing your WebMCP tool definitions using the inspector extension.
- [How to Implement WebMCP: A Step-by-Step Guide with Best Practices for Chrome 146+ – Halmob](https://halmob.com/blog/implementing-webmcp-chrome-146) — Practical Next.js walkthrough covering declarative HTML attributes, imperative `navigator.modelContext.registerTool()`, manifest discovery, and common pitfalls.

## Videos

- [Wes Bos – 15-min WebMCP Explainer (X)](https://x.com/wesbos/status/2023418509330387315) — Quick video walkthrough of the proposal: exposing tools via HTML form attributes and JavaScript schemas.

## Articles & Blog Posts

- [WebMCP is available for early preview – VentureBeat](https://venturebeat.com/infrastructure/google-chrome-ships-webmcp-in-early-preview-turning-every-website-into-a) — In-depth coverage of Chrome 146 WebMCP early preview.
- [WebMCP turns any Chrome web page into an MCP server for AI agents – The New Stack](https://thenewstack.io/webmcp-chrome-ai-agents/) — Architecture-focused overview.
- [WebMCP explained: How browser agents can call web tools without scraping the DOM – Scalekit](https://www.scalekit.com/blog/webmcp-the-missing-bridge-between-ai-agents-and-the-web) — Deep-dive into the protocol design and comparison with DOM scraping.
- [Chrome's WebMCP Early Preview: the end of "AI agents clicking buttons" – DEV Community](https://dev.to/axrisi/chromes-webmcp-early-preview-the-end-of-ai-agents-clicking-buttons-b6e) — Developer perspective on why WebMCP matters.
- [Chrome WebMCP: The Complete 2026 Guide to AI Agent Protocol – DEV Community](https://dev.to/czmilo/chrome-webmcp-the-complete-2026-guide-to-ai-agent-protocol-1ae9) — Comprehensive guide covering both APIs, use cases, and browser support.
- [WebMCP: Making the Web AI-Agent Ready – DEV Community](https://dev.to/sunny7899/webmcp-making-the-web-ai-agent-ready-5152) — Focused on practical integration for existing sites.
- [WebMCP (Web Model Context Protocol): Agents are learning to browse better – Medium](https://abvijaykumar.medium.com/webmcp-web-model-context-protocol-agents-are-learning-to-browse-better-22fcefc981d7) — Overview of the standard's benefits over vision-based browsing.
- [Google AI Introduces the WebMCP – MarkTechPost](https://www.marktechpost.com/2026/02/14/google-ai-introduces-the-webmcp-to-enable-direct-and-structured-website-interactions-for-new-ai-agents/) — ML-focused coverage of the WebMCP announcement.
- [WebMCP explained: Inside Chrome 146's agent-ready web preview – Search Engine Land](https://searchengineland.com/webmcp-explained-inside-chrome-146s-agent-ready-web-preview-470630) — SEO & search perspective on how WebMCP affects discoverability.
- [WebMCP: make your website agent-ready for AI in 2026 – Vydera](https://vydera.com/en/lab/webmcp-site-agent-ready-visibility) — Business and visibility angle of adopting WebMCP.
- [WebMCP Is Coming: How AI Agents Will Reshape the Web – ivanturkovic.com](https://www.ivanturkovic.com/2026/02/15/webmcp-is-coming-how-ai-agents-will-reshape-the-web/) — Early analysis of WebMCP's broader implications for how AI agents will interact with the web.
- [WebMCP: How Websites Will Expose Tools to AI Agents – Zuplo](https://zuplo.com/blog/what-is-webmcp) — API-developer perspective on WebMCP's tool-exposure model and how it compares to traditional REST APIs.
- [WebMCP: Turning web pages into tools for AI agents – Nearform](https://nearform.com/digital-community/webmcp-turning-web-pages-into-tools-for-ai-agents/) — Engineering deep-dive into turning frontend web apps into agentic tools with the declarative and imperative APIs.
- [What Is WebMCP? A Practical Guide to the Web Model Context Protocol – Webfuse](https://www.webfuse.com/blog/what-is-webmcp-the-practical-guide-to-the-web-model-context-protocol) — Practical guide to understanding and implementing WebMCP on existing sites.
- [Google Chrome Launches WebMCP in Early Preview for AI Agent Interactions – eWeek](https://www.eweek.com/news/google-webmcp-chrome-ai-web-standard-preview/) — Enterprise tech coverage of the WebMCP early preview launch.
- [WebMCP: What It Is, Why It Matters, and What to Do Now – Semrush](https://www.semrush.com/blog/webmcp/) — SEO and digital-marketing perspective; explains why sites that adopt WebMCP early will have a compounding advantage in agentic search.
- [Chrome Just Dropped Web MCP (and That's Kind of a Big Deal) – DEV Community](https://dev.to/infoxicator/chrome-just-dropped-web-mcp-and-thats-kind-of-a-big-deal-4fa2) — Hands-on developer reaction covering the architectural significance of WebMCP vs DOM-scraping approaches.
- [Browser Run: give your agents a browser – Cloudflare Blog](https://blog.cloudflare.com/browser-run-for-ai-agents/) — Cloudflare's announcement of Browser Run (formerly Browser Rendering) with native WebMCP support for running AI agents against live Chrome beta instances.
- [WebMCP Is AWESOME: Browser-Native Tools for AI Agents – Medium](https://medium.com/@springmusk/webmcp-is-awesome-browser-native-tools-for-ai-agents-53bf10f2f520) — Enthusiast overview of WebMCP's declarative and imperative APIs with practical examples.

## X (Twitter) Threads

- [Chrome for Developers – Declarative API deep-dive 🧵](https://x.com/ChromiumDev/status/2024932531032789187) — Thread covering the HTML-based declarative API for form-based tasks.
- [Maximiliano Firtman – Chrome 146 WebMCP flag walkthrough](https://x.com/firt/status/2020903127428313461) — Hands-on look at enabling and testing WebMCP in Chrome Canary.
- [Liad Yosef – "WebMCP is here 🤯"](https://x.com/liadyosef/status/2021151526375268643) — Developer reaction and analysis of how WebMCP complements MCP Apps.
- [Carlos Azaustre – "Google acaba de meter MCP dentro de Chrome"](https://x.com/carlosazaustre/status/2021246897868980307) — Spanish-language technical breakdown of `navigator.modelContext.registerTool()`.
- ["MCP Servers Are Coming to the Web" – Philipp Schmid](https://x.com/_philschmid/status/2021289121570775333) — Hugging Face TL explains how WebMCP brings server-side MCP ideas to the frontend without needing a separate server.
- [Eiji Kitamura – Japanese overview of WebMCP APIs](https://x.com/agektmr/status/2021485868507332761) — Summary in Japanese of declarative and imperative APIs.
- [Japanese deep-dive: ブラウザがMCPサーバーになる – Mojofull](https://x.com/furoku/status/2021380025895846218) — Technical breakdown in Japanese of how WebMCP turns the browser into an MCP server and what it means for frontend engineers.
- [Sheing Ng – 15-second demo + setup steps](https://x.com/sashimikun_void/status/2021474668805526009) — Step-by-step: download Canary, enable flag, install extension, see it work.
- [am.will – WebMCP controlling main Chrome instance](https://x.com/LLMJunky/status/2036854508597432826) — Demo of using WebMCP on a live, non-sandboxed browser session.

## Platform Integrations

- [Cloudflare Browser Run adds WebMCP support – Changelog](https://developers.cloudflare.com/changelog/post/2026-04-15-br-webmcp/) — April 15, 2026 changelog entry: Cloudflare Browser Run gains WebMCP support, letting agents call `navigator.modelContextTesting.listTools()` and `executeTool()` on WebMCP-enabled pages via a Chrome beta pool.
- [WebMCP – Cloudflare Browser Run docs](https://developers.cloudflare.com/browser-run/features/webmcp/) — Official Cloudflare documentation for using WebMCP within Browser Run sessions; covers tool discovery, execution, and human-in-the-loop confirmations.

## Tools & Utilities

- [WebMCP Checker](https://webmcp-checker.com/) — Free online tool to check if any website exposes WebMCP tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
