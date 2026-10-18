GameDrive Tracker

An automated catalogue tracker for publicly discoverable releases associated with the GameDrive uploader profile on 1337x.

Project goals

- Discover and catalogue profile listings across available pages.
- Record titles, upload dates, file sizes, and listing URLs where available.
- Detect duplicate listings.
- Refresh the catalogue automatically using GitHub Actions.
- Export structured JSON data for searching and analysis.
- Support Hydra integration only for downloads authorised for distribution.

Automation

Scheduled updates will be handled by GitHub Actions, subject to source availability and website access restrictions.

Data and limitations

- Listings are metadata, not a guarantee that a download is safe or authorised.
- Missing or unavailable metadata will be recorded as unknown rather than guessed.
- The tracker will respect applicable website terms and access restrictions.

Status

Initial repository setup. Automated collection and catalogue generation are not yet implemented.
