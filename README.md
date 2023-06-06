# Hyperledger Fabric

This repository contains a Hyperledger Fabric project built using Fabric 2.0. It demonstrates the implementation of a blockchain network and smart contracts using Hyperledger Fabric.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Development Environment

1. Linux or macOS is recommended for the development environment.

2. For Windows users, it is recommended to set up WSL (Windows Subsystem for Linux) to run this project. Follow the steps below to set up WSL:

- Install WSL: Follow the official Microsoft documentation to install WSL on your Windows machine. You can find more information ![here](https://docs.microsoft.com/en-us/windows/wsl/).

- Install a Linux distribution: Once WSL is set up, install a Linux distribution of your choice from the Microsoft Store or by following the instructions in the WSL documentation.

- Launch a Linux shell: Open the Linux distribution you installed and proceed with the remaining instructions in this README file within the Linux shell.

### Prerequisites

Before running the project, ensure you have the following software installed:

- Docker
- Go programming language (version 1.13 or later)
- Node.js (version 8.x or later)
- npm (Node package manager)

### Installation

Follow these steps to install the project:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/rishitashaw/Hyperledger-Fabric.git
   ```

2. Navigate to the project directory:

   ```
   cd Hyperledger-Fabric
   ```

3. Install the necessary dependencies:

   ```
   npm install
   ```

4. Build the project:

   ```
   make all
   ```

### Running the Project

To start the Hyperledger Fabric network and deploy the smart contracts, follow these steps:

1. Start the network:

   ```
   make network-up
   ```

2. Deploy the smart contracts:

   ```
   make deploy
   ```

### Usage

I'll update as soon as the project is complete

### Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b my-new-branch`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push the branch: `git push origin my-new-branch`
5. Submit a pull request

### License

This project is licensed under the [MIT License](LICENSE.md).

### Acknowledgments

List any acknowledgments or resources that you found helpful during your work on the project.

- [Hyperledger Fabric Documentation](https://hyperledger-fabric.readthedocs.io/)
- [Hyperledger Fabric Samples](https://github.com/hyperledger/fabric-samples)

### Contact

If you have any questions or suggestions, feel free to contact me at [rishitashaw49@gmail.com](mailto:rishitashaw49@gmail.com).

