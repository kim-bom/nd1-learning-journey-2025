# nd1-learning-journey-2025
----------

### **4 Oct 2025**

-   Reviewed knowledge on using circuit simulation programs such as **Tinkercad** by Autodesk, which runs online via a web browser without installation, and **Proteus**, which is used for more serious signal analysis for circuit design.
    
-   Targets of attacks on **OT Systems** include **SCADA, HMI, PLC, IIoT, DCS, RTU**. Potential impacts include **Energy, Manufacturing, Water/Utilities, and Transportation** sectors.
    
-   Currently, selling products requires concern for **security labeling**, following the **IEC 62443** standard for **Industrial Control Systems (ICS) and Operational Technology (OT) cybersecurity**.
    
-   Future trends indicate that **electronic boards** should be designed to support **Multi-Agent** systems, such as voice commands that can instruct boards to operate using AI.
    
-   Learned about **GitHub Pages**, which allows creating small websites for content display without renting hosting.
    
-   Learned about **Kiro Kiro**, an AI Agent that directly addresses this problem using **Spec-Driven Development**, bringing software engineering principles back into AI-assisted workflows. It recommends 3 main steps:
    
    1.  **Requirements**: Clearly define goals and user stories
        
    2.  **Design**: Plan architecture and technologies
        
    3.  **Implementation**: Break large tasks into smaller ones and instruct AI to create plans and cost summaries
        
