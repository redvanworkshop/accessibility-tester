![Logo](docs/img/logo.png "Logo")

Accessibility Tester
---

> Command Line Interface for Automated Accessibility Testing RVW Client Websites

![markdown](https://rvw-a11y.s3.amazonaws.com/markdown.gif?v=1.0.0)

Introduction
---

A CLI tool that tests client websites for Accessibility Issues and generates reports that can be assigned to Developers.

- [X] Support for Continuos Integration Testing
- [X] Save Reports in CSV, HTML, Jira, JSON, Markdown & XML Formats
- [X] Supports Page Automation using Actions
- [X] Supports Testing Websites behind HTTP Authentication
- [X] Reports provide Resource Links for Developers to Learn More about Accessibility


Developer Overview
---

#### Commands

* [`rvw-a11y`](docs/cmd-a11y.md) - Detailed Examples of `rvw-ally` Usage
* [`rvw-a11y auth`](docs/cmd-auth.md) - Generate HTTP Authentication Tokens
* [`rvw-a11y help`](docs/cmd-help.md) - Get Help when you need it

#### Additional Information

* [Automate with Actions](docs/actions.md) - Submit Forms, Click Links & Other Fun Things
* [Troubleshooting](docs/troubleshooting.md) - Some of the Known Issues & how to resolve them


Install
---

#### Requirements

- [X] [Node v10+](https://nodejs.org/en/download/)

#### `npm install`

```bash
npm install -g rvw-accessibility-tester
rvw-a11y help
```

#### `git clone`

```bash
cd ~
git clone https://github.com/redvanworkshop/accessibility-tester.git
cd accessibility-tester
npm install -g
rvw-a11y help
```

Report Samples
---

We worked extensively to make the most helpful reports possible.  Whether you are running a test on a single site, or needing to batch multiple tests into a single report, we wanted to make our reports as developer friendly as possible.

Since this is a CLI tool, the default output is in a terminal window.

![sample-report](https://rvw-a11y.s3.amazonaws.com/sample-report/cli.jpg?v=1.0.0)

#### Below are reports generated in our other supported formats.

* [sample-report.csv](https://gist.github.com/manifestinteractive/fab5fc8cceac093cbe9fb5a5c2ad1b96)
* [sample-report.html](https://rvw-a11y.s3.amazonaws.com/sample-report/a11y_20190804_221047.html)
* [sample-report.jira](https://gist.github.com/manifestinteractive/52a25c431d8280166e005f5c82b5d34e)
* [sample-report.json](https://gist.github.com/manifestinteractive/dbe2909776bd27a1242cc6afbc7d93d9)
* [sample-report.md](https://gist.github.com/manifestinteractive/f2c87d567ff052acc766ce14387e915b)
* [sample-report.xml](https://gist.github.com/manifestinteractive/bca0ee98f455e2cfe67a8d3f1f31b6ad)

_Built using [pa11y](https://github.com/pa11y/pa11y). Customized for RVW Developers & Clients._