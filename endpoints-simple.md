# Api Endpoints (V2)

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

### User Files
`/users/{userId}/files`

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

### User Files Stream
`/users/{userId}/files/stream`

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

### User Usernames
`/users/{userId}/usernames`

Parameters:
- `userId`: The user ID

## Badges

### Badges
`/badges`

### Badge Code Redeem
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

### Images Bulk
`/images/bulk`

### Image By
`/images/by/{key}/{value}`

Parameters:
- `key`: The key to search by
- `value`: The value to search for

## Files

### File
`/files/{fileId}`

Parameters:
- `fileId`: The file ID

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

### Domains Discover
`/domains/discover`

## Random Domains

### Random Domains
`/randomDomains`

### Random Domain
`/randomDomains/{randomDomainId}`

Parameters:
- `randomDomainId`: The user random domain ID

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

### Folder Content
`/folders/{folderId}/content`

Parameters:
- `folderId`: The folder ID

## Shares

### Share
`/shares/{shareCode}`

Parameters:
- `shareCode`: The share code

### Content By Share Code Folder
`/{contentType}/by/shareCode/{shareCode}/folder`

### Share OEmbed
`/shares/{shareCode}/oembed`

Parameters:
- `shareCode`: The share code

### Share Meta
`/shares/{shareCode}/meta`

Parameters:
- `shareCode`: The share code

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

### Subscription Code Redeem
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

## Locales

### Locales
`/locales`

### Locale
`/locales/{localeId}`

Parameters:
- `localeId`: The locale ID

## Subscription Codes

### Subscription Codes Bulk
`/subscriptionCodes/bulk`

## Endpoints

### Endpoints
`/endpoints`