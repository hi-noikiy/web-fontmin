### response with 200

```js
//<response=200>
//"/share/index/:appId/day"

{
  "today":
  {
    "date":"yyyy-MM-dd",
    "data":
    [
      {
        "channelId":"QQ",
        "share":10,
        "channelName":"QQ",
        "total":100,
        "percent":"50%"
      },
      {
        "channelId":"douban",
        "channelName":"douban",
        "share":50,
        "total":100,
        "percent":"50%"
      },
      {
        "channelId":"other",
        "channelName":"其他",
        "share":50,
        "total":100,
        "percent":"50%"
      }
    ]
  },
  "yesterday":
  {
    "date":"yyyy-MM-dd",
    "data":
    [
      {
        "channelId":"QQ",
        "share":20,
        "channelName":"qq",
        "total":100,
        "percent":"50%"
      },
      {
        "channelId":"Weibo",
        "channelName":"weibo",
        "share":50,
        "total":100,
        "percent":"50%"
      },
      {
        "channelId":"other",
        "channelName":"其他",
        "share":50,
        "total":100,
        "percent":"50%"
      }
    ]
  },
  "total":
  {
    "date":"yyyy-MM-dd",
    "data":
    [
      {
        "channelId":"zhihu",
        "share":30,
        "channelName":"zhihu",
        "total":100,
        "percent":"50%"
      },
      {
        "channelId":"facebook",
        "channelName":"facebook",
        "share":50,
        "total":100,
        "percent":"50%"
      },
      {
        "channelId":"other",
        "channelName":"其他",
        "share":50,
        "total":100,
        "percent":"50%"
      }
    ]
  }
}

```