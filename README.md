<div align="center" markdown="1">

<img src=".github/logo.png" alt="Frappe Books logo" width="384"/>

---

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/frappe/books)](https://github.com/frappe/books/releases)
![Platforms](https://img.shields.io/badge/platform-mac%2C%20windows%2C%20linux-yellowgreen)
[![Publish](https://github.com/frappe/books/actions/workflows/publish.yml/badge.svg)](https://github.com/frappe/books/actions/workflows/publish.yml)

Free Desktop book-keeping software for small businesses and freelancers.

[frappebooks.com](https://frappebooks.com/)

<img src=".github/frappe-books-preview.png" alt="Frappe Books Preview" />

</div>

## Index

<details>
<summary><code>[show/hide]</code></summary>

1. [Features](#features)
2. [Installation](#installation)
3. [Development](#development)
4. [Contributions and Community](#contributions-and-community)
5. [Links](#links)
6. [License](#license)

</details>

## Features

1. Double-entry accounting
1. Invoicing
1. Billing
1. Payments
1. Journal Entries
1. Dashboard
1. Works Offline
1. Financial Reports
   - General Ledger
   - Profit and Loss Statement
   - Balance Sheet
   - Trial Balance

## Installation

Download and install the latest release for your platform from the [releases
page](https://github.com/frappe/books/releases) or the [download
page](https://frappebooks.com/download).

## Development

Frappe Books is built on Vue.js and Electron. It is offline by default and uses
a local SQLite file as the database.

### Pre-requisites

To get the dev environment up and running you need to first set up Node.js version
16.13.1 and npm. For this, we suggest using
[nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

Next, you will need to install [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable).

### Clone and Run

Once you are through the Pre-requisites, you can run the following commands to
get Frappe Books running in development mode:

```bash
# clone the repository
git clone https://github.com/frappe/books.git

# change directory
cd books

# install dependencies
yarn

# start the electron app
yarn electron:serve
```

## Contributions and Community

There are many ways you can contribute even if you don't code:

1. If you find any issues, no matter how small (even typos), you can [raise an issue](https://github.com/frappe/books/issues/new) to inform us.
2. You can help us with language support by [contributing translations](https://github.com/frappe/books/wiki/Contributing-Translations).
3. You report errors by setting **Hide & Auto Report Errors** in _Settings > System_.
4. If you're an ardent user you can tell us what you would like to see.
5. If you have accounting requirements, you can become an ardent user. 🙂
6. You can join our [telegram group](https://t.me/frappebooks) and share your thoughts.

If you want to contribute code then you can fork this repo, make changes and raise a PR. ([see how to](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork))

## Links

- [Telegram Group](https://t.me/frappebooks): Used for discussions regarding features, issues, changes, etc. This group is also be used to make decisions regarding project direction.
- [Project Board](https://github.com/frappe/books/projects/1): Roadmap that is updated with acceptable latency.
- [GitHub Discussions](https://github.com/frappe/books/discussions): Used for discussions around a specific topic.
- [Frappe Books Blog](https://frappebooks.com/tech/): Sporadically updated dev blog regarding the development of this project.

## License

[GNU Affero General Public License v3.0](LICENSE)
