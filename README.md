# json2csv
golang tool to convert json to csv file


---
Headers is derived from JSON keys. Column order is sorted alphabetically


Usage
```
.\json2csv input.json
```

Sample json input (file)
```
[
  {
    "Date": "2024-05-13",
    "IsOffice": true,
    "IsDayOff": false
  },
  {
    "Date": "2024-06-07",
    "IsOffice": false,
    "IsDayOff": false
  }
]
```

Sample output csv (stdout)
```
Date,IsDayOff,IsOffice
2024-05-13,false,true
2024-06-05,false,false
```
