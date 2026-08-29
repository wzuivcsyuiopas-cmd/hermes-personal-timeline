# Hermes Personal Timeline

Hermes Personal Timeline is a private, single-user personal assistant integration. It reads data authorized by the owner from Google Health and synchronizes selected observations into the owner's self-hosted Personal Timeline service.

## Data access

The application requests read-only Google Health access for:

- activity and fitness;
- health metrics and measurements;
- sleep;
- nutrition;
- ECG;
- irregular rhythm notifications;
- workout location;
- profile information;
- Google Health settings.

The application does not request Google Health write permissions. The current Personal Timeline adapter normalizes steps, active energy, distance, weight, resting heart rate, sleep, and exercise records. Other authorized categories are not treated as present unless Google returns them and the adapter explicitly supports them.

## Privacy policy

Effective date: August 29, 2026.

- Health data is used only to provide the owner's requested personal timeline and daily-summary features.
- Health data is not sold, advertised against, or shared with unrelated third parties.
- Imported observations are stored only in the owner's self-hosted Personal Timeline database.
- OAuth credentials are stored on the owner's private server and are never included in this public repository.
- Data is retained until the owner deletes it from the self-hosted service or revokes access.
- The owner can revoke access at any time from [Google Account connections](https://myaccount.google.com/connections).
- The integration follows the Google API Services User Data Policy, including the Limited Use requirements.

## Contact

For questions about this integration or its privacy policy, open an issue in this repository.
