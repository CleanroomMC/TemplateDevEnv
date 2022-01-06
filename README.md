## TemplateDevEnv

### Instructions:

1. Click `use this template` at the top.
2. Clone the repository you have created with this template.
3. In the local repository, run the command `gradlew setupDecompWorkspace idea genIntellijRuns`
4. Open the `.ipr` file in IDEA and start working on 1.12.2 modding.

If you are getting errors in your Minecraft Client + Minecraft Server run configs in IDEA, change `-cp` to use `.main`.

A checkstyle is coming soon, meaning Cleanroom's projects will use a specific coding style that has to be abided at time of PR/building.