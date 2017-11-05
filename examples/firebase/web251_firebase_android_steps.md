# web 251
# firebase android implementation


udacity class ud0352

note that files already under git get added as blobs in github, which is bad.

from base project

#deltas to add database support 

add dependencies
https://github.com/udacity/and-nd-firebase/compare/1.00-starting-point...1.01-firebase-gradle-plugin

add write code
https://github.com/udacity/and-nd-firebase/compare/1.01-firebase-gradle-plugin...1.02-firebase-database-write

add read code
https://github.com/udacity/and-nd-firebase/compare/1.02-firebase-database-write...1.03-firebase-database-read

this takes us to saturday, step 30
next: firebase ui to handle auth ui
see https://github.com/firebase/FirebaseUI-Android

firebaseui docs start in the root of the repo and continue
in the /auth subdir

firebase ui versions map to a specific firebase sdk version
for example:
compile 'com.google.firebase:firebase-database:9.6.1'
compile 'com.google.firebase:firebase-auth:9.6.1'
compile 'com.firebaseui:firebase-ui-auth:0.6.0'

add authstatelistener and attach it at the relevant points in the app lifecycle
step 1.04 
https://github.com/udacity/and-nd-firebase/compare/1.03-firebase-database-read...1.04-firebase-auth-firebaseui-signin
step 1.05
https://github.com/udacity/and-nd-firebase/compare/1.04-firebase-auth-firebaseui-signin...1.05-firebase-auth-signin-signout-setup

