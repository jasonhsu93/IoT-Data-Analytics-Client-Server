IoT Data Analytics Project

Objective:
The project aimed to build a scalable Internet of Things (IoT) analytics server. This server receives data from various IoT sensors and actuators and provides a range of services including data aggregation and notification, handling multiple clients simultaneously.

Key Features and Implementation:

Scalable Server Design:

Developed a server capable of receiving sensor data from IoT devices.
Implemented services for data aggregation and providing notifications based on the received data.
Client-Server Model:

Utilized the Client-Server architecture to optimize response time and handle multiple clients simultaneously.
Prioritized incoming requests and messages to enhance server efficiency.
Team Collaboration:

Worked within a three-person team, leveraging collaborative skills in a complex project environment.
Developed and implemented a robust testing system ensuring up to 95% branch coverage, validating network functionalities effectively.
Implementation:

(Entities, Events, Clients, and Requests): Focused on developing data types/classes for sensors, actuators, their events, client interactions, and requests handling. This included creating random simulation metrics for various entity types like TempSensor, PressureSensor, and Switches.

(Providing Services to Clients): Built capabilities to handle various events from clients, offering control and analytics services like setActuatorStateIf, toggleActuatorStateIf, and logIF.

(Handling Concurrent Clients): Enhanced the server to serve multiple clients concurrently, ensuring isolated handling of events and requests for each client to minimize Quality of Service (QoS) violations.

(Prediction Services): Added prediction capabilities to the server, such as predictNextNTimeStamps and predictNextNValues, with a focus on forecasting both double and binary values accurately.

(AWS Lambda Integration): Integrated AWS Lambda for handling excess load, particularly focusing on computational-heavy prediction services.
Testing Methodology:

Employed a combination of unit testing, trace-driven functional testing, and deployment integration testing to ensure the robustness and reliability of the server.

Outcomes and Skills Gained:

Successfully developed a multi-functional IoT analytics server capable of handling real-time data from various sensors and actuators.
Gained significant experience in cloud programming, concurrency handling, and IoT server architecture.
Demonstrated the ability to work effectively in a team environment, with a strong emphasis on testing and quality assurance.
This project is a testament to the team's ability to handle complex software architecture, emphasizing scalability, concurrency, and real-time data processing, making it a significant accomplishment for any role requiring expertise in IoT systems, cloud computing, and data analytics.
