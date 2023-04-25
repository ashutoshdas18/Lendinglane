# Welcome to Lendinglane 🚀

This is P2P lendiing platform that provides easy loan and investment options for Borrowers and Lenders. To run the program follow the below steps

## System Requirements:
- 8GB of RAM
- 20GB of available storage
- Intel Core i5 processor or equivalent

## Prerequisites:
- Docker installed on system.

## To run the project:
1. Clone the repository to your local machine using the command:
`git clone https://github.com/ashutoshdas18/Lendinglane.git`
2. Navigate to the project directory.
3. Uncomment and add your email id and password in lines 3 and 4 in the `application.properties` file of the notification service
4. Uncomment and and your email id in line 37 in the `NotificationServiceImpl` file of the notification service.
5. Go to the parent directory and run `docker compose up --build`
