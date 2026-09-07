<p align="center">
  <a href="https://pize.ai">
    <img src="assets/pize-logo.svg" width="96" height="96" alt="Pize logo" />
  </a>
</p>

<h1 align="center">pize.ai</h1>

<p align="center"><strong>AI programming for scientific computing and statistical analysis.</strong></p>
<p align="center">Understand the data. Build the analysis. Review the results.</p>

<p align="center">
  <a href="https://pize.ai">Website</a> &middot;
  <a href="https://pize.ai/docs">Documentation</a> &middot;
  <a href="https://pize.ai/download">Download</a>
</p>

<p align="center" dir="ltr">
  <a href="README.md">简体中文</a> &middot;
  <a href="README.en.md">English</a> &middot;
  <a href="README.de.md">Deutsch</a> &middot;
  <a href="README.ja.md">日本語</a> &middot;
  <a href="README.fr.md">Français</a><br />
  <a href="README.ar.md">العربية</a> &middot;
  <a href="README.es.md">Español</a> &middot;
  <a href="README.hi.md">हिन्दी</a> &middot;
  <a href="README.id.md">Bahasa Indonesia</a> &middot;
  <a href="README.ru.md">Русский</a>
</p>

---

## Built around research, not just code completion

**Pize is an AI coding assistant for researchers working with scientific code and statistical data.** It helps you understand a project, prepare an analysis, write and run code, inspect output and plots, and revise the next step. Use it in Pize Code, Positron, the CLI, or through the SDK.

Research errors often begin before a model is fitted: a misplaced delimiter, a missing value read as a number, or an observation mistaken for a header. Pize puts data understanding first, so the coding workflow starts with the structure and meaning of the inputs rather than an assumption about their contents.

This repository is Pize's public product and community home, maintained by its founder, [@guopengnaivoc](https://github.com/guopengnaivoc).

## What Pize does

| Capability | What it brings to your work |
| --- | --- |
| **Data-aware reading** | Detect delimiters, headers, missing values, and column types from file contents. Handle comments, metadata, and compressed tables. |
| **Context for large datasets** | Provide a compact data card when a file exceeds the context budget, including schema, a small preview, and explicitly estimated row counts. |
| **Live R / Python context** | In Positron, inspect the focused session and summarize data frames. Run code and retrieve plots with approval, then iterate on real output. |
| **Reviewable code changes** | Coordinate edits across files, inspect diffs, undo changes, and return to a previous task checkpoint. |
| **Planning and execution** | Explore the project in plan mode, agree on an approach, then write code and run terminal commands with approval. |
| **Project and browser context** | Reference files, folders, problems, and URLs. Use browser interactions, screenshots, and logs when debugging. |
| **Reusable conventions** | Apply project rules and skills for statistical definitions, plotting conventions, and directory structure. |

For research containers such as Parquet, Arrow, RDS, HDF5, h5ad, NumPy, SPSS, and Stata, Pize identifies the format and guides the appropriate loading code. This is distinct from decoding every binary format directly into the conversation. See the [data-reading and runtime documentation](https://pize.ai/docs) for the supported behavior and boundaries.

## Work in the environment you already use

| Interface | Use it for |
| --- | --- |
| **Pize Code** | Editor-based assistance, project context, reviewable edits, and terminal workflows. |
| **Positron** | The same agent, with access to the R or Python session you already have focused. |
| **CLI** | Working with Pize from the command line. |
| **SDK** | Embedding the agent and its data-oriented capabilities in your own programs and internal tools. |

The live session bridge is specific to Positron; it is not a promise that every interface has identical runtime access. Installation and interface details are maintained in the [official documentation](https://pize.ai/docs).

## Models and connected tools

Pize supports cloud and local model connections, including Anthropic, OpenAI, Google Gemini, DeepSeek, AWS Bedrock, and OpenRouter, as well as OpenAI-compatible endpoints. Choose a provider and configuration that fit your research environment.

**The SDK embeds Pize; MCP connects Pize to external tools.** As an MCP client, Pize can connect to compatible servers for databases, internal systems, and lab tooling. Available operations depend on the server you connect and the permissions you grant.

## Get started

1. **Choose your interface.** Start with the [official download page](https://pize.ai/download) and follow the setup instructions for your environment.
2. **Configure a model.** Connect a supported provider or local endpoint using the documented configuration.
3. **Bring your research context.** Open the project and attach the relevant script or data. In Positron, focus the session containing the data you want to analyze.
4. **Plan, approve, and iterate.** Agree on the approach, review proposed actions, then inspect the generated code, output, and plots before proceeding.

<details>
<summary><strong>Example research requests</strong></summary>

These are starting prompts, not claims of independently validated results.

- "Inspect this dataset's columns, types, and missing values before proposing an analysis."
- "Explain this R or Python pipeline and identify the assumptions I should review."
- "Help me revise this analysis script, run it after approval, and interpret the diagnostic plots."

</details>

Pize assists with the workflow; it does not replace scientific judgment. Review method assumptions and outputs before relying on a result. Data handling depends on the tools and model services you configure; consult the product's [privacy information](https://pize.ai/privacy) and your provider's policies.

## What is public here

This repository contains product information, community guidance, and the standalone [interactive protein viewer](https://guopengnaivoc.github.io/pize.ai/). The viewer is a visual demonstration, not a protein-prediction service or evidence of validated scientific results. Its data attribution is documented in [protein credits](assets/protein-CREDITS.md).

**Pize's core application source code is not published in this repository.** The public viewer does not make the full product open source. Selected tools, examples, and technical notes may be published separately in the future, with their own scope and licensing. Use the official website for software downloads and current availability.

## Founder, feedback, and collaboration

Pize is founded and maintained by [@guopengnaivoc](https://github.com/guopengnaivoc), publishing under the name **pize.ai**. The website is the product entry point; this repository is where public project information and community feedback come together.

- **Product questions and feature requests:** open a [GitHub issue](https://github.com/guopengnaivoc/pize.ai/issues).
- **Useful bug reports:** describe your environment, the task, expected behavior, actual behavior, and a minimal example. See [contribution guidance](CONTRIBUTING.md).
- **Collaboration, lab use, or private inquiries:** choose the appropriate email address below.

Do not post API keys, credentials, private datasets, or confidential research in public issues. For current product capabilities and setup details, refer to [pize.ai](https://pize.ai) and its [documentation](https://pize.ai/docs).

## Contact Pize

Click an address to open your email app with a suggested subject. These addresses are published on the [official contact page](https://pize.ai/contact).

| Contact | For | Email |
| --- | --- | --- |
| **General inquiries** | Product questions, media requests, and release updates. | [hello@pize.ai](mailto:hello@pize.ai?subject=Pize%20general%20inquiry) |
| **Product contact** | Product demos, implementation questions, and collaborations. | [contact@pize.ai](mailto:contact@pize.ai?subject=Pize%20product%20inquiry) |
| **Technical support** | Account, documentation, privacy, and data deletion requests. | [support@pize.ai](mailto:support@pize.ai?subject=Pize%20support%20request) |
| **Business and partnerships** | Purchasing, research partnerships, and commercial inquiries. | [business@pize.ai](mailto:business@pize.ai?subject=Pize%20business%20inquiry) |
