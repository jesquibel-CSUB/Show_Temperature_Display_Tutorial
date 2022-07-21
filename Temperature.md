# How to Display Temperature to Screen
## First drag the show block to the forever loop.
now place the show block in the **_forever loop_**



here is another sentence to show **UP**




```blocks
basic.forever(function () {
    basic.showNumber(0)
})
```

## section 2 Next drag the temperature sensor bubble to the forever loop.
here is my instructions for section 2

```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})

```