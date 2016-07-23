IDEA resources ja
=================

This project is a community translation project to build a Japanese Resources
for JetBrains IntelliJ IDEA, Integrated Development Environment tool for Java.

How to translate
----------------

The project use OmegaT, Computer Aided Translation tool.
OmegaT is an Open Source Software and freely available for translators.
It is a kind of a translation memory.

The repository is designed to work with OmegaT team features. This means
translators who work on the repository are collaborative team.

If you want to use other tools you can generate TMX file by OmegaT and export 
it at project root as `IDEA_resources_ja-level1.tmx`.

How to generate resource file for IntelliJ IDEA
--------------------------------------

Please call gradle command from console.
You should have an omegat installed.

```
$ ./gradlew build
```

You will get resulted jar file as `build/libs/resources_ja.jar`

License
--------

Source properties and contents are licensed on Apache 2.0 License from JetBrains.
Translation memories and translated resources are distributed on Apache 2.0 License.


Copyright
---------

Copyright(C) 2016    Hiroshi Miura
