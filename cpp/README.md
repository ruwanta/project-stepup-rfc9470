# Step Up Authentication RFC9470

This is an experimental API gateway which can handle Step-Up authentication for APIs using RFC9470

The idea is that this can be used as a side-car, eBPF or any other way to front your API to handle authorization

# Building

```
cmake .

make
```

You will get the built binary as ApiGw.