# Description
The groovy script can be used to read each line from the CSV file. The sample input file consist of "KeyId", "City" and "Country" and the end user will specify the KeyId in the request url. 

The policy script filter can then check if the user entered value exists in the input CSV file. If the value exists then it will show the complete line with KeyId,City and Country.
If the file is not found then it will copy the error trace into API Gateway attribute and show it in the browser. 


## API Management Version Compatibilty
This artefact was successfully tested for the following versions:
- 7.5.1
- 7.5.3

## Install

Sample Policy to check CSV file for user entered value
![alt text][Screenshot1]
[Screenshot2]: https://github.com/Axway-API-Management/Exposing-DB-Table-as-a-JSON-Structure/blob/master/Readme/Screenshot1.png  "Screenshot1"
![alt text][Screenshot2]
[Screenshot2]: https://github.com/Axway-API-Management/Exposing-DB-Table-as-a-JSON-Structure/blob/master/Readme/Screenshot2.png  "Screenshot2"   
![alt text][Screenshot3]
[Screenshot2]: https://github.com/Axway-API-Management/Exposing-DB-Table-as-a-JSON-Structure/blob/master/Readme/Screenshot3.png  "Screenshot3"


## Usage

Copy the input.csv in your local drive
![alt text][input.csv]
[input.csv]: https://github.com/Axway-API-Management/Exposing-DB-Table-as-a-JSON-Structure/blob/master/Readme/input.csv  "input.csv" 
Also, change the file path in the src code as shown
![alt text][changefilepath]
[changefilepath]: https://github.com/Axway-API-Management/Exposing-DB-Table-as-a-JSON-Structure/blob/master/Readme/changepath.png  "changepath.png" 
  

## Bug and Caveats

Nothing identified yet

## Contributing

Please read [Contributing.md] (https://github.com/Axway-API-Management/Common/blob/master/Contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Team

![alt text][Axwaylogo] Axway Team

[Axwaylogo]: https://github.com/Axway-API-Management/Common/blob/master/img/AxwayLogoSmall.png  "Axway logo"


## License
Apache License 2.0 (refer to document [license] (/LICENSE))