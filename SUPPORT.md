# Support & Troubleshooting

This guide covers the most common issues you may run into while using the **Passport CLI**, along with steps to diagnose and resolve them. If your problem isn't listed here, please [search the issue tracker](https://github.com/postmanlabs/passport-cli-support/issues) or [open a new issue](https://github.com/postmanlabs/passport-cli-support/issues/new/choose) following our [reporting guidelines](./CONTRIBUTING.md).

## Before you start

Run these quick checks first — they resolve or narrow down most problems:

- **Confirm your version.** Run `passport --version` and make sure you are on the latest release. Many issues are already fixed in newer versions.
- **Enable verbose/debug output.** Re-run your command with the debug flag (e.g. `passport <command> --verbose`) to get more detail about what's failing.
- **Check your connectivity.** Confirm you can reach Postman's services and that no proxy or firewall is blocking the request.

## Common issues


## Collecting information for a bug report

If none of the above resolves your issue, please gather the following before opening an issue — it helps us triage faster:

- The **Passport CLI version** (`passport --version`).
- Your **Operating System** and version.
- The **exact command** you ran and the **full output** (with `--verbose`/debug enabled), with any secrets redacted.
- Whether the problem is reproducible **every time** or **intermittently**.
- Any relevant (redacted) configuration or profile details.

> **Security note:** Never paste API keys, tokens, or other secrets into a public issue. Redact them first. To report a security vulnerability, follow our [security policy](./SECURITY.md).