-   Learned about creating **Markdown** without memorizing syntax by using **[https://stackedit.io/](https://stackedit.io/)**
    

----------

### **11 Oct 2025**

-   **QUIC Protocol** is MQTT over **UDP**, suitable for low-latency and real-time applications. **EMQX** currently supports QUIC and provides security features.
    
-   **Comet Browser** is a new-generation web browser developed by **Perplexity AI**, deeply integrating AI into web browsing. It includes an AI assistant (**Comet Assistant**) that summarizes content, answers questions about webpages, and performs tasks automatically, aiming to replace traditional link-clicking search with smarter interactions.
    
-   **Bitbucket** is a Git-based repository hosting platform developed by **Atlassian**, suitable for team collaboration, code management, and project planning. It integrates well with **Jira, Trello, and Jenkins** to support CI/CD workflows. A key strength is unlimited private repositories on the free plan.
    
-   **git-scm** refers to **Git**, a free and open-source distributed version control system designed to efficiently manage projects of all sizes.
    
-   **VS Code Insider** is a preview/beta version of Visual Studio Code that provides early access to new features, bug fixes, and improvements before they are released in the stable version.
    
-   Learned how to install **EMQX via Docker Hub**.
    
-   Learned Docker commands and how to expose ports.
    
-   Reviewed **Strong Typing**, which means declaring variable types explicitly.
    
-   Learned about **flet.dev**, a Python-based tool for building beautiful web UIs similar to React, which can run both on the web and locally.
    
-   **Electron.js** is an open-source framework from GitHub that allows developers to build cross-platform desktop applications (Windows, macOS, Linux) using web technologies such as HTML, CSS, and JavaScript (including React or Vue). Electron bundles **Chromium** for rendering and **Node.js** for backend functionality, enabling direct access to OS features. Popular apps like **VS Code, Slack, and Twitch** are built with Electron.
    
-   **MQTT Concept** (image attached):
    
    -   **Publisher**: Sends data (e.g., PLCs, sensors, or other devices)
        
    -   **MQTT Broker**: Acts as a middleman, receiving messages from publishers and distributing them to interested subscribers
        
    -   **Subscriber**: Receives data by subscribing to topics of interest
        
-   **Certbot** is a free and open-source tool used to automatically obtain and manage **Let’s Encrypt** certificates to enable HTTPS on self-managed websites.
    

----------

### **18 Oct 2025**

-   Learned about **PCB/Hardware Design Principles**, especially what must be followed when designing products seriously for commercial sale.
    
-   **Obsidian** is a highly flexible personal knowledge management (PKM) application focused on building a “**Second Brain**” through linked knowledge. This knowledge can be used to train personal AI models, allowing users to query their own knowledge as if it were a second brain.
    
-   **Spline 3D** is a web-based 3D design platform focused on ease of use and real-time collaboration. It is no-code and has an interface similar to Figma, but for 3D.
    
-   **Blend4Web** is an open-source framework used to create and render **interactive 3D graphics** directly in web browsers without plugins.
    

----------

### **25 Oct 2025**

-   Learned how to use **EasyEDA** for online circuit design, including checking component stock and reviewing PCB trace design principles.
    

----------

### **1 Nov 2025**

-   **Deepcraft Studio** is an end-to-end **Edge AI and Machine Learning** development platform designed specifically for small and edge devices.
    
-   Reviewed **Finite State Machines (FSM)** as a method to simplify complex programming problems by visualizing program states using diagrams.
    
-   **Eraser.io** is a platform for creating technical documents and diagrams, designed to help engineering teams collaborate on system planning and documentation.
    
-   **Emscripten** is an open-source compiler toolchain that converts **C/C++** (and other LLVM-based languages) into **WebAssembly (Wasm)** or JavaScript so they can run in browsers or Node.js with near-native performance.
    
-   **Babel** is a toolchain that converts modern **ECMAScript (ES2015+)** code into backward-compatible JavaScript for current and older environments.
    

----------

### **8 Nov 2025**

-   In MCU programming, it is recommended **not to use delay**, as the program may block and miss incoming sensor data.
    
-   Benefits of **Digital Twin**: flashing firmware to an MCU can take several seconds, but with a digital twin, results can be observed immediately.
    
-   Windows libraries typically use file extensions **.lib** and **.dll**.
    
-   Learned how to write programs based on **Finite State Machine diagrams**.
    
-   Learned programming best practices for readability and maintainability, such as using `#define` for switch-case variables.
    
-   **Process Explorer** is useful for developers to inspect processes and tasks in detail.
    

----------

### **15 Nov 2025**

-   **Digital Transformation** refers to using digital technology to create improvements, divided into two parts:
    
    1.  **Digitization**: Converting analog data to digital
        
    2.  **Digitalization**: Integrating technologies into systems and business processes
        
-   Core components of an automation system:
    
    1.  Sensors
        
    2.  Controllers
        
    3.  Actuators
        
-   **SaaS (Software as a Service)** is cloud-based software delivered over the internet via subscription or usage-based pricing, eliminating the need for local installation and reducing IT management overhead.
    
-   **Master-Slave communication** (e.g., Modbus) allows communication only one pair at a time and is not full-duplex; sending and receiving occur at different times on the same communication line.
    
-   Microcontroller communication protocols include:
    
    1.  UART
        
    2.  I2C
        
    3.  SPI
        
    4.  Parallel Communication
        
    5.  CAN
        
    6.  Ethernet
        
    7.  RS-232
        
    8.  RS-485
        
    9.  USB
        
    10.  Bluetooth (Classic / BLE)
        
    11.  Wi-Fi
        

----------

### **22 Nov 2025**

-   **Docker Compose** is a tool for defining and managing multi-container Docker applications using a single **YAML file (docker-compose.yml)**. It allows starting, stopping, and managing all containers with a single command.
    
-   Learned how to run Docker projects created by others and how to troubleshoot common issues.
    
-   Learned the difference between running Docker containers in **foreground vs background**.
    
-   **WebSocket** is a full-duplex, persistent communication protocol between clients and servers, suitable for real-time applications such as live chat, online games, notifications, and dashboards.
    

----------

### **29 Nov 2025**

-   Learned how to use **RStudio** for data analysis, especially importing data from **.csv** files.
    
-   **Positron** is an IDE designed for AI and data science workflows.
    
-   **RStudio** is similar to Jupyter Notebook.
    
-   Workspace settings can be copied between projects using the `.Rproject.user` folder.
    
-   The **Run** button executes code line-by-line, similar to step-into debugging.
    
-   In real-world scenarios, programs do not wait for complete datasets; instead, data behavior is analyzed and synthetic data is generated to match desired patterns.
    
-   R extensions can be installed in **VS Code**.
    
-   Learned the workflow for working with R.
    
-   RStudio is preferred over Excel for large or real-time datasets, as Excel cannot handle them efficiently.
    

----------

### **6 Dec 2025**

-   **ggplot2** is an R package for creating flexible and elegant data visualizations using the **Grammar of Graphics** concept.
    
-   **Tidyverse** is a collection of R packages designed for data science, sharing consistent design philosophy and syntax.
    
-   To generate the same random data consistently, a **seed** must be set.
    
-   Plotting in R is similar to Photoshop layers, where multiple layers combine into a final graph.
    
-   **R Markdown** files can be executed and displayed block-by-block, similar to Jupyter Notebook.


----------

### **13 Dec 2025**

-   Learned the behavior of **MQTT publish and subscribe**
    
-   Explained the system architecture with reference to the image file **`iot_architecture_diagram.svg`**
    
## 1. Host Machine (User / Developer Machine)

### 1.1 Components

**1.1.1 Python Scripts – Student Code**  
→ Used for testing, sending data, or calling APIs

**1.1.2 Web Browser – User Interface**  
→ Users access dashboards and APIs through a web browser

### 1.2 Access

**1.2.1** Users access the system through **a single port only**  
→ **HTTP : 8888 (via Nginx)**

## 2. Docker Network (iot-network)

All services run within the same Docker network.  
They communicate using **internal ports** and are **not directly exposed to the internet**.

## 3. Access Layer (Reverse Proxy)

### 3.1 Nginx – Port 8888

**Responsibilities**

-   **3.1.1** Acts as a reverse proxy
    
-   **3.1.2** Routes user requests to internal services
    
## 4. Application Layer (Logic / Processing)

### 4.1 IoT Simulator – Data Generator

-   **4.1.1** Simulates sensors / devices
    
-   **4.1.2** Publishes data via MQTT
    
### 4.2 Node-RED – Port 1880

**Main responsibilities**

-   **4.2.1** MQTT subscribe / publish
    
-   **4.2.2** Data flow and logic processing
    
-   **4.2.3** Writes data to InfluxDB
    
-   **4.2.4** Provides dashboards (FlowFuse)
    
### 4.3 Flask API – Port 5000

**Responsibilities**

-   **4.3.1** REST API
    
-   **4.3.2** Read / write data from InfluxDB
    
-   **4.3.3** Provides APIs for frontend applications and Grafana
    
**Conceptual roles**

-   **Node-RED** = Flow-based processing
    
-   **Flask** = Programmatic API / integration
    
## 5. Messaging Layer

### 5.1 EMQX MQTT Broker – Port 1883

**Responsibilities**

-   **5.1.1** Message routing (Pub/Sub)
    
-   **5.1.2** Decouples producers from consumers
    
**Usage**

-   **5.1.1** IoT Simulator → Publish
    
-   **5.1.2** Node-RED → Subscribe / Publish
    
-   **5.1.3** Supports large-scale device expansion
    
## 6. Data Layer

### 6.1 InfluxDB – Port 8086

**Database type**

-   **6.1.1** Time-series database
    
**Responsibilities**

-   **6.1.1** Stores sensor data over time
    
-   **6.1.2** Supports time-range queries
    
-   **6.1.3** Integrates well with Grafana
    
## 7. Visualization Layer

### 7.1 Grafana – Port 3000

**Responsibilities**

-   **7.1.1** Displays dashboards
    
-   **7.1.2** Queries data from InfluxDB
    
-   **7.1.3** Calls APIs via Flask
    
**Access**

-   **7.1.1** Accessed only through the Nginx proxy (not directly exposed)
