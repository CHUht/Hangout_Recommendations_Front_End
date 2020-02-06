# Hangout Recommendation -- Front end

This project is part of the Hangout Recommendation project of Atelier Development. It’s named as “front end” since this part is meanly the code for constructing the user interface (i.e. the web pages). The "back end" project can be found  [here](https://github.com/CHUht/Hangout_Recommendations_Back_End).

![Architecture_frontend](https://github.com/CHUht/Hangout_Recommendations_Front_End/blob/master/others/architecture_front_end.jpg)

This project is generated with [Angular CLI](https://github.com/angular/angular-cli/blob/master/README.md).

## Installation
For installation, follow these instructions:

1. Make sure that you have Node 10.13 or later installed. See instructions [here](https://nodejs.org/en/download/)
1. Make sure that you have Angular CLI installed; see instructions [here](https://angular.io/guide/setup-local)
1. Clone to your local computer using `git`
1. Start a terminal in the project folder
1. Using commande `npm install` to install all dependencies


## Usage

1. Run the back end [webservice](https://github.com/CHUht/Hangout_Recommendations_Back_End), here is an example of the result:
![backend_output](https://github.com/CHUht/Hangout_Recommendations_Front_End/blob/master/others/backend_output.jpg)
1. Copy the IP and paste it to the [configuration file](https://github.com/CHUht/Hangout_Recommendations_Front_End/blob/master/src/app/communicator/communicator.service.ts) at the following place
![change_IP](https://github.com/CHUht/Hangout_Recommendations_Front_End/blob/master/others/change_IP.jpg)
1. Start a terminal in the project folder
1. Type `ng serve` to compile the project, 
1. Once finished, enter the `http://localhost:4200/` in the explorar to see the results


## License 
This project  is under the MIT license. See the [LICENSE](https://github.com/CHUht/Hangout_Recommendations_Front_End/blob/master/LICENSE) file for details.
