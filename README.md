# MOX Vault — Price Duel

Public top 18 leaderboard for the Price Duel minigame in MOX Vault.

## Public data

`leaderboard.json` contains the schema version, last update time and ranked scores. Entries contain a player key, chosen display name, score and date. Only publish a name you are comfortable making public. Git history can retain earlier versions.

## Submissions

The app reads the public JSON. Voluntary score submissions go through a separately deployed Google Apps Script, which checks eligibility and writes qualifying scores. The GitHub write token is stored only in private Script Properties, never in the app or this repository. Two-factor authentication on the owner's GitHub account is compatible with token-based API access.

This is a casual minigame: basic validation and rate limits do not prove that a plausible score was earned through genuine play.

## Support

To report an inappropriate display name or request removal from the current leaderboard, contact magicase.support@gmail.com. Removing a current entry does not automatically erase GitHub history.
