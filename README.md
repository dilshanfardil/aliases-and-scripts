# WSO2 Product Utilities

This repository contains custom commands and aliases for working with WSO2 products.

## Custom Commands

### `wso2-init`
Unzips a WSO2 product pack into the current directory.

### `open-issue`
Creates directories for WSO2 issues and opens them in the file manager.

**Usage:**

`wso2-init --apim-4.2.0`

`open-issue ISSUE-23`


## Setup Instructions

1. **Add the aliases** to your `~/.zshrc` file.
2. **Place custom scripts** in the `/usr/local/bin/` directory.
3. Modify the scripts as needed.
4. Reload your shell:
   ```bash
   source ~/.zshrc

