# AvatarDrawable

Drawable for showing circled plain color in gradient form with letters inside.This is very usefull when you haven't downloaded profile image. You can use it as empty view

![Friend list](https://github.com/vomolis/AvatarDrawable/blob/master/screenshots/screen-1.png?raw=true "Title")


## Installation using Gradle

`implementation 'me.dara.avatardrawable:avatardrawable:1.0.0'`

## Usage

```
val drawable  = AvatarDrawable.Builder()
        .textSize(12)
        .startColor("#098475")
        .endColor(R.color.colorAccent)
        .width(60)
        .height(60)
        .fontWeight(Typeface.BOLD)
        .firstName("Jessica")
        .lastName("Alba")
        .textColor(Color.WHITE)
        .create()
 imageView.setImageDrawable(drawable)
```

## Notice

Textsize is in sp format you dont have to convert it to pixels.
Width and height are in dp format you don't have to conver it to pixels also


## License
### Apache-2.0
Copyright

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
