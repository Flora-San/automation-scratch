# automation-scratch
simple guide and first automation configurations 

for this project iḿ using Java 11, and Selenium WebDriver with Intellij

you can check if you already install Java with command line 

```
$ java -version
```



important considerations _this is a minimalist guide to automate a web browser_

**Simple configurations**

you need install the following things

[Intellij IDE](https://www.jetbrains.com/es-es/idea/download/#section=linux)

[Selenium web driver](https://www.selenium.dev/downloads/)

[Java](https://www.oracle.com/java/technologies/downloads/#java11)

[chromedriver](https://chromedriver.chromium.org/)

_if your already have this configuration then go to the next step_

****
clone the repo with this command line

```
git clone https://github.com/Flora-San/automation-scratch.git
```

**How configurate selenium in intellij IDE**

open Intellij IDE and create a new project
File- New Project

add selenium to your project

file - project structure
new pop up
project settings
Modules select dependencies
click +
select JAR or Directories
new window is open
search the location selenium webdriver
click ok 
check the box to select selenium 
click apply 
click ok

if you still see errors check the imports
first check in the project list
External libraries
should be visible selenium jar

otherwise add the following imports

```
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;
```
once you have all this things, run the project 

click run 
