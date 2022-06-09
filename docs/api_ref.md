---
layout: api-ref
title: Api Reference
---
This is some text about API


Follow {#followTitle}
------------------------------------


`DELETE` ***/api​/Follow​/unfollowAll***
**Request:** None
**Response:** Bool


`POST` ***/api​/Follow​/followed***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/notifications***
**Request:**
~~~
{
  "limit": 0,
  "offset": 0,
  "orderBy": "string",
  "orderDirection": "string",
  "query": {<Smart Query>}
}
 
~~~
**Response:**
~~~
{
  "items": [
    {
      "id": 0,
      "objectId": 0,
      "objectType": "string",
      "field": "string",
      "sentOn": "2022-06-09T10:31:40.124Z",
      "receivedOn": "2022-06-09T10:31:40.124Z",
      "currentValue": "string",
      "previousValue": "string",
      "currentIdValue": 0,
      "previousIdValue": 0,
      "metro": "string",
      "name": "string",
      "state": "string"
    }
  ],
  "total": 0
}
~~~
---------
`POST` ***/api​/Follow​/followList***
**Request:**
~~~
[
  {
    "type": "string",
    "id": 0
  }
]
~~~
**Response:** Bool

----
`POST` ***/api​/Follow​/notifications​/test***
**Request:** None
**Response:** Bool
---
`POST` ***/api​/Follow​/userSearch​/follow***
**Request:** None
**Response:** Bool

----
`POST` ***​/api​/Follow​/userSearch​/{id}​/follow***
**Request:** None
**Response:** Bool

`PUT` ***​/api​/Follow​/userSearch​/{id}​/unfollow***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/property​/{id}***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/property​/{id}​/unfollow***
**Request:** None
**Response:** Bool

`POST` ***​/api​/Follow​/property​/followSearchResults***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/property​/unfollowSearchResults***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/pipeline​/{id}***
**Request:** None
**Response:** Bool

`PUT` ***​/api​/Follow​/pipeline​/{id}​/unfollow***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/pipeline​/followSearchResults***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/pipeline​/unfollowSearchResults***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/management​/{id}***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/management​/{id}​/unfollow***
**Request:** None
**Response:** Bool

`POST` ***​/api​/Follow​/management​/followSearchResults***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/management​/unfollowSearchResults***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/directory​/{id}***
**Request:** None
**Response:** Bool

`PUT` ***​/api​/Follow​/directory​/{id}​/unfollow***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/directory​/followSearchResults***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/directory​/unfollowSearchResults***
**Request:** None
**Response:** Bool

`POST` ***​/api​/Follow​/developer​/{id}***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/developer​/{id}​/unfollow***
**Request:** None
**Response:** Bool

`POST` ***/api​/Follow​/developer​/followSearchResults***
**Request:** None
**Response:** Bool

`PUT` ***/api​/Follow​/developer​/unfollowSearchResults***
**Request:** None
**Response:** Bool


NotificationSetting {#notificationTitle}
-------------------


`GET` ***​/api​/NotificationSetting***
**Request:** None
**Response:** Bool

`PUT` ***/api​/NotificationSetting***
**Request:** None
**Response:** Bool

`POST` ***/api​/NotificationSetting***
**Request:** None
**Response:** Bool

`DELETE` ***/api​/NotificationSetting***
**Request:** None
**Response:** Bool

`PUT` ***/api​/NotificationSetting​/token***
**Request:** None
**Response:** Bool

`GET` ***/api​/NotificationSetting​/token***
**Request:** None
**Response:** Bool