## Typescript API client for dc_rest@10

This TypeScript/JavaScript client uses [axios](https://github.com/axios/axios) and is compatible with the following environments:

Environment
* Node.js
* Webpack
* Browserify

Language level
* ES5 - you must have a Promises/A+ library installed
* ES6

Module system
* CommonJS
* ES6 module system

It can be used in both TypeScript and JavaScript. In TypeScript, the definition will be automatically resolved via `package.json`. ([Reference](https://www.typescriptlang.org/docs/handbook/declaration-files/consumption.html))

### Building

To build and compile the typescript sources to javascript use:
```
npm install
npm run build
```

### Publishing

First build the package then run `npm publish`

### Consuming

navigate to the folder of your consuming project and run one of the following commands.

_published:_

```
npm install dc_rest@10 --save
```

_unPublished (not recommended):_

```
npm install PATH_TO_GENERATED_PACKAGE --save
```

### Documentation for API Endpoints

All URIs are relative to *https://discord.com/api/v10*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**addGroupDmUser**](docs/DefaultApi.md#addgroupdmuser) | **PUT** /channels/{channel_id}/recipients/{user_id} | 
*DefaultApi* | [**addGuildMember**](docs/DefaultApi.md#addguildmember) | **PUT** /guilds/{guild_id}/members/{user_id} | 
*DefaultApi* | [**addGuildMemberRole**](docs/DefaultApi.md#addguildmemberrole) | **PUT** /guilds/{guild_id}/members/{user_id}/roles/{role_id} | 
*DefaultApi* | [**addLobbyMember**](docs/DefaultApi.md#addlobbymember) | **PUT** /lobbies/{lobby_id}/members/{user_id} | 
*DefaultApi* | [**addMyMessageReaction**](docs/DefaultApi.md#addmymessagereaction) | **PUT** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/@me | 
*DefaultApi* | [**addThreadMember**](docs/DefaultApi.md#addthreadmember) | **PUT** /channels/{channel_id}/thread-members/{user_id} | 
*DefaultApi* | [**applicationsGetActivityInstance**](docs/DefaultApi.md#applicationsgetactivityinstance) | **GET** /applications/{application_id}/activity-instances/{instance_id} | 
*DefaultApi* | [**banUserFromGuild**](docs/DefaultApi.md#banuserfromguild) | **PUT** /guilds/{guild_id}/bans/{user_id} | 
*DefaultApi* | [**bulkBanUsersFromGuild**](docs/DefaultApi.md#bulkbanusersfromguild) | **POST** /guilds/{guild_id}/bulk-ban | 
*DefaultApi* | [**bulkDeleteMessages**](docs/DefaultApi.md#bulkdeletemessages) | **POST** /channels/{channel_id}/messages/bulk-delete | 
*DefaultApi* | [**bulkSetApplicationCommands**](docs/DefaultApi.md#bulksetapplicationcommands) | **PUT** /applications/{application_id}/commands | 
*DefaultApi* | [**bulkSetGuildApplicationCommands**](docs/DefaultApi.md#bulksetguildapplicationcommands) | **PUT** /applications/{application_id}/guilds/{guild_id}/commands | 
*DefaultApi* | [**bulkUpdateGuildChannels**](docs/DefaultApi.md#bulkupdateguildchannels) | **PATCH** /guilds/{guild_id}/channels | 
*DefaultApi* | [**bulkUpdateGuildRoles**](docs/DefaultApi.md#bulkupdateguildroles) | **PATCH** /guilds/{guild_id}/roles | 
*DefaultApi* | [**bulkUpdateLobbyMembers**](docs/DefaultApi.md#bulkupdatelobbymembers) | **POST** /lobbies/{lobby_id}/members/bulk | 
*DefaultApi* | [**consumeEntitlement**](docs/DefaultApi.md#consumeentitlement) | **POST** /applications/{application_id}/entitlements/{entitlement_id}/consume | 
*DefaultApi* | [**createApplicationCommand**](docs/DefaultApi.md#createapplicationcommand) | **POST** /applications/{application_id}/commands | 
*DefaultApi* | [**createApplicationEmoji**](docs/DefaultApi.md#createapplicationemoji) | **POST** /applications/{application_id}/emojis | 
*DefaultApi* | [**createAutoModerationRule**](docs/DefaultApi.md#createautomoderationrule) | **POST** /guilds/{guild_id}/auto-moderation/rules | 
*DefaultApi* | [**createChannelInvite**](docs/DefaultApi.md#createchannelinvite) | **POST** /channels/{channel_id}/invites | 
*DefaultApi* | [**createDm**](docs/DefaultApi.md#createdm) | **POST** /users/@me/channels | 
*DefaultApi* | [**createEntitlement**](docs/DefaultApi.md#createentitlement) | **POST** /applications/{application_id}/entitlements | 
*DefaultApi* | [**createGuild**](docs/DefaultApi.md#createguild) | **POST** /guilds | 
*DefaultApi* | [**createGuildApplicationCommand**](docs/DefaultApi.md#createguildapplicationcommand) | **POST** /applications/{application_id}/guilds/{guild_id}/commands | 
*DefaultApi* | [**createGuildChannel**](docs/DefaultApi.md#createguildchannel) | **POST** /guilds/{guild_id}/channels | 
*DefaultApi* | [**createGuildEmoji**](docs/DefaultApi.md#createguildemoji) | **POST** /guilds/{guild_id}/emojis | 
*DefaultApi* | [**createGuildFromTemplate**](docs/DefaultApi.md#createguildfromtemplate) | **POST** /guilds/templates/{code} | 
*DefaultApi* | [**createGuildRole**](docs/DefaultApi.md#createguildrole) | **POST** /guilds/{guild_id}/roles | 
*DefaultApi* | [**createGuildScheduledEvent**](docs/DefaultApi.md#createguildscheduledevent) | **POST** /guilds/{guild_id}/scheduled-events | 
*DefaultApi* | [**createGuildSoundboardSound**](docs/DefaultApi.md#createguildsoundboardsound) | **POST** /guilds/{guild_id}/soundboard-sounds | 
*DefaultApi* | [**createGuildSticker**](docs/DefaultApi.md#createguildsticker) | **POST** /guilds/{guild_id}/stickers | 
*DefaultApi* | [**createGuildTemplate**](docs/DefaultApi.md#createguildtemplate) | **POST** /guilds/{guild_id}/templates | 
*DefaultApi* | [**createInteractionResponse**](docs/DefaultApi.md#createinteractionresponse) | **POST** /interactions/{interaction_id}/{interaction_token}/callback | 
*DefaultApi* | [**createLobby**](docs/DefaultApi.md#createlobby) | **POST** /lobbies | 
*DefaultApi* | [**createLobbyMessage**](docs/DefaultApi.md#createlobbymessage) | **POST** /lobbies/{lobby_id}/messages | 
*DefaultApi* | [**createMessage**](docs/DefaultApi.md#createmessage) | **POST** /channels/{channel_id}/messages | 
*DefaultApi* | [**createOrJoinLobby**](docs/DefaultApi.md#createorjoinlobby) | **PUT** /lobbies | 
*DefaultApi* | [**createPin**](docs/DefaultApi.md#createpin) | **PUT** /channels/{channel_id}/messages/pins/{message_id} | 
*DefaultApi* | [**createStageInstance**](docs/DefaultApi.md#createstageinstance) | **POST** /stage-instances | 
*DefaultApi* | [**createThread**](docs/DefaultApi.md#createthread) | **POST** /channels/{channel_id}/threads | 
*DefaultApi* | [**createThreadFromMessage**](docs/DefaultApi.md#createthreadfrommessage) | **POST** /channels/{channel_id}/messages/{message_id}/threads | 
*DefaultApi* | [**createWebhook**](docs/DefaultApi.md#createwebhook) | **POST** /channels/{channel_id}/webhooks | 
*DefaultApi* | [**crosspostMessage**](docs/DefaultApi.md#crosspostmessage) | **POST** /channels/{channel_id}/messages/{message_id}/crosspost | 
*DefaultApi* | [**deleteAllMessageReactions**](docs/DefaultApi.md#deleteallmessagereactions) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions | 
*DefaultApi* | [**deleteAllMessageReactionsByEmoji**](docs/DefaultApi.md#deleteallmessagereactionsbyemoji) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name} | 
*DefaultApi* | [**deleteApplicationCommand**](docs/DefaultApi.md#deleteapplicationcommand) | **DELETE** /applications/{application_id}/commands/{command_id} | 
*DefaultApi* | [**deleteApplicationEmoji**](docs/DefaultApi.md#deleteapplicationemoji) | **DELETE** /applications/{application_id}/emojis/{emoji_id} | 
*DefaultApi* | [**deleteApplicationUserRoleConnection**](docs/DefaultApi.md#deleteapplicationuserroleconnection) | **DELETE** /users/@me/applications/{application_id}/role-connection | 
*DefaultApi* | [**deleteAutoModerationRule**](docs/DefaultApi.md#deleteautomoderationrule) | **DELETE** /guilds/{guild_id}/auto-moderation/rules/{rule_id} | 
*DefaultApi* | [**deleteChannel**](docs/DefaultApi.md#deletechannel) | **DELETE** /channels/{channel_id} | 
*DefaultApi* | [**deleteChannelPermissionOverwrite**](docs/DefaultApi.md#deletechannelpermissionoverwrite) | **DELETE** /channels/{channel_id}/permissions/{overwrite_id} | 
*DefaultApi* | [**deleteEntitlement**](docs/DefaultApi.md#deleteentitlement) | **DELETE** /applications/{application_id}/entitlements/{entitlement_id} | 
*DefaultApi* | [**deleteGroupDmUser**](docs/DefaultApi.md#deletegroupdmuser) | **DELETE** /channels/{channel_id}/recipients/{user_id} | 
*DefaultApi* | [**deleteGuild**](docs/DefaultApi.md#deleteguild) | **DELETE** /guilds/{guild_id} | 
*DefaultApi* | [**deleteGuildApplicationCommand**](docs/DefaultApi.md#deleteguildapplicationcommand) | **DELETE** /applications/{application_id}/guilds/{guild_id}/commands/{command_id} | 
*DefaultApi* | [**deleteGuildEmoji**](docs/DefaultApi.md#deleteguildemoji) | **DELETE** /guilds/{guild_id}/emojis/{emoji_id} | 
*DefaultApi* | [**deleteGuildIntegration**](docs/DefaultApi.md#deleteguildintegration) | **DELETE** /guilds/{guild_id}/integrations/{integration_id} | 
*DefaultApi* | [**deleteGuildMember**](docs/DefaultApi.md#deleteguildmember) | **DELETE** /guilds/{guild_id}/members/{user_id} | 
*DefaultApi* | [**deleteGuildMemberRole**](docs/DefaultApi.md#deleteguildmemberrole) | **DELETE** /guilds/{guild_id}/members/{user_id}/roles/{role_id} | 
*DefaultApi* | [**deleteGuildRole**](docs/DefaultApi.md#deleteguildrole) | **DELETE** /guilds/{guild_id}/roles/{role_id} | 
*DefaultApi* | [**deleteGuildScheduledEvent**](docs/DefaultApi.md#deleteguildscheduledevent) | **DELETE** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id} | 
*DefaultApi* | [**deleteGuildSoundboardSound**](docs/DefaultApi.md#deleteguildsoundboardsound) | **DELETE** /guilds/{guild_id}/soundboard-sounds/{sound_id} | 
*DefaultApi* | [**deleteGuildSticker**](docs/DefaultApi.md#deleteguildsticker) | **DELETE** /guilds/{guild_id}/stickers/{sticker_id} | 
*DefaultApi* | [**deleteGuildTemplate**](docs/DefaultApi.md#deleteguildtemplate) | **DELETE** /guilds/{guild_id}/templates/{code} | 
*DefaultApi* | [**deleteLobbyMember**](docs/DefaultApi.md#deletelobbymember) | **DELETE** /lobbies/{lobby_id}/members/{user_id} | 
*DefaultApi* | [**deleteMessage**](docs/DefaultApi.md#deletemessage) | **DELETE** /channels/{channel_id}/messages/{message_id} | 
*DefaultApi* | [**deleteMyMessageReaction**](docs/DefaultApi.md#deletemymessagereaction) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/@me | 
*DefaultApi* | [**deleteOriginalWebhookMessage**](docs/DefaultApi.md#deleteoriginalwebhookmessage) | **DELETE** /webhooks/{webhook_id}/{webhook_token}/messages/@original | 
*DefaultApi* | [**deletePin**](docs/DefaultApi.md#deletepin) | **DELETE** /channels/{channel_id}/messages/pins/{message_id} | 
*DefaultApi* | [**deleteStageInstance**](docs/DefaultApi.md#deletestageinstance) | **DELETE** /stage-instances/{channel_id} | 
*DefaultApi* | [**deleteThreadMember**](docs/DefaultApi.md#deletethreadmember) | **DELETE** /channels/{channel_id}/thread-members/{user_id} | 
*DefaultApi* | [**deleteUserMessageReaction**](docs/DefaultApi.md#deleteusermessagereaction) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/{user_id} | 
*DefaultApi* | [**deleteWebhook**](docs/DefaultApi.md#deletewebhook) | **DELETE** /webhooks/{webhook_id} | 
*DefaultApi* | [**deleteWebhookByToken**](docs/DefaultApi.md#deletewebhookbytoken) | **DELETE** /webhooks/{webhook_id}/{webhook_token} | 
*DefaultApi* | [**deleteWebhookMessage**](docs/DefaultApi.md#deletewebhookmessage) | **DELETE** /webhooks/{webhook_id}/{webhook_token}/messages/{message_id} | 
*DefaultApi* | [**deprecatedCreatePin**](docs/DefaultApi.md#deprecatedcreatepin) | **PUT** /channels/{channel_id}/pins/{message_id} | 
*DefaultApi* | [**deprecatedDeletePin**](docs/DefaultApi.md#deprecateddeletepin) | **DELETE** /channels/{channel_id}/pins/{message_id} | 
*DefaultApi* | [**deprecatedListPins**](docs/DefaultApi.md#deprecatedlistpins) | **GET** /channels/{channel_id}/pins | 
*DefaultApi* | [**editLobby**](docs/DefaultApi.md#editlobby) | **PATCH** /lobbies/{lobby_id} | 
*DefaultApi* | [**editLobbyChannelLink**](docs/DefaultApi.md#editlobbychannellink) | **PATCH** /lobbies/{lobby_id}/channel-linking | 
*DefaultApi* | [**executeGithubCompatibleWebhook**](docs/DefaultApi.md#executegithubcompatiblewebhook) | **POST** /webhooks/{webhook_id}/{webhook_token}/github | 
*DefaultApi* | [**executeSlackCompatibleWebhook**](docs/DefaultApi.md#executeslackcompatiblewebhook) | **POST** /webhooks/{webhook_id}/{webhook_token}/slack | 
*DefaultApi* | [**executeWebhook**](docs/DefaultApi.md#executewebhook) | **POST** /webhooks/{webhook_id}/{webhook_token} | 
*DefaultApi* | [**followChannel**](docs/DefaultApi.md#followchannel) | **POST** /channels/{channel_id}/followers | 
*DefaultApi* | [**getActiveGuildThreads**](docs/DefaultApi.md#getactiveguildthreads) | **GET** /guilds/{guild_id}/threads/active | 
*DefaultApi* | [**getAnswerVoters**](docs/DefaultApi.md#getanswervoters) | **GET** /channels/{channel_id}/polls/{message_id}/answers/{answer_id} | 
*DefaultApi* | [**getApplication**](docs/DefaultApi.md#getapplication) | **GET** /applications/{application_id} | 
*DefaultApi* | [**getApplicationCommand**](docs/DefaultApi.md#getapplicationcommand) | **GET** /applications/{application_id}/commands/{command_id} | 
*DefaultApi* | [**getApplicationEmoji**](docs/DefaultApi.md#getapplicationemoji) | **GET** /applications/{application_id}/emojis/{emoji_id} | 
*DefaultApi* | [**getApplicationRoleConnectionsMetadata**](docs/DefaultApi.md#getapplicationroleconnectionsmetadata) | **GET** /applications/{application_id}/role-connections/metadata | 
*DefaultApi* | [**getApplicationUserRoleConnection**](docs/DefaultApi.md#getapplicationuserroleconnection) | **GET** /users/@me/applications/{application_id}/role-connection | 
*DefaultApi* | [**getAutoModerationRule**](docs/DefaultApi.md#getautomoderationrule) | **GET** /guilds/{guild_id}/auto-moderation/rules/{rule_id} | 
*DefaultApi* | [**getBotGateway**](docs/DefaultApi.md#getbotgateway) | **GET** /gateway/bot | 
*DefaultApi* | [**getChannel**](docs/DefaultApi.md#getchannel) | **GET** /channels/{channel_id} | 
*DefaultApi* | [**getEntitlement**](docs/DefaultApi.md#getentitlement) | **GET** /applications/{application_id}/entitlements/{entitlement_id} | 
*DefaultApi* | [**getEntitlements**](docs/DefaultApi.md#getentitlements) | **GET** /applications/{application_id}/entitlements | 
*DefaultApi* | [**getGateway**](docs/DefaultApi.md#getgateway) | **GET** /gateway | 
*DefaultApi* | [**getGuild**](docs/DefaultApi.md#getguild) | **GET** /guilds/{guild_id} | 
*DefaultApi* | [**getGuildApplicationCommand**](docs/DefaultApi.md#getguildapplicationcommand) | **GET** /applications/{application_id}/guilds/{guild_id}/commands/{command_id} | 
*DefaultApi* | [**getGuildApplicationCommandPermissions**](docs/DefaultApi.md#getguildapplicationcommandpermissions) | **GET** /applications/{application_id}/guilds/{guild_id}/commands/{command_id}/permissions | 
*DefaultApi* | [**getGuildBan**](docs/DefaultApi.md#getguildban) | **GET** /guilds/{guild_id}/bans/{user_id} | 
*DefaultApi* | [**getGuildEmoji**](docs/DefaultApi.md#getguildemoji) | **GET** /guilds/{guild_id}/emojis/{emoji_id} | 
*DefaultApi* | [**getGuildMember**](docs/DefaultApi.md#getguildmember) | **GET** /guilds/{guild_id}/members/{user_id} | 
*DefaultApi* | [**getGuildNewMemberWelcome**](docs/DefaultApi.md#getguildnewmemberwelcome) | **GET** /guilds/{guild_id}/new-member-welcome | 
*DefaultApi* | [**getGuildPreview**](docs/DefaultApi.md#getguildpreview) | **GET** /guilds/{guild_id}/preview | 
*DefaultApi* | [**getGuildRole**](docs/DefaultApi.md#getguildrole) | **GET** /guilds/{guild_id}/roles/{role_id} | 
*DefaultApi* | [**getGuildScheduledEvent**](docs/DefaultApi.md#getguildscheduledevent) | **GET** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id} | 
*DefaultApi* | [**getGuildSoundboardSound**](docs/DefaultApi.md#getguildsoundboardsound) | **GET** /guilds/{guild_id}/soundboard-sounds/{sound_id} | 
*DefaultApi* | [**getGuildSticker**](docs/DefaultApi.md#getguildsticker) | **GET** /guilds/{guild_id}/stickers/{sticker_id} | 
*DefaultApi* | [**getGuildTemplate**](docs/DefaultApi.md#getguildtemplate) | **GET** /guilds/templates/{code} | 
*DefaultApi* | [**getGuildVanityUrl**](docs/DefaultApi.md#getguildvanityurl) | **GET** /guilds/{guild_id}/vanity-url | 
*DefaultApi* | [**getGuildWebhooks**](docs/DefaultApi.md#getguildwebhooks) | **GET** /guilds/{guild_id}/webhooks | 
*DefaultApi* | [**getGuildWelcomeScreen**](docs/DefaultApi.md#getguildwelcomescreen) | **GET** /guilds/{guild_id}/welcome-screen | 
*DefaultApi* | [**getGuildWidget**](docs/DefaultApi.md#getguildwidget) | **GET** /guilds/{guild_id}/widget.json | 
*DefaultApi* | [**getGuildWidgetPng**](docs/DefaultApi.md#getguildwidgetpng) | **GET** /guilds/{guild_id}/widget.png | 
*DefaultApi* | [**getGuildWidgetSettings**](docs/DefaultApi.md#getguildwidgetsettings) | **GET** /guilds/{guild_id}/widget | 
*DefaultApi* | [**getGuildsOnboarding**](docs/DefaultApi.md#getguildsonboarding) | **GET** /guilds/{guild_id}/onboarding | 
*DefaultApi* | [**getLobby**](docs/DefaultApi.md#getlobby) | **GET** /lobbies/{lobby_id} | 
*DefaultApi* | [**getLobbyMessages**](docs/DefaultApi.md#getlobbymessages) | **GET** /lobbies/{lobby_id}/messages | 
*DefaultApi* | [**getMessage**](docs/DefaultApi.md#getmessage) | **GET** /channels/{channel_id}/messages/{message_id} | 
*DefaultApi* | [**getMyApplication**](docs/DefaultApi.md#getmyapplication) | **GET** /applications/@me | 
*DefaultApi* | [**getMyGuildMember**](docs/DefaultApi.md#getmyguildmember) | **GET** /users/@me/guilds/{guild_id}/member | 
*DefaultApi* | [**getMyOauth2Application**](docs/DefaultApi.md#getmyoauth2application) | **GET** /oauth2/applications/@me | 
*DefaultApi* | [**getMyOauth2Authorization**](docs/DefaultApi.md#getmyoauth2authorization) | **GET** /oauth2/@me | 
*DefaultApi* | [**getMyUser**](docs/DefaultApi.md#getmyuser) | **GET** /users/@me | 
*DefaultApi* | [**getOpenidConnectUserinfo**](docs/DefaultApi.md#getopenidconnectuserinfo) | **GET** /oauth2/userinfo | 
*DefaultApi* | [**getOriginalWebhookMessage**](docs/DefaultApi.md#getoriginalwebhookmessage) | **GET** /webhooks/{webhook_id}/{webhook_token}/messages/@original | 
*DefaultApi* | [**getPublicKeys**](docs/DefaultApi.md#getpublickeys) | **GET** /oauth2/keys | 
*DefaultApi* | [**getSelfVoiceState**](docs/DefaultApi.md#getselfvoicestate) | **GET** /guilds/{guild_id}/voice-states/@me | 
*DefaultApi* | [**getSoundboardDefaultSounds**](docs/DefaultApi.md#getsoundboarddefaultsounds) | **GET** /soundboard-default-sounds | 
*DefaultApi* | [**getStageInstance**](docs/DefaultApi.md#getstageinstance) | **GET** /stage-instances/{channel_id} | 
*DefaultApi* | [**getSticker**](docs/DefaultApi.md#getsticker) | **GET** /stickers/{sticker_id} | 
*DefaultApi* | [**getStickerPack**](docs/DefaultApi.md#getstickerpack) | **GET** /sticker-packs/{pack_id} | 
*DefaultApi* | [**getThreadMember**](docs/DefaultApi.md#getthreadmember) | **GET** /channels/{channel_id}/thread-members/{user_id} | 
*DefaultApi* | [**getUser**](docs/DefaultApi.md#getuser) | **GET** /users/{user_id} | 
*DefaultApi* | [**getVoiceState**](docs/DefaultApi.md#getvoicestate) | **GET** /guilds/{guild_id}/voice-states/{user_id} | 
*DefaultApi* | [**getWebhook**](docs/DefaultApi.md#getwebhook) | **GET** /webhooks/{webhook_id} | 
*DefaultApi* | [**getWebhookByToken**](docs/DefaultApi.md#getwebhookbytoken) | **GET** /webhooks/{webhook_id}/{webhook_token} | 
*DefaultApi* | [**getWebhookMessage**](docs/DefaultApi.md#getwebhookmessage) | **GET** /webhooks/{webhook_id}/{webhook_token}/messages/{message_id} | 
*DefaultApi* | [**inviteResolve**](docs/DefaultApi.md#inviteresolve) | **GET** /invites/{code} | 
*DefaultApi* | [**inviteRevoke**](docs/DefaultApi.md#inviterevoke) | **DELETE** /invites/{code} | 
*DefaultApi* | [**joinThread**](docs/DefaultApi.md#jointhread) | **PUT** /channels/{channel_id}/thread-members/@me | 
*DefaultApi* | [**leaveGuild**](docs/DefaultApi.md#leaveguild) | **DELETE** /users/@me/guilds/{guild_id} | 
*DefaultApi* | [**leaveLobby**](docs/DefaultApi.md#leavelobby) | **DELETE** /lobbies/{lobby_id}/members/@me | 
*DefaultApi* | [**leaveThread**](docs/DefaultApi.md#leavethread) | **DELETE** /channels/{channel_id}/thread-members/@me | 
*DefaultApi* | [**listApplicationCommands**](docs/DefaultApi.md#listapplicationcommands) | **GET** /applications/{application_id}/commands | 
*DefaultApi* | [**listApplicationEmojis**](docs/DefaultApi.md#listapplicationemojis) | **GET** /applications/{application_id}/emojis | 
*DefaultApi* | [**listAutoModerationRules**](docs/DefaultApi.md#listautomoderationrules) | **GET** /guilds/{guild_id}/auto-moderation/rules | 
*DefaultApi* | [**listChannelInvites**](docs/DefaultApi.md#listchannelinvites) | **GET** /channels/{channel_id}/invites | 
*DefaultApi* | [**listChannelWebhooks**](docs/DefaultApi.md#listchannelwebhooks) | **GET** /channels/{channel_id}/webhooks | 
*DefaultApi* | [**listGuildApplicationCommandPermissions**](docs/DefaultApi.md#listguildapplicationcommandpermissions) | **GET** /applications/{application_id}/guilds/{guild_id}/commands/permissions | 
*DefaultApi* | [**listGuildApplicationCommands**](docs/DefaultApi.md#listguildapplicationcommands) | **GET** /applications/{application_id}/guilds/{guild_id}/commands | 
*DefaultApi* | [**listGuildAuditLogEntries**](docs/DefaultApi.md#listguildauditlogentries) | **GET** /guilds/{guild_id}/audit-logs | 
*DefaultApi* | [**listGuildBans**](docs/DefaultApi.md#listguildbans) | **GET** /guilds/{guild_id}/bans | 
*DefaultApi* | [**listGuildChannels**](docs/DefaultApi.md#listguildchannels) | **GET** /guilds/{guild_id}/channels | 
*DefaultApi* | [**listGuildEmojis**](docs/DefaultApi.md#listguildemojis) | **GET** /guilds/{guild_id}/emojis | 
*DefaultApi* | [**listGuildIntegrations**](docs/DefaultApi.md#listguildintegrations) | **GET** /guilds/{guild_id}/integrations | 
*DefaultApi* | [**listGuildInvites**](docs/DefaultApi.md#listguildinvites) | **GET** /guilds/{guild_id}/invites | 
*DefaultApi* | [**listGuildMembers**](docs/DefaultApi.md#listguildmembers) | **GET** /guilds/{guild_id}/members | 
*DefaultApi* | [**listGuildRoles**](docs/DefaultApi.md#listguildroles) | **GET** /guilds/{guild_id}/roles | 
*DefaultApi* | [**listGuildScheduledEventUsers**](docs/DefaultApi.md#listguildscheduledeventusers) | **GET** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id}/users | 
*DefaultApi* | [**listGuildScheduledEvents**](docs/DefaultApi.md#listguildscheduledevents) | **GET** /guilds/{guild_id}/scheduled-events | 
*DefaultApi* | [**listGuildSoundboardSounds**](docs/DefaultApi.md#listguildsoundboardsounds) | **GET** /guilds/{guild_id}/soundboard-sounds | 
*DefaultApi* | [**listGuildStickers**](docs/DefaultApi.md#listguildstickers) | **GET** /guilds/{guild_id}/stickers | 
*DefaultApi* | [**listGuildTemplates**](docs/DefaultApi.md#listguildtemplates) | **GET** /guilds/{guild_id}/templates | 
*DefaultApi* | [**listGuildVoiceRegions**](docs/DefaultApi.md#listguildvoiceregions) | **GET** /guilds/{guild_id}/regions | 
*DefaultApi* | [**listMessageReactionsByEmoji**](docs/DefaultApi.md#listmessagereactionsbyemoji) | **GET** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name} | 
*DefaultApi* | [**listMessages**](docs/DefaultApi.md#listmessages) | **GET** /channels/{channel_id}/messages | 
*DefaultApi* | [**listMyConnections**](docs/DefaultApi.md#listmyconnections) | **GET** /users/@me/connections | 
*DefaultApi* | [**listMyGuilds**](docs/DefaultApi.md#listmyguilds) | **GET** /users/@me/guilds | 
*DefaultApi* | [**listMyPrivateArchivedThreads**](docs/DefaultApi.md#listmyprivatearchivedthreads) | **GET** /channels/{channel_id}/users/@me/threads/archived/private | 
*DefaultApi* | [**listPins**](docs/DefaultApi.md#listpins) | **GET** /channels/{channel_id}/messages/pins | 
*DefaultApi* | [**listPrivateArchivedThreads**](docs/DefaultApi.md#listprivatearchivedthreads) | **GET** /channels/{channel_id}/threads/archived/private | 
*DefaultApi* | [**listPublicArchivedThreads**](docs/DefaultApi.md#listpublicarchivedthreads) | **GET** /channels/{channel_id}/threads/archived/public | 
*DefaultApi* | [**listStickerPacks**](docs/DefaultApi.md#liststickerpacks) | **GET** /sticker-packs | 
*DefaultApi* | [**listThreadMembers**](docs/DefaultApi.md#listthreadmembers) | **GET** /channels/{channel_id}/thread-members | 
*DefaultApi* | [**listVoiceRegions**](docs/DefaultApi.md#listvoiceregions) | **GET** /voice/regions | 
*DefaultApi* | [**partnerSdkToken**](docs/DefaultApi.md#partnersdktoken) | **POST** /partner-sdk/token | 
*DefaultApi* | [**partnerSdkUnmergeProvisionalAccount**](docs/DefaultApi.md#partnersdkunmergeprovisionalaccount) | **POST** /partner-sdk/provisional-accounts/unmerge | 
*DefaultApi* | [**pollExpire**](docs/DefaultApi.md#pollexpire) | **POST** /channels/{channel_id}/polls/{message_id}/expire | 
*DefaultApi* | [**previewPruneGuild**](docs/DefaultApi.md#previewpruneguild) | **GET** /guilds/{guild_id}/prune | 
*DefaultApi* | [**pruneGuild**](docs/DefaultApi.md#pruneguild) | **POST** /guilds/{guild_id}/prune | 
*DefaultApi* | [**putGuildsOnboarding**](docs/DefaultApi.md#putguildsonboarding) | **PUT** /guilds/{guild_id}/onboarding | 
*DefaultApi* | [**searchGuildMembers**](docs/DefaultApi.md#searchguildmembers) | **GET** /guilds/{guild_id}/members/search | 
*DefaultApi* | [**sendSoundboardSound**](docs/DefaultApi.md#sendsoundboardsound) | **POST** /channels/{channel_id}/send-soundboard-sound | 
*DefaultApi* | [**setChannelPermissionOverwrite**](docs/DefaultApi.md#setchannelpermissionoverwrite) | **PUT** /channels/{channel_id}/permissions/{overwrite_id} | 
*DefaultApi* | [**setGuildApplicationCommandPermissions**](docs/DefaultApi.md#setguildapplicationcommandpermissions) | **PUT** /applications/{application_id}/guilds/{guild_id}/commands/{command_id}/permissions | 
*DefaultApi* | [**setGuildMfaLevel**](docs/DefaultApi.md#setguildmfalevel) | **POST** /guilds/{guild_id}/mfa | 
*DefaultApi* | [**syncGuildTemplate**](docs/DefaultApi.md#syncguildtemplate) | **PUT** /guilds/{guild_id}/templates/{code} | 
*DefaultApi* | [**threadSearch**](docs/DefaultApi.md#threadsearch) | **GET** /channels/{channel_id}/threads/search | 
*DefaultApi* | [**triggerTypingIndicator**](docs/DefaultApi.md#triggertypingindicator) | **POST** /channels/{channel_id}/typing | 
*DefaultApi* | [**unbanUserFromGuild**](docs/DefaultApi.md#unbanuserfromguild) | **DELETE** /guilds/{guild_id}/bans/{user_id} | 
*DefaultApi* | [**updateApplication**](docs/DefaultApi.md#updateapplication) | **PATCH** /applications/{application_id} | 
*DefaultApi* | [**updateApplicationCommand**](docs/DefaultApi.md#updateapplicationcommand) | **PATCH** /applications/{application_id}/commands/{command_id} | 
*DefaultApi* | [**updateApplicationEmoji**](docs/DefaultApi.md#updateapplicationemoji) | **PATCH** /applications/{application_id}/emojis/{emoji_id} | 
*DefaultApi* | [**updateApplicationRoleConnectionsMetadata**](docs/DefaultApi.md#updateapplicationroleconnectionsmetadata) | **PUT** /applications/{application_id}/role-connections/metadata | 
*DefaultApi* | [**updateApplicationUserRoleConnection**](docs/DefaultApi.md#updateapplicationuserroleconnection) | **PUT** /users/@me/applications/{application_id}/role-connection | 
*DefaultApi* | [**updateAutoModerationRule**](docs/DefaultApi.md#updateautomoderationrule) | **PATCH** /guilds/{guild_id}/auto-moderation/rules/{rule_id} | 
*DefaultApi* | [**updateChannel**](docs/DefaultApi.md#updatechannel) | **PATCH** /channels/{channel_id} | 
*DefaultApi* | [**updateGuild**](docs/DefaultApi.md#updateguild) | **PATCH** /guilds/{guild_id} | 
*DefaultApi* | [**updateGuildApplicationCommand**](docs/DefaultApi.md#updateguildapplicationcommand) | **PATCH** /applications/{application_id}/guilds/{guild_id}/commands/{command_id} | 
*DefaultApi* | [**updateGuildEmoji**](docs/DefaultApi.md#updateguildemoji) | **PATCH** /guilds/{guild_id}/emojis/{emoji_id} | 
*DefaultApi* | [**updateGuildMember**](docs/DefaultApi.md#updateguildmember) | **PATCH** /guilds/{guild_id}/members/{user_id} | 
*DefaultApi* | [**updateGuildRole**](docs/DefaultApi.md#updateguildrole) | **PATCH** /guilds/{guild_id}/roles/{role_id} | 
*DefaultApi* | [**updateGuildScheduledEvent**](docs/DefaultApi.md#updateguildscheduledevent) | **PATCH** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id} | 
*DefaultApi* | [**updateGuildSoundboardSound**](docs/DefaultApi.md#updateguildsoundboardsound) | **PATCH** /guilds/{guild_id}/soundboard-sounds/{sound_id} | 
*DefaultApi* | [**updateGuildSticker**](docs/DefaultApi.md#updateguildsticker) | **PATCH** /guilds/{guild_id}/stickers/{sticker_id} | 
*DefaultApi* | [**updateGuildTemplate**](docs/DefaultApi.md#updateguildtemplate) | **PATCH** /guilds/{guild_id}/templates/{code} | 
*DefaultApi* | [**updateGuildWelcomeScreen**](docs/DefaultApi.md#updateguildwelcomescreen) | **PATCH** /guilds/{guild_id}/welcome-screen | 
*DefaultApi* | [**updateGuildWidgetSettings**](docs/DefaultApi.md#updateguildwidgetsettings) | **PATCH** /guilds/{guild_id}/widget | 
*DefaultApi* | [**updateMessage**](docs/DefaultApi.md#updatemessage) | **PATCH** /channels/{channel_id}/messages/{message_id} | 
*DefaultApi* | [**updateMyApplication**](docs/DefaultApi.md#updatemyapplication) | **PATCH** /applications/@me | 
*DefaultApi* | [**updateMyGuildMember**](docs/DefaultApi.md#updatemyguildmember) | **PATCH** /guilds/{guild_id}/members/@me | 
*DefaultApi* | [**updateMyUser**](docs/DefaultApi.md#updatemyuser) | **PATCH** /users/@me | 
*DefaultApi* | [**updateOriginalWebhookMessage**](docs/DefaultApi.md#updateoriginalwebhookmessage) | **PATCH** /webhooks/{webhook_id}/{webhook_token}/messages/@original | 
*DefaultApi* | [**updateSelfVoiceState**](docs/DefaultApi.md#updateselfvoicestate) | **PATCH** /guilds/{guild_id}/voice-states/@me | 
*DefaultApi* | [**updateStageInstance**](docs/DefaultApi.md#updatestageinstance) | **PATCH** /stage-instances/{channel_id} | 
*DefaultApi* | [**updateVoiceState**](docs/DefaultApi.md#updatevoicestate) | **PATCH** /guilds/{guild_id}/voice-states/{user_id} | 
*DefaultApi* | [**updateWebhook**](docs/DefaultApi.md#updatewebhook) | **PATCH** /webhooks/{webhook_id} | 
*DefaultApi* | [**updateWebhookByToken**](docs/DefaultApi.md#updatewebhookbytoken) | **PATCH** /webhooks/{webhook_id}/{webhook_token} | 
*DefaultApi* | [**updateWebhookMessage**](docs/DefaultApi.md#updatewebhookmessage) | **PATCH** /webhooks/{webhook_id}/{webhook_token}/messages/{message_id} | 
*DefaultApi* | [**uploadApplicationAttachment**](docs/DefaultApi.md#uploadapplicationattachment) | **POST** /applications/{application_id}/attachment | 


### Documentation For Models

 - [AccountResponse](docs/AccountResponse.md)
 - [ActionRowComponentForMessageRequest](docs/ActionRowComponentForMessageRequest.md)
 - [ActionRowComponentForMessageRequestComponentsInner](docs/ActionRowComponentForMessageRequestComponentsInner.md)
 - [ActionRowComponentForModalRequest](docs/ActionRowComponentForModalRequest.md)
 - [ActionRowComponentResponse](docs/ActionRowComponentResponse.md)
 - [ActionRowComponentResponseComponentsInner](docs/ActionRowComponentResponseComponentsInner.md)
 - [ActivitiesAttachmentResponse](docs/ActivitiesAttachmentResponse.md)
 - [AddGroupDmUser201Response](docs/AddGroupDmUser201Response.md)
 - [AddGroupDmUserRequest](docs/AddGroupDmUserRequest.md)
 - [AddGuildMemberRequest](docs/AddGuildMemberRequest.md)
 - [AddLobbyMemberRequest](docs/AddLobbyMemberRequest.md)
 - [ApplicationCommandAttachmentOption](docs/ApplicationCommandAttachmentOption.md)
 - [ApplicationCommandAttachmentOptionResponse](docs/ApplicationCommandAttachmentOptionResponse.md)
 - [ApplicationCommandAutocompleteCallbackRequest](docs/ApplicationCommandAutocompleteCallbackRequest.md)
 - [ApplicationCommandAutocompleteCallbackRequestData](docs/ApplicationCommandAutocompleteCallbackRequestData.md)
 - [ApplicationCommandBooleanOption](docs/ApplicationCommandBooleanOption.md)
 - [ApplicationCommandBooleanOptionResponse](docs/ApplicationCommandBooleanOptionResponse.md)
 - [ApplicationCommandChannelOption](docs/ApplicationCommandChannelOption.md)
 - [ApplicationCommandChannelOptionResponse](docs/ApplicationCommandChannelOptionResponse.md)
 - [ApplicationCommandCreateRequest](docs/ApplicationCommandCreateRequest.md)
 - [ApplicationCommandCreateRequestOptionsInner](docs/ApplicationCommandCreateRequestOptionsInner.md)
 - [ApplicationCommandIntegerOption](docs/ApplicationCommandIntegerOption.md)
 - [ApplicationCommandIntegerOptionResponse](docs/ApplicationCommandIntegerOptionResponse.md)
 - [ApplicationCommandInteractionMetadataResponse](docs/ApplicationCommandInteractionMetadataResponse.md)
 - [ApplicationCommandMentionableOption](docs/ApplicationCommandMentionableOption.md)
 - [ApplicationCommandMentionableOptionResponse](docs/ApplicationCommandMentionableOptionResponse.md)
 - [ApplicationCommandNumberOption](docs/ApplicationCommandNumberOption.md)
 - [ApplicationCommandNumberOptionResponse](docs/ApplicationCommandNumberOptionResponse.md)
 - [ApplicationCommandOptionIntegerChoice](docs/ApplicationCommandOptionIntegerChoice.md)
 - [ApplicationCommandOptionIntegerChoiceResponse](docs/ApplicationCommandOptionIntegerChoiceResponse.md)
 - [ApplicationCommandOptionNumberChoice](docs/ApplicationCommandOptionNumberChoice.md)
 - [ApplicationCommandOptionNumberChoiceResponse](docs/ApplicationCommandOptionNumberChoiceResponse.md)
 - [ApplicationCommandOptionStringChoice](docs/ApplicationCommandOptionStringChoice.md)
 - [ApplicationCommandOptionStringChoiceResponse](docs/ApplicationCommandOptionStringChoiceResponse.md)
 - [ApplicationCommandPatchRequestPartial](docs/ApplicationCommandPatchRequestPartial.md)
 - [ApplicationCommandPermission](docs/ApplicationCommandPermission.md)
 - [ApplicationCommandResponse](docs/ApplicationCommandResponse.md)
 - [ApplicationCommandResponseOptionsInner](docs/ApplicationCommandResponseOptionsInner.md)
 - [ApplicationCommandRoleOption](docs/ApplicationCommandRoleOption.md)
 - [ApplicationCommandRoleOptionResponse](docs/ApplicationCommandRoleOptionResponse.md)
 - [ApplicationCommandStringOption](docs/ApplicationCommandStringOption.md)
 - [ApplicationCommandStringOptionResponse](docs/ApplicationCommandStringOptionResponse.md)
 - [ApplicationCommandSubcommandGroupOption](docs/ApplicationCommandSubcommandGroupOption.md)
 - [ApplicationCommandSubcommandGroupOptionResponse](docs/ApplicationCommandSubcommandGroupOptionResponse.md)
 - [ApplicationCommandSubcommandOption](docs/ApplicationCommandSubcommandOption.md)
 - [ApplicationCommandSubcommandOptionOptionsInner](docs/ApplicationCommandSubcommandOptionOptionsInner.md)
 - [ApplicationCommandSubcommandOptionResponse](docs/ApplicationCommandSubcommandOptionResponse.md)
 - [ApplicationCommandSubcommandOptionResponseOptionsInner](docs/ApplicationCommandSubcommandOptionResponseOptionsInner.md)
 - [ApplicationCommandUpdateRequest](docs/ApplicationCommandUpdateRequest.md)
 - [ApplicationCommandUserOption](docs/ApplicationCommandUserOption.md)
 - [ApplicationCommandUserOptionResponse](docs/ApplicationCommandUserOptionResponse.md)
 - [ApplicationFormPartial](docs/ApplicationFormPartial.md)
 - [ApplicationFormPartialDescription](docs/ApplicationFormPartialDescription.md)
 - [ApplicationFormPartialIntegrationTypesConfigValue](docs/ApplicationFormPartialIntegrationTypesConfigValue.md)
 - [ApplicationIncomingWebhookResponse](docs/ApplicationIncomingWebhookResponse.md)
 - [ApplicationIntegrationTypeConfiguration](docs/ApplicationIntegrationTypeConfiguration.md)
 - [ApplicationIntegrationTypeConfigurationResponse](docs/ApplicationIntegrationTypeConfigurationResponse.md)
 - [ApplicationOAuth2InstallParams](docs/ApplicationOAuth2InstallParams.md)
 - [ApplicationOAuth2InstallParamsResponse](docs/ApplicationOAuth2InstallParamsResponse.md)
 - [ApplicationResponse](docs/ApplicationResponse.md)
 - [ApplicationRoleConnectionsMetadataItemRequest](docs/ApplicationRoleConnectionsMetadataItemRequest.md)
 - [ApplicationRoleConnectionsMetadataItemResponse](docs/ApplicationRoleConnectionsMetadataItemResponse.md)
 - [ApplicationUserRoleConnectionResponse](docs/ApplicationUserRoleConnectionResponse.md)
 - [AttachmentResponse](docs/AttachmentResponse.md)
 - [AuditLogEntryResponse](docs/AuditLogEntryResponse.md)
 - [AuditLogObjectChangeResponse](docs/AuditLogObjectChangeResponse.md)
 - [BanUserFromGuildRequest](docs/BanUserFromGuildRequest.md)
 - [BaseCreateMessageCreateRequest](docs/BaseCreateMessageCreateRequest.md)
 - [BaseCreateMessageCreateRequestComponentsInner](docs/BaseCreateMessageCreateRequestComponentsInner.md)
 - [BasicApplicationResponse](docs/BasicApplicationResponse.md)
 - [BasicMessageResponse](docs/BasicMessageResponse.md)
 - [BasicMessageResponseComponentsInner](docs/BasicMessageResponseComponentsInner.md)
 - [BasicMessageResponseInteractionMetadata](docs/BasicMessageResponseInteractionMetadata.md)
 - [BasicMessageResponseNonce](docs/BasicMessageResponseNonce.md)
 - [BlockMessageAction](docs/BlockMessageAction.md)
 - [BlockMessageActionMetadata](docs/BlockMessageActionMetadata.md)
 - [BlockMessageActionMetadataResponse](docs/BlockMessageActionMetadataResponse.md)
 - [BlockMessageActionResponse](docs/BlockMessageActionResponse.md)
 - [BotAccountPatchRequest](docs/BotAccountPatchRequest.md)
 - [BulkBanUsersFromGuildRequest](docs/BulkBanUsersFromGuildRequest.md)
 - [BulkBanUsersResponse](docs/BulkBanUsersResponse.md)
 - [BulkDeleteMessagesRequest](docs/BulkDeleteMessagesRequest.md)
 - [BulkLobbyMemberRequest](docs/BulkLobbyMemberRequest.md)
 - [BulkUpdateGuildChannelsRequestInner](docs/BulkUpdateGuildChannelsRequestInner.md)
 - [BulkUpdateGuildRolesRequestInner](docs/BulkUpdateGuildRolesRequestInner.md)
 - [ButtonComponentForMessageRequest](docs/ButtonComponentForMessageRequest.md)
 - [ButtonComponentResponse](docs/ButtonComponentResponse.md)
 - [ChannelFollowerResponse](docs/ChannelFollowerResponse.md)
 - [ChannelFollowerWebhookResponse](docs/ChannelFollowerWebhookResponse.md)
 - [ChannelPermissionOverwriteRequest](docs/ChannelPermissionOverwriteRequest.md)
 - [ChannelPermissionOverwriteResponse](docs/ChannelPermissionOverwriteResponse.md)
 - [ChannelSelectComponentForMessageRequest](docs/ChannelSelectComponentForMessageRequest.md)
 - [ChannelSelectComponentResponse](docs/ChannelSelectComponentResponse.md)
 - [ChannelSelectDefaultValue](docs/ChannelSelectDefaultValue.md)
 - [ChannelSelectDefaultValueResponse](docs/ChannelSelectDefaultValueResponse.md)
 - [CommandPermissionResponse](docs/CommandPermissionResponse.md)
 - [CommandPermissionsResponse](docs/CommandPermissionsResponse.md)
 - [ComponentEmojiForMessageRequest](docs/ComponentEmojiForMessageRequest.md)
 - [ComponentEmojiResponse](docs/ComponentEmojiResponse.md)
 - [ConnectedAccountGuildResponse](docs/ConnectedAccountGuildResponse.md)
 - [ConnectedAccountIntegrationResponse](docs/ConnectedAccountIntegrationResponse.md)
 - [ConnectedAccountResponse](docs/ConnectedAccountResponse.md)
 - [ContainerComponentForMessageRequest](docs/ContainerComponentForMessageRequest.md)
 - [ContainerComponentForMessageRequestComponentsInner](docs/ContainerComponentForMessageRequestComponentsInner.md)
 - [ContainerComponentResponse](docs/ContainerComponentResponse.md)
 - [ContainerComponentResponseComponentsInner](docs/ContainerComponentResponseComponentsInner.md)
 - [CreateApplicationEmojiRequest](docs/CreateApplicationEmojiRequest.md)
 - [CreateAutoModerationRule200Response](docs/CreateAutoModerationRule200Response.md)
 - [CreateAutoModerationRuleRequest](docs/CreateAutoModerationRuleRequest.md)
 - [CreateChannelInviteRequest](docs/CreateChannelInviteRequest.md)
 - [CreateEntitlementRequestData](docs/CreateEntitlementRequestData.md)
 - [CreateForumThreadRequest](docs/CreateForumThreadRequest.md)
 - [CreateGroupDMInviteRequest](docs/CreateGroupDMInviteRequest.md)
 - [CreateGuildChannelRequest](docs/CreateGuildChannelRequest.md)
 - [CreateGuildEmojiRequest](docs/CreateGuildEmojiRequest.md)
 - [CreateGuildFromTemplateRequest](docs/CreateGuildFromTemplateRequest.md)
 - [CreateGuildInviteRequest](docs/CreateGuildInviteRequest.md)
 - [CreateGuildRequestChannelItem](docs/CreateGuildRequestChannelItem.md)
 - [CreateGuildRequestRoleItem](docs/CreateGuildRequestRoleItem.md)
 - [CreateGuildRoleRequest](docs/CreateGuildRoleRequest.md)
 - [CreateGuildScheduledEventRequest](docs/CreateGuildScheduledEventRequest.md)
 - [CreateGuildTemplateRequest](docs/CreateGuildTemplateRequest.md)
 - [CreateInteractionResponseRequest](docs/CreateInteractionResponseRequest.md)
 - [CreateLobbyRequest](docs/CreateLobbyRequest.md)
 - [CreateMessageInteractionCallbackRequest](docs/CreateMessageInteractionCallbackRequest.md)
 - [CreateMessageInteractionCallbackResponse](docs/CreateMessageInteractionCallbackResponse.md)
 - [CreateOrJoinLobbyRequest](docs/CreateOrJoinLobbyRequest.md)
 - [CreateOrUpdateThreadTagRequest](docs/CreateOrUpdateThreadTagRequest.md)
 - [CreatePrivateChannelRequest](docs/CreatePrivateChannelRequest.md)
 - [CreateStageInstanceRequest](docs/CreateStageInstanceRequest.md)
 - [CreateTextThreadWithMessageRequest](docs/CreateTextThreadWithMessageRequest.md)
 - [CreateTextThreadWithoutMessageRequest](docs/CreateTextThreadWithoutMessageRequest.md)
 - [CreateThreadRequest](docs/CreateThreadRequest.md)
 - [CreateWebhookRequest](docs/CreateWebhookRequest.md)
 - [CreatedThreadResponse](docs/CreatedThreadResponse.md)
 - [DefaultKeywordListTriggerMetadata](docs/DefaultKeywordListTriggerMetadata.md)
 - [DefaultKeywordListTriggerMetadataResponse](docs/DefaultKeywordListTriggerMetadataResponse.md)
 - [DefaultKeywordListUpsertRequest](docs/DefaultKeywordListUpsertRequest.md)
 - [DefaultKeywordListUpsertRequestActionsInner](docs/DefaultKeywordListUpsertRequestActionsInner.md)
 - [DefaultKeywordListUpsertRequestPartial](docs/DefaultKeywordListUpsertRequestPartial.md)
 - [DefaultKeywordRuleResponse](docs/DefaultKeywordRuleResponse.md)
 - [DefaultKeywordRuleResponseActionsInner](docs/DefaultKeywordRuleResponseActionsInner.md)
 - [DefaultReactionEmojiResponse](docs/DefaultReactionEmojiResponse.md)
 - [DiscordIntegrationResponse](docs/DiscordIntegrationResponse.md)
 - [EditLobbyChannelLinkRequest](docs/EditLobbyChannelLinkRequest.md)
 - [EmbeddedActivityInstance](docs/EmbeddedActivityInstance.md)
 - [EmbeddedActivityInstanceLocation](docs/EmbeddedActivityInstanceLocation.md)
 - [EmojiResponse](docs/EmojiResponse.md)
 - [EntitlementResponse](docs/EntitlementResponse.md)
 - [EntityMetadataExternal](docs/EntityMetadataExternal.md)
 - [EntityMetadataExternalResponse](docs/EntityMetadataExternalResponse.md)
 - [ErrorDetails](docs/ErrorDetails.md)
 - [ErrorResponse](docs/ErrorResponse.md)
 - [ExecuteWebhookRequest](docs/ExecuteWebhookRequest.md)
 - [ExternalConnectionIntegrationResponse](docs/ExternalConnectionIntegrationResponse.md)
 - [ExternalScheduledEventCreateRequest](docs/ExternalScheduledEventCreateRequest.md)
 - [ExternalScheduledEventPatchRequestPartial](docs/ExternalScheduledEventPatchRequestPartial.md)
 - [ExternalScheduledEventResponse](docs/ExternalScheduledEventResponse.md)
 - [FileComponentForMessageRequest](docs/FileComponentForMessageRequest.md)
 - [FileComponentResponse](docs/FileComponentResponse.md)
 - [FlagToChannelAction](docs/FlagToChannelAction.md)
 - [FlagToChannelActionMetadata](docs/FlagToChannelActionMetadata.md)
 - [FlagToChannelActionMetadataResponse](docs/FlagToChannelActionMetadataResponse.md)
 - [FlagToChannelActionResponse](docs/FlagToChannelActionResponse.md)
 - [FollowChannelRequest](docs/FollowChannelRequest.md)
 - [ForumTagResponse](docs/ForumTagResponse.md)
 - [FriendInviteResponse](docs/FriendInviteResponse.md)
 - [GatewayBotResponse](docs/GatewayBotResponse.md)
 - [GatewayBotSessionStartLimitResponse](docs/GatewayBotSessionStartLimitResponse.md)
 - [GatewayResponse](docs/GatewayResponse.md)
 - [GetChannel200Response](docs/GetChannel200Response.md)
 - [GetEntitlementsSkuIdsParameter](docs/GetEntitlementsSkuIdsParameter.md)
 - [GetSticker200Response](docs/GetSticker200Response.md)
 - [GithubAuthor](docs/GithubAuthor.md)
 - [GithubCheckApp](docs/GithubCheckApp.md)
 - [GithubCheckPullRequest](docs/GithubCheckPullRequest.md)
 - [GithubCheckRun](docs/GithubCheckRun.md)
 - [GithubCheckRunOutput](docs/GithubCheckRunOutput.md)
 - [GithubCheckSuite](docs/GithubCheckSuite.md)
 - [GithubComment](docs/GithubComment.md)
 - [GithubCommit](docs/GithubCommit.md)
 - [GithubDiscussion](docs/GithubDiscussion.md)
 - [GithubIssue](docs/GithubIssue.md)
 - [GithubRelease](docs/GithubRelease.md)
 - [GithubRepository](docs/GithubRepository.md)
 - [GithubReview](docs/GithubReview.md)
 - [GithubUser](docs/GithubUser.md)
 - [GithubWebhook](docs/GithubWebhook.md)
 - [GroupDMInviteResponse](docs/GroupDMInviteResponse.md)
 - [GuildAuditLogResponse](docs/GuildAuditLogResponse.md)
 - [GuildAuditLogResponseIntegrationsInner](docs/GuildAuditLogResponseIntegrationsInner.md)
 - [GuildBanResponse](docs/GuildBanResponse.md)
 - [GuildChannelLocation](docs/GuildChannelLocation.md)
 - [GuildChannelResponse](docs/GuildChannelResponse.md)
 - [GuildCreateRequest](docs/GuildCreateRequest.md)
 - [GuildHomeSettingsResponse](docs/GuildHomeSettingsResponse.md)
 - [GuildIncomingWebhookResponse](docs/GuildIncomingWebhookResponse.md)
 - [GuildInviteResponse](docs/GuildInviteResponse.md)
 - [GuildMFALevelResponse](docs/GuildMFALevelResponse.md)
 - [GuildMemberResponse](docs/GuildMemberResponse.md)
 - [GuildOnboardingResponse](docs/GuildOnboardingResponse.md)
 - [GuildPatchRequestPartial](docs/GuildPatchRequestPartial.md)
 - [GuildPreviewResponse](docs/GuildPreviewResponse.md)
 - [GuildProductPurchaseResponse](docs/GuildProductPurchaseResponse.md)
 - [GuildPruneResponse](docs/GuildPruneResponse.md)
 - [GuildResponse](docs/GuildResponse.md)
 - [GuildRoleResponse](docs/GuildRoleResponse.md)
 - [GuildRoleTagsResponse](docs/GuildRoleTagsResponse.md)
 - [GuildStickerResponse](docs/GuildStickerResponse.md)
 - [GuildSubscriptionIntegrationResponse](docs/GuildSubscriptionIntegrationResponse.md)
 - [GuildTemplateChannelResponse](docs/GuildTemplateChannelResponse.md)
 - [GuildTemplateChannelTags](docs/GuildTemplateChannelTags.md)
 - [GuildTemplateResponse](docs/GuildTemplateResponse.md)
 - [GuildTemplateRoleResponse](docs/GuildTemplateRoleResponse.md)
 - [GuildTemplateSnapshotResponse](docs/GuildTemplateSnapshotResponse.md)
 - [GuildWelcomeChannel](docs/GuildWelcomeChannel.md)
 - [GuildWelcomeScreenChannelResponse](docs/GuildWelcomeScreenChannelResponse.md)
 - [GuildWelcomeScreenResponse](docs/GuildWelcomeScreenResponse.md)
 - [GuildWithCountsResponse](docs/GuildWithCountsResponse.md)
 - [IncomingWebhookInteractionRequest](docs/IncomingWebhookInteractionRequest.md)
 - [IncomingWebhookRequestPartial](docs/IncomingWebhookRequestPartial.md)
 - [IncomingWebhookUpdateForInteractionCallbackRequestPartial](docs/IncomingWebhookUpdateForInteractionCallbackRequestPartial.md)
 - [IncomingWebhookUpdateRequestPartial](docs/IncomingWebhookUpdateRequestPartial.md)
 - [InnerErrors](docs/InnerErrors.md)
 - [IntegrationApplicationResponse](docs/IntegrationApplicationResponse.md)
 - [InteractionApplicationCommandAutocompleteCallbackIntegerData](docs/InteractionApplicationCommandAutocompleteCallbackIntegerData.md)
 - [InteractionApplicationCommandAutocompleteCallbackNumberData](docs/InteractionApplicationCommandAutocompleteCallbackNumberData.md)
 - [InteractionApplicationCommandAutocompleteCallbackStringData](docs/InteractionApplicationCommandAutocompleteCallbackStringData.md)
 - [InteractionCallbackResponse](docs/InteractionCallbackResponse.md)
 - [InteractionCallbackResponseResource](docs/InteractionCallbackResponseResource.md)
 - [InteractionResponse](docs/InteractionResponse.md)
 - [InviteApplicationResponse](docs/InviteApplicationResponse.md)
 - [InviteChannelRecipientResponse](docs/InviteChannelRecipientResponse.md)
 - [InviteChannelResponse](docs/InviteChannelResponse.md)
 - [InviteGuildResponse](docs/InviteGuildResponse.md)
 - [KeywordRuleResponse](docs/KeywordRuleResponse.md)
 - [KeywordTriggerMetadata](docs/KeywordTriggerMetadata.md)
 - [KeywordTriggerMetadataResponse](docs/KeywordTriggerMetadataResponse.md)
 - [KeywordUpsertRequest](docs/KeywordUpsertRequest.md)
 - [KeywordUpsertRequestPartial](docs/KeywordUpsertRequestPartial.md)
 - [LaunchActivityInteractionCallbackRequest](docs/LaunchActivityInteractionCallbackRequest.md)
 - [LaunchActivityInteractionCallbackResponse](docs/LaunchActivityInteractionCallbackResponse.md)
 - [ListApplicationEmojisResponse](docs/ListApplicationEmojisResponse.md)
 - [ListAutoModerationRules200ResponseInner](docs/ListAutoModerationRules200ResponseInner.md)
 - [ListChannelInvites200ResponseInner](docs/ListChannelInvites200ResponseInner.md)
 - [ListChannelWebhooks200ResponseInner](docs/ListChannelWebhooks200ResponseInner.md)
 - [ListGuildIntegrations200ResponseInner](docs/ListGuildIntegrations200ResponseInner.md)
 - [ListGuildScheduledEvents200ResponseInner](docs/ListGuildScheduledEvents200ResponseInner.md)
 - [ListGuildSoundboardSoundsResponse](docs/ListGuildSoundboardSoundsResponse.md)
 - [LobbyMemberRequest](docs/LobbyMemberRequest.md)
 - [LobbyMemberResponse](docs/LobbyMemberResponse.md)
 - [LobbyMessageResponse](docs/LobbyMessageResponse.md)
 - [LobbyResponse](docs/LobbyResponse.md)
 - [MLSpamRuleResponse](docs/MLSpamRuleResponse.md)
 - [MLSpamUpsertRequest](docs/MLSpamUpsertRequest.md)
 - [MLSpamUpsertRequestPartial](docs/MLSpamUpsertRequestPartial.md)
 - [MediaGalleryComponentForMessageRequest](docs/MediaGalleryComponentForMessageRequest.md)
 - [MediaGalleryComponentResponse](docs/MediaGalleryComponentResponse.md)
 - [MediaGalleryItemRequest](docs/MediaGalleryItemRequest.md)
 - [MediaGalleryItemResponse](docs/MediaGalleryItemResponse.md)
 - [MentionSpamRuleResponse](docs/MentionSpamRuleResponse.md)
 - [MentionSpamTriggerMetadata](docs/MentionSpamTriggerMetadata.md)
 - [MentionSpamTriggerMetadataResponse](docs/MentionSpamTriggerMetadataResponse.md)
 - [MentionSpamUpsertRequest](docs/MentionSpamUpsertRequest.md)
 - [MentionSpamUpsertRequestPartial](docs/MentionSpamUpsertRequestPartial.md)
 - [MentionableSelectComponentForMessageRequest](docs/MentionableSelectComponentForMessageRequest.md)
 - [MentionableSelectComponentForMessageRequestDefaultValuesInner](docs/MentionableSelectComponentForMessageRequestDefaultValuesInner.md)
 - [MentionableSelectComponentResponse](docs/MentionableSelectComponentResponse.md)
 - [MentionableSelectComponentResponseDefaultValuesInner](docs/MentionableSelectComponentResponseDefaultValuesInner.md)
 - [MessageAllowedMentionsRequest](docs/MessageAllowedMentionsRequest.md)
 - [MessageAttachmentRequest](docs/MessageAttachmentRequest.md)
 - [MessageAttachmentResponse](docs/MessageAttachmentResponse.md)
 - [MessageCallResponse](docs/MessageCallResponse.md)
 - [MessageComponentInteractionMetadataResponse](docs/MessageComponentInteractionMetadataResponse.md)
 - [MessageCreateRequest](docs/MessageCreateRequest.md)
 - [MessageEditRequestPartial](docs/MessageEditRequestPartial.md)
 - [MessageEmbedAuthorResponse](docs/MessageEmbedAuthorResponse.md)
 - [MessageEmbedFieldResponse](docs/MessageEmbedFieldResponse.md)
 - [MessageEmbedFooterResponse](docs/MessageEmbedFooterResponse.md)
 - [MessageEmbedImageResponse](docs/MessageEmbedImageResponse.md)
 - [MessageEmbedProviderResponse](docs/MessageEmbedProviderResponse.md)
 - [MessageEmbedResponse](docs/MessageEmbedResponse.md)
 - [MessageEmbedVideoResponse](docs/MessageEmbedVideoResponse.md)
 - [MessageInteractionResponse](docs/MessageInteractionResponse.md)
 - [MessageMentionChannelResponse](docs/MessageMentionChannelResponse.md)
 - [MessageReactionCountDetailsResponse](docs/MessageReactionCountDetailsResponse.md)
 - [MessageReactionEmojiResponse](docs/MessageReactionEmojiResponse.md)
 - [MessageReactionResponse](docs/MessageReactionResponse.md)
 - [MessageReferenceRequest](docs/MessageReferenceRequest.md)
 - [MessageReferenceResponse](docs/MessageReferenceResponse.md)
 - [MessageResponse](docs/MessageResponse.md)
 - [MessageRoleSubscriptionDataResponse](docs/MessageRoleSubscriptionDataResponse.md)
 - [MessageSnapshotResponse](docs/MessageSnapshotResponse.md)
 - [MessageStickerItemResponse](docs/MessageStickerItemResponse.md)
 - [MinimalContentMessageResponse](docs/MinimalContentMessageResponse.md)
 - [ModalInteractionCallbackRequest](docs/ModalInteractionCallbackRequest.md)
 - [ModalInteractionCallbackRequestData](docs/ModalInteractionCallbackRequestData.md)
 - [ModalSubmitInteractionMetadataResponse](docs/ModalSubmitInteractionMetadataResponse.md)
 - [ModalSubmitInteractionMetadataResponseTriggeringInteractionMetadata](docs/ModalSubmitInteractionMetadataResponseTriggeringInteractionMetadata.md)
 - [ModelError](docs/ModelError.md)
 - [MyGuildResponse](docs/MyGuildResponse.md)
 - [NewMemberActionResponse](docs/NewMemberActionResponse.md)
 - [OAuth2GetAuthorizationResponse](docs/OAuth2GetAuthorizationResponse.md)
 - [OAuth2GetKeys](docs/OAuth2GetKeys.md)
 - [OAuth2GetOpenIDConnectUserInfoResponse](docs/OAuth2GetOpenIDConnectUserInfoResponse.md)
 - [OAuth2Key](docs/OAuth2Key.md)
 - [OnboardingPromptOptionRequest](docs/OnboardingPromptOptionRequest.md)
 - [OnboardingPromptOptionResponse](docs/OnboardingPromptOptionResponse.md)
 - [OnboardingPromptResponse](docs/OnboardingPromptResponse.md)
 - [PartialDiscordIntegrationResponse](docs/PartialDiscordIntegrationResponse.md)
 - [PartialExternalConnectionIntegrationResponse](docs/PartialExternalConnectionIntegrationResponse.md)
 - [PartialGuildSubscriptionIntegrationResponse](docs/PartialGuildSubscriptionIntegrationResponse.md)
 - [PartnerSdkUnmergeProvisionalAccountRequest](docs/PartnerSdkUnmergeProvisionalAccountRequest.md)
 - [PinnedMessageResponse](docs/PinnedMessageResponse.md)
 - [PinnedMessagesResponse](docs/PinnedMessagesResponse.md)
 - [PollAnswerCreateRequest](docs/PollAnswerCreateRequest.md)
 - [PollAnswerDetailsResponse](docs/PollAnswerDetailsResponse.md)
 - [PollAnswerResponse](docs/PollAnswerResponse.md)
 - [PollCreateRequest](docs/PollCreateRequest.md)
 - [PollEmoji](docs/PollEmoji.md)
 - [PollEmojiCreateRequest](docs/PollEmojiCreateRequest.md)
 - [PollMedia](docs/PollMedia.md)
 - [PollMediaCreateRequest](docs/PollMediaCreateRequest.md)
 - [PollMediaResponse](docs/PollMediaResponse.md)
 - [PollResponse](docs/PollResponse.md)
 - [PollResultsEntryResponse](docs/PollResultsEntryResponse.md)
 - [PollResultsResponse](docs/PollResultsResponse.md)
 - [PongInteractionCallbackRequest](docs/PongInteractionCallbackRequest.md)
 - [PrivateApplicationResponse](docs/PrivateApplicationResponse.md)
 - [PrivateChannelLocation](docs/PrivateChannelLocation.md)
 - [PrivateChannelResponse](docs/PrivateChannelResponse.md)
 - [PrivateGroupChannelResponse](docs/PrivateGroupChannelResponse.md)
 - [PrivateGuildMemberResponse](docs/PrivateGuildMemberResponse.md)
 - [ProvisionalTokenResponse](docs/ProvisionalTokenResponse.md)
 - [PruneGuildRequest](docs/PruneGuildRequest.md)
 - [PruneGuildRequestIncludeRoles](docs/PruneGuildRequestIncludeRoles.md)
 - [PurchaseNotificationResponse](docs/PurchaseNotificationResponse.md)
 - [QuarantineUserAction](docs/QuarantineUserAction.md)
 - [QuarantineUserActionResponse](docs/QuarantineUserActionResponse.md)
 - [ResolvedObjectsResponse](docs/ResolvedObjectsResponse.md)
 - [ResourceChannelResponse](docs/ResourceChannelResponse.md)
 - [RichEmbed](docs/RichEmbed.md)
 - [RichEmbedAuthor](docs/RichEmbedAuthor.md)
 - [RichEmbedField](docs/RichEmbedField.md)
 - [RichEmbedFooter](docs/RichEmbedFooter.md)
 - [RichEmbedImage](docs/RichEmbedImage.md)
 - [RichEmbedProvider](docs/RichEmbedProvider.md)
 - [RichEmbedThumbnail](docs/RichEmbedThumbnail.md)
 - [RichEmbedVideo](docs/RichEmbedVideo.md)
 - [RoleSelectComponentForMessageRequest](docs/RoleSelectComponentForMessageRequest.md)
 - [RoleSelectComponentResponse](docs/RoleSelectComponentResponse.md)
 - [RoleSelectDefaultValue](docs/RoleSelectDefaultValue.md)
 - [RoleSelectDefaultValueResponse](docs/RoleSelectDefaultValueResponse.md)
 - [SDKMessageRequest](docs/SDKMessageRequest.md)
 - [ScheduledEventResponse](docs/ScheduledEventResponse.md)
 - [ScheduledEventUserResponse](docs/ScheduledEventUserResponse.md)
 - [SectionComponentForMessageRequest](docs/SectionComponentForMessageRequest.md)
 - [SectionComponentForMessageRequestAccessory](docs/SectionComponentForMessageRequestAccessory.md)
 - [SectionComponentResponse](docs/SectionComponentResponse.md)
 - [SectionComponentResponseAccessory](docs/SectionComponentResponseAccessory.md)
 - [SeparatorComponentForMessageRequest](docs/SeparatorComponentForMessageRequest.md)
 - [SeparatorComponentResponse](docs/SeparatorComponentResponse.md)
 - [SetChannelPermissionOverwriteRequest](docs/SetChannelPermissionOverwriteRequest.md)
 - [SetGuildApplicationCommandPermissionsRequest](docs/SetGuildApplicationCommandPermissionsRequest.md)
 - [SetGuildMfaLevelRequest](docs/SetGuildMfaLevelRequest.md)
 - [SettingsEmojiResponse](docs/SettingsEmojiResponse.md)
 - [SlackWebhook](docs/SlackWebhook.md)
 - [SoundboardCreateRequest](docs/SoundboardCreateRequest.md)
 - [SoundboardPatchRequestPartial](docs/SoundboardPatchRequestPartial.md)
 - [SoundboardSoundResponse](docs/SoundboardSoundResponse.md)
 - [SoundboardSoundSendRequest](docs/SoundboardSoundSendRequest.md)
 - [SpamLinkRuleResponse](docs/SpamLinkRuleResponse.md)
 - [StageInstanceResponse](docs/StageInstanceResponse.md)
 - [StageScheduledEventCreateRequest](docs/StageScheduledEventCreateRequest.md)
 - [StageScheduledEventPatchRequestPartial](docs/StageScheduledEventPatchRequestPartial.md)
 - [StageScheduledEventResponse](docs/StageScheduledEventResponse.md)
 - [StandardStickerResponse](docs/StandardStickerResponse.md)
 - [StickerPackCollectionResponse](docs/StickerPackCollectionResponse.md)
 - [StickerPackResponse](docs/StickerPackResponse.md)
 - [StringSelectComponentForMessageRequest](docs/StringSelectComponentForMessageRequest.md)
 - [StringSelectComponentResponse](docs/StringSelectComponentResponse.md)
 - [StringSelectOptionForMessageRequest](docs/StringSelectOptionForMessageRequest.md)
 - [StringSelectOptionResponse](docs/StringSelectOptionResponse.md)
 - [TeamMemberResponse](docs/TeamMemberResponse.md)
 - [TeamResponse](docs/TeamResponse.md)
 - [TextDisplayComponentForMessageRequest](docs/TextDisplayComponentForMessageRequest.md)
 - [TextDisplayComponentResponse](docs/TextDisplayComponentResponse.md)
 - [TextInputComponentForModalRequest](docs/TextInputComponentForModalRequest.md)
 - [TextInputComponentResponse](docs/TextInputComponentResponse.md)
 - [ThreadMemberResponse](docs/ThreadMemberResponse.md)
 - [ThreadMetadataResponse](docs/ThreadMetadataResponse.md)
 - [ThreadResponse](docs/ThreadResponse.md)
 - [ThreadSearchResponse](docs/ThreadSearchResponse.md)
 - [ThreadSearchTagParameter](docs/ThreadSearchTagParameter.md)
 - [ThreadsResponse](docs/ThreadsResponse.md)
 - [ThumbnailComponentForMessageRequest](docs/ThumbnailComponentForMessageRequest.md)
 - [ThumbnailComponentResponse](docs/ThumbnailComponentResponse.md)
 - [UnfurledMediaRequest](docs/UnfurledMediaRequest.md)
 - [UnfurledMediaRequestWithAttachmentReferenceRequired](docs/UnfurledMediaRequestWithAttachmentReferenceRequired.md)
 - [UnfurledMediaResponse](docs/UnfurledMediaResponse.md)
 - [UpdateApplicationEmojiRequest](docs/UpdateApplicationEmojiRequest.md)
 - [UpdateApplicationUserRoleConnectionRequest](docs/UpdateApplicationUserRoleConnectionRequest.md)
 - [UpdateAutoModerationRuleRequest](docs/UpdateAutoModerationRuleRequest.md)
 - [UpdateChannelRequest](docs/UpdateChannelRequest.md)
 - [UpdateDMRequestPartial](docs/UpdateDMRequestPartial.md)
 - [UpdateDefaultReactionEmojiRequest](docs/UpdateDefaultReactionEmojiRequest.md)
 - [UpdateGroupDMRequestPartial](docs/UpdateGroupDMRequestPartial.md)
 - [UpdateGuildChannelRequestPartial](docs/UpdateGuildChannelRequestPartial.md)
 - [UpdateGuildEmojiRequest](docs/UpdateGuildEmojiRequest.md)
 - [UpdateGuildMemberRequest](docs/UpdateGuildMemberRequest.md)
 - [UpdateGuildOnboardingRequest](docs/UpdateGuildOnboardingRequest.md)
 - [UpdateGuildScheduledEventRequest](docs/UpdateGuildScheduledEventRequest.md)
 - [UpdateGuildStickerRequest](docs/UpdateGuildStickerRequest.md)
 - [UpdateGuildTemplateRequest](docs/UpdateGuildTemplateRequest.md)
 - [UpdateGuildWidgetSettingsRequest](docs/UpdateGuildWidgetSettingsRequest.md)
 - [UpdateMessageInteractionCallbackRequest](docs/UpdateMessageInteractionCallbackRequest.md)
 - [UpdateMessageInteractionCallbackResponse](docs/UpdateMessageInteractionCallbackResponse.md)
 - [UpdateMyGuildMemberRequest](docs/UpdateMyGuildMemberRequest.md)
 - [UpdateOnboardingPromptRequest](docs/UpdateOnboardingPromptRequest.md)
 - [UpdateSelfVoiceStateRequest](docs/UpdateSelfVoiceStateRequest.md)
 - [UpdateStageInstanceRequest](docs/UpdateStageInstanceRequest.md)
 - [UpdateThreadRequestPartial](docs/UpdateThreadRequestPartial.md)
 - [UpdateThreadTagRequest](docs/UpdateThreadTagRequest.md)
 - [UpdateVoiceStateRequest](docs/UpdateVoiceStateRequest.md)
 - [UpdateWebhookByTokenRequest](docs/UpdateWebhookByTokenRequest.md)
 - [UpdateWebhookRequest](docs/UpdateWebhookRequest.md)
 - [UserAvatarDecorationResponse](docs/UserAvatarDecorationResponse.md)
 - [UserCollectiblesResponse](docs/UserCollectiblesResponse.md)
 - [UserCommunicationDisabledAction](docs/UserCommunicationDisabledAction.md)
 - [UserCommunicationDisabledActionMetadata](docs/UserCommunicationDisabledActionMetadata.md)
 - [UserCommunicationDisabledActionMetadataResponse](docs/UserCommunicationDisabledActionMetadataResponse.md)
 - [UserCommunicationDisabledActionResponse](docs/UserCommunicationDisabledActionResponse.md)
 - [UserGuildOnboardingResponse](docs/UserGuildOnboardingResponse.md)
 - [UserNameplateResponse](docs/UserNameplateResponse.md)
 - [UserPIIResponse](docs/UserPIIResponse.md)
 - [UserPrimaryGuildResponse](docs/UserPrimaryGuildResponse.md)
 - [UserResponse](docs/UserResponse.md)
 - [UserSelectComponentForMessageRequest](docs/UserSelectComponentForMessageRequest.md)
 - [UserSelectComponentResponse](docs/UserSelectComponentResponse.md)
 - [UserSelectDefaultValue](docs/UserSelectDefaultValue.md)
 - [UserSelectDefaultValueResponse](docs/UserSelectDefaultValueResponse.md)
 - [VanityURLErrorResponse](docs/VanityURLErrorResponse.md)
 - [VanityURLResponse](docs/VanityURLResponse.md)
 - [VoiceRegionResponse](docs/VoiceRegionResponse.md)
 - [VoiceScheduledEventCreateRequest](docs/VoiceScheduledEventCreateRequest.md)
 - [VoiceScheduledEventPatchRequestPartial](docs/VoiceScheduledEventPatchRequestPartial.md)
 - [VoiceScheduledEventResponse](docs/VoiceScheduledEventResponse.md)
 - [VoiceStateResponse](docs/VoiceStateResponse.md)
 - [WebhookSlackEmbed](docs/WebhookSlackEmbed.md)
 - [WebhookSlackEmbedField](docs/WebhookSlackEmbedField.md)
 - [WebhookSourceChannelResponse](docs/WebhookSourceChannelResponse.md)
 - [WebhookSourceGuildResponse](docs/WebhookSourceGuildResponse.md)
 - [WelcomeMessageResponse](docs/WelcomeMessageResponse.md)
 - [WelcomeScreenPatchRequestPartial](docs/WelcomeScreenPatchRequestPartial.md)
 - [WidgetActivity](docs/WidgetActivity.md)
 - [WidgetChannel](docs/WidgetChannel.md)
 - [WidgetMember](docs/WidgetMember.md)
 - [WidgetResponse](docs/WidgetResponse.md)
 - [WidgetSettingsResponse](docs/WidgetSettingsResponse.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization


Authentication schemes defined for the API:
<a id="BotToken"></a>
### BotToken

- **Type**: API key
- **API key parameter name**: Authorization
- **Location**: HTTP header

<a id="OAuth2"></a>
### OAuth2

- **Type**: OAuth
- **Flow**: implicit
- **Authorization URL**: https://discord.com/api/oauth2/authorize
- **Scopes**: 
 - **activities.invites.write**: allows your app to send activity invites - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
 - **activities.read**: allows your app to fetch data from a user\'s \"Now Playing/Recently Played\" list - requires Discord approval
 - **activities.write**: allows your app to update a user\'s activity - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
 - **applications.builds.read**: allows your app to read build data for a user\'s applications
 - **applications.builds.upload**: allows your app to upload/update builds for a user\'s applications - requires Discord approval
 - **applications.commands**: allows your app to use commands in a guild
 - **applications.commands.permissions.update**: allows your app to update permissions for its commands in a guild a user has permissions to
 - **applications.entitlements**: allows your app to read entitlements for a user\'s applications
 - **applications.store.update**: allows your app to read and update store data (SKUs, store listings, achievements, etc.) for a user\'s applications
 - **bot**: for oauth2 bots, this puts the bot in the user\'s selected guild by default
 - **connections**: allows /users/@me/connections to return linked third-party accounts
 - **dm_channels.read**: allows your app to see information about the user\'s DMs and group DMs - requires Discord approval
 - **email**: enables /users/@me to return an email
 - **gdm.join**: allows your app to join users to a group dm
 - **guilds**: allows /users/@me/guilds to return basic information about all of a user\'s guilds
 - **guilds.join**: allows /guilds/{guild.id}/members/{user.id} to be used for joining users to a guild
 - **guilds.members.read**: allows /users/@me/guilds/{guild.id}/member to return a user\'s member information in a guild
 - **identify**: allows /users/@me without email
 - **messages.read**: for local rpc server api access, this allows you to read messages from all client channels (otherwise restricted to channels/guilds your app creates)
 - **openid**: for OpenID Connect, this allows your app to receive user id and basic profile information
 - **relationships.read**: allows your app to know a user\'s friends and implicit relationships - requires Discord approval
 - **rpc**: for local rpc server access, this allows you to control a user\'s local Discord client - requires Discord approval
 - **rpc.activities.write**: for local rpc server access, this allows you to update a user\'s activity - requires Discord approval
 - **rpc.notifications.read**: for local rpc server access, this allows you to receive notifications pushed out to the user - requires Discord approval
 - **rpc.screenshare.read**: for local rpc server access, this allows you to read a user\'s screenshare status- requires Discord approval
 - **rpc.screenshare.write**: for local rpc server access, this allows you to update a user\'s screenshare settings- requires Discord approval
 - **rpc.video.read**: for local rpc server access, this allows you to read a user\'s video status - requires Discord approval
 - **rpc.video.write**: for local rpc server access, this allows you to update a user\'s video settings - requires Discord approval
 - **rpc.voice.read**: for local rpc server access, this allows you to read a user\'s voice settings and listen for voice events - requires Discord approval
 - **rpc.voice.write**: for local rpc server access, this allows you to update a user\'s voice settings - requires Discord approval
 - **voice**: allows your app to connect to voice on user\'s behalf and see all the voice members - requires Discord approval
 - **webhook.incoming**: this generates a webhook that is returned in the oauth token response for authorization code grants

<a id="OAuth2"></a>
### OAuth2

- **Type**: OAuth
- **Flow**: application
- **Authorization URL**: 
- **Scopes**: 
 - **activities.invites.write**: allows your app to send activity invites - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
 - **activities.read**: allows your app to fetch data from a user\'s \"Now Playing/Recently Played\" list - requires Discord approval
 - **activities.write**: allows your app to update a user\'s activity - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
 - **applications.builds.read**: allows your app to read build data for a user\'s applications
 - **applications.builds.upload**: allows your app to upload/update builds for a user\'s applications - requires Discord approval
 - **applications.commands**: allows your app to use commands in a guild
 - **applications.commands.permissions.update**: allows your app to update permissions for its commands in a guild a user has permissions to
 - **applications.commands.update**: allows your app to update its commands using a Bearer token - client credentials grant only
 - **applications.entitlements**: allows your app to read entitlements for a user\'s applications
 - **applications.store.update**: allows your app to read and update store data (SKUs, store listings, achievements, etc.) for a user\'s applications
 - **bot**: for oauth2 bots, this puts the bot in the user\'s selected guild by default
 - **connections**: allows /users/@me/connections to return linked third-party accounts
 - **dm_channels.read**: allows your app to see information about the user\'s DMs and group DMs - requires Discord approval
 - **email**: enables /users/@me to return an email
 - **gdm.join**: allows your app to join users to a group dm
 - **guilds**: allows /users/@me/guilds to return basic information about all of a user\'s guilds
 - **guilds.join**: allows /guilds/{guild.id}/members/{user.id} to be used for joining users to a guild
 - **guilds.members.read**: allows /users/@me/guilds/{guild.id}/member to return a user\'s member information in a guild
 - **identify**: allows /users/@me without email
 - **messages.read**: for local rpc server api access, this allows you to read messages from all client channels (otherwise restricted to channels/guilds your app creates)
 - **openid**: for OpenID Connect, this allows your app to receive user id and basic profile information
 - **relationships.read**: allows your app to know a user\'s friends and implicit relationships - requires Discord approval
 - **rpc**: for local rpc server access, this allows you to control a user\'s local Discord client - requires Discord approval
 - **rpc.activities.write**: for local rpc server access, this allows you to update a user\'s activity - requires Discord approval
 - **rpc.notifications.read**: for local rpc server access, this allows you to receive notifications pushed out to the user - requires Discord approval
 - **rpc.screenshare.read**: for local rpc server access, this allows you to read a user\'s screenshare status- requires Discord approval
 - **rpc.screenshare.write**: for local rpc server access, this allows you to update a user\'s screenshare settings- requires Discord approval
 - **rpc.video.read**: for local rpc server access, this allows you to read a user\'s video status - requires Discord approval
 - **rpc.video.write**: for local rpc server access, this allows you to update a user\'s video settings - requires Discord approval
 - **rpc.voice.read**: for local rpc server access, this allows you to read a user\'s voice settings and listen for voice events - requires Discord approval
 - **rpc.voice.write**: for local rpc server access, this allows you to update a user\'s voice settings - requires Discord approval
 - **voice**: allows your app to connect to voice on user\'s behalf and see all the voice members - requires Discord approval
 - **webhook.incoming**: this generates a webhook that is returned in the oauth token response for authorization code grants

<a id="OAuth2"></a>
### OAuth2

- **Type**: OAuth
- **Flow**: accessCode
- **Authorization URL**: https://discord.com/api/oauth2/authorize
- **Scopes**: 
 - **activities.invites.write**: allows your app to send activity invites - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
 - **activities.read**: allows your app to fetch data from a user\'s \"Now Playing/Recently Played\" list - requires Discord approval
 - **activities.write**: allows your app to update a user\'s activity - requires Discord approval (NOT REQUIRED FOR GAMESDK ACTIVITY MANAGER)
 - **applications.builds.read**: allows your app to read build data for a user\'s applications
 - **applications.builds.upload**: allows your app to upload/update builds for a user\'s applications - requires Discord approval
 - **applications.commands**: allows your app to use commands in a guild
 - **applications.commands.permissions.update**: allows your app to update permissions for its commands in a guild a user has permissions to
 - **applications.entitlements**: allows your app to read entitlements for a user\'s applications
 - **applications.store.update**: allows your app to read and update store data (SKUs, store listings, achievements, etc.) for a user\'s applications
 - **bot**: for oauth2 bots, this puts the bot in the user\'s selected guild by default
 - **connections**: allows /users/@me/connections to return linked third-party accounts
 - **dm_channels.read**: allows your app to see information about the user\'s DMs and group DMs - requires Discord approval
 - **email**: enables /users/@me to return an email
 - **gdm.join**: allows your app to join users to a group dm
 - **guilds**: allows /users/@me/guilds to return basic information about all of a user\'s guilds
 - **guilds.join**: allows /guilds/{guild.id}/members/{user.id} to be used for joining users to a guild
 - **guilds.members.read**: allows /users/@me/guilds/{guild.id}/member to return a user\'s member information in a guild
 - **identify**: allows /users/@me without email
 - **messages.read**: for local rpc server api access, this allows you to read messages from all client channels (otherwise restricted to channels/guilds your app creates)
 - **openid**: for OpenID Connect, this allows your app to receive user id and basic profile information
 - **relationships.read**: allows your app to know a user\'s friends and implicit relationships - requires Discord approval
 - **role_connections.write**: allows your app to update a user\'s connection and metadata for the app
 - **rpc**: for local rpc server access, this allows you to control a user\'s local Discord client - requires Discord approval
 - **rpc.activities.write**: for local rpc server access, this allows you to update a user\'s activity - requires Discord approval
 - **rpc.notifications.read**: for local rpc server access, this allows you to receive notifications pushed out to the user - requires Discord approval
 - **rpc.screenshare.read**: for local rpc server access, this allows you to read a user\'s screenshare status- requires Discord approval
 - **rpc.screenshare.write**: for local rpc server access, this allows you to update a user\'s screenshare settings- requires Discord approval
 - **rpc.video.read**: for local rpc server access, this allows you to read a user\'s video status - requires Discord approval
 - **rpc.video.write**: for local rpc server access, this allows you to update a user\'s video settings - requires Discord approval
 - **rpc.voice.read**: for local rpc server access, this allows you to read a user\'s voice settings and listen for voice events - requires Discord approval
 - **rpc.voice.write**: for local rpc server access, this allows you to update a user\'s voice settings - requires Discord approval
 - **voice**: allows your app to connect to voice on user\'s behalf and see all the voice members - requires Discord approval
 - **webhook.incoming**: this generates a webhook that is returned in the oauth token response for authorization code grants

