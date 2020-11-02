# ar-configurator
Define and configure and manage reality experiences for Hololens
## purpose
Configurator App for Hololens my generic AR inspection application.

Expose a web application (UI + backend) to declare the rooms where you want to create an AR experience.
The App will generate a QR code that you can place in you room.
When User will look at the QRCode with Hololens, the Hololens app will connect to the backend services to retrieve anchors, object to place, interactions, etc.,  configured for this experience. Then the Hololens App also keeps track of the user interactions using the backend services.

## Components
A set of lambda functions and dynamoDB tables for the backend
An angular 10 app for the UI (to store in S3 and expose through Cloud Front).

 
