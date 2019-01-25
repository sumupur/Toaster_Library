# Toaster_Library
Toaster_Library



###Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


###Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.sumupur:Toaster_Library:0.1.0'
	}



Now, Add this line in your code where you wanr show toasts message


 ToasterMessage.s(Context,String message);
 
 Ex.:-ToasterMessage.s(MainActivity.this,"Hello"); 		//MainActivity class
