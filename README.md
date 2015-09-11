# Objective8 Activity Stream

Document for defining Activities generated from [Objective8](https://objective8.dcentproject.eu)

---
### Create Objective

```
{
  "@context": "http://www.w3.org/ns/activitystreams",
  "@type": "Create",
  "published": "2014-08-2T12:34:56Z"
  "actor": {
    "@type": "Person",
    "displayName": "johnc"
  },
  "object": {
    "@type": "Objective",
    "displayName": "Ping-pong table should always be available",
    "description": "In order to increase ping-pong enjoyment...",
    "url": "https://objective8.dcentproject.eu/objectives/21"
  }
}
```

---
### Question about Objective

```
 {
  "@context": "http://www.w3.org/ns/activitystreams",
  "@type": "Question",
  "published": "2014-08-2T12:34:56Z",
  "actor": {
    "@type": "Person",
    "displayName": "johnc"
  },
  "object": {
    "@type": "Objective Question"
    "displayName": "Can't you play table football instead?",
    "url": "https://objective8.dcentproject.eu/objectives/21/questions/1"
  }
 }
```

---
### Comment about Objective

todo..

---


