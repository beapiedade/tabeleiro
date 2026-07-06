# tabeleiro

## Testes Py
pip install openpyxl
python3 -m pip install --upgrade pip 

## Testes GET
Em https://developer.microsoft.com/en-us/graph/graph-explorer
- GET /me
- GET https://graph.microsoft.com/v1.0/me/joinedTeams
```
{
    "id": "a1f7efe7-6c0c-4200-93ad-4433305c1834",
    "createdDateTime": null,
    "displayName": "Teste Tabeleiro",
    "description": "Teste Tabeleiro",
    "internalId": null,
    "classification": null,
    "specialization": null,
    "visibility": null,
    "webUrl": null,
    "isArchived": false,
    "tenantId": "a7cdc447-3b29-4b41-b73e-8a2cb54b06c6",
    "isMembershipLimitedToOwners": null,
    "memberSettings": null,
    "guestSettings": null,
    "messagingSettings": null,
    "funSettings": null,
    "discoverySettings": null,
    "tagSettings": null,
    "summary": null
}
```
- GET https://graph.microsoft.com/v1.0/teams/{TEAM_ID}/schedule
