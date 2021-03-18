# Hero Squad

This is a java app that enables a user create a hero and a squad and also the user can add a hero to a squad
## Author

Jeanine NISHIMWE


## Demo
![Alt text](src/main/resources/public/img/demo.png?raw=true "")
## How to use
The main interface 
![Alt text](src/main/resources/public/img/demo.png?raw=true "")
When you want to create Hero you click on create hero and receive the form below
![Alt text](src/main/resources/public/img/createhero.png?raw=true "")
Once you have created the Hero click submit, and you will receive success message.
![Alt text](src/main/resources/public/img/success.png?raw=true "")
Now you are successful create Hero. The next you can view the current heroes.
![Alt text](src/main/resources/public/img/currenthero.png?raw=true "")
In that page you cna add your hero in a squad. This can be done by clicking on add (name of hero) to squad
![Alt text](src/main/resources/public/img/currentsquad.png?raw=true "")
Now you have added your hero to squad. 

The last activity you can perform is to create your squad by navigating to squad page and click on create squad.
![Alt text](src/main/resources/public/img/createsquad.png?raw=true "")

## Getting Started

Clone this repository to your local machine to get Started

Github: https://github.com/NJeanine-creator/Hero-Squad

### Prerequisites

You need the following installed on your machine
- java
- JDK - Java Development Kit
- Gradle
- An IDE - Intellij


To confirm run the following command on linux
```
$ java --version       //java version
$ gradle --version     //gradle version
```

## Installing

After cloning to your local machine navigate to the folder you cloned into and open it with intellij.
* Navigate into the ``` src/main/java/App.java ``` and click run in intellij.
* Go to your browser and type ``` localhost:4567 ```

## Running the Tests 

Create a test class for running tests in the application.

This is a sample test that tests if the getter method works

```
@Test
public void newHero_getName_String(){
  hero testHero = Hero.setUpNewHero();
  assertEquals("jenny", testHero.getName());
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments
You can reach me on jnishimwe321@daviscollege.com or using phone number 0780629636.

