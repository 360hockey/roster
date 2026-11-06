[README.md](https://github.com/user-attachments/files/34504461/README.md)
[README.md](https://github.com/user-attachments/files/34495411/README.md)
# Rocky Mountain Moose Roster Builder

## Live Google Sheet source
The builder reads only the published `Test` worksheet using its exact worksheet ID (`gid=1710339715`). It does not fall back to the first worksheet or read other tabs.

Column groups:
- 15U Blue: A-D (`#`, Player Name, Position, Available)
- 15U Black: F-I (`#`, Player Name, Position, Available)
- 16U: K-O (`#`, Player Name, Rating, Type, Available)
- 19U: Q-U (`#`, Player Name, Rating, Type, Available)

The page refreshes periodically and includes a **Refresh Sheet** button. Google Sheets checkbox values are interpreted as TRUE/checked = available and FALSE/unchecked = unavailable. Blank or unrecognized values are shown as availability not set and are not assignable.

## Publish
Replace `index.html` in the `moosestats` GitHub repository with this file and allow GitHub Pages to redeploy. No CSV download or upload is required.
