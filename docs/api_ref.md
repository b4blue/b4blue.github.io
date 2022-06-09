---
layout: api-ref
title: Api Reference
---
This is the Smart API related to ***notifications***. It's divided to ***Follow API*** and ***Notification Settings API***. With first, user can define which items to follow and with second what kind of updates he wants to receive from those items.


### Follow API {#followTitle}

---
<div class="alert alert-warning">
#### `DELETE` ***/api​/Follow​/unfollowAll*** {#anc1}
</div>


**Request:** None

**Response:** Bool

---------

#### `POST` ***/api​/Follow​/followed*** {#anc2}
---

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
      "name": "string",
      "accountId": 0,
      "productType": "string",
      "state": "string",
      "metro": "string",
      "zip": "string",
      "city": "string"
    }
  ],
  "total": 0,
  "totalWithoutQuery": 0
}
~~~

------------

#### `POST` ***/api​/Follow​/notifications*** {#anc3}
---

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

#### `POST` ***/api​/Follow​/followList*** {#anc4}
---

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

#### `POST` ***/api​/Follow​/notifications​/test*** {#anc5}
---

**Request:** None

**Response:** Bool

----

#### `POST` ***​/api​/Follow​/userSearch​/{id}​/follow*** {#anc6}
---

**Request:** None

**Response:** Bool

---

#### `PUT` ***​/api​/Follow​/userSearch​/{id}​/unfollow*** {#anc7}
---

**Request:** None

**Response:** Bool

---

#### `POST` ***/api​/Follow​/property​/{id}*** {#anc8}
---

**Request:** None

**Response:** Bool

---

#### `PUT` ***/api​/Follow​/property​/{id}​/unfollow*** {#anc9}
---

**Request:** None

**Response:** Bool

---

#### `POST` ***​/api​/Follow​/property​/followSearchResults*** {#anc10}
---

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
[
  0
]
~~~

---

#### `PUT` ***/api​/Follow​/property​/unfollowSearchResults*** {#anc11}
---

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
[
  0
]
~~~

---

#### `POST` ***/api​/Follow​/pipeline​/{id}*** {#anc12}
---

**Request:** None

**Response:** Bool

---

#### `PUT` ***​/api​/Follow​/pipeline​/{id}​/unfollow*** {#anc13}
---

**Request:** None

**Response:** Bool

---

#### `POST` ***/api​/Follow​/pipeline​/followSearchResults*** {#anc14}
---

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
[
  0
]
~~~

---

#### `PUT` ***/api​/Follow​/pipeline​/unfollowSearchResults*** {#anc15}
---

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
[
  0
]
~~~

---

#### `POST` ***/api​/Follow​/management​/{id}*** {#anc16}
---

**Request:** None

**Response:** Bool

---

#### `PUT` ***/api​/Follow​/management​/{id}​/unfollow*** {#anc17}
---

**Request:** None

**Response:** Bool

---

#### `POST` ***​/api​/Follow​/management​/followSearchResults*** {#anc18}
---

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
[
  0
]
~~~

---

#### `PUT` ***/api​/Follow​/management​/unfollowSearchResults*** {#anc19}
---

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
[
  0
]
~~~

---

#### `POST` ***/api​/Follow​/directory​/{id}*** {#anc20}
---

**Request:** None

**Response:** Bool

---

#### `PUT` ***​/api​/Follow​/directory​/{id}​/unfollow*** {#anc21}
---

**Request:** None

**Response:** Bool

---

#### `POST` ***/api​/Follow​/directory​/followSearchResults*** {#anc22}
---

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
[
  0
]
~~~
---

#### `PUT` ***/api​/Follow​/directory​/unfollowSearchResults*** {#anc23}
---

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
[
  0
]
~~~

---

#### `POST` ***​/api​/Follow​/developer​/{id}*** {#anc24}
---

**Request:** None

**Response:** Bool

---

#### `PUT` ***/api​/Follow​/developer​/{id}​/unfollow*** {#anc25}
---

**Request:** None

**Response:** Bool

---

#### `POST` ***/api​/Follow​/developer​/followSearchResults*** {#anc26}
---

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
[
  0
]
~~~

---

#### `PUT` ***/api​/Follow​/developer​/unfollowSearchResults*** {#anc27}
---

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
[
  0
]
~~~


### Notification Setting API {#notificationTitle}


---
<div class="alert alert-note">
#### `GET` ***​/api​/NotificationSetting*** {#anc28}
</div>

**Request:** None

