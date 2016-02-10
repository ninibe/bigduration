# BidDuration

Like time.Duration but with "year", "month" and "day" making the following assumptions:

```go
dayDuration   = 24 * time.Hour
monthDuration = 30 * dayDuration
yearDuration  = 365 * dayDuration
```

Check the [godocs](https://godoc.org/github.com/ninibe/bigduration)
