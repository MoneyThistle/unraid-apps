# MoneyThistle for Unraid Community Applications

This repository holds the Unraid Community Applications templates for the Thistle projects. It does not contain the applications themselves; each template points at the project's published Docker image.

## Apps

- **MoneyThistle** (`templates/moneythistle.xml`): a self-hosted household money manager. Accounts, bills and deposits, paychecks, budgets, reports, and automatic backups, with no bank connections. Image: `ghcr.io/moneythistle/moneythistle`. Project: https://github.com/MoneyThistle/MoneyThistle · Site: https://money.thistle.casa

## Installing

Once this repository is listed in Community Applications, install MoneyThistle from the Apps tab like any other app.

To try the template before then: in Unraid, go to Apps, Settings, Template Repositories, add `https://github.com/MoneyThistle/unraid-apps`, and MoneyThistle will appear in the Apps tab.

After installing, open the WebUI: the first visit creates the administrator's sign-in. Keep MoneyThistle on your home network or reach it over Tailscale or another private VPN. Do not open it to the public internet.

## Support

Issues and questions: https://github.com/MoneyThistle/MoneyThistle/issues

## License

AGPL-3.0, the same license as MoneyThistle. See `LICENSE`.
