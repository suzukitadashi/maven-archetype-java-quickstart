# ����͉��H

Java8 + JUnit 5.3.1 �̃v���W�F�N�g�̐��`���쐬���邽�߂̃I���W�i���v���W�F�N�g�B

# �C���X�g�[���̕��@

1. mvn install
2. mvn archetype:update-local-catalog

# �v���W�F�N�g�쐬�R�}���h

�R�}���h�v�����v�g���炱�̃R�}���h��łB

```
mvn archetype:generate -DarchetypeGroupId=tada.suzu.maven.archetype -DarchetypeArtifactId=java8-quickstart -DinteractiveMode=false -DgroupId={groupId} -DartifactId={project-name}
```

## �R�}���h��

```
mvn archetype:generate -DarchetypeGroupId=tada.suzu.maven.archetype -DarchetypeArtifactId=java8-quickstart -DinteractiveMode=false -DgroupId=tada.suzu -DartifactId=orginalMavenProject
```