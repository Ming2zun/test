# test
# Kit SDK

This package contains the Kit Kernel and the Kit Base Editor sample application with all necessary extensions pre-cached and ready to run!

The Kit Base Editor is a great way to get familiar with [OpenUSD](https://docs.omniverse.nvidia.com/usd/latest/index.html), and to experience the capabilities of the [RTX Rendering](https://docs.omniverse.nvidia.com/materials-and-rendering/latest/rtx-renderer.html).

To launch the Kit Base Editor, run the following batch script:

- Windows: `omni.app.editor.base.bat`
- Linux: `omni.app.editor.base.sh`

Use the Extension Manager (`Window -> Extensions`) to explore all the extensions available for Kit applications.

## Build Your Own Kit Application

### Kit App Template

> **NEW In Kit 106.4** : Kit App Template is now included in the Kit SDK package.

To get started building your own applications and extensions using the Omniverse Kit SDK, the  [Omniverse Kit App Template](https://github.com/NVIDIA-Omniverse/kit-app-template) is included along with a tool to setup a new project from scratch.

### Usage

1. Open a terminal to where Kit SDK has been extracted.
2. Create a new project from the Kit App Template:
    - Windows: `.\new_project.bat`
    - Linux: `./new_project.sh`

> **NOTE:** If this is your first time running `new_project`, you'll be prompted to accept the Omniverse Licensing Terms.

3. Choose a folder to create a new Kit project.

4. Navigate to your newly created project folder and run the following commands:

    - `repo template new` - Create new application and extensions from Kit templates.
    - `repo build` - Build your application and extensions.
    - `repo launch` - Launch your application.
    - `repo --help` - List all available repo commands and options.

> **NOTE** : Repo tools are shell scripts: Use `.\repo.bat` on Windows and `./repo.sh` on Linux. Learn more about [Repo Tools here](https://docs.omniverse.nvidia.com/kit/docs/repo_man/latest/docs/overview.html.).

Running `new_project` is roughly equivelant to cloning Omniverse Kit App Template github repo. The benefit is that this new project will have no link to Kit App Template repo on GitHub.

> **NOTE** :
> The newly created project will link to the local Kit SDK folder as a dependency using `kit-sdk.packman.xml.user` in the `./tools/deps` folder.
> Kit App Template from Github, by comparison, will download `kit-kernel` as a dependency and link to that resource instead. Read more in the [Kit Manual](https://docs.omniverse.nvidia.com/kit/docs/kit-manual/latest/guide/kit_overview.html).


## Get Help
Access Omniverse Knowledge Base articles and submit support cases with [Enterprise Support Services](https://www.nvidia.com/en-us/support/enterprise/).

Explore detailed guides for deploying and managing NVIDIA Omniverse applications at [NVIDIA Omniverse Docs Hub](https://docs.nvidia.com/omniverse/index.html).

Manage your software licenses at the [NVIDIA Licensing Portal](https://ui.licensing.nvidia.com/login).

Join the developer and user community to share knowledge, ask questions, and connect with experts:

- [NVIDIA Omniverse Dev Community](https://developer.nvidia.com/omniverse/community)
- [NVIDIA Omniverse Discord Server](https://discord.com/invite/XWQNJDNuaC)
- [NVIDIA Omniverse Forums](https://forums.developer.nvidia.com/c/omniverse/300/)

## Governing Terms

NVIDIA Omniverse is governed by the [NVIDIA Agreements | Enterprise Software | NVIDIA Software License Agreement](https://www.nvidia.com/en-us/agreements/enterprise-software/nvidia-software-license-agreement/)
and [NVIDIA Agreements | Enterprise Software | Product Specific Terms for Omniverse](https://www.nvidia.com/en-us/agreements/enterprise-software/product-specific-terms-for-omniverse/).

By downloading or using NVIDIA Omniverse, you agree to the NVIDIA Omniverse terms.
