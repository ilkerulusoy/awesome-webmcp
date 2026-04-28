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
- [The Complete Agentic Web Standards Map 2026: WebMCP, MCP, LLMFeed, and Beyond – WellKnownMCP](https://wellknownmcp.org/en/news/2026-02-15-agentic-web-standards-map-2026-complete-guide) — Comprehensive map of the three-layer AI protocol stack (MCP for tools, A2A for agents, WebMCP for web access) showing how WebMCP fits into the broader agentic web ecosystem.

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
- [hangwin/mcp-chrome – GitHub](https://github.com/hangwin/mcp-chrome) — Chrome extension-based MCP server that exposes browser functionality (automation, content analysis, semantic search) to AI assistants like Claude; community-built complement to the official Chrome DevTools MCP.

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
- [Build Your First WebMCP Application (Step-by-Step Developer Tutorial) – DEV Community](https://dev.to/salamexperts/build-your-first-webmcp-application-step-by-step-developer-tutorial-291o) — Hands-on walkthrough registering tools with both declarative and imperative APIs from scratch.
- [WebMCP and WebAI: Exploring native AI tools in Chrome – DEV Community](https://dev.to/kevin-uehara/webmcp-and-webai-exploring-native-ai-tools-in-chrome-4ocf) — Side-by-side look at WebMCP and Chrome's built-in AI (Prompt API / WebAI) and how they complement each other.
- [Implementing WebMCP on a Recruitment Website – DEV Community](https://dev.to/richardbaxter/implementing-webmcp-on-a-recruitment-website-19a) — Real-world case study wiring up WebMCP tools on an actual recruitment site; useful domain-specific reference beyond e-commerce examples.

## Videos

- [Wes Bos – 15-min WebMCP Explainer (X)](https://x.com/wesbos/status/2023418509330387315) — Quick video walkthrough of the proposal: exposing tools via HTML form attributes and JavaScript schemas.

## Articles & Blog Posts

- [WebMCP is available for early preview – VentureBeat](https://venturebeat.com/infrastructure/google-chrome-ships-webmcp-in-early-preview-turning-every-website-into-a) — In-depth coverage of Chrome 146 WebMCP early preview.
- [Google previews WebMCP, a new protocol for AI agent interactions – Search Engine Land](https://searchengineland.com/google-releases-preview-of-webmcp-how-ai-agents-interact-with-websites-469024) — Search Engine Land's initial launch coverage of the WebMCP early preview program announcement.
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
- [Google Chrome Releases Early Preview Of WebMCP – Search Engine Roundtable](https://www.seroundtable.com/google-webmcp-40918.html) — Search marketing community coverage; includes Dan Petrovic's take that WebMCP is the biggest shift in technical SEO since structured data.
- [Chrome's Built-In MCP Server: Use It in Your Workflow – ComputeLeap](https://www.computeleap.com/blog/chrome-built-in-mcp-server-native-mcp-v2-2026/) — Practical guide to integrating Chrome's native MCP (WebMCP + Chrome DevTools MCP) into AI-powered developer workflows.
- [WebMCP – a much needed way to make agents play with rather than against the web – Christian Heilmann](https://christianheilmann.com/2026/02/16/webmcp-a-much-needed-way-to-make-agents-play-with-rather-than-against-the-web/) — Influential developer advocate (ex-Mozilla, ex-Microsoft) argues that WebMCP repairs the predatory relationship between agentic AI and the web by giving agents a structured contract instead of forcing them to impersonate human users.
- [Google's WebMCP Protocol: Everything You Need To Know – Dataconomy](https://dataconomy.com/2026/02/25/google-webmcp-protocol-everything-you-need-to-know/) — Comprehensive overview from a data and tech journalism angle covering the spec history, API design, and enterprise implications.
- [WebMCP Security: Why Every Browser Session Is About to Carry More Power – Valence Security](https://www.valencesecurity.com/resources/blogs/webmcp-browser-security) — Security-focused analysis explaining why WebMCP dramatically expands the blast radius of a compromised browser session and what SaaS security teams should watch for.
- [WebMCP in Early Preview: Google Prepares for the Era of Agentic AI – Delante](https://delante.co/webmcp-in-early-preview/) — SEO/SEM agency perspective covering how WebMCP changes technical SEO, structured data strategies, and organic visibility for sites that adopt it early.
- [WebMCP: A New Contract Between AI Agents and Websites – DEV Community](https://dev.to/playfulprogramming/webmcp-a-new-contract-between-ai-agents-and-websites-4g07) — Conceptual deep-dive into how WebMCP redefines the relationship between web apps and autonomous agents.
- [Future of Internet Crawling: WebMCP – DEV Community](https://dev.to/devanshhh/future-of-internet-crawling-webmcp-m95) — Explores how WebMCP could replace traditional web crawling and scraping for AI-driven data collection.
- [Implementing WebMCP: letting AI agents interact with my website – Richard MacManus](https://ricmac.org/2026/03/11/webmcp-ai-agents-interact-website/) — ReadWriteWeb founder documents a hands-on March 2026 implementation of both MCP-B and native WebMCP on a personal WordPress site, including real tool registrations.
- [The Agentic Web: how AI systems will change websites – Richard MacManus](https://ricmac.org/2026/04/07/the-agentic-web/) — April 2026 analysis placing WebMCP within the broader agentic web shift; explores how websites must evolve beyond human-facing UIs.
- [WebMCP: Making the Web Deterministic for AI Agents – Medium](https://senoritadeveloper.medium.com/webmcp-making-the-web-deterministic-for-ai-agents-9f42dba425a3) — Nil Seri's engineering-focused take on how WebMCP replaces probabilistic DOM guessing with deterministic, schema-driven agent interactions.
- [Google Chrome Ships WebMCP, Turning Websites Into AI Agent Tools – WinBuzzer](https://winbuzzer.com/2026/02/13/google-chrome-webmcp-early-preview-ai-agents-xcxwbn/) — Enterprise Windows-focused news coverage of the WebMCP early preview launch.
- [WebMCP Explained: How AI Agents Will Interact Directly with Websites – Locomotive Agency](https://locomotive.agency/blog/webmcp-ai-agents-website-functions/) — Digital-agency perspective on the protocol design and what it means for teams building client sites.
- [Google previews WebMCP, a new protocol for AI agent interactions – Search Engine Land](https://searchengineland.com/google-releases-preview-of-webmcp-how-ai-agents-interact-with-websites-469024) — Primary announcement coverage by Search Engine Land, quoting Google's André Cipriani Bandarra on how WebMCP gives agents a standard way to perform structured actions on any site.
- [What Is WebMCP? The Web Standard That Makes Your Website AI-Agent Ready – Searchable](https://www.searchable.com/blog/what-is-webmcp) — Concise explainer covering the W3C draft, declarative vs. imperative APIs, and practical steps for making an existing site agent-ready.

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
- [Glenn Gabe – "This is a big deal. Agents can bypass the UI via WebMCP"](https://x.com/glenngabe/status/2021582770326159477) — SEO professional's reaction to the early preview; highlights the significance of agents being able to skip the human UI layer entirely.
- ["Arranca la era del Frontend para agentes con WebMCP" – Maximiliano Firtman](https://x.com/maxifirtman/status/2021189001365877180) — Spanish-language thread heralding the dawn of agent-first frontend development with WebMCP.
- [Chinese overview: 當大家都重新打造給 AI 看的標準 – fox hsiao](https://x.com/pirrer/status/2022591448781328608) — Chinese-language breakdown of WebMCP as a standard for AI agents, comparing it to existing site interaction models.
- [Polish technical summary of WebMCP – Leszek Bukowski](https://x.com/LeszBuk/status/2021290109417439642) — Polish-language thread on WebMCP as a new AI-agent interface that could replace the traditional human-facing UI.
- [Miguel Ángel Durán – "¡La web va a cambiar para siempre con WebMCP!"](https://x.com/midudev/status/2021599130624143689) — High-reach Spanish-language thread by popular dev educator midudev contrasting WebMCP's structured tools with fragile DOM scraping.
- [Glenn Gabe – "This is a big deal. Agents can bypass the UI via WebMCP"](https://x.com/glenngabe/status/2021582770326159477) — SEO and technical marketing perspective from a leading search expert on WebMCP's implications for search.
- [Natzir – Spanish live demo thread 🤖](https://x.com/natzir9/status/2022255092099846606) — 7-part Spanish-language thread with a hands-on demo showing WebMCP in action on a real Chrome Canary instance.
- [Korean WebMCP summary – GeekNews](https://x.com/GeekNewsHada/status/2021397735824556326) — Korean-language summary of WebMCP covering how it lets websites self-describe capabilities to AI agents instead of relying on DOM scraping.

## Platform Integrations

- [Cloudflare Browser Run adds WebMCP support – Changelog](https://developers.cloudflare.com/changelog/post/2026-04-15-br-webmcp/) — April 15, 2026 changelog entry: Cloudflare Browser Run gains WebMCP support, letting agents call `navigator.modelContextTesting.listTools()` and `executeTool()` on WebMCP-enabled pages via a Chrome beta pool.
- [WebMCP – Cloudflare Browser Run docs](https://developers.cloudflare.com/browser-run/features/webmcp/) — Official Cloudflare documentation for using WebMCP within Browser Run sessions; covers tool discovery, execution, and human-in-the-loop confirmations.
- [Microsoft Edge 147 Web Platform Release Notes – Microsoft Learn](https://learn.microsoft.com/en-us/microsoft-edge/web-platform/release-notes/147) — Official April 2026 Edge 147 release notes documenting WebMCP support landing in Microsoft's browser alongside Chrome.

## Tools & Utilities

- [WebMCP Checker](https://webmcp-checker.com/) — Free online tool to check if any website exposes WebMCP tools.
- [WebMCP Cheat Sheet – Webfuse](https://www.webfuse.com/webmcp-cheat-sheet) — Quick-reference card covering the full W3C Browser AI Tool API: declarative HTML attributes, imperative `navigator.modelContext` calls, manifest format, and common pitfalls.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
