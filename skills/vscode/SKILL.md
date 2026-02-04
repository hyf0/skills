---
name: vscode
description: Open the current working directory or a specified folder in Visual Studio Code. Use /vscode command.
metadata:
  author: Yunfei He
  version: "1.0.0"
---

# VS Code Opener

Open folders in Visual Studio Code from your terminal.

## Usage

- `/vscode` - Opens the current working directory
- `/vscode /path/to/folder` - Opens the specified folder

## Implementation

When invoked:
1. If arguments are provided, use them as the folder path
2. Otherwise, use the current working directory
3. Run the `code` command to open VS Code

```bash
# With arguments
code $ARGUMENTS

# Without arguments
code .
```
