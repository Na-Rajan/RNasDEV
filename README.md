<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
    <li><a href="#-what-is-rnasdev">🤔 What is RNasDEV?</a></li>
    <li><a href="#-why-rnasdev">🐚 Why RNasDEV?</a></li>
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<div align="center">
  <a href="https://github.com/Na-Rajan/RNasDEV/graphs/contributors"><img src="https://img.shields.io/github/contributors/Na-Rajan/RNasDEV?style=for-the-badge" alt="Contributors"></a>
  <a href="https://github.com/Na-Rajan/RNasDEV/network/members"><img src="https://img.shields.io/github/forks/Na-Rajan/RNasDEV?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/Na-Rajan/RNasDEV/stargazers"><img src="https://img.shields.io/github/stars/Na-Rajan/RNasDEV?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/Na-Rajan/RNasDEV/issues"><img src="https://img.shields.io/github/issues/Na-Rajan/RNasDEV?style=for-the-badge" alt="Issues"></a>
  <a href="https://github.com/Na-Rajan/RNasDEV/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Na-Rajan/RNasDEV?style=for-the-badge" alt="MIT License"></a>
  </br>
  <a href="https://join.slack.com/t/opendevin/shared_invite/zt-2etftj1dd-X1fDL2PYIVpsmJZkqEYANw"><img src="https://img.shields.io/badge/Slack-Join%20Us-red?logo=slack&logoColor=white&style=for-the-badge" alt="Join our Slack community"></a>
  <a href="https://discord.gg/mBuDGRzzES"><img src="https://img.shields.io/badge/Discord-Join%20Us-purple?logo=discord&logoColor=white&style=for-the-badge" alt="Join our Discord community"></a>
</div>

<details>
  <summary>🗂️ Table of Contents</summary>
  <ol>
    <li><a href="#-mission">🎯 Mission</a></li>
    <li><a href="#-what-is-devin">🤔 What is Devin?</a></li>
    <li><a href="#-why-opendevin">🐚 Why OpenDevin?</a></li>
    <li><a href="#-project-status">🚧 Project Status</a></li>
      <a href="#-get-started">🚀 Get Started</a>
      <ul>
        <li><a href="#1-requirements">1. Requirements</a></li>
        <li><a href="#2-build-and-setup">2. Build and Setup</a></li>
        <li><a href="#3-run-the-application">3. Run the Application</a></li>
        <li><a href="#4-individual-server-startup">4. Individual Server Startup</a></li>
        <li><a href="#5-help">5. Help</a></li>
      </ul>
    </li>
    <li><a href="#%EF%B8%8F-research-strategy">⭐️ Research Strategy</a></li>
    <li><a href="#-how-to-contribute">🤝 How to Contribute</a></li>
    <li><a href="#-join-our-community">🤖 Join Our Community</a></li>
    <li><a href="#%EF%B8%8F-built-with">🛠️ Built With</a></li>
    <li><a href="#-license">📜 License</a></li>
  </ol>
</details>

## 🎯 Mission

Welcome to RNasDEV, an open-source autonomous AI developer agent project by Rajan Nagarajan. RNasDEV aims to push the boundaries of AI-driven software engineering, enabling users to build, collaborate, and innovate with minimal code and maximum intelligence.

## 🚀 Vision & Roadmap

- **Multi-LLM Support:** Integrate Gemini, Claude, and local models for flexible AI backends.
RNasDEV is built on the foundation of OpenDevin (MIT License). All original contributors are credited, and the project welcomes new ideas and contributions from the open-source community.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## 🤔 What is Devin?
Devin represents a cutting-edge autonomous agent designed to navigate the complexities of software engineering. It leverages a combination of tools such as a shell, code editor, and web browser, showcasing the untapped potential of LLMs in software development. Our goal is to explore and expand upon Devin's capabilities, identifying both its strengths and areas for improvement, to guide the progress of open code models.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>


