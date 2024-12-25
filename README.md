# Akka Actor System Application

## Overview
The **Akka Actor System Application** demonstrates a simple yet powerful implementation of an actor-based system using the **Akka framework**. This project focuses on processing objects and facilitating message-passing between actors, showcasing the core concepts of Akka for building scalable and fault-tolerant applications.

## Features
- **Actor-Based Design**: Implements actors for modular and concurrent operations.
- **Message-Passing**: Enables efficient communication between actors.
- **Scalability**: Demonstrates Akka's capability to scale applications horizontally.
- **Easy Integration**: Built with Maven for dependency and build management.

## Project Structure
```
Akka-ile-basit-bir-aktor-sistemi-main
│
├── AkkaProje
│   ├── pom.xml                              # Maven project configuration
│   ├── src/main/java/com/mycompany/akkaproje
│   │   ├── AkkaProje.java                   # Project entry point
│   │   ├── Main.java                        # Main execution logic
│   │   ├── MessageActor.java                # Core actor implementation
│   └── target
│       ├── AkkaProje-1.0-SNAPSHOT.jar       # Compiled JAR file
│       ├── classes                          # Compiled classes
│       └── maven-archiver                   # Maven build info
```

## Technologies Used
- **Framework**: Akka (Java-based)
- **Build Tool**: Apache Maven
- **Programming Language**: Java
- **Design Pattern**: Actor Model

## Getting Started

### Prerequisites
Ensure you have the following installed:
- **Java JDK 8+**
- **Apache Maven**

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AkkaActorSystem.git
   cd AkkaActorSystem/AkkaProje
   ```

2. Build the project:
   ```bash
   mvn clean install
   ```

3. Run the application:
   ```bash
   java -cp target/AkkaProje-1.0-SNAPSHOT.jar com.mycompany.akkaproje.Main
   ```

## Usage
- **Main Class**: The `Main` class initializes the actor system and sends messages to actors.
- **MessageActor**: Processes and logs incoming messages.
- **Extend Functionality**: Add new actor classes to expand system capabilities.

## Example Output
When you run the application, it will demonstrate basic message-passing functionality with output similar to:
```
[INFO] ActorSystem started.
[INFO] Message received: Hello, Akka!
[INFO] Message processed: Hello, Akka!
```

## Contribution
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries or feedback, feel free to reach out:
- **Email**: eraykelesk@gmail.com
- **LinkedIn**: [Eray Keleş](https://linkedin.com/in/eraykeles)
