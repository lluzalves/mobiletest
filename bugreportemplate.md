# BUG REPORT TEMPLATE

# 1. Estrutura do report 

#### 1.1 - __Summary__: [Request] [AppName] [DeviceModel] - Apk Version - date

#### 1.2 -__Description__


| Pre condition | Steps do Reproduce | Current Behavior | Expected Behavior |
| ------------- | ------------------ | ---------------- | ----------------- |


#### 1.3 - __Attempts__

#### 1.4 - __Severity Level__

#### 1.5 - __Attached Files__

#### 1.6 - __Tags(people, project and related)__

# 2. Exemplo 

Example:

__Summary__ 
[001] [NotareApp] [Lenovo A6020l36] - Apk Version 1.0a - 10.22.2014

__Description__

 * __Pre condition__:
   + Lenovo K5 device with Android 5.0 build.
   + Install the Notare app apk version 1.0a [server path] (http://localhost/shared/apk10a_notare/)
   
 * __Steps to reproduce__:
   + Start the application.
   + Tap the '+' icon on ActionBar to create a new note.
   + Type a random text.
   + Press back to save and return to the main view.
   + See the behavior.
   
 * __Current Behavior__:
   + After press back to return to the main view, application force close.
   
 * __Expected Behaivor__:
   + The application should return to the main view and show the newly created note without force closing.


* __Attempts__
  + 5 attemps
  
* __Severity Level__
  + Critical

* __Attached Files__
  + [logcat file] (http://localhost/shared/apk10a_notare/tests/bug_reports/files/logcat.txt)
  + [bugreport.ppt] (http://localhost/shared/apk10a_notare/tests/bug_reports/files/bugreport.ppt)
  + [notare_force_close.mp4] (http://localhost/shared/apk10a_notare/tests/bug_reports/files/notare_force_close.mp4)

* __Tags(people, project and related)__
   + @Daniel
   + @Sarah
   + @Carol
   + @testTeam004
   + @devTeam005
