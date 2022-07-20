# How to Display Temperature to Screen
## First drag the show block to the forever loop.
```blocks
basic.forever(function () {
    basic.showNumber(0)
})
```

## Next drag the temperature sensor bubble to the forever loop.
```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})

```