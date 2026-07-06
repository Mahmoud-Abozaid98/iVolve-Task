# Lab 2 - Build Java Application with Maven

## Objective

Build, test, package, and run a Java application using Maven.

---

## Prerequisites

- Java 21
- Maven

---

## Step 1 - Verify Maven

```bash
mvn --version
```

![Maven Version](Screenshots/01-maven-version.png)

---

## Step 2 - Clone Repository

```bash
git clone https://github.com/Ibrahim-Adel15/calculator-maven.git
cd calculator-maven
```

![Clone Repository](Screenshots/02-clone-project.png)

---

## Step 3 - View Project Structure

```bash
tree
```

![Project Tree](Screenshots/03-project-tree.png)

---

## Step 4 - Run Unit Tests

```bash
mvn test
```

![Maven Test](Screenshots/04-maven-test.png)

---

## Step 5 - Build the Project

```bash
mvn clean package
```

![Build Project](Screenshots/05-maven-package.png)

---

## Step 6 - Verify Generated JAR

```bash
ls target
```

![Target Folder](Screenshots/06-target-folder.png)

---

## Step 7 - Run the Application

```bash
java -jar target/calculator.jar
```

![Run Application](Screenshots/07-run-application.png)
