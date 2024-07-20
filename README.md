Facial Recognition App with AI and Blockchain Integration

Overview

This is a Flutter application that demonstrates the integration of Artificial Intelligence (AI) and Blockchain technologies. The app uses computer vision and facial recognition to identify users and stores their face embeddings on a blockchain.

Features

Facial recognition using TensorFlow Lite
Blockchain integration using Web3Dart
User registration with face embeddings on a smart contract
Camera preview and image capture
Getting Started

Prerequisites

Flutter installed on your machine
Android or iOS device for testing
Infura project ID and contract address for blockchain integration
Installation

Clone the repository: git clone https://github.com/your-username/facial-recognition-app.git
Open the project in your preferred IDE or code editor
Install the required dependencies: flutter pub get
Configure your Infura project ID and contract address in the main.dart file
Run the app on an Android or iOS device: flutter run
Usage

Open the app and grant camera permissions
Tap the "Recognize Face" button to capture an image and extract a face embedding
The app will register the user with their face embedding on the blockchain
View the user's face embedding on the blockchain by interacting with the smart contract
Smart Contract

The smart contract is written in Solidity and deployed on the Ethereum blockchain. It has a single function registerUser that takes a face embedding as input and stores it on the blockchain.

AI Model

The AI model used for facial recognition is a pre-trained TensorFlow Lite model. You can modify or replace this model to improve the accuracy of the facial recognition feature.

Blockchain Integration

The app uses Web3Dart to interact with the Ethereum blockchain. You'll need to replace the YOUR_PROJECT_ID and YOUR_CONTRACT_ADDRESS placeholders with your own Infura project ID and contract address.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

Issues

If you encounter any issues or bugs, please report them in the issues section of this repository.