## 🐚 Why RNasDEV?
The RNasDEV project is born out of a desire to replicate, enhance, and innovate beyond the original Devin model. By engaging the open-source community, we aim to tackle the challenges faced by Code LLMs in practical scenarios, producing works that significantly contribute to the community and pave the way for future advancements. RNasDEV builds on OpenDevin and adds a unique roadmap for extensibility, collaboration, and multi-LLM support.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## 🚧 Project Status


RNasDEV is currently a work in progress, but you can already run the alpha version to see the end-to-end system in action. The project team is actively working on the following key milestones:

- **Multi-LLM Support:** Add Gemini, Claude, and local models for flexible AI backends.
    ghcr.io/na-rajan/rnasdev:main
- **Real-Time Collaboration:** Build multi-user chat and shared workspace features for team productivity.
- **Project Templates:** Provide quick-start templates for React, Django, Node.js, and other stacks.
- **Advanced Evaluation:** Implement dashboards and metrics to track agent performance and reliability.
- **Plugin Marketplace:** Enable community-driven plugins and agent extensions.
- **Security & Sandboxing:** Enhance workspace protection and safe execution.
- **Onboarding & Tutorials:** Create easy onboarding and guided flows for new users.
- **Voice & Natural Language:** Support voice command and natural language task creation.
- **Transparent Roadmap:** Document goals, features, and future plans clearly in the README and project docs.

After completing the MVP, the team will focus on research in various areas, including foundation models, specialist capabilities, evaluation, agent studies, and expanding the plugin ecosystem.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## ⚠️ Caveats and Warnings

* RNasDEV is still an alpha project. It is changing very quickly and is unstable. We are working on getting a stable release out in the coming weeks.
* RNasDEV will issue many prompts to the LLM you configure. Most of these LLMs cost money--be sure to set spending limits and monitor usage.
* RNasDEV runs `bash` commands within a Docker sandbox, so it should not affect your machine. But your workspace directory will be attached to that sandbox, and files in the directory may be modified or deleted.
* Our default Agent is currently the MonologueAgent, which has limited capabilities, but is fairly stable. We're working on other Agent implementations, including [SWE Agent](https://swe-agent.com/). You can [read about our current set of agents here](./docs/documentation/Agents.md).

## 🚀 Get Started

The easiest way to run RNasDEV is inside a Docker container.
You can run:
```powershell
# Your OpenAI API key, Gemini, Claude, or any other LLM API key
$env:LLM_API_KEY="sk-..." # or your Gemini/Claude/local model key

# The directory you want RNasDEV to modify. MUST be an absolute path!
$env:WORKSPACE_DIR="C:\Path\To\Your\Workspace"

dockerrun \
    -e LLM_API_KEY \
    -e WORKSPACE_MOUNT_PATH=$env:WORKSPACE_DIR \
    -v $env:WORKSPACE_DIR:/opt/workspace_base \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -p 3000:3000 \
    ghcr.io/opendevin/opendevin:main
```
Replace `$env:WORKSPACE_DIR` with the path to the code you want RNasDEV to work with.
See [Development.md](Development.md) for instructions on running RNasDEV without Docker.

## 🤖 LLM Backends

