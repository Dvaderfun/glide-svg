# Glide SVG

## Installation
Use [JitPack.io](https://jitpack.io/#qoqa/glide-svg/1.0.0)

```
repositories {
  ...
  maven { url 'https://jitpack.io' }
}
```
```
dependencies {
  ...
  implementation 'com.github.qoqa:glide-svg:2.0.4'
}
```

## Usage
```kotlin
GlideApp.with(this)
  .load(url)
  .into(picto_view)
```
