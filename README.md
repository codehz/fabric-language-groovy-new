# fabric-language-groovy-new
![jitpack badge](https://jitpack.io/v/one.codehz/fabric-language-groovy-new.svg)
A Fabric Language module for the Apache Groovy programming language.
Updated groovy version to 4.0.1

### Usage:

Add it as a dependency:
```
dependencies {
	compile "one.codehz:fabric-language-groovy-new:0.1.0"
}
```
Set the language adapter for your mod to use by setting the languageAdapter property in the mod.json file:
```
{
  "languageAdapter": "one.codehz.language.groovy.GroovyLanguageAdapter"
}
```
Add a dependency entry to your mod.json file:
```
{
  "depends": {
    "fabric-language-groovy-new": "*"
  }
}
```

### Apache License v2.0:

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
