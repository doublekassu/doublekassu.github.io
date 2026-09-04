# Antistrat Privacy Policy

_Last updated: September 4, 2026_

Antistrat is a Chrome extension that provides CS2 tactical analysis for FACEIT matches. This document explains what data the Extension and its backend collect, why, where it is stored, how long it is kept, and what rights you have regarding that data.

## What We Collect

Tacticly collects the following data when you use the Extension to request a match analysis:

- **FACEIT usernames** — used only to match players to their in-match positions so the analysis can be generated correctly.
- **Demo URLs** — the temporary FACEIT demo download link for the match being analyzed, used only to fetch and process the match data.
- **Generated analysis videos** — the output video created from the analysis, so it can be viewed and shared.

We do **not** collect passwords, payment information, or any other personal data beyond what is listed above.

## How We Use This Data

Data is used exclusively to:

- Run the requested demo analysis
- Generate the resulting tactical analysis video

We do not use this data for advertising, profiling, or any purpose unrelated to producing your analysis.

## Where Data Is Stored

Data is stored on our backend infrastructure, using S3-compatible object storage (MinIO):

- **Demo URLs and intermediate processing data** are used only for the duration of the analysis job and are not kept afterward.
- **Analysis videos** are stored in our object storage so they can be viewed and shared via a link.

## How Long We Keep Data

- Demo URLs and temporary processing data are deleted immediately after the analysis completes.
- Analysis videos are retained for **30 days** after creation to allow for viewing and sharing, after which they are automatically deleted.

## Your Rights

You may request deletion of your data (including any stored analysis video) at any time by contacting us at:

**antistrat.dev@gmail.com**

We will process deletion requests promptly.

## Data We Do Not Collect

Tacticly does not collect or store passwords, payment details, or any personal information beyond FACEIT usernames, demo URLs, and generated analysis videos as described above.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last updated" date.

## Contact

Questions about this Privacy Policy or your data can be sent to **antistrat.dev@gmail.com**.