RNasDEV can work with any LLM backend, including OpenAI, Gemini, Claude, and local models. For a full list of supported providers and models, see the [litellm documentation](https://docs.litellm.ai/docs/providers).

The `LLM_MODEL` environment variable controls which model is used in programmatic interactions, but choosing a model in the RNasDEV UI will override this setting.

The following environment variables might be necessary for some LLMs:
* `LLM_API_KEY`
* `LLM_BASE_URL`
* `LLM_EMBEDDING_MODEL`
* `LLM_DEPLOYMENT_NAME`
* `LLM_API_VERSION`

**Note on Alternative Models:**
Some alternative models may require additional configuration. RNasDEV will soon provide LLM-specific documentation to guide you. If you've mastered the art of using a model other than OpenAI's GPT, Gemini, or Claude, please share your setup instructions with the community!

There is also [documentation for running with local models using ollama](./docs/documentation/LOCAL_LLM_GUIDE.md).

## ⭐️ Research Strategy

Achieving full replication of production-grade applications with LLMs is a complex endeavor. Our strategy involves:

1. **Core Technical Research:** Focusing on foundational research to understand and improve the technical aspects of code generation and handling.
2. **Specialist Abilities:** Enhancing the effectiveness of core components through data curation, training methods, and more.
3. **Task Planning:** Developing capabilities for bug detection, codebase management, and optimization.
4. **Evaluation:** Establishing comprehensive evaluation metrics to better understand and improve our models.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## 🤝 How to Contribute


RNasDEV is a community-driven project, and we welcome contributions from everyone. Whether you're a developer, a researcher, or simply enthusiastic about advancing the field of software engineering with AI, there are many ways to get involved:

- **Code Contributions:** Help us develop the core functionalities, frontend interface, plugin system, or sandboxing solutions.
- **Research and Evaluation:** Contribute to our understanding of LLMs in software engineering, participate in evaluating the models, or suggest improvements.
- **Feedback and Testing:** Use the RNasDEV toolset, report bugs, suggest features, or provide feedback on usability.

For details, please check [this document](./CONTRIBUTING.md).

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## 🤖 Join Our Community


Now we have both Slack workspace for the collaboration on building RNasDEV and Discord server for discussion about anything related, e.g., this project, LLM, agent, etc.

* [Slack workspace](https://join.slack.com/t/opendevin/shared_invite/zt-2etftj1dd-X1fDL2PYIVpsmJZkqEYANw)
* [Discord server](https://discord.gg/mBuDGRzzES)

If you would love to contribute, feel free to join our community (note that now there is no need to fill in the [form](https://forms.gle/758d5p6Ve8r2nxxq6)). Let's simplify software engineering together!

🐚 **Code less, make more with RNasDEV.**

[![Star History Chart](https://api.star-history.com/svg?repos=Na-Rajan/RNasDEV&type=Date)](https://star-history.com/#Na-Rajan/RNasDEV&Date)

## 🛠️ Built With


RNasDEV is built using a combination of powerful frameworks and libraries, providing a robust foundation for its development. Here are the key technologies used in the project:

![FastAPI](https://img.shields.io/badge/FastAPI-black?style=for-the-badge) ![uvicorn](https://img.shields.io/badge/uvicorn-black?style=for-the-badge) ![LiteLLM](https://img.shields.io/badge/LiteLLM-black?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-black?style=for-the-badge) ![Ruff](https://img.shields.io/badge/Ruff-black?style=for-the-badge) ![MyPy](https://img.shields.io/badge/MyPy-black?style=for-the-badge) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-black?style=for-the-badge) ![React](https://img.shields.io/badge/React-black?style=for-the-badge)

Please note that the selection of these technologies is in progress, and additional technologies may be added or existing ones may be removed as the project evolves. We strive to adopt the most suitable and efficient tools to enhance the capabilities of RNasDEV.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

## 📜 License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for more information.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

[contributors-shield]: https://img.shields.io/github/contributors/Na-Rajan/RNasDEV?style=for-the-badge
[contributors-url]: https://github.com/Na-Rajan/RNasDEV/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Na-Rajan/RNasDEV?style=for-the-badge
[forks-url]: https://github.com/Na-Rajan/RNasDEV/network/members
[stars-shield]: https://img.shields.io/github/stars/Na-Rajan/RNasDEV?style=for-the-badge
[stars-url]: https://github.com/Na-Rajan/RNasDEV/stargazers
[issues-shield]: https://img.shields.io/github/issues/Na-Rajan/RNasDEV?style=for-the-badge
[issues-url]: https://github.com/Na-Rajan/RNasDEV/issues
[license-shield]: https://img.shields.io/github/license/Na-Rajan/RNasDEV?style=for-the-badge
[license-url]: https://github.com/Na-Rajan/RNasDEV/blob/main/LICENSE
