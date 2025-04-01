# Python Chat App

A simple real-time chat application built with Flask and Flask-SocketIO.

## Features
- Create and join chat rooms with unique codes
- Real-time messaging
- Displays active users in the room
- Automatically removes empty rooms

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/AgrawalAdarsh/Python_ChatApp_Basic.git
   ```
2. Navigate to the project folder
   ```
   cd Python_ChatApp_Basic
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
## Usage:

1. Run the app:
   ```
   python main.py
   ```
2. Acceess the chatapp in your browser:
   ```http://localhost:5000```
   or if accessing from another device on same network:
   ```http:<your-device-ip>:5000```
   (Find your local ip using ```ipcongig``` on **windows** or ```ifconfig``` on **Linux**)

## Deployment 

1.To allow external devices to connect, run the app using:
  ```
  python main.py
  ```
  Then on other devies, enter:
  ```
  http:<you-ip>:5000
  ```
  Ensure all the devices are on same network

## Requirements:

- See requirements.txt for dependencies

## License:

- This project is licensed under MIT License.
