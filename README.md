# BoxieField - An easy-to-use boxed EditText

A library that allows you to create a set of boxed EditTexts that are managed for cursor movement, enabling, tint, text addition and deletion, and text change notification. 

<p align="center"><img alt="Screenshot" src="https://github.com/akri16/BoxieField/blob/main/assets/1.jpeg" width="200" center/></p>

## Motivation

Almost every commercial app has a login screen followed by OTP verification. Modern OTP verification layouts use split EditTexts like the BoxedEditText in this library. These EditText have o be made using multiple EditTexts of unit length. This clutters up the XML file and makes the process of designing a simple authentication screen cumbersome. To add to this, making it smoothly function when moving cursor from one box to the next, adding and removing text and attaching callbacks for text changes require lots of code. 

With this library all of this is managed internally. You will get a fully functional, standard and customizable BoxedEditText in just two simple steps.

## Download

Add the following dependency in your app level *build.gradle* file:

```groovy
dependencies {
  implementation 'io.github.akri16:boxiefieldlibrary:1.0.0'
}
```

## Usage

```xml
<com.akribase.boxiefield.BoxedEditText
        android:id="@+id/boxedET"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:numBoxes="6"
        app:tint="@color/black"
        app:textSize="11sp" />
```

## License

      MIT License

      Copyright (c) 2021 Amit Krishna A

      Permission is hereby granted, free of charge, to any person obtaining a copy
      of this software and associated documentation files (the "Software"), to deal
      in the Software without restriction, including without limitation the rights
      to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
      copies of the Software, and to permit persons to whom the Software is
      furnished to do so, subject to the following conditions:

      The above copyright notice and this permission notice shall be included in all
      copies or substantial portions of the Software.

      THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
      IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
      FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
      AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
      LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
      OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
      SOFTWARE.
