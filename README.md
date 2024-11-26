ConsultEase

ConsultEase is an Android application designed to streamline the process of service requests and management for both clients and ICT administrators for Verstex Trading 505 (Pty) Ltd. This application is created to mordenise the ways Versatex Trdaing manages their tasks. The app supports two user roles: Client and Admin. Clients can request services and make payments, while Admins can manage user profiles, accept or deny service requests, approve payments, schedule meetings, and generate reports. The app also features biometric authentication for secure login and utilizes Firebase for user management and PayPal for payment processing.

Features:

Client Side:

• User Authentication: Clients can register and log in to the app using their credentials and biometric authentication (fingerprint/password). • Service Request: Clients can request various services such as Wi-Fi, ICT support, telephone services, etc. • Pricelist: A comprehensive list of available services along with their prices. • Payment Integration: Clients can make secure payments via PayPal for services they request. • Service Tracking: Clients can track the status of their service requests.

Admin Side:

• User Authentication: Admins have their own registration and login, with biometric authentication. • Client Management: Admins can view the client list and access specific client profiles to manage personal information. • Service Request Management: Admins can review and accept or deny the service requests submitted by clients. • Payment Approval: Admins can approve or deny payments made by clients before the service is fulfilled. • Meeting Scheduling: Admins can schedule meetings with clients for further consultations or follow-ups. • Reports: Admins can generate reports related to client services, payments, and activities.

Client Flow:

Registration & Login: Clients register an account using their email or phone number, followed by login via credentials or biometric authentication.
Service Request: Clients browse the available services (e.g., Wi-Fi, ICT support, etc.) and select a service they wish to request.
Payment: Upon selecting a service, the client views the pricelist and makes a payment via PayPal.
Payment Approval: The Admin will review and approve the payment before proceeding with the service request.
Status Updates: Clients can track the status of their service requests and be notified of changes.
Admin Flow:

Registration & Login: Admins can register and log in with their own credentials and biometric authentication.
Client Management: Admins can view a list of clients and access detailed profiles with personal information.
Service Request Approval: Admins can review and either approve or deny the service requests submitted by clients.
Payment Approval: Admins review and approve payments made by clients before service fulfillment.
Meeting Scheduling: Admins can schedule meetings with clients for further discussions or consultations.
Reports: Admins can generate reports for service requests, payments, and other activities.
System Requirements

• Android Version: 15.0 (VanillaIceCream) or higher • Internet Connection: Required for account authentication, service requests, and payment transactions. Technical Details • Language: Kotlin for Android development • Authentication: Firebase Authentication with support for biometric authentication. • Cloud Firestore : storing user data and service requests • Payment Integration: PayPal API for processing payments.

Running the code on Android studio

Clone repository :(https://github.com/noluthandokhumalo55/ConsultEase.git)
Then chose which device to run (emulator/physical device)
Then clean and rebuild
lastly you can run the code.
How the App Was Compiled

The ConsultEase Android App was developed using Kotlin as the primary programming language due to its efficiency and strong support for Android development. The development process included the following key components:

Android Studio was used as the integrated development environment (IDE) to write, test, and compile the app.
Firebase Authentication and Firebase Cloud Firestore were integrated for secure user authentication and data storage, respectively.
PayPal API was used for secure payment integration to facilitate smooth transactions between clients and admins.
The Biometric Authentication feature was enabled using Android's native biometric API to ensure secure and convenient login options for both clients and admins.
The app follows the MVVM architecture pattern for better maintainability and scalability. This architecture helps in managing the UI, business logic, and data separately, which is essential for efficient app performance.
Testing and debugging were carried out using Android's unit testing and UI testing tools to ensure the app is bug-free and user-friendly before deployment.
