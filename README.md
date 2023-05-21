# Face Auth Backend

## Overview
An efficient and secure backend system for facial recognition and authentication. This project uses the PCA (Principal Component Analysis) algorithm to extract facial features and stores the data in MongoDB for further authentication purposes. Additionally, the emotion detection feature is under development and utilizes Azure API.

## API Structure

### Endpoints

1. **Add Facial Features**
    - Method: `POST`
    - Endpoint: `/addFacialFeatures`
    - Description: Adds new facial features to the database.
    
2. **Face Identification**
    - Method: `POST`
    - Endpoint: `/faceIdentification`
    - Description: Compares input facial features with those in the database for identification and authentication purposes.
    
3. **Get Emotion**
    - Method: `POST`
    - Endpoint: `/getEmotion`
    - Description: Extracts the emotion from the input face image (currently under development).

## Getting Started

To get started with the Face Auth Backend, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Configure your MongoDB connection.
4. Set up your Azure API credentials.
5. Start the server and test the endpoints.

For more detailed instructions and examples, please refer to the [documentation](link-to-documentation).

## Contributing

We appreciate any contributions to improve the Face Auth Backend. Please feel free to submit a pull request, report a bug, or suggest a new feature. Refer to the [contributing guidelines](link-to-contributing-guidelines) for more information on how to contribute to this project.

## License

This project is licensed under the [MIT License](link-to-license).
