# Actions
240215-1625  
240215-1306  
240215-1304  

# PAT Token
Needs (read:org, repo).

# Owner vs Member

| Type | 1-Clone-Local | 2-Clone-Remote | 3-Tag-Local | 4-Tag-Remote | 5-Push-Local | 6-Push-Remote | 7-PR-Local | 8-PR-Remote | Notes |
|---|---|---|---|---|---|---|---|---|---|
| Owner | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Baseline |
| Member | Allowed | Allowed | Allowed | Denied | Allowed | Denied | Denied | Denied | Changing to member |
| Owner | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Rolling back to member |
| Member + Write | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Allowed | Changing to member + write permissions on local & remote repo |
