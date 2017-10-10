## Checker service

Goal: Run daily and monitoring the house pricing in certain market, zipcode
Try to understand the trending of increase price, decrease price, number of listing, days in market

To achive that goal, we could break down to smaller systems:
1. Checker - run, mining and collect information 
2. Analyzer - aggregate and understand the information

To make MVP simpler, initial information could be just in a config file

To run:

```
$ ./gradlew bootRun
```

