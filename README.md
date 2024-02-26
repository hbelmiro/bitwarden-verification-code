# bitwarden-verification-code

## Overview

This script retrieves a verification code from Bitwarden for a specified item using Time-based One-Time Password (TOTP). It requires Bitwarden CLI to be installed and logged in. The script prompts for the name of the Bitwarden item if not provided as an argument.

## Prerequisites

* [Bitwarden CLI](https://bitwarden.com/help/cli/) installed and configured.

Usage

```bash
bitwarden-verification-code [item_name]
```

* item_name (optional): Name of the Bitwarden item for which you want to retrieve the verification code.

## Notes

    Ensure Bitwarden CLI is properly configured and logged in before using this script.
    This script assumes that TOTP is set up for the specified Bitwarden item.