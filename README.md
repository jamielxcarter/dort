# dort
Dynamically get free ports

## Example

``` go
ports := dort.Get(3)
// ports is something like []int{10000, 10001, 10002}
```

Or

``` go
ports, err := dort.GetWithErr(3)
if err != nil {
  // handle err
}

// use ports...
```

Or 

```
ports := dort.GetS(3)
// ports is something like []string{"10000", "10001", "10002"}
```

## License

MIT

--- 

- [jamiel.codes](http://jamiel.codes)
