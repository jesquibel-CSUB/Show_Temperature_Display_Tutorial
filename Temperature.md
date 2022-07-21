### @flyoutOnly true

# How to Display Temperature to Screen
## Step 1 
First grab a **_show number_** block and place it in the **_forever loop_**


```blocks
basic.forever(function () {
    basic.showNumber()
})

```

## Step 2 
Next drag the **_temperature sensor_** bubble to the forever loop.

```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})

```

## Step 3
Congratulations you have created your temperature sensor. 

Now try to load this program on to your ``micro:bit``