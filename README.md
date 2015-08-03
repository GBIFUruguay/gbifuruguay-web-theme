base-web-theme
====================

WingLongitude base web components used to style our web applications.

You should not reuse this project as is but instead copy and change it to apply you [own styling](wiki/Create-your-own-theme) to some Canadensys web applications.

### Usage
This component should be used as a WAR Overlay.

* [Using Gradle](https://github.com/scalding/gradle-waroverlay-plugin)
* [Using Maven](http://maven.apache.org/plugins/maven-war-plugin/overlays.html)

### Documentation
Please visit our [wiki](https://github.com/Canadensys/canadensys-web-theme/wiki).

### Build
If you want to adapt it to apply your own styling, it is recommanded to follow [this guide](wiki/Create-your-own-theme).

Install on local Maven repository:
```bash
mvn install -Dgpg.skip=true
```

### Dependencies
* Freemarker
* SiteMesh 3
