# GTExpress

GTExpress is a logistics company web application that provides users with an interface to search and view shipment details, and update shipment status and delivery information. The application is built with React and consumes a Spring REST API for data retrieval and manipulation. The web application provides features such as authentication and authorization for users, search and view shipments by ID, customer name, and status, and update shipment status and delivery information. The application uses JWT tokens for authentication and authorization, and the data is stored in a MongoDB NoSQL database for flexibility and scalability. Overall, GTExpress aims to provide a seamless logistics experience for its users, with efficient and user-friendly features for managing shipments.

## Features
The web application provides the following features:

 * Authentication and authorization for users.
 * Viewing and searching shipments by ID, customer name, and status.
 * Viewing shipment details, including origin, destination, and delivery status.
 * Updating shipment status and delivery information.

## Getting Started
To get started with the application, follow these steps:

 * Clone the repository to your local machine.
 * Navigate to the root directory of the project and run npm install to install the dependencies.
 * Create a .env file in the root directory of the project and add the following environment variables:

```
API_BASE_URL=<API base URL>
```
Replace `<API base URL>` with the base URL of the Spring REST API.

 * Running `yarn dev` to start the development server the application will start automatically in the browser.

## Authentication and Authorization
The web application uses JWT tokens for authentication and authorization. To log in, click the "Log in" button in the top right corner of the application and enter your credentials. If you don't have an account, click the "Register" button to create one.

## Searching and Viewing Shipments
To search for a shipment, enter its ID, customer name, or status in the search bar at the top of the page and click the "Search" button. The results will be displayed in a table below the search bar.

To view the details of a shipment, click on its row in the table. The shipment details will be displayed in a panel on the right side of the page.

## Updating Shipment Status and Delivery Information
To update the status of a shipment, click the "Update Status" button in the shipment details panel and select a new status from the dropdown menu. You can also enter delivery information, such as the date and time of delivery, in the form fields provided.

## Contributing
If you would like to contribute to the development of this application, please create a pull request with your changes.

## License
This application is licensed under the MIT License. See the LICENSE file for more information.