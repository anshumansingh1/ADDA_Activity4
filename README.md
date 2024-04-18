# ADDA_Activity4
Build a CI/CD pipeline with GitHub Actions

# Anshuman Singh
## 20MIC0026

### Steps to create a new project using archetypes

1) Create the project (In parent forder): mvn archetype:generate -DgroupId=com.asp.app -DartifactId=ADDA_Activity4 -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

2) Edit the generated project as per requirements: cd ADDA_Activity4

3) Build the project: mvn package

4) Test the created JAR file: java -cp target/ADDA_Activity4-1.0-SNAPSHOT.jar com.asp.app.App