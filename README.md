# crop-image
[![](https://jitpack.io/v/nightcrawler-/crop-image.svg)](https://jitpack.io/#nightcrawler-/crop-image)

## Usage
1. Add it in your root build.gradle at the end of repositories:
```groovy
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
2.  Add the dependency
```groovy
dependencies {
	        implementation 'com.github.nightcrawler-:crop-image:Tag'
	}
```
3. Add to your AndroidManifest.xml
```
<activity
    android:name="com.cafrecode.imagecrop.CropImageActivity"
    android:theme="@style/AppThemeCrop" />
```
