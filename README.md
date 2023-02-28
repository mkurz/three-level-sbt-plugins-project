Run following command:

```sh
sbt -Dsbt.color=false -Dsbt.log.noformat=true -Dsbt.supershell=false "+stewardDependencies;reload plugins;stewardDependencies;reload plugins;stewardDependencies;reload plugins;stewardDependencies"
```

The scala steward plugin was downloaded from:
https://github.com/scala-steward-org/sbt-plugin/blob/main/modules/sbt-plugin-1_3_11/src/main/scala/org/scalasteward/sbt/plugin/StewardPlugin_1_3_11.scala
