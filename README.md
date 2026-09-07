# St. Michael's Holy Name Society Website

Website for the St. Michael's Holy Name Society in Bismarck, North Dakota.

Website:

https://stmichaelshns.github.io


## Purpose

This site is an informational resource for Holy Name Society members.

The website is intentionally simple, lightweight, mobile-friendly,
and primarily text-based.

Frequently changing information and private documents are hosted
through external Google services rather than stored in this repository.


## Important Files

### `_config.yml`

Site-wide settings, including:

- Site title
- Site description
- Last updated date

Update the `last_updated` value when making a monthly update.


### `index.md`

The homepage.

Use this for:

- Welcome message
- Latest update
- Basic homepage information


### `resources/index.md`

The Resources page.

This is where the links to external resources are maintained:

- Holy Name Calendar
- Current To-Do List
- Meeting Minutes
- St. Michael's Roman Catholic Church


### `_layouts/default.html`

The common site layout.

Contains:

- Header
- Navigation
- Main page structure
- Footer


### `assets/css/style.css`

The site's main stylesheet.

This controls:

- Colors
- Typography
- Spacing
- Mobile layout
- Accessibility styles


### `assets/images/favicon.svg`

The small icon displayed by browsers for the website.


## Monthly Maintenance

When information needs to be updated:

1. Edit the appropriate page.
2. Update `last_updated` in `_config.yml`.
3. Commit the changes.
4. Wait for GitHub Pages to rebuild the site.
5. Check the website on a phone.


## Privacy

The website itself should not contain private member information.

Meeting minutes and other private information should remain
in Google Drive/Google Docs with appropriate sharing permissions.

The website is not intended to be publicly advertised.
