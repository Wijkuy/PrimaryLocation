# PrimaryLocation
Find Home based on GPS coordinates and Time stamp data

[![GitHub issues](https://img.shields.io/github/issues/Wijkuy/PrimaryLocation.svg?style=flat-square)](https://github.com/Wijkuy/PrimaryLocation/issues)
[![Travis](https://img.shields.io/travis/Wijkuy/PrimaryLocation.svg?style=flat-square)](https://travis-ci.org/Wijkuy/PrimaryLocation/)

## Getting Started

To run do a pull request on the repository and build from an existing project with eclipse or intellij if you have maven configured on your machine. From there you can run in the IDE or command line with java if you have it configured on your system path. And you can run mvn test to run the tests if you have it configured on your system path.

This project is primarily using test cases to show its use.

Ideally this would be expanded to support streaming data input or reading from files. 


```
[user@desktop ~]$ java Main
```

This will output the GeoLocation that is the most frequently visited at night from a list of input.

It is built using a hashmap and using streams to get max value from the map.

### Prerequisites

To run have Java 8+ and have java on your environmental variables and path
Have maven 3.5+ and have it on your environmental variables and path
If maven is having trouble loading the referenced libraries open the pom xml and it will find them



### Installing

If you have all the prerequisites just do a pull request on this repo and copy the source code into a folder

From there your ready to run this project

 
## Running the tests

Tests are ran with Travis-ci with mvn cobertura:cobertura command. It runs tests continuously every time there is a new commit.

## Built With
* [Maven](https://maven.apache.org/) - Dependency Management
* [junit4](https://junit.org/junit4/) - Unit testing
* [cucumber-java](https://cucumber.io/) - Behavior driven testing


## Authors

* **Shawn Anderson** - [Wijkuy](https://github.com/Wijkuy)


