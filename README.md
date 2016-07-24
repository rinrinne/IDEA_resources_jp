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

You will get resource jar file as `build/distribution/resources_ja-<version>.jar`
Currently we provide two resource files; for version 2016 and version 15.0.6.


Contributions
---------------

There are two way to contirbute to the project.

Translation
^^^^^^^^^^^

Translation updates are not supporeted to merge with PR. Instead of push a request,
please ask us to join as a member who can write a repository.

OmegaT has a team feature. It automatically push translation contribution
onto github repository.

If you want to join, please leave a issue to express your will.



Build scripts
^^^^^^^^^^^^^^
You are welcome to fork project and to ask PR.


License
--------

Source properties and contents are licensed on Apache 2.0 License from JetBrains.
Translation memories and translated resources are distributed on Apache 2.0 License.


Copyright
---------

Copyright 2000-2015 JetBrains s.r.o.
Copyright 2013      Yuzo Morioka
Copyright 2013      GH@morizo999
Copyright 2016      Hiroshi Miura
