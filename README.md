[![](https://jitpack.io/v/liyuzhao/mpchart.svg)](https://jitpack.io/#liyuzhao/mpchart)

>2.x migrate to androidx

#### Step 1.
Add it in your root build.gradle at the end of repositories:

```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

#### Step 2.
Add the dependency

```
	dependencies {
	        implementation 'com.github.liyuzhao:mpchart:v2.0.0'
	}

```