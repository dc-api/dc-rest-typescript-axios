# DefaultApi

All URIs are relative to *https://discord.com/api/v10*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**addGroupDmUser**](#addgroupdmuser) | **PUT** /channels/{channel_id}/recipients/{user_id} | |
|[**addGuildMember**](#addguildmember) | **PUT** /guilds/{guild_id}/members/{user_id} | |
|[**addGuildMemberRole**](#addguildmemberrole) | **PUT** /guilds/{guild_id}/members/{user_id}/roles/{role_id} | |
|[**addLobbyMember**](#addlobbymember) | **PUT** /lobbies/{lobby_id}/members/{user_id} | |
|[**addMyMessageReaction**](#addmymessagereaction) | **PUT** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/@me | |
|[**addThreadMember**](#addthreadmember) | **PUT** /channels/{channel_id}/thread-members/{user_id} | |
|[**applicationsGetActivityInstance**](#applicationsgetactivityinstance) | **GET** /applications/{application_id}/activity-instances/{instance_id} | |
|[**banUserFromGuild**](#banuserfromguild) | **PUT** /guilds/{guild_id}/bans/{user_id} | |
|[**botPartnerSdkToken**](#botpartnersdktoken) | **POST** /partner-sdk/token/bot | |
|[**bulkBanUsersFromGuild**](#bulkbanusersfromguild) | **POST** /guilds/{guild_id}/bulk-ban | |
|[**bulkDeleteMessages**](#bulkdeletemessages) | **POST** /channels/{channel_id}/messages/bulk-delete | |
|[**bulkSetApplicationCommands**](#bulksetapplicationcommands) | **PUT** /applications/{application_id}/commands | |
|[**bulkSetGuildApplicationCommands**](#bulksetguildapplicationcommands) | **PUT** /applications/{application_id}/guilds/{guild_id}/commands | |
|[**bulkUpdateGuildChannels**](#bulkupdateguildchannels) | **PATCH** /guilds/{guild_id}/channels | |
|[**bulkUpdateGuildRoles**](#bulkupdateguildroles) | **PATCH** /guilds/{guild_id}/roles | |
|[**bulkUpdateLobbyMembers**](#bulkupdatelobbymembers) | **POST** /lobbies/{lobby_id}/members/bulk | |
|[**consumeEntitlement**](#consumeentitlement) | **POST** /applications/{application_id}/entitlements/{entitlement_id}/consume | |
|[**createApplicationCommand**](#createapplicationcommand) | **POST** /applications/{application_id}/commands | |
|[**createApplicationEmoji**](#createapplicationemoji) | **POST** /applications/{application_id}/emojis | |
|[**createAutoModerationRule**](#createautomoderationrule) | **POST** /guilds/{guild_id}/auto-moderation/rules | |
|[**createChannelInvite**](#createchannelinvite) | **POST** /channels/{channel_id}/invites | |
|[**createDm**](#createdm) | **POST** /users/@me/channels | |
|[**createEntitlement**](#createentitlement) | **POST** /applications/{application_id}/entitlements | |
|[**createGuild**](#createguild) | **POST** /guilds | |
|[**createGuildApplicationCommand**](#createguildapplicationcommand) | **POST** /applications/{application_id}/guilds/{guild_id}/commands | |
|[**createGuildChannel**](#createguildchannel) | **POST** /guilds/{guild_id}/channels | |
|[**createGuildEmoji**](#createguildemoji) | **POST** /guilds/{guild_id}/emojis | |
|[**createGuildFromTemplate**](#createguildfromtemplate) | **POST** /guilds/templates/{code} | |
|[**createGuildRole**](#createguildrole) | **POST** /guilds/{guild_id}/roles | |
|[**createGuildScheduledEvent**](#createguildscheduledevent) | **POST** /guilds/{guild_id}/scheduled-events | |
|[**createGuildSoundboardSound**](#createguildsoundboardsound) | **POST** /guilds/{guild_id}/soundboard-sounds | |
|[**createGuildSticker**](#createguildsticker) | **POST** /guilds/{guild_id}/stickers | |
|[**createGuildTemplate**](#createguildtemplate) | **POST** /guilds/{guild_id}/templates | |
|[**createInteractionResponse**](#createinteractionresponse) | **POST** /interactions/{interaction_id}/{interaction_token}/callback | |
|[**createLinkedLobbyGuildInviteForSelf**](#createlinkedlobbyguildinviteforself) | **POST** /lobbies/{lobby_id}/members/@me/invites | |
|[**createLinkedLobbyGuildInviteForUser**](#createlinkedlobbyguildinviteforuser) | **POST** /lobbies/{lobby_id}/members/{user_id}/invites | |
|[**createLobby**](#createlobby) | **POST** /lobbies | |
|[**createLobbyMessage**](#createlobbymessage) | **POST** /lobbies/{lobby_id}/messages | |
|[**createMessage**](#createmessage) | **POST** /channels/{channel_id}/messages | |
|[**createOrJoinLobby**](#createorjoinlobby) | **PUT** /lobbies | |
|[**createPin**](#createpin) | **PUT** /channels/{channel_id}/messages/pins/{message_id} | |
|[**createStageInstance**](#createstageinstance) | **POST** /stage-instances | |
|[**createThread**](#createthread) | **POST** /channels/{channel_id}/threads | |
|[**createThreadFromMessage**](#createthreadfrommessage) | **POST** /channels/{channel_id}/messages/{message_id}/threads | |
|[**createWebhook**](#createwebhook) | **POST** /channels/{channel_id}/webhooks | |
|[**crosspostMessage**](#crosspostmessage) | **POST** /channels/{channel_id}/messages/{message_id}/crosspost | |
|[**deleteAllMessageReactions**](#deleteallmessagereactions) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions | |
|[**deleteAllMessageReactionsByEmoji**](#deleteallmessagereactionsbyemoji) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name} | |
|[**deleteApplicationCommand**](#deleteapplicationcommand) | **DELETE** /applications/{application_id}/commands/{command_id} | |
|[**deleteApplicationEmoji**](#deleteapplicationemoji) | **DELETE** /applications/{application_id}/emojis/{emoji_id} | |
|[**deleteApplicationUserRoleConnection**](#deleteapplicationuserroleconnection) | **DELETE** /users/@me/applications/{application_id}/role-connection | |
|[**deleteAutoModerationRule**](#deleteautomoderationrule) | **DELETE** /guilds/{guild_id}/auto-moderation/rules/{rule_id} | |
|[**deleteChannel**](#deletechannel) | **DELETE** /channels/{channel_id} | |
|[**deleteChannelPermissionOverwrite**](#deletechannelpermissionoverwrite) | **DELETE** /channels/{channel_id}/permissions/{overwrite_id} | |
|[**deleteEntitlement**](#deleteentitlement) | **DELETE** /applications/{application_id}/entitlements/{entitlement_id} | |
|[**deleteGroupDmUser**](#deletegroupdmuser) | **DELETE** /channels/{channel_id}/recipients/{user_id} | |
|[**deleteGuild**](#deleteguild) | **DELETE** /guilds/{guild_id} | |
|[**deleteGuildApplicationCommand**](#deleteguildapplicationcommand) | **DELETE** /applications/{application_id}/guilds/{guild_id}/commands/{command_id} | |
|[**deleteGuildEmoji**](#deleteguildemoji) | **DELETE** /guilds/{guild_id}/emojis/{emoji_id} | |
|[**deleteGuildIntegration**](#deleteguildintegration) | **DELETE** /guilds/{guild_id}/integrations/{integration_id} | |
|[**deleteGuildMember**](#deleteguildmember) | **DELETE** /guilds/{guild_id}/members/{user_id} | |
|[**deleteGuildMemberRole**](#deleteguildmemberrole) | **DELETE** /guilds/{guild_id}/members/{user_id}/roles/{role_id} | |
|[**deleteGuildRole**](#deleteguildrole) | **DELETE** /guilds/{guild_id}/roles/{role_id} | |
|[**deleteGuildScheduledEvent**](#deleteguildscheduledevent) | **DELETE** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id} | |
|[**deleteGuildSoundboardSound**](#deleteguildsoundboardsound) | **DELETE** /guilds/{guild_id}/soundboard-sounds/{sound_id} | |
|[**deleteGuildSticker**](#deleteguildsticker) | **DELETE** /guilds/{guild_id}/stickers/{sticker_id} | |
|[**deleteGuildTemplate**](#deleteguildtemplate) | **DELETE** /guilds/{guild_id}/templates/{code} | |
|[**deleteLobbyMember**](#deletelobbymember) | **DELETE** /lobbies/{lobby_id}/members/{user_id} | |
|[**deleteMessage**](#deletemessage) | **DELETE** /channels/{channel_id}/messages/{message_id} | |
|[**deleteMyMessageReaction**](#deletemymessagereaction) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/@me | |
|[**deleteOriginalWebhookMessage**](#deleteoriginalwebhookmessage) | **DELETE** /webhooks/{webhook_id}/{webhook_token}/messages/@original | |
|[**deletePin**](#deletepin) | **DELETE** /channels/{channel_id}/messages/pins/{message_id} | |
|[**deleteStageInstance**](#deletestageinstance) | **DELETE** /stage-instances/{channel_id} | |
|[**deleteThreadMember**](#deletethreadmember) | **DELETE** /channels/{channel_id}/thread-members/{user_id} | |
|[**deleteUserMessageReaction**](#deleteusermessagereaction) | **DELETE** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}/{user_id} | |
|[**deleteWebhook**](#deletewebhook) | **DELETE** /webhooks/{webhook_id} | |
|[**deleteWebhookByToken**](#deletewebhookbytoken) | **DELETE** /webhooks/{webhook_id}/{webhook_token} | |
|[**deleteWebhookMessage**](#deletewebhookmessage) | **DELETE** /webhooks/{webhook_id}/{webhook_token}/messages/{message_id} | |
|[**deprecatedCreatePin**](#deprecatedcreatepin) | **PUT** /channels/{channel_id}/pins/{message_id} | |
|[**deprecatedDeletePin**](#deprecateddeletepin) | **DELETE** /channels/{channel_id}/pins/{message_id} | |
|[**deprecatedListPins**](#deprecatedlistpins) | **GET** /channels/{channel_id}/pins | |
|[**editLobby**](#editlobby) | **PATCH** /lobbies/{lobby_id} | |
|[**editLobbyChannelLink**](#editlobbychannellink) | **PATCH** /lobbies/{lobby_id}/channel-linking | |
|[**executeGithubCompatibleWebhook**](#executegithubcompatiblewebhook) | **POST** /webhooks/{webhook_id}/{webhook_token}/github | |
|[**executeSlackCompatibleWebhook**](#executeslackcompatiblewebhook) | **POST** /webhooks/{webhook_id}/{webhook_token}/slack | |
|[**executeWebhook**](#executewebhook) | **POST** /webhooks/{webhook_id}/{webhook_token} | |
|[**followChannel**](#followchannel) | **POST** /channels/{channel_id}/followers | |
|[**getActiveGuildThreads**](#getactiveguildthreads) | **GET** /guilds/{guild_id}/threads/active | |
|[**getAnswerVoters**](#getanswervoters) | **GET** /channels/{channel_id}/polls/{message_id}/answers/{answer_id} | |
|[**getApplication**](#getapplication) | **GET** /applications/{application_id} | |
|[**getApplicationCommand**](#getapplicationcommand) | **GET** /applications/{application_id}/commands/{command_id} | |
|[**getApplicationEmoji**](#getapplicationemoji) | **GET** /applications/{application_id}/emojis/{emoji_id} | |
|[**getApplicationRoleConnectionsMetadata**](#getapplicationroleconnectionsmetadata) | **GET** /applications/{application_id}/role-connections/metadata | |
|[**getApplicationUserRoleConnection**](#getapplicationuserroleconnection) | **GET** /users/@me/applications/{application_id}/role-connection | |
|[**getAutoModerationRule**](#getautomoderationrule) | **GET** /guilds/{guild_id}/auto-moderation/rules/{rule_id} | |
|[**getBotGateway**](#getbotgateway) | **GET** /gateway/bot | |
|[**getChannel**](#getchannel) | **GET** /channels/{channel_id} | |
|[**getEntitlement**](#getentitlement) | **GET** /applications/{application_id}/entitlements/{entitlement_id} | |
|[**getEntitlements**](#getentitlements) | **GET** /applications/{application_id}/entitlements | |
|[**getGateway**](#getgateway) | **GET** /gateway | |
|[**getGuild**](#getguild) | **GET** /guilds/{guild_id} | |
|[**getGuildApplicationCommand**](#getguildapplicationcommand) | **GET** /applications/{application_id}/guilds/{guild_id}/commands/{command_id} | |
|[**getGuildApplicationCommandPermissions**](#getguildapplicationcommandpermissions) | **GET** /applications/{application_id}/guilds/{guild_id}/commands/{command_id}/permissions | |
|[**getGuildBan**](#getguildban) | **GET** /guilds/{guild_id}/bans/{user_id} | |
|[**getGuildEmoji**](#getguildemoji) | **GET** /guilds/{guild_id}/emojis/{emoji_id} | |
|[**getGuildMember**](#getguildmember) | **GET** /guilds/{guild_id}/members/{user_id} | |
|[**getGuildNewMemberWelcome**](#getguildnewmemberwelcome) | **GET** /guilds/{guild_id}/new-member-welcome | |
|[**getGuildPreview**](#getguildpreview) | **GET** /guilds/{guild_id}/preview | |
|[**getGuildRole**](#getguildrole) | **GET** /guilds/{guild_id}/roles/{role_id} | |
|[**getGuildScheduledEvent**](#getguildscheduledevent) | **GET** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id} | |
|[**getGuildSoundboardSound**](#getguildsoundboardsound) | **GET** /guilds/{guild_id}/soundboard-sounds/{sound_id} | |
|[**getGuildSticker**](#getguildsticker) | **GET** /guilds/{guild_id}/stickers/{sticker_id} | |
|[**getGuildTemplate**](#getguildtemplate) | **GET** /guilds/templates/{code} | |
|[**getGuildVanityUrl**](#getguildvanityurl) | **GET** /guilds/{guild_id}/vanity-url | |
|[**getGuildWebhooks**](#getguildwebhooks) | **GET** /guilds/{guild_id}/webhooks | |
|[**getGuildWelcomeScreen**](#getguildwelcomescreen) | **GET** /guilds/{guild_id}/welcome-screen | |
|[**getGuildWidget**](#getguildwidget) | **GET** /guilds/{guild_id}/widget.json | |
|[**getGuildWidgetPng**](#getguildwidgetpng) | **GET** /guilds/{guild_id}/widget.png | |
|[**getGuildWidgetSettings**](#getguildwidgetsettings) | **GET** /guilds/{guild_id}/widget | |
|[**getGuildsOnboarding**](#getguildsonboarding) | **GET** /guilds/{guild_id}/onboarding | |
|[**getLobby**](#getlobby) | **GET** /lobbies/{lobby_id} | |
|[**getLobbyMessages**](#getlobbymessages) | **GET** /lobbies/{lobby_id}/messages | |
|[**getMessage**](#getmessage) | **GET** /channels/{channel_id}/messages/{message_id} | |
|[**getMyApplication**](#getmyapplication) | **GET** /applications/@me | |
|[**getMyGuildMember**](#getmyguildmember) | **GET** /users/@me/guilds/{guild_id}/member | |
|[**getMyOauth2Application**](#getmyoauth2application) | **GET** /oauth2/applications/@me | |
|[**getMyOauth2Authorization**](#getmyoauth2authorization) | **GET** /oauth2/@me | |
|[**getMyUser**](#getmyuser) | **GET** /users/@me | |
|[**getOpenidConnectUserinfo**](#getopenidconnectuserinfo) | **GET** /oauth2/userinfo | |
|[**getOriginalWebhookMessage**](#getoriginalwebhookmessage) | **GET** /webhooks/{webhook_id}/{webhook_token}/messages/@original | |
|[**getPublicKeys**](#getpublickeys) | **GET** /oauth2/keys | |
|[**getSelfVoiceState**](#getselfvoicestate) | **GET** /guilds/{guild_id}/voice-states/@me | |
|[**getSoundboardDefaultSounds**](#getsoundboarddefaultsounds) | **GET** /soundboard-default-sounds | |
|[**getStageInstance**](#getstageinstance) | **GET** /stage-instances/{channel_id} | |
|[**getSticker**](#getsticker) | **GET** /stickers/{sticker_id} | |
|[**getStickerPack**](#getstickerpack) | **GET** /sticker-packs/{pack_id} | |
|[**getThreadMember**](#getthreadmember) | **GET** /channels/{channel_id}/thread-members/{user_id} | |
|[**getUser**](#getuser) | **GET** /users/{user_id} | |
|[**getVoiceState**](#getvoicestate) | **GET** /guilds/{guild_id}/voice-states/{user_id} | |
|[**getWebhook**](#getwebhook) | **GET** /webhooks/{webhook_id} | |
|[**getWebhookByToken**](#getwebhookbytoken) | **GET** /webhooks/{webhook_id}/{webhook_token} | |
|[**getWebhookMessage**](#getwebhookmessage) | **GET** /webhooks/{webhook_id}/{webhook_token}/messages/{message_id} | |
|[**inviteResolve**](#inviteresolve) | **GET** /invites/{code} | |
|[**inviteRevoke**](#inviterevoke) | **DELETE** /invites/{code} | |
|[**joinThread**](#jointhread) | **PUT** /channels/{channel_id}/thread-members/@me | |
|[**leaveGuild**](#leaveguild) | **DELETE** /users/@me/guilds/{guild_id} | |
|[**leaveLobby**](#leavelobby) | **DELETE** /lobbies/{lobby_id}/members/@me | |
|[**leaveThread**](#leavethread) | **DELETE** /channels/{channel_id}/thread-members/@me | |
|[**listApplicationCommands**](#listapplicationcommands) | **GET** /applications/{application_id}/commands | |
|[**listApplicationEmojis**](#listapplicationemojis) | **GET** /applications/{application_id}/emojis | |
|[**listAutoModerationRules**](#listautomoderationrules) | **GET** /guilds/{guild_id}/auto-moderation/rules | |
|[**listChannelInvites**](#listchannelinvites) | **GET** /channels/{channel_id}/invites | |
|[**listChannelWebhooks**](#listchannelwebhooks) | **GET** /channels/{channel_id}/webhooks | |
|[**listGuildApplicationCommandPermissions**](#listguildapplicationcommandpermissions) | **GET** /applications/{application_id}/guilds/{guild_id}/commands/permissions | |
|[**listGuildApplicationCommands**](#listguildapplicationcommands) | **GET** /applications/{application_id}/guilds/{guild_id}/commands | |
|[**listGuildAuditLogEntries**](#listguildauditlogentries) | **GET** /guilds/{guild_id}/audit-logs | |
|[**listGuildBans**](#listguildbans) | **GET** /guilds/{guild_id}/bans | |
|[**listGuildChannels**](#listguildchannels) | **GET** /guilds/{guild_id}/channels | |
|[**listGuildEmojis**](#listguildemojis) | **GET** /guilds/{guild_id}/emojis | |
|[**listGuildIntegrations**](#listguildintegrations) | **GET** /guilds/{guild_id}/integrations | |
|[**listGuildInvites**](#listguildinvites) | **GET** /guilds/{guild_id}/invites | |
|[**listGuildMembers**](#listguildmembers) | **GET** /guilds/{guild_id}/members | |
|[**listGuildRoles**](#listguildroles) | **GET** /guilds/{guild_id}/roles | |
|[**listGuildScheduledEventUsers**](#listguildscheduledeventusers) | **GET** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id}/users | |
|[**listGuildScheduledEvents**](#listguildscheduledevents) | **GET** /guilds/{guild_id}/scheduled-events | |
|[**listGuildSoundboardSounds**](#listguildsoundboardsounds) | **GET** /guilds/{guild_id}/soundboard-sounds | |
|[**listGuildStickers**](#listguildstickers) | **GET** /guilds/{guild_id}/stickers | |
|[**listGuildTemplates**](#listguildtemplates) | **GET** /guilds/{guild_id}/templates | |
|[**listGuildVoiceRegions**](#listguildvoiceregions) | **GET** /guilds/{guild_id}/regions | |
|[**listMessageReactionsByEmoji**](#listmessagereactionsbyemoji) | **GET** /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name} | |
|[**listMessages**](#listmessages) | **GET** /channels/{channel_id}/messages | |
|[**listMyConnections**](#listmyconnections) | **GET** /users/@me/connections | |
|[**listMyGuilds**](#listmyguilds) | **GET** /users/@me/guilds | |
|[**listMyPrivateArchivedThreads**](#listmyprivatearchivedthreads) | **GET** /channels/{channel_id}/users/@me/threads/archived/private | |
|[**listPins**](#listpins) | **GET** /channels/{channel_id}/messages/pins | |
|[**listPrivateArchivedThreads**](#listprivatearchivedthreads) | **GET** /channels/{channel_id}/threads/archived/private | |
|[**listPublicArchivedThreads**](#listpublicarchivedthreads) | **GET** /channels/{channel_id}/threads/archived/public | |
|[**listStickerPacks**](#liststickerpacks) | **GET** /sticker-packs | |
|[**listThreadMembers**](#listthreadmembers) | **GET** /channels/{channel_id}/thread-members | |
|[**listVoiceRegions**](#listvoiceregions) | **GET** /voice/regions | |
|[**partnerSdkToken**](#partnersdktoken) | **POST** /partner-sdk/token | |
|[**partnerSdkUnmergeProvisionalAccount**](#partnersdkunmergeprovisionalaccount) | **POST** /partner-sdk/provisional-accounts/unmerge | |
|[**pollExpire**](#pollexpire) | **POST** /channels/{channel_id}/polls/{message_id}/expire | |
|[**previewPruneGuild**](#previewpruneguild) | **GET** /guilds/{guild_id}/prune | |
|[**pruneGuild**](#pruneguild) | **POST** /guilds/{guild_id}/prune | |
|[**putGuildsOnboarding**](#putguildsonboarding) | **PUT** /guilds/{guild_id}/onboarding | |
|[**searchGuildMembers**](#searchguildmembers) | **GET** /guilds/{guild_id}/members/search | |
|[**sendSoundboardSound**](#sendsoundboardsound) | **POST** /channels/{channel_id}/send-soundboard-sound | |
|[**setChannelPermissionOverwrite**](#setchannelpermissionoverwrite) | **PUT** /channels/{channel_id}/permissions/{overwrite_id} | |
|[**setGuildApplicationCommandPermissions**](#setguildapplicationcommandpermissions) | **PUT** /applications/{application_id}/guilds/{guild_id}/commands/{command_id}/permissions | |
|[**setGuildMfaLevel**](#setguildmfalevel) | **POST** /guilds/{guild_id}/mfa | |
|[**syncGuildTemplate**](#syncguildtemplate) | **PUT** /guilds/{guild_id}/templates/{code} | |
|[**threadSearch**](#threadsearch) | **GET** /channels/{channel_id}/threads/search | |
|[**triggerTypingIndicator**](#triggertypingindicator) | **POST** /channels/{channel_id}/typing | |
|[**unbanUserFromGuild**](#unbanuserfromguild) | **DELETE** /guilds/{guild_id}/bans/{user_id} | |
|[**updateApplication**](#updateapplication) | **PATCH** /applications/{application_id} | |
|[**updateApplicationCommand**](#updateapplicationcommand) | **PATCH** /applications/{application_id}/commands/{command_id} | |
|[**updateApplicationEmoji**](#updateapplicationemoji) | **PATCH** /applications/{application_id}/emojis/{emoji_id} | |
|[**updateApplicationRoleConnectionsMetadata**](#updateapplicationroleconnectionsmetadata) | **PUT** /applications/{application_id}/role-connections/metadata | |
|[**updateApplicationUserRoleConnection**](#updateapplicationuserroleconnection) | **PUT** /users/@me/applications/{application_id}/role-connection | |
|[**updateAutoModerationRule**](#updateautomoderationrule) | **PATCH** /guilds/{guild_id}/auto-moderation/rules/{rule_id} | |
|[**updateChannel**](#updatechannel) | **PATCH** /channels/{channel_id} | |
|[**updateGuild**](#updateguild) | **PATCH** /guilds/{guild_id} | |
|[**updateGuildApplicationCommand**](#updateguildapplicationcommand) | **PATCH** /applications/{application_id}/guilds/{guild_id}/commands/{command_id} | |
|[**updateGuildEmoji**](#updateguildemoji) | **PATCH** /guilds/{guild_id}/emojis/{emoji_id} | |
|[**updateGuildMember**](#updateguildmember) | **PATCH** /guilds/{guild_id}/members/{user_id} | |
|[**updateGuildRole**](#updateguildrole) | **PATCH** /guilds/{guild_id}/roles/{role_id} | |
|[**updateGuildScheduledEvent**](#updateguildscheduledevent) | **PATCH** /guilds/{guild_id}/scheduled-events/{guild_scheduled_event_id} | |
|[**updateGuildSoundboardSound**](#updateguildsoundboardsound) | **PATCH** /guilds/{guild_id}/soundboard-sounds/{sound_id} | |
|[**updateGuildSticker**](#updateguildsticker) | **PATCH** /guilds/{guild_id}/stickers/{sticker_id} | |
|[**updateGuildTemplate**](#updateguildtemplate) | **PATCH** /guilds/{guild_id}/templates/{code} | |
|[**updateGuildWelcomeScreen**](#updateguildwelcomescreen) | **PATCH** /guilds/{guild_id}/welcome-screen | |
|[**updateGuildWidgetSettings**](#updateguildwidgetsettings) | **PATCH** /guilds/{guild_id}/widget | |
|[**updateMessage**](#updatemessage) | **PATCH** /channels/{channel_id}/messages/{message_id} | |
|[**updateMyApplication**](#updatemyapplication) | **PATCH** /applications/@me | |
|[**updateMyGuildMember**](#updatemyguildmember) | **PATCH** /guilds/{guild_id}/members/@me | |
|[**updateMyUser**](#updatemyuser) | **PATCH** /users/@me | |
|[**updateOriginalWebhookMessage**](#updateoriginalwebhookmessage) | **PATCH** /webhooks/{webhook_id}/{webhook_token}/messages/@original | |
|[**updateSelfVoiceState**](#updateselfvoicestate) | **PATCH** /guilds/{guild_id}/voice-states/@me | |
|[**updateStageInstance**](#updatestageinstance) | **PATCH** /stage-instances/{channel_id} | |
|[**updateVoiceState**](#updatevoicestate) | **PATCH** /guilds/{guild_id}/voice-states/{user_id} | |
|[**updateWebhook**](#updatewebhook) | **PATCH** /webhooks/{webhook_id} | |
|[**updateWebhookByToken**](#updatewebhookbytoken) | **PATCH** /webhooks/{webhook_id}/{webhook_token} | |
|[**updateWebhookMessage**](#updatewebhookmessage) | **PATCH** /webhooks/{webhook_id}/{webhook_token}/messages/{message_id} | |
|[**uploadApplicationAttachment**](#uploadapplicationattachment) | **POST** /applications/{application_id}/attachment | |

# **addGroupDmUser**
> AddGroupDmUser201Response addGroupDmUser(addGroupDmUserRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    AddGroupDmUserRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let userId: string; // (default to undefined)
let addGroupDmUserRequest: AddGroupDmUserRequest; //

const { status, data } = await apiInstance.addGroupDmUser(
    channelId,
    userId,
    addGroupDmUserRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **addGroupDmUserRequest** | **AddGroupDmUserRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**AddGroupDmUser201Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for add_group_dm_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for add_group_dm_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **addGuildMember**
> GuildMemberResponse addGuildMember(botAddGuildMemberRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    BotAddGuildMemberRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)
let botAddGuildMemberRequest: BotAddGuildMemberRequest; //

const { status, data } = await apiInstance.addGuildMember(
    guildId,
    userId,
    botAddGuildMemberRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **botAddGuildMemberRequest** | **BotAddGuildMemberRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**GuildMemberResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for add_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for add_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **addGuildMemberRole**
> addGuildMemberRole()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)
let roleId: string; // (default to undefined)

const { status, data } = await apiInstance.addGuildMemberRole(
    guildId,
    userId,
    roleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|
| **roleId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for add_guild_member_role |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **addLobbyMember**
> LobbyMemberResponse addLobbyMember(addLobbyMemberRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    AddLobbyMemberRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let userId: string; // (default to undefined)
let addLobbyMemberRequest: AddLobbyMemberRequest; //

const { status, data } = await apiInstance.addLobbyMember(
    lobbyId,
    userId,
    addLobbyMemberRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **addLobbyMemberRequest** | **AddLobbyMemberRequest**|  | |
| **lobbyId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyMemberResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for add_lobby_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **addMyMessageReaction**
> addMyMessageReaction()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let emojiName: string; // (default to undefined)

const { status, data } = await apiInstance.addMyMessageReaction(
    channelId,
    messageId,
    emojiName
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **emojiName** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for add_my_message_reaction |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **addThreadMember**
> addThreadMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.addThreadMember(
    channelId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for add_thread_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **applicationsGetActivityInstance**
> EmbeddedActivityInstance applicationsGetActivityInstance()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let instanceId: string; // (default to undefined)

const { status, data } = await apiInstance.applicationsGetActivityInstance(
    applicationId,
    instanceId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **instanceId** | [**string**] |  | defaults to undefined|


### Return type

**EmbeddedActivityInstance**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for applications_get_activity_instance |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **banUserFromGuild**
> banUserFromGuild(banUserFromGuildRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    BanUserFromGuildRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)
let banUserFromGuildRequest: BanUserFromGuildRequest; //

const { status, data } = await apiInstance.banUserFromGuild(
    guildId,
    userId,
    banUserFromGuildRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **banUserFromGuildRequest** | **BanUserFromGuildRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for ban_user_from_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **botPartnerSdkToken**
> ProvisionalTokenResponse botPartnerSdkToken(botPartnerSdkTokenRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    BotPartnerSdkTokenRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let botPartnerSdkTokenRequest: BotPartnerSdkTokenRequest; //

const { status, data } = await apiInstance.botPartnerSdkToken(
    botPartnerSdkTokenRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **botPartnerSdkTokenRequest** | **BotPartnerSdkTokenRequest**|  | |


### Return type

**ProvisionalTokenResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for bot_partner_sdk_token |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkBanUsersFromGuild**
> BulkBanUsersResponse bulkBanUsersFromGuild(bulkBanUsersFromGuildRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    BulkBanUsersFromGuildRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let bulkBanUsersFromGuildRequest: BulkBanUsersFromGuildRequest; //

const { status, data } = await apiInstance.bulkBanUsersFromGuild(
    guildId,
    bulkBanUsersFromGuildRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **bulkBanUsersFromGuildRequest** | **BulkBanUsersFromGuildRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**BulkBanUsersResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for bulk_ban_users_from_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkDeleteMessages**
> bulkDeleteMessages(bulkDeleteMessagesRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    BulkDeleteMessagesRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let bulkDeleteMessagesRequest: BulkDeleteMessagesRequest; //

const { status, data } = await apiInstance.bulkDeleteMessages(
    channelId,
    bulkDeleteMessagesRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **bulkDeleteMessagesRequest** | **BulkDeleteMessagesRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for bulk_delete_messages |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkSetApplicationCommands**
> Array<ApplicationCommandResponse> bulkSetApplicationCommands(applicationCommandUpdateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let applicationCommandUpdateRequest: Array<ApplicationCommandUpdateRequest>; //

const { status, data } = await apiInstance.bulkSetApplicationCommands(
    applicationId,
    applicationCommandUpdateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationCommandUpdateRequest** | **Array<ApplicationCommandUpdateRequest>**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ApplicationCommandResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for bulk_set_application_commands |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkSetGuildApplicationCommands**
> Array<ApplicationCommandResponse> bulkSetGuildApplicationCommands(applicationCommandUpdateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let applicationCommandUpdateRequest: Array<ApplicationCommandUpdateRequest>; //

const { status, data } = await apiInstance.bulkSetGuildApplicationCommands(
    applicationId,
    guildId,
    applicationCommandUpdateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationCommandUpdateRequest** | **Array<ApplicationCommandUpdateRequest>**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ApplicationCommandResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for bulk_set_guild_application_commands |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkUpdateGuildChannels**
> bulkUpdateGuildChannels(bulkUpdateGuildChannelsRequestInner)


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let bulkUpdateGuildChannelsRequestInner: Array<BulkUpdateGuildChannelsRequestInner>; //

const { status, data } = await apiInstance.bulkUpdateGuildChannels(
    guildId,
    bulkUpdateGuildChannelsRequestInner
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **bulkUpdateGuildChannelsRequestInner** | **Array<BulkUpdateGuildChannelsRequestInner>**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for bulk_update_guild_channels |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkUpdateGuildRoles**
> Array<GuildRoleResponse> bulkUpdateGuildRoles(bulkUpdateGuildRolesRequestInner)


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let bulkUpdateGuildRolesRequestInner: Array<BulkUpdateGuildRolesRequestInner>; //

const { status, data } = await apiInstance.bulkUpdateGuildRoles(
    guildId,
    bulkUpdateGuildRolesRequestInner
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **bulkUpdateGuildRolesRequestInner** | **Array<BulkUpdateGuildRolesRequestInner>**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<GuildRoleResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for bulk_update_guild_roles |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **bulkUpdateLobbyMembers**
> Array<LobbyMemberResponse> bulkUpdateLobbyMembers(bulkLobbyMemberRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let bulkLobbyMemberRequest: Array<BulkLobbyMemberRequest>; //

const { status, data } = await apiInstance.bulkUpdateLobbyMembers(
    lobbyId,
    bulkLobbyMemberRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **bulkLobbyMemberRequest** | **Array<BulkLobbyMemberRequest>**|  | |
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

**Array<LobbyMemberResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for bulk_update_lobby_members |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **consumeEntitlement**
> consumeEntitlement()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let entitlementId: string; // (default to undefined)

const { status, data } = await apiInstance.consumeEntitlement(
    applicationId,
    entitlementId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **entitlementId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for consume_entitlement |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createApplicationCommand**
> ApplicationCommandResponse createApplicationCommand(applicationCommandCreateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ApplicationCommandCreateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let applicationCommandCreateRequest: ApplicationCommandCreateRequest; //

const { status, data } = await apiInstance.createApplicationCommand(
    applicationId,
    applicationCommandCreateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationCommandCreateRequest** | **ApplicationCommandCreateRequest**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationCommandResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**201** | 201 response for create_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createApplicationEmoji**
> EmojiResponse createApplicationEmoji(createApplicationEmojiRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateApplicationEmojiRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let createApplicationEmojiRequest: CreateApplicationEmojiRequest; //

const { status, data } = await apiInstance.createApplicationEmoji(
    applicationId,
    createApplicationEmojiRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createApplicationEmojiRequest** | **CreateApplicationEmojiRequest**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**EmojiResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_application_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createAutoModerationRule**
> CreateAutoModerationRule200Response createAutoModerationRule(createAutoModerationRuleRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateAutoModerationRuleRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let createAutoModerationRuleRequest: CreateAutoModerationRuleRequest; //

const { status, data } = await apiInstance.createAutoModerationRule(
    guildId,
    createAutoModerationRuleRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createAutoModerationRuleRequest** | **CreateAutoModerationRuleRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**CreateAutoModerationRule200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_auto_moderation_rule |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createChannelInvite**
> ListChannelInvites200ResponseInner createChannelInvite(createChannelInviteRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateChannelInviteRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let createChannelInviteRequest: CreateChannelInviteRequest; //

const { status, data } = await apiInstance.createChannelInvite(
    channelId,
    createChannelInviteRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createChannelInviteRequest** | **CreateChannelInviteRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**ListChannelInvites200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_channel_invite |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for create_channel_invite |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createDm**
> AddGroupDmUser201Response createDm(createPrivateChannelRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreatePrivateChannelRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let createPrivateChannelRequest: CreatePrivateChannelRequest; //

const { status, data } = await apiInstance.createDm(
    createPrivateChannelRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createPrivateChannelRequest** | **CreatePrivateChannelRequest**|  | |


### Return type

**AddGroupDmUser201Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_dm |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createEntitlement**
> EntitlementResponse createEntitlement(createEntitlementRequestData)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateEntitlementRequestData
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let createEntitlementRequestData: CreateEntitlementRequestData; //

const { status, data } = await apiInstance.createEntitlement(
    applicationId,
    createEntitlementRequestData
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createEntitlementRequestData** | **CreateEntitlementRequestData**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**EntitlementResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_entitlement |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuild**
> GuildResponse createGuild(guildCreateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    GuildCreateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildCreateRequest: GuildCreateRequest; //

const { status, data } = await apiInstance.createGuild(
    guildCreateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildCreateRequest** | **GuildCreateRequest**|  | |


### Return type

**GuildResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildApplicationCommand**
> ApplicationCommandResponse createGuildApplicationCommand(applicationCommandCreateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ApplicationCommandCreateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let applicationCommandCreateRequest: ApplicationCommandCreateRequest; //

const { status, data } = await apiInstance.createGuildApplicationCommand(
    applicationId,
    guildId,
    applicationCommandCreateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationCommandCreateRequest** | **ApplicationCommandCreateRequest**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationCommandResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_guild_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**201** | 201 response for create_guild_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildChannel**
> GuildChannelResponse createGuildChannel(createGuildChannelRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildChannelRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let createGuildChannelRequest: CreateGuildChannelRequest; //

const { status, data } = await apiInstance.createGuildChannel(
    guildId,
    createGuildChannelRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildChannelRequest** | **CreateGuildChannelRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildChannelResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_guild_channel |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildEmoji**
> EmojiResponse createGuildEmoji(createGuildEmojiRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildEmojiRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let createGuildEmojiRequest: CreateGuildEmojiRequest; //

const { status, data } = await apiInstance.createGuildEmoji(
    guildId,
    createGuildEmojiRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildEmojiRequest** | **CreateGuildEmojiRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**EmojiResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_guild_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildFromTemplate**
> GuildResponse createGuildFromTemplate(createGuildFromTemplateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildFromTemplateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let code: string; // (default to undefined)
let createGuildFromTemplateRequest: CreateGuildFromTemplateRequest; //

const { status, data } = await apiInstance.createGuildFromTemplate(
    code,
    createGuildFromTemplateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildFromTemplateRequest** | **CreateGuildFromTemplateRequest**|  | |
| **code** | [**string**] |  | defaults to undefined|


### Return type

**GuildResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_guild_from_template |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildRole**
> GuildRoleResponse createGuildRole(createGuildRoleRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildRoleRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let createGuildRoleRequest: CreateGuildRoleRequest; //

const { status, data } = await apiInstance.createGuildRole(
    guildId,
    createGuildRoleRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildRoleRequest** | **CreateGuildRoleRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildRoleResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_guild_role |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildScheduledEvent**
> ListGuildScheduledEvents200ResponseInner createGuildScheduledEvent(createGuildScheduledEventRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildScheduledEventRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let createGuildScheduledEventRequest: CreateGuildScheduledEventRequest; //

const { status, data } = await apiInstance.createGuildScheduledEvent(
    guildId,
    createGuildScheduledEventRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildScheduledEventRequest** | **CreateGuildScheduledEventRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**ListGuildScheduledEvents200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_guild_scheduled_event |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildSoundboardSound**
> SoundboardSoundResponse createGuildSoundboardSound(soundboardCreateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SoundboardCreateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let soundboardCreateRequest: SoundboardCreateRequest; //

const { status, data } = await apiInstance.createGuildSoundboardSound(
    guildId,
    soundboardCreateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **soundboardCreateRequest** | **SoundboardCreateRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**SoundboardSoundResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_guild_soundboard_sound |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildSticker**
> GuildStickerResponse createGuildSticker()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let name: string; // (default to undefined)
let tags: string; // (default to undefined)
let file: string; // (default to undefined)
let description: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.createGuildSticker(
    guildId,
    name,
    tags,
    file,
    description
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **name** | [**string**] |  | defaults to undefined|
| **tags** | [**string**] |  | defaults to undefined|
| **file** | [**string**] |  | defaults to undefined|
| **description** | [**string**] |  | (optional) defaults to undefined|


### Return type

**GuildStickerResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_guild_sticker |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createGuildTemplate**
> GuildTemplateResponse createGuildTemplate(createGuildTemplateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildTemplateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let createGuildTemplateRequest: CreateGuildTemplateRequest; //

const { status, data } = await apiInstance.createGuildTemplate(
    guildId,
    createGuildTemplateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildTemplateRequest** | **CreateGuildTemplateRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildTemplateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_guild_template |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createInteractionResponse**
> InteractionCallbackResponse createInteractionResponse(createInteractionResponseRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateInteractionResponseRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let interactionId: string; // (default to undefined)
let interactionToken: string; // (default to undefined)
let createInteractionResponseRequest: CreateInteractionResponseRequest; //
let withResponse: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.createInteractionResponse(
    interactionId,
    interactionToken,
    createInteractionResponseRequest,
    withResponse
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createInteractionResponseRequest** | **CreateInteractionResponseRequest**|  | |
| **interactionId** | [**string**] |  | defaults to undefined|
| **interactionToken** | [**string**] |  | defaults to undefined|
| **withResponse** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**InteractionCallbackResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_interaction_response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for create_interaction_response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createLinkedLobbyGuildInviteForSelf**
> LobbyGuildInviteResponse createLinkedLobbyGuildInviteForSelf()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)

const { status, data } = await apiInstance.createLinkedLobbyGuildInviteForSelf(
    lobbyId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyGuildInviteResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_linked_lobby_guild_invite_for_self |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createLinkedLobbyGuildInviteForUser**
> LobbyGuildInviteResponse createLinkedLobbyGuildInviteForUser()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.createLinkedLobbyGuildInviteForUser(
    lobbyId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lobbyId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyGuildInviteResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_linked_lobby_guild_invite_for_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createLobby**
> LobbyResponse createLobby(createLobbyRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateLobbyRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let createLobbyRequest: CreateLobbyRequest; //

const { status, data } = await apiInstance.createLobby(
    createLobbyRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createLobbyRequest** | **CreateLobbyRequest**|  | |


### Return type

**LobbyResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_lobby |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createLobbyMessage**
> LobbyMessageResponse createLobbyMessage(sDKMessageRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SDKMessageRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let sDKMessageRequest: SDKMessageRequest; //

const { status, data } = await apiInstance.createLobbyMessage(
    lobbyId,
    sDKMessageRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sDKMessageRequest** | **SDKMessageRequest**|  | |
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyMessageResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_lobby_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createMessage**
> MessageResponse createMessage(messageCreateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    MessageCreateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageCreateRequest: MessageCreateRequest; //

const { status, data } = await apiInstance.createMessage(
    channelId,
    messageCreateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **messageCreateRequest** | **MessageCreateRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createOrJoinLobby**
> LobbyResponse createOrJoinLobby(createOrJoinLobbyRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateOrJoinLobbyRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let createOrJoinLobbyRequest: CreateOrJoinLobbyRequest; //

const { status, data } = await apiInstance.createOrJoinLobby(
    createOrJoinLobbyRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createOrJoinLobbyRequest** | **CreateOrJoinLobbyRequest**|  | |


### Return type

**LobbyResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_or_join_lobby |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createPin**
> createPin()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.createPin(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for create_pin |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createStageInstance**
> StageInstanceResponse createStageInstance(createStageInstanceRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateStageInstanceRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let createStageInstanceRequest: CreateStageInstanceRequest; //

const { status, data } = await apiInstance.createStageInstance(
    createStageInstanceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createStageInstanceRequest** | **CreateStageInstanceRequest**|  | |


### Return type

**StageInstanceResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_stage_instance |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createThread**
> CreatedThreadResponse createThread(createThreadRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateThreadRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let createThreadRequest: CreateThreadRequest; //

const { status, data } = await apiInstance.createThread(
    channelId,
    createThreadRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createThreadRequest** | **CreateThreadRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**CreatedThreadResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_thread |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createThreadFromMessage**
> ThreadResponse createThreadFromMessage(createTextThreadWithMessageRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateTextThreadWithMessageRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let createTextThreadWithMessageRequest: CreateTextThreadWithMessageRequest; //

const { status, data } = await apiInstance.createThreadFromMessage(
    channelId,
    messageId,
    createTextThreadWithMessageRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createTextThreadWithMessageRequest** | **CreateTextThreadWithMessageRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

**ThreadResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | 201 response for create_thread_from_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **createWebhook**
> GuildIncomingWebhookResponse createWebhook(createWebhookRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateWebhookRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let createWebhookRequest: CreateWebhookRequest; //

const { status, data } = await apiInstance.createWebhook(
    channelId,
    createWebhookRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createWebhookRequest** | **CreateWebhookRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**GuildIncomingWebhookResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for create_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **crosspostMessage**
> MessageResponse crosspostMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.crosspostMessage(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for crosspost_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteAllMessageReactions**
> deleteAllMessageReactions()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteAllMessageReactions(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_all_message_reactions |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteAllMessageReactionsByEmoji**
> deleteAllMessageReactionsByEmoji()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let emojiName: string; // (default to undefined)

const { status, data } = await apiInstance.deleteAllMessageReactionsByEmoji(
    channelId,
    messageId,
    emojiName
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **emojiName** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_all_message_reactions_by_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteApplicationCommand**
> deleteApplicationCommand()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let commandId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteApplicationCommand(
    applicationId,
    commandId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteApplicationEmoji**
> deleteApplicationEmoji()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let emojiId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteApplicationEmoji(
    applicationId,
    emojiId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **emojiId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_application_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteApplicationUserRoleConnection**
> deleteApplicationUserRoleConnection()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteApplicationUserRoleConnection(
    applicationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_application_user_role_connection |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteAutoModerationRule**
> deleteAutoModerationRule()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let ruleId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteAutoModerationRule(
    guildId,
    ruleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **ruleId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_auto_moderation_rule |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteChannel**
> GetChannel200Response deleteChannel()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteChannel(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**GetChannel200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for delete_channel |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteChannelPermissionOverwrite**
> deleteChannelPermissionOverwrite()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let overwriteId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteChannelPermissionOverwrite(
    channelId,
    overwriteId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **overwriteId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_channel_permission_overwrite |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteEntitlement**
> deleteEntitlement()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let entitlementId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteEntitlement(
    applicationId,
    entitlementId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **entitlementId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_entitlement |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGroupDmUser**
> deleteGroupDmUser()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGroupDmUser(
    channelId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_group_dm_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuild**
> deleteGuild()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuild(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildApplicationCommand**
> deleteGuildApplicationCommand()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let commandId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildApplicationCommand(
    applicationId,
    guildId,
    commandId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildEmoji**
> deleteGuildEmoji()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let emojiId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildEmoji(
    guildId,
    emojiId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **emojiId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildIntegration**
> deleteGuildIntegration()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let integrationId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildIntegration(
    guildId,
    integrationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **integrationId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_integration |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildMember**
> deleteGuildMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildMember(
    guildId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildMemberRole**
> deleteGuildMemberRole()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)
let roleId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildMemberRole(
    guildId,
    userId,
    roleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|
| **roleId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_member_role |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildRole**
> deleteGuildRole()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let roleId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildRole(
    guildId,
    roleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **roleId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_role |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildScheduledEvent**
> deleteGuildScheduledEvent()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let guildScheduledEventId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildScheduledEvent(
    guildId,
    guildScheduledEventId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **guildScheduledEventId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_scheduled_event |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildSoundboardSound**
> deleteGuildSoundboardSound()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let soundId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildSoundboardSound(
    guildId,
    soundId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **soundId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_soundboard_sound |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildSticker**
> deleteGuildSticker()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let stickerId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildSticker(
    guildId,
    stickerId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **stickerId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_guild_sticker |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteGuildTemplate**
> GuildTemplateResponse deleteGuildTemplate()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let code: string; // (default to undefined)

const { status, data } = await apiInstance.deleteGuildTemplate(
    guildId,
    code
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **code** | [**string**] |  | defaults to undefined|


### Return type

**GuildTemplateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for delete_guild_template |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteLobbyMember**
> deleteLobbyMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteLobbyMember(
    lobbyId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lobbyId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_lobby_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteMessage**
> deleteMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteMessage(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteMyMessageReaction**
> deleteMyMessageReaction()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let emojiName: string; // (default to undefined)

const { status, data } = await apiInstance.deleteMyMessageReaction(
    channelId,
    messageId,
    emojiName
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **emojiName** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_my_message_reaction |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteOriginalWebhookMessage**
> deleteOriginalWebhookMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let threadId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.deleteOriginalWebhookMessage(
    webhookId,
    webhookToken,
    threadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_original_webhook_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deletePin**
> deletePin()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.deletePin(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_pin |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteStageInstance**
> deleteStageInstance()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteStageInstance(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_stage_instance |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteThreadMember**
> deleteThreadMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteThreadMember(
    channelId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_thread_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteUserMessageReaction**
> deleteUserMessageReaction()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let emojiName: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteUserMessageReaction(
    channelId,
    messageId,
    emojiName,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **emojiName** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_user_message_reaction |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteWebhook**
> deleteWebhook()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteWebhook(
    webhookId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteWebhookByToken**
> deleteWebhookByToken()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)

const { status, data } = await apiInstance.deleteWebhookByToken(
    webhookId,
    webhookToken
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_webhook_by_token |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deleteWebhookMessage**
> deleteWebhookMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let messageId: string; // (default to undefined)
let threadId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.deleteWebhookMessage(
    webhookId,
    webhookToken,
    messageId,
    threadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for delete_webhook_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deprecatedCreatePin**
> deprecatedCreatePin()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.deprecatedCreatePin(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for deprecated_create_pin |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deprecatedDeletePin**
> deprecatedDeletePin()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.deprecatedDeletePin(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for deprecated_delete_pin |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deprecatedListPins**
> Array<MessageResponse> deprecatedListPins()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.deprecatedListPins(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**Array<MessageResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for deprecated_list_pins |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **editLobby**
> LobbyResponse editLobby(createLobbyRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateLobbyRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let createLobbyRequest: CreateLobbyRequest; //

const { status, data } = await apiInstance.editLobby(
    lobbyId,
    createLobbyRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createLobbyRequest** | **CreateLobbyRequest**|  | |
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for edit_lobby |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **editLobbyChannelLink**
> LobbyResponse editLobbyChannelLink(editLobbyChannelLinkRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    EditLobbyChannelLinkRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let editLobbyChannelLinkRequest: EditLobbyChannelLinkRequest; //

const { status, data } = await apiInstance.editLobbyChannelLink(
    lobbyId,
    editLobbyChannelLinkRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **editLobbyChannelLinkRequest** | **EditLobbyChannelLinkRequest**|  | |
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for edit_lobby_channel_link |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **executeGithubCompatibleWebhook**
> executeGithubCompatibleWebhook(githubWebhook)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    GithubWebhook
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let githubWebhook: GithubWebhook; //
let wait: boolean; // (optional) (default to undefined)
let threadId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.executeGithubCompatibleWebhook(
    webhookId,
    webhookToken,
    githubWebhook,
    wait,
    threadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **githubWebhook** | **GithubWebhook**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **wait** | [**boolean**] |  | (optional) defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for execute_github_compatible_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **executeSlackCompatibleWebhook**
> string executeSlackCompatibleWebhook(slackWebhook)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SlackWebhook
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let slackWebhook: SlackWebhook; //
let wait: boolean; // (optional) (default to undefined)
let threadId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.executeSlackCompatibleWebhook(
    webhookId,
    webhookToken,
    slackWebhook,
    wait,
    threadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **slackWebhook** | **SlackWebhook**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **wait** | [**boolean**] |  | (optional) defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|


### Return type

**string**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for execute_slack_compatible_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **executeWebhook**
> MessageResponse executeWebhook(executeWebhookRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ExecuteWebhookRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let executeWebhookRequest: ExecuteWebhookRequest; //
let wait: boolean; // (optional) (default to undefined)
let threadId: string; // (optional) (default to undefined)
let withComponents: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.executeWebhook(
    webhookId,
    webhookToken,
    executeWebhookRequest,
    wait,
    threadId,
    withComponents
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **executeWebhookRequest** | **ExecuteWebhookRequest**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **wait** | [**boolean**] |  | (optional) defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|
| **withComponents** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for execute_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for execute_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **followChannel**
> ChannelFollowerResponse followChannel(followChannelRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    FollowChannelRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let followChannelRequest: FollowChannelRequest; //

const { status, data } = await apiInstance.followChannel(
    channelId,
    followChannelRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **followChannelRequest** | **FollowChannelRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**ChannelFollowerResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for follow_channel |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getActiveGuildThreads**
> ThreadsResponse getActiveGuildThreads()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getActiveGuildThreads(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**ThreadsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_active_guild_threads |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAnswerVoters**
> PollAnswerDetailsResponse getAnswerVoters()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let answerId: number; // (default to undefined)
let after: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.getAnswerVoters(
    channelId,
    messageId,
    answerId,
    after,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **answerId** | [**number**] |  | defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**PollAnswerDetailsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_answer_voters |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getApplication**
> PrivateApplicationResponse getApplication()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)

const { status, data } = await apiInstance.getApplication(
    applicationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**PrivateApplicationResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_application |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getApplicationCommand**
> ApplicationCommandResponse getApplicationCommand()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let commandId: string; // (default to undefined)

const { status, data } = await apiInstance.getApplicationCommand(
    applicationId,
    commandId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationCommandResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getApplicationEmoji**
> EmojiResponse getApplicationEmoji()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let emojiId: string; // (default to undefined)

const { status, data } = await apiInstance.getApplicationEmoji(
    applicationId,
    emojiId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **emojiId** | [**string**] |  | defaults to undefined|


### Return type

**EmojiResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_application_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getApplicationRoleConnectionsMetadata**
> Array<ApplicationRoleConnectionsMetadataItemResponse> getApplicationRoleConnectionsMetadata()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)

const { status, data } = await apiInstance.getApplicationRoleConnectionsMetadata(
    applicationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ApplicationRoleConnectionsMetadataItemResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_application_role_connections_metadata |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getApplicationUserRoleConnection**
> ApplicationUserRoleConnectionResponse getApplicationUserRoleConnection()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)

const { status, data } = await apiInstance.getApplicationUserRoleConnection(
    applicationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationUserRoleConnectionResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_application_user_role_connection |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getAutoModerationRule**
> CreateAutoModerationRule200Response getAutoModerationRule()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let ruleId: string; // (default to undefined)

const { status, data } = await apiInstance.getAutoModerationRule(
    guildId,
    ruleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **ruleId** | [**string**] |  | defaults to undefined|


### Return type

**CreateAutoModerationRule200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_auto_moderation_rule |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getBotGateway**
> GatewayBotResponse getBotGateway()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getBotGateway();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**GatewayBotResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_bot_gateway |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getChannel**
> GetChannel200Response getChannel()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.getChannel(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**GetChannel200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_channel |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEntitlement**
> EntitlementResponse getEntitlement()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let entitlementId: string; // (default to undefined)

const { status, data } = await apiInstance.getEntitlement(
    applicationId,
    entitlementId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **entitlementId** | [**string**] |  | defaults to undefined|


### Return type

**EntitlementResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_entitlement |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getEntitlements**
> Array<EntitlementResponse | null> getEntitlements()


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    GetEntitlementsSkuIdsParameter
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let skuIds: GetEntitlementsSkuIdsParameter; // (default to undefined)
let applicationId: string; // (default to undefined)
let userId: string; // (optional) (default to undefined)
let guildId: string; // (optional) (default to undefined)
let before: string; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)
let excludeEnded: boolean; // (optional) (default to undefined)
let excludeDeleted: boolean; // (optional) (default to undefined)
let onlyActive: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.getEntitlements(
    skuIds,
    applicationId,
    userId,
    guildId,
    before,
    after,
    limit,
    excludeEnded,
    excludeDeleted,
    onlyActive
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **skuIds** | **GetEntitlementsSkuIdsParameter** |  | defaults to undefined|
| **applicationId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | (optional) defaults to undefined|
| **guildId** | [**string**] |  | (optional) defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **excludeEnded** | [**boolean**] |  | (optional) defaults to undefined|
| **excludeDeleted** | [**boolean**] |  | (optional) defaults to undefined|
| **onlyActive** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**Array<EntitlementResponse | null>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_entitlements |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGateway**
> GatewayResponse getGateway()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getGateway();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**GatewayResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_gateway |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuild**
> GuildWithCountsResponse getGuild()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let withCounts: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.getGuild(
    guildId,
    withCounts
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **withCounts** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**GuildWithCountsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildApplicationCommand**
> ApplicationCommandResponse getGuildApplicationCommand()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let commandId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildApplicationCommand(
    applicationId,
    guildId,
    commandId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationCommandResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildApplicationCommandPermissions**
> CommandPermissionsResponse getGuildApplicationCommandPermissions()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let commandId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildApplicationCommandPermissions(
    applicationId,
    guildId,
    commandId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

**CommandPermissionsResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_application_command_permissions |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildBan**
> GuildBanResponse getGuildBan()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildBan(
    guildId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**GuildBanResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_ban |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildEmoji**
> EmojiResponse getGuildEmoji()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let emojiId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildEmoji(
    guildId,
    emojiId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **emojiId** | [**string**] |  | defaults to undefined|


### Return type

**EmojiResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildMember**
> GuildMemberResponse getGuildMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildMember(
    guildId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**GuildMemberResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildNewMemberWelcome**
> GuildHomeSettingsResponse getGuildNewMemberWelcome()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildNewMemberWelcome(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildHomeSettingsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_new_member_welcome |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for get_guild_new_member_welcome |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildPreview**
> GuildPreviewResponse getGuildPreview()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildPreview(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildPreviewResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_preview |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildRole**
> GuildRoleResponse getGuildRole()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let roleId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildRole(
    guildId,
    roleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **roleId** | [**string**] |  | defaults to undefined|


### Return type

**GuildRoleResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_role |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildScheduledEvent**
> ListGuildScheduledEvents200ResponseInner getGuildScheduledEvent()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let guildScheduledEventId: string; // (default to undefined)
let withUserCount: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.getGuildScheduledEvent(
    guildId,
    guildScheduledEventId,
    withUserCount
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **guildScheduledEventId** | [**string**] |  | defaults to undefined|
| **withUserCount** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**ListGuildScheduledEvents200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_scheduled_event |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildSoundboardSound**
> SoundboardSoundResponse getGuildSoundboardSound()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let soundId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildSoundboardSound(
    guildId,
    soundId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **soundId** | [**string**] |  | defaults to undefined|


### Return type

**SoundboardSoundResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_soundboard_sound |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildSticker**
> GuildStickerResponse getGuildSticker()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let stickerId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildSticker(
    guildId,
    stickerId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **stickerId** | [**string**] |  | defaults to undefined|


### Return type

**GuildStickerResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_sticker |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildTemplate**
> GuildTemplateResponse getGuildTemplate()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let code: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildTemplate(
    code
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **code** | [**string**] |  | defaults to undefined|


### Return type

**GuildTemplateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_template |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildVanityUrl**
> VanityURLResponse getGuildVanityUrl()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildVanityUrl(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**VanityURLResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_vanity_url |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildWebhooks**
> Array<ListChannelWebhooks200ResponseInner> getGuildWebhooks()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildWebhooks(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ListChannelWebhooks200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_webhooks |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildWelcomeScreen**
> GuildWelcomeScreenResponse getGuildWelcomeScreen()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildWelcomeScreen(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildWelcomeScreenResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_welcome_screen |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildWidget**
> WidgetResponse getGuildWidget()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildWidget(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**WidgetResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_widget |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildWidgetPng**
> string getGuildWidgetPng()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let style: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getGuildWidgetPng(
    guildId,
    style
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **style** | [**string**] |  | (optional) defaults to undefined|


### Return type

**string**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: image/png, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_widget_png |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildWidgetSettings**
> WidgetSettingsResponse getGuildWidgetSettings()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildWidgetSettings(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**WidgetSettingsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guild_widget_settings |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getGuildsOnboarding**
> UserGuildOnboardingResponse getGuildsOnboarding()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getGuildsOnboarding(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**UserGuildOnboardingResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_guilds_onboarding |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLobby**
> LobbyResponse getLobby()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)

const { status, data } = await apiInstance.getLobby(
    lobbyId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

**LobbyResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_lobby |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getLobbyMessages**
> Array<LobbyMessageResponse> getLobbyMessages()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.getLobbyMessages(
    lobbyId,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lobbyId** | [**string**] |  | defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**Array<LobbyMessageResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_lobby_messages |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMessage**
> MessageResponse getMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.getMessage(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyApplication**
> PrivateApplicationResponse getMyApplication()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getMyApplication();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**PrivateApplicationResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_my_application |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyGuildMember**
> PrivateGuildMemberResponse getMyGuildMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getMyGuildMember(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**PrivateGuildMemberResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_my_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyOauth2Application**
> PrivateApplicationResponse getMyOauth2Application()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getMyOauth2Application();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**PrivateApplicationResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_my_oauth2_application |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyOauth2Authorization**
> OAuth2GetAuthorizationResponse getMyOauth2Authorization()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getMyOauth2Authorization();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**OAuth2GetAuthorizationResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_my_oauth2_authorization |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyUser**
> UserPIIResponse getMyUser()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getMyUser();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**UserPIIResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_my_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getOpenidConnectUserinfo**
> OAuth2GetOpenIDConnectUserInfoResponse getOpenidConnectUserinfo()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getOpenidConnectUserinfo();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**OAuth2GetOpenIDConnectUserInfoResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_openid_connect_userinfo |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getOriginalWebhookMessage**
> MessageResponse getOriginalWebhookMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let threadId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getOriginalWebhookMessage(
    webhookId,
    webhookToken,
    threadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_original_webhook_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getPublicKeys**
> OAuth2GetKeys getPublicKeys()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getPublicKeys();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**OAuth2GetKeys**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_public_keys |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSelfVoiceState**
> VoiceStateResponse getSelfVoiceState()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.getSelfVoiceState(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**VoiceStateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_self_voice_state |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSoundboardDefaultSounds**
> Array<SoundboardSoundResponse> getSoundboardDefaultSounds()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.getSoundboardDefaultSounds();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<SoundboardSoundResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_soundboard_default_sounds |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getStageInstance**
> StageInstanceResponse getStageInstance()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.getStageInstance(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**StageInstanceResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_stage_instance |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getSticker**
> GetSticker200Response getSticker()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let stickerId: string; // (default to undefined)

const { status, data } = await apiInstance.getSticker(
    stickerId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **stickerId** | [**string**] |  | defaults to undefined|


### Return type

**GetSticker200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_sticker |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getStickerPack**
> StickerPackResponse getStickerPack()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let packId: string; // (default to undefined)

const { status, data } = await apiInstance.getStickerPack(
    packId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **packId** | [**string**] |  | defaults to undefined|


### Return type

**StickerPackResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_sticker_pack |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getThreadMember**
> ThreadMemberResponse getThreadMember()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let userId: string; // (default to undefined)
let withMember: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.getThreadMember(
    channelId,
    userId,
    withMember
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|
| **withMember** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**ThreadMemberResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_thread_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUser**
> UserResponse getUser()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let userId: string; // (default to undefined)

const { status, data } = await apiInstance.getUser(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**UserResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getVoiceState**
> VoiceStateResponse getVoiceState()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.getVoiceState(
    guildId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**VoiceStateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_voice_state |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWebhook**
> ListChannelWebhooks200ResponseInner getWebhook()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)

const { status, data } = await apiInstance.getWebhook(
    webhookId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|


### Return type

**ListChannelWebhooks200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWebhookByToken**
> ListChannelWebhooks200ResponseInner getWebhookByToken()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)

const { status, data } = await apiInstance.getWebhookByToken(
    webhookId,
    webhookToken
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|


### Return type

**ListChannelWebhooks200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_webhook_by_token |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getWebhookMessage**
> MessageResponse getWebhookMessage()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let messageId: string; // (default to undefined)
let threadId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getWebhookMessage(
    webhookId,
    webhookToken,
    messageId,
    threadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for get_webhook_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **inviteResolve**
> ListChannelInvites200ResponseInner inviteResolve()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let code: string; // (default to undefined)
let withCounts: boolean; // (optional) (default to undefined)
let guildScheduledEventId: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.inviteResolve(
    code,
    withCounts,
    guildScheduledEventId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **code** | [**string**] |  | defaults to undefined|
| **withCounts** | [**boolean**] |  | (optional) defaults to undefined|
| **guildScheduledEventId** | [**string**] |  | (optional) defaults to undefined|


### Return type

**ListChannelInvites200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for invite_resolve |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **inviteRevoke**
> ListChannelInvites200ResponseInner inviteRevoke()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let code: string; // (default to undefined)

const { status, data } = await apiInstance.inviteRevoke(
    code
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **code** | [**string**] |  | defaults to undefined|


### Return type

**ListChannelInvites200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for invite_revoke |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **joinThread**
> joinThread()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.joinThread(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for join_thread |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **leaveGuild**
> leaveGuild()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.leaveGuild(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for leave_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **leaveLobby**
> leaveLobby()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let lobbyId: string; // (default to undefined)

const { status, data } = await apiInstance.leaveLobby(
    lobbyId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lobbyId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for leave_lobby |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **leaveThread**
> leaveThread()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.leaveThread(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for leave_thread |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listApplicationCommands**
> Array<ApplicationCommandResponse> listApplicationCommands()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let withLocalizations: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.listApplicationCommands(
    applicationId,
    withLocalizations
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **withLocalizations** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**Array<ApplicationCommandResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_application_commands |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listApplicationEmojis**
> ListApplicationEmojisResponse listApplicationEmojis()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)

const { status, data } = await apiInstance.listApplicationEmojis(
    applicationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**ListApplicationEmojisResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_application_emojis |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listAutoModerationRules**
> Array<ListAutoModerationRules200ResponseInner> listAutoModerationRules()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listAutoModerationRules(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ListAutoModerationRules200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_auto_moderation_rules |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listChannelInvites**
> Array<ListChannelInvites200ResponseInner> listChannelInvites()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.listChannelInvites(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ListChannelInvites200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_channel_invites |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listChannelWebhooks**
> Array<ListChannelWebhooks200ResponseInner> listChannelWebhooks()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.listChannelWebhooks(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ListChannelWebhooks200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_channel_webhooks |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildApplicationCommandPermissions**
> Array<CommandPermissionsResponse> listGuildApplicationCommandPermissions()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildApplicationCommandPermissions(
    applicationId,
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<CommandPermissionsResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_application_command_permissions |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildApplicationCommands**
> Array<ApplicationCommandResponse> listGuildApplicationCommands()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let withLocalizations: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.listGuildApplicationCommands(
    applicationId,
    guildId,
    withLocalizations
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|
| **withLocalizations** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**Array<ApplicationCommandResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_application_commands |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildAuditLogEntries**
> GuildAuditLogResponse listGuildAuditLogEntries()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (optional) (default to undefined)
let targetId: string; // (optional) (default to undefined)
let actionType: number; // (optional) (default to undefined)
let before: string; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listGuildAuditLogEntries(
    guildId,
    userId,
    targetId,
    actionType,
    before,
    after,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | (optional) defaults to undefined|
| **targetId** | [**string**] |  | (optional) defaults to undefined|
| **actionType** | [**number**] |  | (optional) defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**GuildAuditLogResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_audit_log_entries |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildBans**
> Array<GuildBanResponse> listGuildBans()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let limit: number; // (optional) (default to undefined)
let before: string; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.listGuildBans(
    guildId,
    limit,
    before,
    after
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|


### Return type

**Array<GuildBanResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_bans |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildChannels**
> Array<GetChannel200Response> listGuildChannels()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildChannels(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<GetChannel200Response>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_channels |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildEmojis**
> Array<EmojiResponse> listGuildEmojis()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildEmojis(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<EmojiResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_emojis |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildIntegrations**
> Array<ListGuildIntegrations200ResponseInner> listGuildIntegrations()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildIntegrations(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ListGuildIntegrations200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_integrations |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildInvites**
> Array<ListChannelInvites200ResponseInner> listGuildInvites()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildInvites(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ListChannelInvites200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_invites |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildMembers**
> Array<GuildMemberResponse> listGuildMembers()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let limit: number; // (optional) (default to undefined)
let after: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listGuildMembers(
    guildId,
    limit,
    after
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **after** | [**number**] |  | (optional) defaults to undefined|


### Return type

**Array<GuildMemberResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_members |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildRoles**
> Array<GuildRoleResponse> listGuildRoles()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildRoles(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<GuildRoleResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_roles |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildScheduledEventUsers**
> Array<ScheduledEventUserResponse> listGuildScheduledEventUsers()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let guildScheduledEventId: string; // (default to undefined)
let withMember: boolean; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)
let before: string; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.listGuildScheduledEventUsers(
    guildId,
    guildScheduledEventId,
    withMember,
    limit,
    before,
    after
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **guildScheduledEventId** | [**string**] |  | defaults to undefined|
| **withMember** | [**boolean**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|


### Return type

**Array<ScheduledEventUserResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_scheduled_event_users |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildScheduledEvents**
> Array<ListGuildScheduledEvents200ResponseInner> listGuildScheduledEvents()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let withUserCount: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.listGuildScheduledEvents(
    guildId,
    withUserCount
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **withUserCount** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**Array<ListGuildScheduledEvents200ResponseInner>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_scheduled_events |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildSoundboardSounds**
> ListGuildSoundboardSoundsResponse listGuildSoundboardSounds()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildSoundboardSounds(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**ListGuildSoundboardSoundsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_soundboard_sounds |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildStickers**
> Array<GuildStickerResponse> listGuildStickers()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildStickers(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<GuildStickerResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_stickers |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildTemplates**
> Array<GuildTemplateResponse> listGuildTemplates()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildTemplates(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<GuildTemplateResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_templates |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listGuildVoiceRegions**
> Array<VoiceRegionResponse> listGuildVoiceRegions()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.listGuildVoiceRegions(
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<VoiceRegionResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_guild_voice_regions |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listMessageReactionsByEmoji**
> Array<UserResponse> listMessageReactionsByEmoji()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let emojiName: string; // (default to undefined)
let after: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)
let type: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listMessageReactionsByEmoji(
    channelId,
    messageId,
    emojiName,
    after,
    limit,
    type
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **emojiName** | [**string**] |  | defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **type** | [**number**] |  | (optional) defaults to undefined|


### Return type

**Array<UserResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_message_reactions_by_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listMessages**
> Array<MessageResponse> listMessages()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let around: string; // (optional) (default to undefined)
let before: string; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listMessages(
    channelId,
    around,
    before,
    after,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **around** | [**string**] |  | (optional) defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**Array<MessageResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_messages |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listMyConnections**
> Array<ConnectedAccountResponse> listMyConnections()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.listMyConnections();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<ConnectedAccountResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_my_connections |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listMyGuilds**
> Array<MyGuildResponse> listMyGuilds()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let before: string; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)
let withCounts: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.listMyGuilds(
    before,
    after,
    limit,
    withCounts
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **withCounts** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**Array<MyGuildResponse>**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_my_guilds |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listMyPrivateArchivedThreads**
> ThreadsResponse listMyPrivateArchivedThreads()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let before: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listMyPrivateArchivedThreads(
    channelId,
    before,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**ThreadsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_my_private_archived_threads |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listPins**
> PinnedMessagesResponse listPins()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let before: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listPins(
    channelId,
    before,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**PinnedMessagesResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_pins |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listPrivateArchivedThreads**
> ThreadsResponse listPrivateArchivedThreads()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let before: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listPrivateArchivedThreads(
    channelId,
    before,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**ThreadsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_private_archived_threads |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listPublicArchivedThreads**
> ThreadsResponse listPublicArchivedThreads()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let before: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.listPublicArchivedThreads(
    channelId,
    before,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **before** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|


### Return type

**ThreadsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_public_archived_threads |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listStickerPacks**
> StickerPackCollectionResponse listStickerPacks()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.listStickerPacks();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**StickerPackCollectionResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_sticker_packs |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listThreadMembers**
> Array<ThreadMemberResponse> listThreadMembers()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let withMember: boolean; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)
let after: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.listThreadMembers(
    channelId,
    withMember,
    limit,
    after
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **withMember** | [**boolean**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **after** | [**string**] |  | (optional) defaults to undefined|


### Return type

**Array<ThreadMemberResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_thread_members |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listVoiceRegions**
> Array<VoiceRegionResponse> listVoiceRegions()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.listVoiceRegions();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<VoiceRegionResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for list_voice_regions |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **partnerSdkToken**
> ProvisionalTokenResponse partnerSdkToken(partnerSdkUnmergeProvisionalAccountRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    PartnerSdkUnmergeProvisionalAccountRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let partnerSdkUnmergeProvisionalAccountRequest: PartnerSdkUnmergeProvisionalAccountRequest; //

const { status, data } = await apiInstance.partnerSdkToken(
    partnerSdkUnmergeProvisionalAccountRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **partnerSdkUnmergeProvisionalAccountRequest** | **PartnerSdkUnmergeProvisionalAccountRequest**|  | |


### Return type

**ProvisionalTokenResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for partner_sdk_token |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **partnerSdkUnmergeProvisionalAccount**
> partnerSdkUnmergeProvisionalAccount(partnerSdkUnmergeProvisionalAccountRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    PartnerSdkUnmergeProvisionalAccountRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let partnerSdkUnmergeProvisionalAccountRequest: PartnerSdkUnmergeProvisionalAccountRequest; //

const { status, data } = await apiInstance.partnerSdkUnmergeProvisionalAccount(
    partnerSdkUnmergeProvisionalAccountRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **partnerSdkUnmergeProvisionalAccountRequest** | **PartnerSdkUnmergeProvisionalAccountRequest**|  | |


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for partner_sdk_unmerge_provisional_account |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pollExpire**
> MessageResponse pollExpire()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)

const { status, data } = await apiInstance.pollExpire(
    channelId,
    messageId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for poll_expire |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **previewPruneGuild**
> GuildPruneResponse previewPruneGuild()


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    GetEntitlementsSkuIdsParameter
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let days: number; // (optional) (default to undefined)
let includeRoles: GetEntitlementsSkuIdsParameter; // (optional) (default to undefined)

const { status, data } = await apiInstance.previewPruneGuild(
    guildId,
    days,
    includeRoles
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **days** | [**number**] |  | (optional) defaults to undefined|
| **includeRoles** | **GetEntitlementsSkuIdsParameter** |  | (optional) defaults to undefined|


### Return type

**GuildPruneResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for preview_prune_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pruneGuild**
> GuildPruneResponse pruneGuild(pruneGuildRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    PruneGuildRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let pruneGuildRequest: PruneGuildRequest; //

const { status, data } = await apiInstance.pruneGuild(
    guildId,
    pruneGuildRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **pruneGuildRequest** | **PruneGuildRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildPruneResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for prune_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **putGuildsOnboarding**
> GuildOnboardingResponse putGuildsOnboarding(updateGuildOnboardingRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildOnboardingRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let updateGuildOnboardingRequest: UpdateGuildOnboardingRequest; //

const { status, data } = await apiInstance.putGuildsOnboarding(
    guildId,
    updateGuildOnboardingRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildOnboardingRequest** | **UpdateGuildOnboardingRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildOnboardingResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for put_guilds_onboarding |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **searchGuildMembers**
> Array<GuildMemberResponse> searchGuildMembers()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let limit: number; // (default to undefined)
let query: string; // (default to undefined)
let guildId: string; // (default to undefined)

const { status, data } = await apiInstance.searchGuildMembers(
    limit,
    query,
    guildId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] |  | defaults to undefined|
| **query** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**Array<GuildMemberResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for search_guild_members |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sendSoundboardSound**
> sendSoundboardSound(soundboardSoundSendRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SoundboardSoundSendRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let soundboardSoundSendRequest: SoundboardSoundSendRequest; //

const { status, data } = await apiInstance.sendSoundboardSound(
    channelId,
    soundboardSoundSendRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **soundboardSoundSendRequest** | **SoundboardSoundSendRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for send_soundboard_sound |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **setChannelPermissionOverwrite**
> setChannelPermissionOverwrite(setChannelPermissionOverwriteRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SetChannelPermissionOverwriteRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let overwriteId: string; // (default to undefined)
let setChannelPermissionOverwriteRequest: SetChannelPermissionOverwriteRequest; //

const { status, data } = await apiInstance.setChannelPermissionOverwrite(
    channelId,
    overwriteId,
    setChannelPermissionOverwriteRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **setChannelPermissionOverwriteRequest** | **SetChannelPermissionOverwriteRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|
| **overwriteId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for set_channel_permission_overwrite |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **setGuildApplicationCommandPermissions**
> CommandPermissionsResponse setGuildApplicationCommandPermissions(setGuildApplicationCommandPermissionsRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SetGuildApplicationCommandPermissionsRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let commandId: string; // (default to undefined)
let setGuildApplicationCommandPermissionsRequest: SetGuildApplicationCommandPermissionsRequest; //

const { status, data } = await apiInstance.setGuildApplicationCommandPermissions(
    applicationId,
    guildId,
    commandId,
    setGuildApplicationCommandPermissionsRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **setGuildApplicationCommandPermissionsRequest** | **SetGuildApplicationCommandPermissionsRequest**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

**CommandPermissionsResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for set_guild_application_command_permissions |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **setGuildMfaLevel**
> GuildMFALevelResponse setGuildMfaLevel(setGuildMfaLevelRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SetGuildMfaLevelRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let setGuildMfaLevelRequest: SetGuildMfaLevelRequest; //

const { status, data } = await apiInstance.setGuildMfaLevel(
    guildId,
    setGuildMfaLevelRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **setGuildMfaLevelRequest** | **SetGuildMfaLevelRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildMFALevelResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for set_guild_mfa_level |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **syncGuildTemplate**
> GuildTemplateResponse syncGuildTemplate()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let code: string; // (default to undefined)

const { status, data } = await apiInstance.syncGuildTemplate(
    guildId,
    code
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **code** | [**string**] |  | defaults to undefined|


### Return type

**GuildTemplateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for sync_guild_template |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **threadSearch**
> ThreadSearchResponse threadSearch()


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ThreadSearchTagParameter
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let name: string; // (optional) (default to undefined)
let slop: number; // (optional) (default to undefined)
let minId: string; // (optional) (default to undefined)
let maxId: string; // (optional) (default to undefined)
let tag: ThreadSearchTagParameter; // (optional) (default to undefined)
let tagSetting: string; // (optional) (default to undefined)
let archived: boolean; // (optional) (default to undefined)
let sortBy: string; // (optional) (default to undefined)
let sortOrder: string; // (optional) (default to undefined)
let limit: number; // (optional) (default to undefined)
let offset: number; // (optional) (default to undefined)

const { status, data } = await apiInstance.threadSearch(
    channelId,
    name,
    slop,
    minId,
    maxId,
    tag,
    tagSetting,
    archived,
    sortBy,
    sortOrder,
    limit,
    offset
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|
| **name** | [**string**] |  | (optional) defaults to undefined|
| **slop** | [**number**] |  | (optional) defaults to undefined|
| **minId** | [**string**] |  | (optional) defaults to undefined|
| **maxId** | [**string**] |  | (optional) defaults to undefined|
| **tag** | **ThreadSearchTagParameter** |  | (optional) defaults to undefined|
| **tagSetting** | [**string**] |  | (optional) defaults to undefined|
| **archived** | [**boolean**] |  | (optional) defaults to undefined|
| **sortBy** | [**string**] |  | (optional) defaults to undefined|
| **sortOrder** | [**string**] |  | (optional) defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to undefined|
| **offset** | [**number**] |  | (optional) defaults to undefined|


### Return type

**ThreadSearchResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for thread_search |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **triggerTypingIndicator**
> object triggerTypingIndicator()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)

const { status, data } = await apiInstance.triggerTypingIndicator(
    channelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**object**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for trigger_typing_indicator |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for trigger_typing_indicator |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **unbanUserFromGuild**
> unbanUserFromGuild()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)

const { status, data } = await apiInstance.unbanUserFromGuild(
    guildId,
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for unban_user_from_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateApplication**
> PrivateApplicationResponse updateApplication(applicationFormPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ApplicationFormPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let applicationFormPartial: ApplicationFormPartial; //

const { status, data } = await apiInstance.updateApplication(
    applicationId,
    applicationFormPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationFormPartial** | **ApplicationFormPartial**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**PrivateApplicationResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_application |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateApplicationCommand**
> ApplicationCommandResponse updateApplicationCommand(applicationCommandPatchRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ApplicationCommandPatchRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let commandId: string; // (default to undefined)
let applicationCommandPatchRequestPartial: ApplicationCommandPatchRequestPartial; //

const { status, data } = await apiInstance.updateApplicationCommand(
    applicationId,
    commandId,
    applicationCommandPatchRequestPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationCommandPatchRequestPartial** | **ApplicationCommandPatchRequestPartial**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationCommandResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateApplicationEmoji**
> EmojiResponse updateApplicationEmoji(updateApplicationEmojiRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateApplicationEmojiRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let emojiId: string; // (default to undefined)
let updateApplicationEmojiRequest: UpdateApplicationEmojiRequest; //

const { status, data } = await apiInstance.updateApplicationEmoji(
    applicationId,
    emojiId,
    updateApplicationEmojiRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateApplicationEmojiRequest** | **UpdateApplicationEmojiRequest**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|
| **emojiId** | [**string**] |  | defaults to undefined|


### Return type

**EmojiResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_application_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateApplicationRoleConnectionsMetadata**
> Array<ApplicationRoleConnectionsMetadataItemResponse> updateApplicationRoleConnectionsMetadata(applicationRoleConnectionsMetadataItemRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let applicationRoleConnectionsMetadataItemRequest: Array<ApplicationRoleConnectionsMetadataItemRequest>; //

const { status, data } = await apiInstance.updateApplicationRoleConnectionsMetadata(
    applicationId,
    applicationRoleConnectionsMetadataItemRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationRoleConnectionsMetadataItemRequest** | **Array<ApplicationRoleConnectionsMetadataItemRequest>**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**Array<ApplicationRoleConnectionsMetadataItemResponse>**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_application_role_connections_metadata |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateApplicationUserRoleConnection**
> ApplicationUserRoleConnectionResponse updateApplicationUserRoleConnection(updateApplicationUserRoleConnectionRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateApplicationUserRoleConnectionRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let updateApplicationUserRoleConnectionRequest: UpdateApplicationUserRoleConnectionRequest; //

const { status, data } = await apiInstance.updateApplicationUserRoleConnection(
    applicationId,
    updateApplicationUserRoleConnectionRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateApplicationUserRoleConnectionRequest** | **UpdateApplicationUserRoleConnectionRequest**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationUserRoleConnectionResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_application_user_role_connection |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateAutoModerationRule**
> CreateAutoModerationRule200Response updateAutoModerationRule(updateAutoModerationRuleRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateAutoModerationRuleRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let ruleId: string; // (default to undefined)
let updateAutoModerationRuleRequest: UpdateAutoModerationRuleRequest; //

const { status, data } = await apiInstance.updateAutoModerationRule(
    guildId,
    ruleId,
    updateAutoModerationRuleRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateAutoModerationRuleRequest** | **UpdateAutoModerationRuleRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **ruleId** | [**string**] |  | defaults to undefined|


### Return type

**CreateAutoModerationRule200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_auto_moderation_rule |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateChannel**
> GetChannel200Response updateChannel(updateChannelRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateChannelRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let updateChannelRequest: UpdateChannelRequest; //

const { status, data } = await apiInstance.updateChannel(
    channelId,
    updateChannelRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateChannelRequest** | **UpdateChannelRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**GetChannel200Response**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_channel |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuild**
> GuildResponse updateGuild(guildPatchRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    GuildPatchRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let guildPatchRequestPartial: GuildPatchRequestPartial; //

const { status, data } = await apiInstance.updateGuild(
    guildId,
    guildPatchRequestPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **guildPatchRequestPartial** | **GuildPatchRequestPartial**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildApplicationCommand**
> ApplicationCommandResponse updateGuildApplicationCommand(applicationCommandPatchRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ApplicationCommandPatchRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let guildId: string; // (default to undefined)
let commandId: string; // (default to undefined)
let applicationCommandPatchRequestPartial: ApplicationCommandPatchRequestPartial; //

const { status, data } = await apiInstance.updateGuildApplicationCommand(
    applicationId,
    guildId,
    commandId,
    applicationCommandPatchRequestPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationCommandPatchRequestPartial** | **ApplicationCommandPatchRequestPartial**|  | |
| **applicationId** | [**string**] |  | defaults to undefined|
| **guildId** | [**string**] |  | defaults to undefined|
| **commandId** | [**string**] |  | defaults to undefined|


### Return type

**ApplicationCommandResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_application_command |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildEmoji**
> EmojiResponse updateGuildEmoji(updateGuildEmojiRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildEmojiRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let emojiId: string; // (default to undefined)
let updateGuildEmojiRequest: UpdateGuildEmojiRequest; //

const { status, data } = await apiInstance.updateGuildEmoji(
    guildId,
    emojiId,
    updateGuildEmojiRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildEmojiRequest** | **UpdateGuildEmojiRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **emojiId** | [**string**] |  | defaults to undefined|


### Return type

**EmojiResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_emoji |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildMember**
> GuildMemberResponse updateGuildMember(updateGuildMemberRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildMemberRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)
let updateGuildMemberRequest: UpdateGuildMemberRequest; //

const { status, data } = await apiInstance.updateGuildMember(
    guildId,
    userId,
    updateGuildMemberRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildMemberRequest** | **UpdateGuildMemberRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**GuildMemberResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**204** | 204 response for update_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildRole**
> GuildRoleResponse updateGuildRole(createGuildRoleRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    CreateGuildRoleRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let roleId: string; // (default to undefined)
let createGuildRoleRequest: CreateGuildRoleRequest; //

const { status, data } = await apiInstance.updateGuildRole(
    guildId,
    roleId,
    createGuildRoleRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createGuildRoleRequest** | **CreateGuildRoleRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **roleId** | [**string**] |  | defaults to undefined|


### Return type

**GuildRoleResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_role |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildScheduledEvent**
> ListGuildScheduledEvents200ResponseInner updateGuildScheduledEvent(updateGuildScheduledEventRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildScheduledEventRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let guildScheduledEventId: string; // (default to undefined)
let updateGuildScheduledEventRequest: UpdateGuildScheduledEventRequest; //

const { status, data } = await apiInstance.updateGuildScheduledEvent(
    guildId,
    guildScheduledEventId,
    updateGuildScheduledEventRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildScheduledEventRequest** | **UpdateGuildScheduledEventRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **guildScheduledEventId** | [**string**] |  | defaults to undefined|


### Return type

**ListGuildScheduledEvents200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_scheduled_event |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildSoundboardSound**
> SoundboardSoundResponse updateGuildSoundboardSound(soundboardPatchRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    SoundboardPatchRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let soundId: string; // (default to undefined)
let soundboardPatchRequestPartial: SoundboardPatchRequestPartial; //

const { status, data } = await apiInstance.updateGuildSoundboardSound(
    guildId,
    soundId,
    soundboardPatchRequestPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **soundboardPatchRequestPartial** | **SoundboardPatchRequestPartial**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **soundId** | [**string**] |  | defaults to undefined|


### Return type

**SoundboardSoundResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_soundboard_sound |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildSticker**
> GuildStickerResponse updateGuildSticker(updateGuildStickerRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildStickerRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let stickerId: string; // (default to undefined)
let updateGuildStickerRequest: UpdateGuildStickerRequest; //

const { status, data } = await apiInstance.updateGuildSticker(
    guildId,
    stickerId,
    updateGuildStickerRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildStickerRequest** | **UpdateGuildStickerRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **stickerId** | [**string**] |  | defaults to undefined|


### Return type

**GuildStickerResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_sticker |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildTemplate**
> GuildTemplateResponse updateGuildTemplate(updateGuildTemplateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildTemplateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let code: string; // (default to undefined)
let updateGuildTemplateRequest: UpdateGuildTemplateRequest; //

const { status, data } = await apiInstance.updateGuildTemplate(
    guildId,
    code,
    updateGuildTemplateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildTemplateRequest** | **UpdateGuildTemplateRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **code** | [**string**] |  | defaults to undefined|


### Return type

**GuildTemplateResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_template |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildWelcomeScreen**
> GuildWelcomeScreenResponse updateGuildWelcomeScreen(welcomeScreenPatchRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    WelcomeScreenPatchRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let welcomeScreenPatchRequestPartial: WelcomeScreenPatchRequestPartial; //

const { status, data } = await apiInstance.updateGuildWelcomeScreen(
    guildId,
    welcomeScreenPatchRequestPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **welcomeScreenPatchRequestPartial** | **WelcomeScreenPatchRequestPartial**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**GuildWelcomeScreenResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_welcome_screen |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateGuildWidgetSettings**
> WidgetSettingsResponse updateGuildWidgetSettings(updateGuildWidgetSettingsRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateGuildWidgetSettingsRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let updateGuildWidgetSettingsRequest: UpdateGuildWidgetSettingsRequest; //

const { status, data } = await apiInstance.updateGuildWidgetSettings(
    guildId,
    updateGuildWidgetSettingsRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateGuildWidgetSettingsRequest** | **UpdateGuildWidgetSettingsRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**WidgetSettingsResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_guild_widget_settings |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateMessage**
> MessageResponse updateMessage(messageEditRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    MessageEditRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let messageId: string; // (default to undefined)
let messageEditRequestPartial: MessageEditRequestPartial; //

const { status, data } = await apiInstance.updateMessage(
    channelId,
    messageId,
    messageEditRequestPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **messageEditRequestPartial** | **MessageEditRequestPartial**|  | |
| **channelId** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateMyApplication**
> PrivateApplicationResponse updateMyApplication(applicationFormPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    ApplicationFormPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationFormPartial: ApplicationFormPartial; //

const { status, data } = await apiInstance.updateMyApplication(
    applicationFormPartial
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationFormPartial** | **ApplicationFormPartial**|  | |


### Return type

**PrivateApplicationResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_my_application |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateMyGuildMember**
> PrivateGuildMemberResponse updateMyGuildMember(updateMyGuildMemberRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateMyGuildMemberRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let updateMyGuildMemberRequest: UpdateMyGuildMemberRequest; //

const { status, data } = await apiInstance.updateMyGuildMember(
    guildId,
    updateMyGuildMemberRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateMyGuildMemberRequest** | **UpdateMyGuildMemberRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

**PrivateGuildMemberResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_my_guild_member |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateMyUser**
> UserPIIResponse updateMyUser(botAccountPatchRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    BotAccountPatchRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let botAccountPatchRequest: BotAccountPatchRequest; //

const { status, data } = await apiInstance.updateMyUser(
    botAccountPatchRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **botAccountPatchRequest** | **BotAccountPatchRequest**|  | |


### Return type

**UserPIIResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_my_user |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateOriginalWebhookMessage**
> MessageResponse updateOriginalWebhookMessage(incomingWebhookUpdateRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    IncomingWebhookUpdateRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let incomingWebhookUpdateRequestPartial: IncomingWebhookUpdateRequestPartial; //
let threadId: string; // (optional) (default to undefined)
let withComponents: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.updateOriginalWebhookMessage(
    webhookId,
    webhookToken,
    incomingWebhookUpdateRequestPartial,
    threadId,
    withComponents
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **incomingWebhookUpdateRequestPartial** | **IncomingWebhookUpdateRequestPartial**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|
| **withComponents** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_original_webhook_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateSelfVoiceState**
> updateSelfVoiceState(updateSelfVoiceStateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateSelfVoiceStateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let updateSelfVoiceStateRequest: UpdateSelfVoiceStateRequest; //

const { status, data } = await apiInstance.updateSelfVoiceState(
    guildId,
    updateSelfVoiceStateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateSelfVoiceStateRequest** | **UpdateSelfVoiceStateRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for update_self_voice_state |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateStageInstance**
> StageInstanceResponse updateStageInstance(updateStageInstanceRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateStageInstanceRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let channelId: string; // (default to undefined)
let updateStageInstanceRequest: UpdateStageInstanceRequest; //

const { status, data } = await apiInstance.updateStageInstance(
    channelId,
    updateStageInstanceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateStageInstanceRequest** | **UpdateStageInstanceRequest**|  | |
| **channelId** | [**string**] |  | defaults to undefined|


### Return type

**StageInstanceResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_stage_instance |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateVoiceState**
> updateVoiceState(updateVoiceStateRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateVoiceStateRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let guildId: string; // (default to undefined)
let userId: string; // (default to undefined)
let updateVoiceStateRequest: UpdateVoiceStateRequest; //

const { status, data } = await apiInstance.updateVoiceState(
    guildId,
    userId,
    updateVoiceStateRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateVoiceStateRequest** | **UpdateVoiceStateRequest**|  | |
| **guildId** | [**string**] |  | defaults to undefined|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | 204 response for update_voice_state |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateWebhook**
> ListChannelWebhooks200ResponseInner updateWebhook(updateWebhookRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateWebhookRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let updateWebhookRequest: UpdateWebhookRequest; //

const { status, data } = await apiInstance.updateWebhook(
    webhookId,
    updateWebhookRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateWebhookRequest** | **UpdateWebhookRequest**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|


### Return type

**ListChannelWebhooks200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_webhook |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateWebhookByToken**
> ListChannelWebhooks200ResponseInner updateWebhookByToken(updateWebhookByTokenRequest)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    UpdateWebhookByTokenRequest
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let updateWebhookByTokenRequest: UpdateWebhookByTokenRequest; //

const { status, data } = await apiInstance.updateWebhookByToken(
    webhookId,
    webhookToken,
    updateWebhookByTokenRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **updateWebhookByTokenRequest** | **UpdateWebhookByTokenRequest**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|


### Return type

**ListChannelWebhooks200ResponseInner**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_webhook_by_token |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateWebhookMessage**
> MessageResponse updateWebhookMessage(incomingWebhookUpdateRequestPartial)


### Example

```typescript
import {
    DefaultApi,
    Configuration,
    IncomingWebhookUpdateRequestPartial
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let webhookId: string; // (default to undefined)
let webhookToken: string; // (default to undefined)
let messageId: string; // (default to undefined)
let incomingWebhookUpdateRequestPartial: IncomingWebhookUpdateRequestPartial; //
let threadId: string; // (optional) (default to undefined)
let withComponents: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.updateWebhookMessage(
    webhookId,
    webhookToken,
    messageId,
    incomingWebhookUpdateRequestPartial,
    threadId,
    withComponents
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **incomingWebhookUpdateRequestPartial** | **IncomingWebhookUpdateRequestPartial**|  | |
| **webhookId** | [**string**] |  | defaults to undefined|
| **webhookToken** | [**string**] |  | defaults to undefined|
| **messageId** | [**string**] |  | defaults to undefined|
| **threadId** | [**string**] |  | (optional) defaults to undefined|
| **withComponents** | [**boolean**] |  | (optional) defaults to undefined|


### Return type

**MessageResponse**

### Authorization

[BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: application/json, application/x-www-form-urlencoded, multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for update_webhook_message |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **uploadApplicationAttachment**
> ActivitiesAttachmentResponse uploadApplicationAttachment()


### Example

```typescript
import {
    DefaultApi,
    Configuration
} from 'dc_rest';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let applicationId: string; // (default to undefined)
let file: string; // (default to undefined)

const { status, data } = await apiInstance.uploadApplicationAttachment(
    applicationId,
    file
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **applicationId** | [**string**] |  | defaults to undefined|
| **file** | [**string**] |  | defaults to undefined|


### Return type

**ActivitiesAttachmentResponse**

### Authorization

[OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [OAuth2](../README.md#OAuth2), [BotToken](../README.md#BotToken)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | 200 response for upload_application_attachment |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**429** | Client ratelimited response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |
|**4XX** | Client error response |  * X-RateLimit-Limit -  <br>  * X-RateLimit-Remaining -  <br>  * X-RateLimit-Reset -  <br>  * X-RateLimit-Reset-After -  <br>  * X-RateLimit-Bucket -  <br>  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

