## TemplateDevEnv

### Instructions:

1. Click `use this template` at the top.
2. Clone the repository you have created with this template.
3. In the local repository, run the command `gradlew setupDecompWorkspace idea`
4. Open the `.ipr` file in IDEA.
5. Right-click in IDEA `build.gradle` of your project, and select `Link Gradle Project`, after completion, hit `Refresh All` in the gradle tab on the right.
6. Instead of running `genIntellijRuns` and using generated IntelliJ tasks, just run `gradlew runClient` and `gradlew runServer`.

*A checkstyle is coming soon, meaning Cleanroom's projects will use a specific coding style that has to be abided at time of PR/building.*
