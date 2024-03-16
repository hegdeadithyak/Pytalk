# Pytalk
## Introduction

**Pytalk** is a real-time chat application built using Python Flask and Socket.IO. It enables users to create chat rooms, send messages, and interact with each other in a dynamic and engaging way.

## Features

**Real-time communication**: Messages are delivered instantly using Socket.IO, providing a seamless chat experience.
<br>
**Chat rooms**: Users can create and join chat rooms to connect with specific groups or communities.
<br>
**Simple and intuitive interface**: The web-based interface is designed for ease of use, allowing users to focus on conversations.
<br>
**Storing** : Everytime you refresh the data will be cleared as we use dictionaries so do not do that in future MONGODB will be added to solve this.

## Installation

**Prerequisites**: Ensure you have Python (version 3.x recommended) and pip (the package installer) installed on your system. You can verify this by running python --version and pip --version in your terminal.

**Clone the repository**: Use Git to clone this repository to your local machine:

```
git clone https://github.com/<your-username>/Pytalk.git
```

**Install dependencies**: Navigate to the cloned directory and install the required Python packages using pip:

```
cd Pytalk
pip install -r requirements.txt
```
### Running the Application

Start the development server: Execute the following command in your terminal to launch the Flask development server:

```
flask run
```

## Usage

**Create a chat room**: Provide a unique code for your chat room and click "Create Room" or a similar button in the interface.
<br>

**Join a chat room**: Enter the existing chat room code and click "Join Room" to participate in the conversation.
<br>

**Send messages**: Type your message in the designated input field and press Enter or click the "Send" button to broadcast it to other users in the chat room.

