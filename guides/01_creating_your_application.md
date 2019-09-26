# 01. Creating your application
<walkthrough-tutorial-duration duration="15">
</walkthrough-tutorial-duration>
## Quick Start

In this tutorial, we will create an application named BugTrackerJHipster that is inspired from the issue tracking system from [GitHub](https://github.com/)

1. First of all, go to the directory you've created in the previous tutorial

```bash
cd ~/BlogJHipster
```
# 04. Creating entities with JDL Studio

<walkthrough-tutorial-duration duration="10">
</walkthrough-tutorial-duration>

## Introduction

Now that your application is up and running, you will soon need to create _entities_, and so you will need:


## JDL Studio

You can use a graphical tool to create your entities. In this case, we advise you to use [JDL Studio](https://start.jhipster.tech/jdl-studio/), our online tool to create entities and relationships using our domain-specific language [JDL](https://www.jhipster.tech/jdl/).


If you look in the `res` folder, you will see a file named <walkthrough-editor-open-file filePath="jhipster-blog-guides/res/jhipster-jdl.jh" text="jhipster-jdl.jh"></walkthrough-editor-open-file> that is the .jh file that should be exported when you click on the top right button "Download text file of this JDL". If you open it, you will see that it is what you've written before.

## Importing the .jh file

After creating the .jh file, you can now generate entities from the JDL file using the `import-jdl` sub-generator, by running `jhipster import-jdl your-jdl-file.jh`

Go to your project directory and type:

```bash
jhipster import-jdl ~/jhipster-blog-guides/res/jhipster-jdl.jh
```

Run the generated test suite, with 

```bash
mvn test
```

Launch the application (for example with `mvn`), log in and click on "Entities" in the menu. You should see the entities you have created with the JDL Studio.

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>

Congratulations! You now know how to create entities !

Enter the next command line to start the next tutorial:

```bash
cloudshell launch-tutorial -d ~/jhipster-blog-guides/guides/02_updating_your_back-end.md;
```
