Create Desktop, Android, Ios, Embedded Apps with single Codebase using Gluon Mobile and JavaFx.

JavaFx is a ui toolkit for java like awt and swing.

Gluon which enables us to use javafx for creating mobile apps uses javafxports internally to generate mobile applications and desktop jars.


_________________________________________________________

For Running on Desktop : ./gradlew run

For Creating debug apk : ./gradlew android

For All other commands : goto https://docs.gluonhq.com/charm/5.0.1/#_building_and_deploying

Important : Read build.gradle file and modify it where asked according to your system.

_________________________________________________________



Hybrid Frameworks comparison for hello world app.
																														
Cordova/ionic		(html/css/javascript for ui)	(For Desktop,Mobile,Web through Capacitor)		1MB apk size approx.

Gluon/javafxports	(Java,javafx for ui)		(For Desktop,Mobile,Web through TeaVM)			12MB apk size approx.

CrossMobile.tech	(Java,ios like classes for ui)	(For Desktop,Mobile,Web through TeaVM)			1MB apk size approx.

Flutter 		(Dart which is like java/c#)	(For Desktop,Mobile,Web)				4.5MB apk size approx.



TeaVM for porting java apps to run in webrowsers(Not tried yet)
		
