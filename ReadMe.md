# これは何？

Java8 + JUnit 5.3.1 のプロジェクトの雛形を作成するためのオリジナルプロジェクト。

# インストールの方法

1. mvn install
2. mvn archetype:update-local-catalog

# プロジェクト作成コマンド

コマンドプロンプトからこのコマンドを打つ。

```
mvn archetype:generate -DarchetypeGroupId=tada.suzu.maven.archetype -DarchetypeArtifactId=java8-quickstart -DinteractiveMode=false -DgroupId={groupId} -DartifactId={project-name}
```

## コマンド例

```
mvn archetype:generate -DarchetypeGroupId=tada.suzu.maven.archetype -DarchetypeArtifactId=java8-quickstart -DinteractiveMode=false -DgroupId=tada.suzu -DartifactId=orginalMavenProject
```