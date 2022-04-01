# first-javafx

- Download javafx [https://openjfx.io/](https://openjfx.io/)
- Intall e(fx)clipse plugin
- Add javafx to Java>Build Path> User librarie
- Select jars from jafafx-sdk/lib
- Create javaFX project
- Add javafx user library created previously to 'Java Build Path/Libraries/Modulepath'
- Create module-info.java
	Configure > Create module-info.java
- Add required modules to module-infor.java
```requires transitive javafx.controls;```

- In order to import maven projects, its necessary add libraries manually to maven dependencies
Run Configuraration > Java Application > {Application_name}
Click on tab Dependencies and add external jars to Modulepath Entries
