Maven - 
* Maven is a tool used to compile, build, package, test java applications
* Maven provides Archetypes
* Maven uses a pom.xml (Project Object Model), to define the configurations and dependencies
* refer pom.xml
* pom xml by default shows only the things that we want to change, it won't show everything
* there is something called effective pom which won't show everything
* we can right-click on pom xml and under maven option we can choose show effective pom
* we can create projects with maven central as the catalog, 
  it will give us different archetypes
* It will automatically give us all dependencies
* How maven works (behind the scenes) - 
    For every project, when we add a dependency in pom.xml, we are telling maven to include it
    Maven will search for the files in local machine
    If it cannot find the file, it will find it from Maven Central
    We should always use safe and stable versions
    Most companies won't connect with remote repository, they will use another layer(company repo)
* 