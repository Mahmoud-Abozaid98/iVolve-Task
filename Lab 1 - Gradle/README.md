# Lab 1 - Build Java Application with Gradle

## Objective

Build, test, package, and run a Java application using Gradle.

---

## Prerequisites

- Java 21
- Gradle

---

## Step 1 - Verify Gradle

```bash
gradle --version
```

![Gradle Version](Screenshots/01-gradle-version.png)

---

## Step 2 - Clone Repository

```bash
git clone https://github.com/Ibrahim-Adel15/calculator-gradle.git
cd calculator-gradle
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
gradle test
```

![Gradle Test](Screenshots/04-gradle-test.png)

---

## Step 5 - Build the Project

```bash
gradle build
```

![Gradle Build](Screenshots/05-gradle-build.png)

---

## Step 6 - Verify Generated JAR

```bash
ls build/libs
```

![Generated JAR](Screenshots/06-build-libs.png)

---

## Step 7 - Run the Application

```bash
java -jar build/libs/calculator.jar
```

![Run Application](Screenshots/07-run-application.png)
