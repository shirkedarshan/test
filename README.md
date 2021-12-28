1. Install Appium

2. Install Intellij 

3. Install Android Studio

4. Install Java jdk file and environment variable path

Set system variable
JAVA_HOME = C:\Program Files\Java\jdk-16.0.1

set environment variable
path = C:\Program Files\Java\jdk-16.0.1\bin

5.Install Android sdk

https://developer.android.com/studio

7. Keep Downloaded folder to C:\Users\shirk\AppData\Local\Android\Sdk\

	i. Inside downloaded folder bin perform this command
		> sdkmanager "platform-tools" "platforms;android-28" --sdk_root="C:\Users\shirk\AppData\Local\Android\Sdk"

	ii. goto CMD and run -> adb

8.Set system variable
ANDROID_HOME = C:\Users\shirk\AppData\Local\Android\Sdk

set environment variable
path = C:\Users\shirk\AppData\Local\Android\Sdk\platform-tools

9. Open Android Studio and select device having play store by AVD Manager

10. Open Intellij to update dependencies
(edit pom.xml for dependencies)

	<dependency>
            <groupId>io.appium</groupId>
            <artifactId>java-client</artifactId>
            <version>7.3.0</version>
        </dependency>


11. Write your first code in
C:\Users\shirk\IdeaProjects\Appium\src\main\java\Main.java
