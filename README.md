# Awesome Sonnet 5

*Unofficial community list for Claude Sonnet 5. Not affiliated with Anthropic. All trademarks belong to their owners.*

A curated list of resources for working with Claude Sonnet 5, the Anthropic model announced on June 30, 2026 and available on the Claude API as `claude-sonnet-5`. Anthropic calls it "the most agentic Sonnet model yet" and prices it at $2 per million input tokens and $10 per million output tokens. The links below come from the announcement, the platform docs and the CodeRabbit review that rank for the query; where a source names something without linking it, it appears in plain text.

> Building a product that also needs image, video or audio generation? [Try Synexa - one REST endpoint and Python SDK for FLUX, video and audio models, pay per run](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=awesome-sonnet-5&utm_content=readme-top&utm_term=tier-r).

## Official resources

- [Introducing Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5) - The launch post: positioning against Sonnet 4.6 and Opus 4.8, pricing, plan availability.
- [What's new in Claude Sonnet 5](https://platform.claude.com/docs/en/about-claude/models/whats-new-sonnet-5) - Model ID, the three behaviour changes from Sonnet 4.6, new tokenizer, tool support.
- [Claude Sonnet 5 overview](https://platform.claude.com/docs/en/models/sonnet-5/overview) - The model page in the platform docs.
- [Sonnet 5 migration guide](https://platform.claude.com/docs/en/models/sonnet-5/migration-guide) - What breaks when moving from Sonnet 4.6.
- [Claude Sonnet 5 System Card](https://www.anthropic.com/claude-sonnet-5-system-card) - The broader evaluation set the announcement points to.
- [Models overview](https://platform.claude.com/docs/en/about-claude/models/overview) - Where the announcement sends developers for `claude-sonnet-5`.
- [Pricing](https://platform.claude.com/docs/en/about-claude/pricing) - Current rates; the announcement says the $2/$10 introductory pricing was made permanent.

## Getting started

- [Try Claude](https://claude.ai/) - Sonnet 5 is the default model for Free and Pro plans and available to Max, Team and Enterprise, per the announcement.
- [CLI, SDKs, and libraries](https://platform.claude.com/docs/en/cli-sdks-libraries/overview) - Client libraries for calling the API.
- [Context windows](https://platform.claude.com/docs/en/build-with-claude/context-windows) - 1M tokens is both the default and the maximum on Sonnet 5; 128k max output.
- [Thinking](https://platform.claude.com/docs/en/build-with-claude/thinking) - Adaptive thinking is on by default; manual extended thinking now returns a 400.
- [Effort](https://platform.claude.com/docs/en/build-with-claude/effort) - The setting the launch charts vary from medium up to xhigh.
- [Model IDs and versioning](https://platform.claude.com/docs/en/about-claude/models/model-ids-and-versions) - How the `claude-sonnet-5` alias resolves.

## Tutorials and articles

- [Claude Sonnet 5 review: Should you switch?](https://www.coderabbit.ai/blog/claude-sonnet-5-review) - Hands-on review of how Sonnet 5 writes and reviews code; the verdict differs between the two.
- [Choosing a model](https://platform.claude.com/docs/en/about-claude/models/choosing-a-model) - Anthropic's guide to picking a tier.
- [Optimizing for cost and intelligence](https://platform.claude.com/docs/en/about-claude/models/optimizing-for-cost-and-intelligence) - Background for reading the cost-performance curves in the launch post.
- [Upgrade between model versions](https://platform.claude.com/docs/en/about-claude/models/migration-guide) - The family-wide migration page.
- [BrowseComp](https://arxiv.org/abs/2504.12516) - The agentic search evaluation used in the launch charts.
- [OSWorld-Verified](https://xlang.ai/blog/osworld-verified) - The computer use evaluation used in the launch charts.
- [What is code review](https://www.coderabbit.ai/guides/what-is-code-review-and-how-is-it-changing) - Context for the review half of the CodeRabbit write-up.

## Tools and integrations

- [Browser use tool](https://platform.claude.com/docs/en/agents-and-tools/tool-use/browser-use-tool) - Supported on Sonnet 5 on the Claude API and Google Cloud; not on Sonnet 4.6.
- [Computer use tool](https://platform.claude.com/docs/en/agents-and-tools/tool-use/computer-use-tool) - Sonnet 5 supports the stable `computer_toolset_20260801` version; `computer_20251124` is still accepted.
- [Service tiers](https://platform.claude.com/docs/en/api/service-tiers#supported-models) - Priority Tier is not available on Sonnet 5.
- [Claude API skill](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/claude-api-skill) - Keeps coding agents on current request shapes.
- [Release notes](https://platform.claude.com/docs/en/release-notes/overview) - Platform changes since launch.

## Alternatives

- [Synexa - hosted model API for FLUX, video and audio, pay per run](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=awesome-sonnet-5&utm_content=readme-top&utm_term=tier-r) - Not a text model; the option when the missing piece next to Sonnet 5 is media generation behind one endpoint.
- [Claude Opus 5](https://platform.claude.com/docs/en/models/opus-5/overview) - The tier above in the docs navigation.
- [Claude Fable 5.1](https://platform.claude.com/docs/en/models/fable-5-1/overview) - The top model page in the current docs.
- [Claude Haiku 4.5](https://platform.claude.com/docs/en/models/haiku-4-5/overview) - The small model in the line-up.
- Opus 4.8 - The model the launch post compares Sonnet 5 against; priced at $5/MTok input and $25/MTok output per the same post.
- Nemotron 3 Ultra - NVIDIA's open model, reviewed by CodeRabbit as "fast and to the point".

## Related

- [Anthropic news](https://www.anthropic.com/news) - Where future announcements land.
- [Model deprecations](https://platform.claude.com/docs/en/about-claude/model-deprecations) - Retirement schedule for older Sonnet versions.
- [CodeRabbit blog](https://www.coderabbit.ai/blog) - Reviews of Opus 4.8, Fable 5 and Nemotron 3 Ultra referenced in the Sonnet 5 write-up.

## Contributing

Open a pull request with a link, one line on why it belongs, and where it is referenced from.


_Last reviewed: 2026-09-22_
