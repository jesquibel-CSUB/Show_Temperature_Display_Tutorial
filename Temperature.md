### @flyoutOnly true
# How to Display Temperature to Screen
## Step 1 
First grab a ``||basic:show number||`` block and place it in the ``||basic:forever||`` loop


```blocks
basic.forever(function () {
    basic.showNumber()
})

```

## Step 2 
Next drag the ``||input:temperature||`` bubble to the ``||basic:forever||`` loop.

```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```

## Step 3
Congratulations you have created your temperature sensor. 

Now try to load this program on to your ``micro:bit``