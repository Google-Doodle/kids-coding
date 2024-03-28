This solution:

![Example](https://github.com/Google-Doodle/kids-coding/assets/122696391/ffc52b85-756c-4fd1-ba0d-01e2ddbcf5a4)

Will be written like this:
```
Loop 5 (
  Turn Left
  Forward
  Right
)
```

### Problem 1
```
Forward
Forward
```

### Problem 2
```
Forward
Forward
Right
Forward
Forward
```

### Problem 3
```
Loop 4 (
  Forward
  Forward
  Right
)
```

### Problem 4
```
Loop 2 (
  Loop 4 (
    Forward
    Forward
    Turn Right
  )
  Turn Right
)
```

### Problem 5
```
Loop 4 (
  Loop 4 (
    Forward
    Forward
    Turn Right
  )
  Turn Right
)
```

### Problem 6
##### Official "Considered" Shortest Solution
```
Loop 4 (
  Loop 4 (
    Forward
    Turn Right
    Forward
  )
  Turn Left
)
```
##### Real shortest (not very efficient)
```
Loop 13 (
    Loop 3 (
        Forward
    )
    Turn Right
)
```
