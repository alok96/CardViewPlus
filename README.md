# CardViewPlus [![](https://jitpack.io/v/AliBardide5124/CardViewPlus.svg)](https://jitpack.io/#AliBardide5124/CardViewPlus)
 An small library to animate Card View shadow
<br/>
[![](https://drive.google.com/uc?authuser=0&id=1M0buUC6WQiKrr7oQEtO1y0rH53j5MXl9&export=download)](https://drive.google.com/file/d/1M0buUC6WQiKrr7oQEtO1y0rH53j5MXl9/view?usp=drivesdk)
<br/>
<br/>
<br/>
Download demo app 
<br/>
[![](https://drive.google.com/uc?authuser=0&id=1d4cH9m1ev8TLYwQHBcXsBcXUbee7PudO&export=download)](https://drive.google.com/uc?authuser=0&id=1PGaxhKUXieBOdJNAn2VwCsLl_6knV7DK&export=download)
<br/>
<br/>

## How to add
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.AliBardide5124:CardViewPlus:1.0.0'
	}
<br/>

## How to use
You can use CardViewPlus just like a noraml CardView
But it give you some more attributes 

	app:minElevation="2dp"
	app:maxElevation="5dp"
	app:animationEnabled="true"
	app:clickMode="collapse"
<br/>

  Lets know whats this attributes do
<br/>

  #### minElevation - Dimension:
   You can set minimum CardViewPlus elevation by this attribute. Its like cardElevation on a regular CardView. This is the CardViewPlus elevation before touching.  By default its set to "2dp"
<br/>
  #### maxElevation - Dimension:
   You can set maximum CardViewPlus elevation. This is the CardViewPlus elevation after touching. By default its set to "5dp"
 <br/>
 #### animationEnabled - Boolean: 
   You can enable or disable CardViewPlus shadow animation by this attribute. if you want to use CardViewPlus just like a regular CardView, set this to "false". By default its set to "true".
<br/>
#### clickMode - collapse.release:
   You can specify when CardViewPlus is clicked. When it value is equal to "collapse", CardViewPlus is clicked after its released and its shadow is collapsed. When it value is equal to "release", CardViewPlus is clicked right after release.
<br/>
<br/>

  Thank you for using my library.
  <br/>
  You can send your suggestions to my email: 
   
	alibardide5124@gmail.com 
  
