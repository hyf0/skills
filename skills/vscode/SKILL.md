---
name: vscode
description: Open the current working directory or a specified folder in Visual Studio Code.
---

## Usage

- `/vscode` - Opens the current working directory
- `/vscode /path/to/folder` - Opens the specified folder

## Implementation

Run `code` with arguments if provided, otherwise open current directory:

```bash
code ${ARGUMENTS:-.}
```
