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

### User Connection Discord Refresh Roles
`/users/{userId}/connections/discord/refreshRoles`

Parameters:
- `userId`: The user ID

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

### Redeem User Subscription
`/users/{userId}/subscriptions/redeem`

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

### User Notifications
`/users/{userId}/notifications`

Parameters:
- `userId`: The user ID

### User Sessions
`/users/{userId}/sessions`

Parameters:
- `userId`: The user ID

### User Stats
`/users/{userId}/stats`

### User Award Assignments
`/users/{userId}/awardAssignments`

Parameters:
- `userId`: The user ID

### User Items
`/users/{userId}/items`

Parameters:
- `userId`: The user ID

### User Purchases
`/users/{userId}/purchases`

Parameters:
- `userId`: The user ID

### User Likes
`/users/{userId}/likes`

Parameters:
- `userId`: The user ID

### Download User Images
`/users/{userId}/images/download`

Parameters:
- `userId`: The user ID

### Bulk Users
`/users/bulk`

### Staff Users
`/users/staff`

## Badges

### Badges
`/badges`

### Badge Code Redeem
`/badges/redeem`

## Languages

### Languages
`/languages`

### Language
`/languages/{languageId}`

Parameters:
- `languageId`: The language ID

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

### Files
`/files`

## Pastes

### Paste
`/pastes/{pasteId}`

Parameters:
- `pasteId`: The paste ID

### Pastes
`/pastes`

### Paste Content
`/pastes/{pasteId}/content`

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

### Domain Nameservers
`/domains/{domainId}/nameservers`

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

### Resend Confirmation
`/confirmations/{confirmationType}/resend`

Parameters:
- `confirmationType`: The confirmation type (email, password, etc.)

## Reports

### Reports
`/reports`

### Report
`/report/{reportId}`

Parameters:
- `reportId`: The report ID

## Feedbacks

### Feedbacks
`/feedbacks`

## Password Resets

### Password Resets
`/passwordResets`

### Reset Password 
`/passwordResets/reset`

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

### Shares
`/shares`

### Bulk Shares
`/shares/bulk`

### Share
`/shares/{shareCode}`

Parameters:
- `shareCode`: The share code

### Content By Share Code Folder
`/{contentType}/by/shareCode/{shareCode}/folder`

Parameters:
- `contentType`: The content type as plural ("images", "pastes", etc.)
- `shareCode`: The share code

### Share OEmbed
`/shares/{shareCode}/oembed`

Parameters:
- `shareCode`: The share code

### Share Meta
`/shares/{shareCode}/meta`

Parameters:
- `shareCode`: The share code

### Review Share
`/shares/{shareCode}/review`

Parameters:
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

### Permission Groups Users
`/permissionGroups/users`

### Permission Group Users
`/permissionGroups/{permissionGroupId}/users`

Parameters:
- `permissionGroupId`: The permission group ID

## Locales

### Locales
`/locales`

### Locale
`/locales/{localeId}`

Parameters:
- `localeId`: The locale ID

### Report Missing Locale
`/locales/report-missing`

## Subscription Codes

### Bulk Subscription Codes
`/subscriptionCodes/bulk`

## Sessions

### Sessions Bulk
`/sessions/bulk`

### Session
`/sessions/{sessionId}`

Parameters:
- `sessionId`: The session ID

## Badge Codes

### Bulk Badge Codes
`/badgeCodes/bulk`

## Endpoints

### Endpoints
`/endpoints`

## Redirects

### Redirect
`/redirect/{string}`

Parameters:
- `string`: The redirection string

## Stats

### Stats
`/stats`

## Testimonials

### Testimonials
`/testimonials`

## Levels

### Levels
`/levels`

### Claim Level
`/levels/claim`

## Awards

### Awards
`/awards`

### Claim Award
`/awards/claim`

## Products

### Products
`/products`

## Items

### Items
`/items`

## Purchases

### Purchases
`/purchases`

## Likes

### Likes
`/likes`

## Like
`/likes/{likeId}`

Parameters:
- `likeId`: The like ID

## Award Stages

### Award Stages
`/awardStages`