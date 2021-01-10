# City Scoop 
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)
                                                                                            
 ## Description
        
CityScoop is an application that allows its users to consolidate information of various locations around the world.

            
## Table of Contents

- [Installation](#Installation)
- [Usage](#Usage)
- [Credits](#credits)
- [license](#license)
- [Badges](#Badges)
- [Contributing](#Contributing)
- [Tests](#Tests)
            
            
## Installation
Install Contributor Covenant by executing the following commands in command terminal: npm install -g covgen; covgen "<your_email_address>"
There are no dependTo contribute to City Scoop, use jQuery and Materialize 
        

## Usage 
        
The user will input a desired location by (city) and the application will populate the following information:

  - City name with it's corresponding image as well as the current population
  - Brief desription of location
  - A more in depth look at statistics relating to: Job/Salary, General education, Cost of living, Health/safety, Weather, and recreational activities

Each of the statistics listed above recieves a general score out of 10, in relation to other locations around the world. This score can be found on the far right side of the listed criteria.

cityScoop provides the user a means to make informed decisions on a move to move basis.


## Link

[link to CityScoop](https://dyoder838.github.io/CityScoop/)

![CityScoop](./assets/img/CityScoop.PNG?raw=true)

            
## Credits

### Collaborators
            
  - Daniel Yoder - Git Master, Backend Development https://github.com/dyoder838
  - Chris Sisson - Frontend Development https://github.com/chrisasison
  - Nikolai Van Baak - Project Manager, Backend Development https://github.com/nvanbaak
  - Dexter Sage - Back End Development https://github.com/Advent24
  - Jack Solaro - Frontend Development https://github.com/jacksolaro


### Third Party Assets
            
  - Teleport
  - Openweathermap
  - CovidTracking


## Badges

![GitHub language count](https://img.shields.io/github/languages/count/dyoder838/dyoder838/CityScoop)
![GitHub repo size](https://img.shields.io/github/repo-size/dyoder838/dyoder838/CityScoop)

### Awards: 

"Peoples Choice", "Best Presentation"
            
## Contributing

[Contributor Covenant](.CODE_OF_CONDUCT.md)
            
            
## Tests

Response objects are stored under the following variable names:

* *cityMain* // Top-level json with city name, population, and lat/lon
* *covidJSON* // Json containing covid data for the chosen state
* *uaDetails* // Urban Area "details" json
* *uaImages* // json containing free-to-use image links for city
* *uaSalary* // json with salary data for city
* *uaScores* // json with score data for city
* *weatherCityHistory* // Weather history for selected city
* *highLowTemps* // Highest and lowest temps for city this year