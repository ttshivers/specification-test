# selectAvatar with default avatar id

## Issues
```
Response schema mismatch: Unexpected property at #/googleDetails, Unexpected property at #/last_mobile.
```

## Request
`put https://api.vrchat.cloud/api/1/avatars/avtr_c38a1615-5bf5-42b4-84eb-a8b6c37cbd11/select`

| Header | Value |
| ------ | ----- |
| user-agent | `specification-test/@<unstable> https://github.com/vrchatapi/specification-test/issues/new` |
| cookie | `auth=<redacted>; twoFactorAuth=<redacted>` |


## Response
`200 OK`

| Header | Value |
| ------ | ----- |
| access-control-allow-credentials | `true` |
| cache-control | `private, no-cache, no-store` |
| connection | `keep-alive` |
| content-type | `application/json; charset=utf-8` |
| etag | `<redacted>` |
| pragma | `no-cache` |
| server | `cloudflare` |
| transfer-encoding | `chunked` |
| vary | `Authorization, Accept-Encoding` |
| x-frame-options | `deny` |

```jsonc
{
  "id": "usr_9439f8cc-1c6b-4dca-9a07-d2eccb570701",
  "displayName": "8cf3def6b8cea",
  "userIcon": "",
  "bio": "",
  "bioLinks": [],
  "profilePicOverride": "",
  "statusDescription": "",
  "username": "8cf3def6b8cea",
  "pastDisplayNames": [],
  "hasEmail": true,
  "hasPendingEmail": false,
  "obfuscatedEmail": "<redacted>",
  "obfuscatedPendingEmail": "",
  "emailVerified": true,
  "hasBirthday": true,
  "hideContentFilterSettings": false,
  "unsubscribe": true,
  "statusHistory": [
    "Looking to make new friends",
    "Ask me about ․․․",
    "Let's partyǃ",
    "I'm AFK right now",
    "I'm streaming on Twitch",
    "My mic is muted",
    "I'm here but busy",
    "I speak ［English］",
    "I create ․․․",
    "My discord is ․․․‚"
  ],
  "statusFirstTime": true,
  "friends": [],
  "friendGroupNames": [],
  "userLanguage": null,
  "userLanguageCode": "en",
  "currentAvatarImageUrl": "https://api.vrchat.cloud/api/1/file/file_0e8c4e32-7444-44ea-ade4-313c010d4bae/1/file",
  "currentAvatarThumbnailImageUrl": "https://api.vrchat.cloud/api/1/image/file_0e8c4e32-7444-44ea-ade4-313c010d4bae/1/256",
  "currentAvatarTags": [
    "admin_featured_legacy",
    "admin_content_reviewed"
  ],
  "currentAvatar": "avtr_c38a1615-5bf5-42b4-84eb-a8b6c37cbd11",
  "currentAvatarAssetUrl": "https://api.vrchat.cloud/api/1/file/file_534ffc10-15d0-4fc5-86d5-2dcd55f0ac45/1/file",
  "fallbackAvatar": "avtr_07917a03-5e0b-48e9-b041-e94086bc658f",
  "accountDeletionDate": null,
  "accountDeletionLog": null,
  "acceptedTOSVersion": 9,
  "acceptedPrivacyVersion": 1,
  "steamId": "",
  "steamDetails": {},
  "googleId": "",
  /**
   * Unexpected property.
   *
   * @schema CurrentUser
   * @keyword additionalProperties
   *
   * #/additionalProperties
   * #/googleDetails
   */
  "googleDetails": {},
  "oculusId": "",
  "picoId": "",
  "viveId": "",
  "hasLoggedInFromClient": false,
  "homeLocation": "",
  "twoFactorAuthEnabled": true,
  "twoFactorAuthEnabledDate": "2023-04-11T22:29:32.524Z",
  "updated_at": "<unstable: string>",
  "state": "offline",
  /**
   * Unexpected property.
   *
   * @schema CurrentUser
   * @keyword additionalProperties
   *
   * #/additionalProperties
   * #/last_mobile
   */
  "last_mobile": null,
  "tags": [
    "system_no_captcha",
    "language_eng"
  ],
  "developerType": "none",
  "last_login": "<unstable: string>",
  "last_platform": "standalonewindows",
  "allowAvatarCopying": true,
  "status": "active",
  "date_joined": "2023-04-11",
  "isFriend": false,
  "friendKey": "c61f12138fd21145f86eca5b51631932",
  "last_activity": "<unstable: string>"
}
```