**Response:**
~~~
{
  "cronExpression": "string",
  "externalId": "string",
  "property": {
    "management": true,
    "ownership": true,
    "regional": true,
    "onsiteManager": true,
    "renovations": true,
    "name": true
  },
  "pipeline": {
    "status": true,
    "startDate": true,
    "endDate": true,
    "managementCompany": true
  },
  "developer": {
    "newDevelopments": true,
    "pipelineStatus": true
  },
  "management": {
    "acquisitions": true,
    "dispositions": true,
    "personnel": true,
    "name": true,
    "newMarkets": true
  },
  "directory": {
    "employment": true,
    "title": true
  },
  "active": true,
  "lastUpdated": "2022-06-09T13:01:04.025Z",
  "nextNotificationAt": "2022-06-09T13:01:04.025Z"
}
~~~

---

#### `PUT` ***/api​/NotificationSetting*** {#anc29}
---

**Request:**
~~~
{
  "cronExpression": "string",
  "active": true,
  "property": {
    "management": true,
    "ownership": true,
    "regional": true,
    "onsiteManager": true,
    "renovations": true,
    "name": true,
    "active": true
  },
  "pipeline": {
    "status": true,
    "startDate": true,
    "endDate": true,
    "managementCompany": true,
    "active": true
  },
  "developer": {
    "newDevelopments": true,
    "pipelineStatus": true,
    "active": true
  },
  "management": {
    "acquisitions": true,
    "dispositions": true,
    "personnel": true,
    "name": true,
    "newMarkets": true,
    "active": true
  },
  "directory": {
    "employment": true,
    "title": true,
    "active": true
  }
}
~~~

**Response:**
~~~
{
  "cronExpression": "string",
  "externalId": "string",
  "property": {
    "management": true,
    "ownership": true,
    "regional": true,
    "onsiteManager": true,
    "renovations": true,
    "name": true
  },
  "pipeline": {
    "status": true,
    "startDate": true,
    "endDate": true,
    "managementCompany": true
  },
  "developer": {
    "newDevelopments": true,
    "pipelineStatus": true
  },
  "management": {
    "acquisitions": true,
    "dispositions": true,
    "personnel": true,
    "name": true,
    "newMarkets": true
  },
  "directory": {
    "employment": true,
    "title": true
  },
  "active": true,
  "lastUpdated": "2022-06-09T13:01:04.025Z",
  "nextNotificationAt": "2022-06-09T13:01:04.025Z"
}
~~~

---

#### `POST` ***/api​/NotificationSetting*** {#anc30}
---

**Request:**
~~~
{
  "cronExpression": "string",
  "active": true,
  "property": {
    "management": true,
    "ownership": true,
    "regional": true,
    "onsiteManager": true,
    "renovations": true,
    "name": true,
    "active": true
  },
  "pipeline": {
    "status": true,
    "startDate": true,
    "endDate": true,
    "managementCompany": true,
    "active": true
  },
  "developer": {
    "newDevelopments": true,
    "pipelineStatus": true,
    "active": true
  },
  "management": {
    "acquisitions": true,
    "dispositions": true,
    "personnel": true,
    "name": true,
    "newMarkets": true,
    "active": true
  },
  "directory": {
    "employment": true,
    "title": true,
    "active": true
  }
}
~~~

**Response:**
~~~
{
  "cronExpression": "string",
  "externalId": "string",
  "property": {
    "management": true,
    "ownership": true,
    "regional": true,
    "onsiteManager": true,
    "renovations": true,
    "name": true
  },
  "pipeline": {
    "status": true,
    "startDate": true,
    "endDate": true,
    "managementCompany": true
  },
  "developer": {
    "newDevelopments": true,
    "pipelineStatus": true
  },
  "management": {
    "acquisitions": true,
    "dispositions": true,
    "personnel": true,
    "name": true,
    "newMarkets": true
  },
  "directory": {
    "employment": true,
    "title": true
  },
  "active": true,
  "lastUpdated": "2022-06-09T13:01:04.025Z",
  "nextNotificationAt": "2022-06-09T13:01:04.025Z"
}
~~~

---

#### `DELETE` ***/api​/NotificationSetting*** {#anc31}
---
**Request:** None

**Response:** Bool

---

#### `PUT` ***/api​/NotificationSetting​/token*** {#anc32}
---

**Request:** None

**Response:** Bool
~~~
{ 
    "name": "INTEGRATION_KEY", 
    "value": "string" 
}
~~~

---

#### `GET` ***/api​/NotificationSetting​/token*** {#anc33}
---

**Request:** None

**Response:**
~~~
{ 
    "name": "INTEGRATION_KEY", 
    "value": "string" 
}
~~~