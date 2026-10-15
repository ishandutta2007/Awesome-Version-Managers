# Awesome-Version-Managers

## Top Version Managers Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Language Runtime Managers, Multi-Tool Version Switching, shims & Per-Project Toolchains*  

**Last updated: October 2026**



This repository tracks notable **hosted offerings** and **open-source projects** for **Version Managers**. These tools install and switch language runtimes and CLIs—Node, Python, Ruby, Java, and many others—per user or per project.



**Examples** include nvm, rbenv, pyenv, SDKMAN!, asdf, Volta, fnm, RVM, jenv, GVM, and **asdf** (`asdf-vm/asdf`)—an extendable version manager for multiple languages and tools.



**Open-source emphasis**: Version managers are almost entirely open source. **asdf**, **nvm**, **pyenv**, **rbenv**, **fnm**, **Volta**, and **SDKMAN!** are the daily drivers for millions of developers. This section is the primary focus and is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cloud IDEs & managed runtimes (GitHub Codespaces, Gitpod, Replit)](https://github.com/features/codespaces)**  

  Hosted development environments that provision language versions for you—less “version manager,” more environment-as-a-service.



- **[Language vendor cloud builds (e.g. managed Node/Python images on PaaS)](https://www.heroku.com/)**  

  Platforms that pin runtimes via buildpacks or container images rather than local version managers.



- **[Commercial support around open toolchains](https://sdkman.io/)**  

  Limited commercial packaging or support offerings; core version managers remain open.



- **[Other hosted developer environments](https://gitpod.io/)**  

  Additional cloud workspaces that abstract local runtime management.



## Open-Source GitHub Projects



### Multi-Language Managers



- **[asdf](https://github.com/asdf-vm/asdf)**  

  Extendable open version manager—one tool for Node, Python, Ruby, Terraform, and hundreds of plugins via a consistent CLI.



- **[mise (formerly rtx)](https://github.com/jdx/mise)**  

  Fast open polyglot version manager—asdf-compatible plugins with improved UX and performance.



- **[proto](https://github.com/moonrepo/proto)**  

  Open multi-toolchain version manager from the moonrepo ecosystem—unified installs for many languages.



### Language-Specific Managers



- **[nvm (Node Version Manager)](https://github.com/nvm-sh/nvm)**  

  Classic open shell-based manager for installing and switching Node.js versions.



- **[fnm](https://github.com/Schniz/fnm)**  

  Fast open Node version manager written in Rust—compatible workflows with better performance than pure shell nvm.



- **[Volta](https://github.com/volta-cli/volta)**  

  Open Node toolchain manager—pins Node/npm/yarn per project with seamless shims.



- **[pyenv](https://github.com/pyenv/pyenv)**  

  Open Python version manager—install and switch CPython and alternative builds with virtualenv integration helpers.



- **[rbenv](https://github.com/rbenv/rbenv)**  

  Lightweight open Ruby version manager—shim-based switching (often paired with ruby-build).



- **[RVM](https://github.com/rvm/rvm)**  

  Full-featured open Ruby version manager—gemsets and broader environment isolation.



- **[SDKMAN!](https://github.com/sdkman/sdkman-cli)**  

  Open manager for JVMs and related SDKs—Java, Groovy, Kotlin, Maven, Gradle, and more.



- **[jenv](https://github.com/jenv/jenv)**  

  Open Java version switcher—manage multiple JDKs on a single machine.



- **[gvm / goenv](https://github.com/go-nv/goenv)**  

  Open Go version managers for installing and selecting Go toolchains.



- **[rustup](https://github.com/rust-lang/rustup)**  

  Official open Rust toolchain installer and version manager.



- **[phpenv / phpbrew](https://github.com/phpbrew/phpbrew)**  

  Open PHP version management tools for multiple concurrent PHP installs.



### Additional Strong Open-Source Options



- **One manager for everything**: asdf or mise.

- **Node-focused**: fnm or Volta (or nvm for maximum familiarity).

- **Python**: pyenv.

- **Ruby**: rbenv or RVM.

- **JVM**: SDKMAN! / jenv.

- **Rust**: rustup.

- **Composable stacks**: asdf/mise in dotfiles → `.tool-versions` per repo → CI images matching local pins.

- Hosted IDEs reduce local manager need but still benefit from the same version pins in project files.



**Frameworks for building custom systems**:  

**asdf** or **mise** as the default polyglot choice; language-native managers when you want the deepest ecosystem fit.  

Fully open version management is the universal standard for local development toolchains.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's hosted/SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Version managers execute install scripts and modify your shell—review plugins and install from trusted sources. Pin versions in projects for reproducible builds.

- Open-source managers offer transparency and local control. Cloud IDEs shift environment provisioning to the vendor. Neither replaces lockfiles and CI verification of the same versions.



---



**Made for developers who juggle many languages and need reproducible toolchains.**  

Let's expand open version managers while recognizing the convenience of hosted development environments when local setup is not required.
