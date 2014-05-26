NoTils
======

Never again need a .utils. package yur scurvy sea dogs!

Whats Included
======

- AndroidUtils, for showing the keyboard, checking running services etc
- ClassCaster - to help with listeners between Activitys & Fragments
- No need to cast when referencing Views / Fragments
- No need to double type your types when creating collections
- Simple Fade animations in & out done for you
- Logging Novogger & Simple Log to give to give automatic details of where the Log executed
- StrictMode Management - enable strict mode in one line
- WebViews , allowing custom loading of different scenarios (raw assets, external urls)


Adding to your project
======

Gradle
-
````groovy
repositories {
    maven {
        url 'https://github.com/novoda/public-mvn-repo/raw/master/releases'
    }
}
`````

````groovy
dependencies {
    compile 'com.novoda:notils:2.2.6'
}
````


Maven
-

````xml
<repositories>
  <repository>
    <id>public-mvn-repo-releases</id>
    <url>
      https://github.com/novoda/public-mvn-repo/raw/master/releases
    </url>
  </repository>
</repositories>
````

````xml
<dependency>
  <groupId>com.novoda</groupId>
  <artifactId>notils</artifactId>
  <version>2.2.6</version>
</dependency>
````

License
-------

    (c) Copyright 2014 Novoda

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
