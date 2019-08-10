# How to setup JUnit on IntelliJ

## Setting up your class

    - Right click src
    - New >> Java Class
    - private String name
    - alt+insert >> Constructor
    - alt+insert >> Getter
    - etc

## Setting up your JUnit

    - create new folder in project
    - name it tests
    - File >> Project Structure... >> Modules >> Sources
    - mark "tests" director as Test >> Apply >> Ok
    - Go to class file
    - Highlight class name >> alt+enter >> Create Test >> Testing Library >> Junit4
    - Fix if necessary and generate test method