# projectName

-----------------------------------------------------------------------------------

## Without JRE

### Build instructions

- Build distributions using maven tool:

```bash
mvn -P without-jre clean package
```

- Use the following archives:
    - `target/project-${project.version}-windows.zip` for Windows
    - `target/project-${project.version}-unix.tar.gz` for MacOS or Linux

### Run instructions

- Download [OpenJDK 18](https://jdk.java.net/java-se-ri/18);
- Unzip the downloaded OpenJDK archive;
- Configure the `PATH` environment variable:
    - Add `%JDK_HOME%\bin\` directory for Windows;
    - Add `$JDK_HOME/bin/` directory for MacOS and Linux;
- Re-login or restart computer;
- Unzip the project distribution:
    - Unzip `project-${project.version}-windows.zip` for Windows;
    - Unzip `project-${project.version}-unix.tar.gz` for MacOS or Linux;
- Go to unzipped directory;
- Run the project by double-click on the start script:
    - `start.cmd` for Windows;
    - `start.sh` for MacOS or Linux;

-----------------------------------------------------------------------------------

## With JRE

### Build instructions

- Build distributions using maven tool:

```bash
mvn -P with-jre clean package
```

- Use the following archives:
    - `target/project-${project.version}-windows-with-jre.zip` for Windows
    - `target/project-${project.version}-macos-with-jre.tar.gz` for MacOS
    - `target/project-${project.version}-linux-with-jre.tar.gz` for Linux

### Run instructions

- Unzip the project distribution:
    - Unzip `project-${project.version}-windows-with-jre.zip` for Windows;
    - Unzip `project-${project.version}-macos-with-jre.tar.gz` for MacOS;
    - Unzip `project-${project.version}-linux-with-jre.tar.gz` for Linux;
- Go to unzipped directory;
- Run the project by double-click on the start script:
    - `start.cmd` for Windows;
    - `start.sh` for MacOS or Linux;