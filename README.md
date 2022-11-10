## TemplateDevEnv

Template workspace for modding Minecraft 1.12.2. Licensed under MIT, it is made for public use.

This template currently utilizies **Gradle 4.10.3** + **ForgeGradle 2.3.4** + **Forge 14.23.5.2847**.

With **coremod and mixin support** that is easy to configure.

### Instructions:

1. Click `use this template` at the top.
2. Clone the repository you have created with this template.
3. In the local repository, run the command `gradlew setupDecompWorkspace idea`
4. Open the `.ipr` file in IDEA.
5. Right-click in IDEA `build.gradle` of your project, and select `Link Gradle Project`, after completion, hit `Refresh All` in the gradle tab on the right.
6. Instead of running `genIntellijRuns` and using generated IntelliJ tasks, just run `gradlew runClient` and `gradlew runServer`.
