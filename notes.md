# notes

+ https://github.com/mbostock/d3/wiki
+ https://github.com/rvagg/node-levelup
+ http://feltron.com/
+ http://www.reporter-app.com/
+ https://reporter.zendesk.com/hc/en-us
+ https://reporter.zendesk.com/hc/en-us/articles/200273009-How-DropBox-works-with-Reporter

Felton model:
+ 2014-01-15-reporter-export.json (in this repo)

proposed barebones alternative model in lieu of Felton model:
```javascript
{
  day~0: {
    date: '11-2-14',
    score: '1',
    tags: [0,1]
  },
  tag~0: 'depression',
  tag~1: 'anxiety'
}
```