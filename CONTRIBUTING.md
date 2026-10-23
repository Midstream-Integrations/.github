# Contributing

Thanks for helping improve these Business Central extensions.

## Reporting a bug

Open an issue in the app's repo using the **Bug report** form. Include your Business Central version, the app version (Extension Management shows both) and the steps to reproduce. Never paste customer data, card numbers, API keys or tenant IDs.

## Suggesting a feature

Use the **Feature request** form and describe the business problem first; there may be more than one way to solve it.

## Pull requests

1. Fork the repo and create a branch from `main`.
2. Keep to the house style:
   - Every new object uses the `MID` prefix and an ID inside the app's range in `app.json`.
   - Every field and action has a `ToolTip`; user-facing text goes in `Label`s.
   - No hardcoded company data: no emails, G/L accounts, location codes, item numbers or report IDs. Put values like these in a setup table instead.
   - Add any new object to the app's permission set.
3. Build with no errors and no new warnings (CodeCop, UICop and PerTenantExtensionCop enabled).
4. Test in a sandbox, and say in the pull request what you tested.
5. Add a line under "Unreleased" in `CHANGELOG.md`.

By contributing, you agree that your contribution is licensed under the repo's MIT license.
