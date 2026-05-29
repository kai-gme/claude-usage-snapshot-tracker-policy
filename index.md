# Privacy Policy

Effective date: 2026-05-28

This privacy policy describes how Claude Usage Snapshot Tracker handles user data.

## Purpose

Claude Usage Snapshot Tracker is an internal operations extension used to collect lightweight Claude usage snapshots for license and usage reporting.

## Information Collected

The extension may collect:

- Employee name and employee email entered by the user or administrator in the extension popup.
- Snapshot date and time.
- Usage percentages and reset-time text visibly displayed on the user's Claude Usage page.
- Capture status, error message, extension version, source label, and collection reason.

## Information Not Collected

The extension does not collect:

- Claude conversations.
- User prompts.
- Claude responses.
- Chat titles or project names.
- Attachment names or attachment contents.
- Cookies, passwords, session tokens, localStorage, or authentication secrets.
- Raw Claude API responses.
- Browser history outside the configured Claude Usage page.

## How Information Is Used

Collected information is used only for internal license operations, usage trend reporting, and troubleshooting the usage snapshot workflow.

## How Information Is Shared

The extension sends snapshots to the Google Apps Script Web App URL configured in the extension settings. That endpoint writes rows to the organization's configured Google Sheet.

Data is not sold, used for advertising, or shared with third parties for marketing purposes.

Organization administrators or authorized operations staff may view the Google Sheet for internal reporting and troubleshooting.

## Storage

The extension stores settings, recent snapshots, and pending uploads locally in Chrome storage. Uploaded snapshots are stored in the configured Google Sheet.

## Security

Snapshots are transmitted over HTTPS to the configured Google Apps Script Web App URL. The extension can include an optional shared secret with each upload so the backend can reject unexpected requests.

## User Controls

Users or administrators can:

- Configure or clear employee name and email in the extension popup.
- Configure or clear the webhook URL.
- Disable automatic collection.
- Use manual-only collection.
- Clear local extension data from the extension popup if that control is enabled in the installed build.

Data already written to Google Sheets can be reviewed or deleted by the sheet owner or organization administrator according to the organization's retention process.

## Limited Use

The extension uses collected data only to provide and improve its stated internal usage reporting feature. It does not use collected data for advertising, user profiling, sale of data, or unrelated purposes.

## Contact

For privacy or support questions, contact the organization administrator responsible for this internal extension deployment.
