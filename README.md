# ![LOGO](logo.png) Google+ Domains **flow**ground Connector

## Description

A generated **flow**ground connector for the Google+ Domains API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/plusDomains/v1/swagger.json<br/>
Generated at: 2019-05-07T17:41:51+03:00

## API Description

Builds on top of the Google+ platform for Google Apps Domains.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get an activity.

*Tags:* `activities`

#### Input Parameters
* `activityId` - _required_ - The ID of the activity to get.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the comments for an activity.

*Tags:* `comments`

#### Input Parameters
* `activityId` - _required_ - The ID of the activity to get comments for.
* `maxResults` - _optional_ - The maximum number of comments to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `sortOrder` - _optional_ - The order in which to sort the list of comments.
    Possible values: ascending, descending.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Create a new comment in reply to an activity.

*Tags:* `comments`

#### Input Parameters
* `activityId` - _required_ - The ID of the activity to reply to.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the people in the specified collection for a particular activity.

*Tags:* `people`

#### Input Parameters
* `activityId` - _required_ - The ID of the activity to get the list of people for.
* `collection` - _required_ - The collection of people to list.
    Possible values: plusoners, resharers, sharedto.
* `maxResults` - _optional_ - The maximum number of people to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Delete a circle.

*Tags:* `circles`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to delete.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get a circle.

*Tags:* `circles`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to get.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update a circle's description. This method supports patch semantics.

*Tags:* `circles`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to update.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update a circle's description.

*Tags:* `circles`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to update.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Remove a person from a circle.

*Tags:* `circles`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to remove the person from.
* `email` - _optional_ - Email of the people to add to the circle. Optional, can be repeated.
* `userId` - _optional_ - IDs of the people to remove from the circle. Optional, can be repeated.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the people who are members of a circle.

*Tags:* `people`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to get the members of.
* `maxResults` - _optional_ - The maximum number of people to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Add a person to a circle. Google+ limits certain circle operations, including the number of circle adds. Learn More.

*Tags:* `circles`

#### Input Parameters
* `circleId` - _required_ - The ID of the circle to add the person to.
* `email` - _optional_ - Email of the people to add to the circle. Optional, can be repeated.
* `userId` - _optional_ - IDs of the people to add to the circle. Optional, can be repeated.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get a comment.

*Tags:* `comments`

#### Input Parameters
* `commentId` - _required_ - The ID of the comment to get.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get a person's profile.

*Tags:* `people`

#### Input Parameters
* `userId` - _required_ - The ID of the person to get the profile for. The special value "me" can be used to indicate the authenticated user.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Create a new activity for the authenticated user.

*Tags:* `activities`

#### Input Parameters
* `preview` - _optional_ - If "true", extract the potential media attachments for a URL. The response will include all possible attachments for a URL, including video, photos, and articles based on the content of the page.
* `userId` - _required_ - The ID of the user to create the activity on behalf of. Its value should be "me", to indicate the authenticated user.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the activities in the specified collection for a particular user.

*Tags:* `activities`

#### Input Parameters
* `collection` - _required_ - The collection of activities to list.
    Possible values: user.
* `maxResults` - _optional_ - The maximum number of activities to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `userId` - _required_ - The ID of the user to get activities for. The special value "me" can be used to indicate the authenticated user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the audiences to which a user can share.

*Tags:* `audiences`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of circles to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `userId` - _required_ - The ID of the user to get audiences for. The special value "me" can be used to indicate the authenticated user.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the circles for a user.

*Tags:* `circles`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of circles to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `userId` - _required_ - The ID of the user to get circles for. The special value "me" can be used to indicate the authenticated user.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Create a new circle for the authenticated user.

*Tags:* `circles`

#### Input Parameters
* `userId` - _required_ - The ID of the user to create the circle on behalf of. The value "me" can be used to indicate the authenticated user.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Add a new media item to an album. The current upload size limitations are 36MB for a photo and 1GB for a video. Uploads do not count against quota if photos are less than 2048 pixels on their longest side or videos are less than 15 minutes in length.

*Tags:* `media`

#### Input Parameters
* `collection` - _required_
    Possible values: cloud.
* `userId` - _required_ - The ID of the user to create the activity on behalf of.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all of the people in the specified collection.

*Tags:* `people`

#### Input Parameters
* `collection` - _required_ - The collection of people to list.
    Possible values: circled.
* `maxResults` - _optional_ - The maximum number of people to include in the response, which is used for paging. For any response, the actual number returned might be less than the specified maxResults.
* `orderBy` - _optional_ - The order to return people in.
    Possible values: alphabetical, best.
* `pageToken` - _optional_ - The continuation token, which is used to page through large result sets. To get the next page of results, set this parameter to the value of "nextPageToken" from the previous response.
* `userId` - _required_ - Get the collection of people for the person identified. Use "me" to indicate the authenticated user.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-plus-domains-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
