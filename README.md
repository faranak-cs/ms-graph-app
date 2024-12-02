# MS Graph App

A simple app that connects to Microsoft 365 and calls the Microsoft Graph API

## Steps

### GET team-id

Request

```
https://graph.microsoft.com/v1.0/me/joinedTeams
```

### GET channel-id

Request

```
https://graph.microsoft.com/v1.0/teams/{team-id}/channels
```

### GET message-ids

Request

```
https://graph.microsoft.com/beta/teams/{group-id-for-teams}/channels/{channel-id}/messages
```

### GET replies from message-id

Request

```
https://graph.microsoft.com/beta/teams/{group-id-for-teams}/channels/{channel-id}/messages/{message-id}/replies
```

## Tutorial

Follow the Microsoft Tutorial [here](https://learn.microsoft.com/en-gb/entra/identity-platform/quickstart-single-page-app-javascript-sign-in)
