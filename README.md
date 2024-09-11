## Uncurated WebKit Security-related Commits Dataset (including relevant APIs and components)

Data directory contents are not distributed directly but can be accessed through the official repository.

Example:
```bash
jq '.[] | select(.keywords_found[] == "oob" and .security_team_member == 1)'  security_related_commits.json
```

```json
{
  "commit": "698c6e293734c3c46f223b77d5b4ee48b320e32c",
  "commit_date": "2023-05-22 13:40:46 -0700",
  "commit_url": "https://github.com/WebKit/WebKit/commit/698c6e293734c3c46f223b77d5b4ee48b320e32c",
  "commit_author": "msaboff",
  "blame_author": "removed",
  "keywords_found": [
    "CVE-2023-28204",
    "oob",
    "oob read"
  ],
  "security_team_member": 1,
  "patch_file": "data/698c6e293734c3c46f223b77d5b4ee48b320e32c.patch"
}
{
  "commit": "5d84a773e0370cdd4098ef11edf6980857f9783f",
  "commit_date": "2021-04-27 00:23:25 +0000",
  "commit_url": "https://github.com/WebKit/WebKit/commit/5d84a773e0370cdd4098ef11edf6980857f9783f",
  "commit_author": "ntim",
  "blame_author": "removed",
  "keywords_found": [
    "oob"
  ],
  "security_team_member": 1,
  "patch_file": "data/5d84a773e0370cdd4098ef11edf6980857f9783f.patch"
}
{
  "commit": "0cf4a62252a442731a49191fd7d3baf3aa2f68d5",
  "commit_date": "2017-03-08 22:50:51 +0000",
  "commit_url": "https://github.com/WebKit/WebKit/commit/0cf4a62252a442731a49191fd7d3baf3aa2f68d5",
  "commit_author": "keith_miller",
  "blame_author": "removed",
  "keywords_found": [
    "oob"
  ],
  "security_team_member": 1,
  "patch_file": "data/0cf4a62252a442731a49191fd7d3baf3aa2f68d5.patch"
}
```
