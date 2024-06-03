# Api Endpoints

## Users

### Users
`/users`

### User
`/users/{userId}`

Parameters:
- `userId`: The user ID

### User Images
`/users/{userId}/images`

Parameters:
- `userId`: The user ID

### User Pastes
`/users/{userId}/pastes`

Parameters:
- `userId`: The user ID

### User Avatar
`/users/{userId}/avatar`

Parameters:
- `userId`: The user ID

### User Random Domains
`/users/{userId}/randomDomains`

Parameters:
- `userId`: The user ID

### User Connection
`/users/{userId}/connections/{connection}`

Parameters:
- `userId`: The user ID
- `connection`: The connection type (discord, etc.)

### User Connection Refresh
`/users/{userId}/connections/{connection}/refresh`

Parameters:
- `userId`: The user ID
- `connection`: The connection type (discord, etc.)

### User Folders
`/users/{userId}/folders`

Parameters:
- `userId`: The user ID

### User Images Stream
`/users/{userId}/images/stream`

Parameters:
- `userId`: The user ID

### User Pastes Stream
`/users/{userId}/pastes/stream`

Parameters:
- `userId`: The user ID

### User By
`/users/by/{key}/{value}`

Parameters:
- `key`: The key to search by
- `value`: The value to search for

### User Extended
`/users/{userId}/extended`

Parameters:
- `userId`: The user ID

### User Subscriptions
`/users/{userId}/subscriptions`

Parameters:
- `userId`: The user ID

### User Infractions
`/users/{userId}/infractions`

Parameters:
- `userId`: The user ID

### User Bios
`/users/{userId}/bios`

Parameters:
- `userId`: The user ID

## Badges

### Badges
`/badges`

### Redeem Badge Code
`/badges/redeem`

## Languages

### Languages
`/languages`

## Paste Highlights

### Paste Highlights
`/pasteHighlights`

## Images

### Image
`/images/{imageId}`

Parameters:
- `imageId`: The image ID

### Images
`/images`

### Bulk Images
`/images/bulk`

## Pastes

### Paste
`/pastes/{pasteId}`

Parameters:
- `pasteId`: The paste ID

## General Uploads

### Add Download Count
`/{uploadType}/{uploadId}/download`

#### Adds a download count to an upload

Parameters:
- `uploadType`: The upload type as plural ("images", "pastes", etc.)
- `uploadId`: The upload ID

## Subscription Groups

### Subscription Groups
`/subscriptionGroups`

## Downloads

### Download Config
`/downloads/configs/{platform}/{type}`

Parameters:
- `platform`: The platform (sharex, etc.)
- `type`: The config type (images, etc.)

## Domains

### Domains
`/domains`

### Domain
`/domains/{domainId}`

Parameters:
- `domainId`: The domain ID

## User Random Domains

### User Random Domains
`/userRandomDomains`

### User Random Domain
`/userRandomDomains/{userRandomDomainId}`

Parameters:
- `userRandomDomainId`: The user random domain ID

## Confirmations

### Confirmation
`/confirmations/{confirmationType}`

Parameters:
- `confirmationType`: The confirmation type (email, password, etc.)

## Reports

### Reports
`/reports`

## Feedbacks

### Feedbacks
`/feedbacks`

## Password Reset

### Password Reset
`/passwordReset`

### Send Password Reset
`/passwordReset/send`

## Folders

### Folders
`/folders`

### Folder
`/folders/{folderId}`

Parameters:
- `folderId`: The folder ID

## Shares

### Share
`/shares/{shareCode}`

Parameters:
- `shareCode`: The share code

### Content By Share Code Folder
`/{contentType}/by/shareCode/{shareCode}/folder`

Parameters:
- `contentType`: The content type as plural ("images", "pastes", etc.)
- `shareCode`: The share code

## Authentication

### Login
`/auth/login`

### Register
`/auth/register`

## Bio Socials

### Bio Social
`/bioSocials/{bioSocialId}`

Parameters:
- `bioSocialId`: The bio social ID

### Bio Socials
`/bioSocials`

## Bios

### Bio
`/bios/{bioId}`

Parameters:
- `bioId`: The bio ID

### Bio Avatar
`/bios/{bioId}/avatar`

Parameters:
- `bioId`: The bio ID

### Bio Banner
`/bios/{bioId}/banner`

Parameters:
- `bioId`: The bio ID

### Bio Background
`/bios/{bioId}/background`

Parameters:
- `bioId`: The bio ID

### Bios
`/bios`

## Subscriptions

### Redeem Subscription Code
`/subscriptions/redeem`

### Subscriptions
`/subscriptions/{subscriptionId}`

Parameters:
- `subscriptionId`: The subscription ID

## Infractions

### Infractions
`/infractions`

### Infraction
`/infractions/{infractionId}`

Parameters:
- `infractionId`: The infraction ID

## Announcements

### Announcements
`/announcements`

## Ping

### Ping
`/ping`

## Changelogs

### Changelogs
`/changelogs`

## Permission Groups

### Permission Groups
`/permissionGroups`

### Permission Group
`/permissionGroups/{permissionGroupId}`

Parameters:
- `permissionGroupId`: The permission group ID
