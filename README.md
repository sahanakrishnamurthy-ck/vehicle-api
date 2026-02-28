Collaborative project developed for Vehicle API for Connected Vehicles.

Original repository by Bhushan-Bhad.

This fork represents my contribution and portfolio version.

This project was developed during an Innovation Sprint at Vector Tech Playground, organized by Vector Informatik with the support of NXTGN.

The goal was to design a connected vehicle API that enables remote interaction with vehicle functions using modern automotive communication standards.

Problem Statement:

    Modern connected vehicles require:

        Standardized access to vehicle signals

        Secure, real-time communication

        Scalable APIs for mobile and web applications

This project addresses these challenges using Vehicle Signal Specification (VSS) and MQTT-based messaging.

Solution Overview:

    We developed a Vehicle API platform that allows remote control and monitoring of vehicle parameters such as:

        Door lock / unlock

        Air-conditioning & heating control

        Vehicle signal access via VSS

        Web/mobile-ready frontend interface

The system includes:

    A VSS-based signal abstraction layer

    MQTT communication for real-time updates

    A self-developed test bench for validation

    An Angular frontend for user interaction

Tech Stack:

    Frontend: Angular, TypeScript, SCSS

    Communication: MQTT

    Automotive Standard: Vehicle Signal Specification (VSS)

Architecture: Modular Vehicle API design

Project Structure
src/
├── app/          # Angular application logic
├── assets/       # Static assets
├── index.html    # Entry point
├── main.ts       # Angular bootstrap
├── styles.scss   # Global styles

Getting Started
# Install dependencies
npm install

# Run the application
ng serve

# Open in browser
http://localhost:4200

Achievements:

    Winner – Innovation Sprint @ Vector Tech Playground

    Positive feedback from industry experts and judges

    Demonstrated real-world connected vehicle use-cases
