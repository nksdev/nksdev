# ApplyFlow — Local-First Job Application Tracker

A responsive, single-page job-search tracker built with plain HTML, CSS, and JavaScript. No package installation, backend, account, paid API, analytics, external script, or font download is required.

## Run locally

Open `index.html` in a modern browser. Use **Add application** to track a role, employer, status, posting link, date applied, follow-up date, and notes. Records are stored in that browser's `localStorage`.

## Features

- Create, edit, search, filter, sort, and delete applications.
- Dashboard totals for tracked roles, interviews, offers, and follow-ups due.
- Download a CSV export or JSON backup.
- Import a JSON backup, with a choice to merge or replace existing records.
- Load clearly labelled demo records.
- Responsive layout and keyboard-visible focus states.
- CSV formula-injection mitigation and URL scheme validation.

## Deploy on GitHub Pages

This page is in the `applyflow/` directory of the `nksdev/nksdev` repository. If GitHub Pages is configured to publish the repository's `main` branch from the root, it is served at:

https://nksdev.github.io/nksdev/applyflow/

## Privacy and limitations

Application records stay in browser storage unless you export them. They are not automatically synced to other devices. Browser data may be removed by clearing site data; export a JSON backup regularly. Anyone with access to the same browser profile may be able to view its stored records. Do not store passwords or highly sensitive personal data here.

This is a personal productivity tool, not a hiring platform. Job status and follow-up reminders are managed locally; the app does not submit applications or contact employers.

## License

MIT. See [LICENSE](../LICENSE) in the parent repository.
