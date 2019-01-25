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
		.....
	        implementation 'com.github.sumupur:Toaster_Library:0.1.0'
	}



Now, Add this line in your code where you wanr show toasts message


 		ToasterMessage.s(Context,String message);
 
 		Ex.:-ToasterMessage.s(MainActivity.this,"Hello"); 		//MainActivity class
		

# Apache License


Copyright 2019 sumupur

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
