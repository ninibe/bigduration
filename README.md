# BidDuration

Like time.Duration but with "year", "month" and "day" making the following assumptions:

```go
bigduration.Day   = 24 * time.Hour
bigduration.Month = 30 * Day
bigduration.Year  = 365 * Day
```

Check the [godocs](https://godoc.org/github.com/ninibe/bigduration)
