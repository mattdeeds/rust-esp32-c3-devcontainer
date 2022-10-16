# rust-esp32-c3-devcontainer
A template for creating a ready to use rust development environment for the ESP32-C3 using Development Containers

## Prerequisites
- Docker Desktop 
- VS Code
- Dev Containers extension from Microsoft

## Getting Started
- Clone this repo to your local machine 
- Open the repo folder in VS Code
- USB Device /dev/tty.usbmodem14201 is exported to container for programming, change this in devcontainer.json if this isn't your usb device
- In the VS Code command palette (press F1) type **rebuild** and select the option **Dev Containers: Rebuild and Reopen in Container**
- The dev container will now begin building. This could take several minutes the first time through. 
- Click **Show Log** to see the build log 
- When the container is done building you should see the configuration prompt for your new esp-idf project 

Now you'll have a fully setup dev environment for programming your ESP32-C3 board in rust 