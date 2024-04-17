# Mantine Next Template for Chrome Extensions

Get started with the template by clicking `Use this template` button on the top of the page.

# Build

`pnpm build` will build the extension into the `.out` directory. By default Next creates a `.out/_next` directory, however Chrome won't load extensions with files or directories beginning with "\_". Therefore, the pnpm build script renames that directory and all references to it to `next` instead.

# Load

In the `chrome://extensions/` Extension Manager, select `Load Unpacked` and load from the `.out` directory to add your extension.
