TemplateDevEnv

A template for mods in 1.12.2. It is released under the MIT licence and is intended for general use.

This template works with Java 21.
It uses Gradle 8.12 + RetroFuturaGradle 1.4.1 + Forge 14.23.5.2847.

It includes built-in support for core mods and mixins, making setup simple.

Procedure:
Click ‘Use this template’ at the top of the template.
Clone the repository created with this template to your local machine.
Before synchronising the project, make sure that IDEA is using Java 21 for Gradle. This can be confirmed in IDEA's ‘Settings’ > ‘Build, Execution, Deployment’ > ‘Build Tools’ > “Gradle” > ‘Gradle JVM’.
Open the project folder in IDEA. When the build.gradle file is detected, click ‘Load Gradle Project’. If the prompt does not appear, right-click the project's build.gradle in IDEA, select ‘Link Gradle Project’, and after completion, click ‘Update All’ in the Gradle tab on the right.
Execute Gradle tasks such as runClient or runServer in IDEA's Gradle tab, or use the automatically imported run configuration (e.g., 1. Run Client).
Notes:  
Dependency scripts are stored in gradle/scripts/dependencies.gradle, with explanations commented within the file.  
Publishing scripts are stored in gradle/scripts/publishing.gradle.  
When writing Mixins in IntelliJ, we recommend using the latest MinecraftDev Fork for RetroFuturaGradle.