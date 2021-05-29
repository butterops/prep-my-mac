<p align="center"><img src="./prepmymac.png"><i>Screenshot of PrepMyMac desktop app</i></p>


# Prep My Mac

Separate your project infrastructure from that of your Mac. Install a vagrant based VM with your dev tools in one click.

> One click install, configure and manage automations for development in node, python & php through vagrant based IaC vm and app containers.

### Getting Started

Clone this repository, install dependencies and run using either `dev`, `debug` or `build` command.

```bash
# Clone this repository
# change directory to cloned path

# Install dependencies
npm install

# Run in `debug` mode, to debug app using VSCODE
npm run debug

# Run in `dev` mode
npm run dev

# Build installer for this app
npm run build
```

### Project structure

`src/main` contains electron main script.

`src/renderer` contains vue-js application.

`src/utilities/workerSample.ts` a sample worker script.

#### Credits

All credits to authors of packages and tools used in the project.

## Contributors

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
