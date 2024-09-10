# Online Code Editor

This project is a Repl.it-like online code editor implemented using **Node.js**, **Kubernetes (K8s)**, **Express**, and **Socket.io**. It allows users to write, execute, and test code directly in their browser, offering real-time collaboration and an interactive coding environment.

## Features

- **Real-time Collaboration**: Users can collaborate on coding projects with real-time synchronized code editing and execution, powered by Socket.io.
- **Scalability**: Kubernetes handles container orchestration, ensuring that the platform scales effortlessly while providing high availability.
- **Multi-language Support**: The editor can execute code written in multiple programming languages.
- **Interactive Terminal**: Provides a terminal environment for running commands, testing scripts, and debugging code directly in the browser.

## Tech Stack

- **Node.js**: Backend framework used for handling requests and managing the code execution engine.
- **Kubernetes (K8s)**: For container orchestration and management, ensuring efficient resource allocation and scalability.
- **Express**: Backend framework for building APIs and handling HTTP requests.
- **Socket.io**: Enables real-time, bi-directional communication between the client and server for collaborative coding.

## Getting Started

### Prerequisites

To run this project locally, you'll need:

- [Node.js](https://nodejs.org/) v14+ installed.
- [Docker](https://www.docker.com/get-started) and [Kubernetes](https://kubernetes.io/docs/setup/) for container orchestration.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/IamAbhinavSINGH/replit.git
   cd replit
   
2. Install the dependencies:
   ```bash
   npm install
   
3. Set up Kubernetes and Docker to start managing containers for the editor environment.

4. Start the server.
   ```bash
     npm run start
   
5. Open your browser and navigate to http://localhost:3000 to start using the   editor.

  ### Usage
  
- Access the code editor in your browser.
- Collaborate with others in real-time.
- Write and run code in multiple languages.
- Use the integrated terminal for debugging and testing.

### Contributing

If you'd like to contribute, feel free to submit a pull request or report issues on the issue tracker.

### License

This project is licensed under the MIT License.
