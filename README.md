# A developer's guide to the IoT by IBM

* [About this Course](https://github.com/leehaesung/A-developer-s-guide-to-the-IoT-by-IBM/blob/master/01_Lecture_Notes/README.md)
* [Visit the Coursera (A developer's guide to the Internet of Things (IoT) by IBM)](https://www.coursera.org/learn/developer-iot/home/welcome)

![IBM Watson IoT](https://github.com/leehaesung/A-developer-s-guide-to-the-IoT-by-IBM/blob/master/01_Lecture_Notes/ImageFiles/IBM_Watson_IoT.png)

# Contents

## Week 01. Introduction to the course
* Up to now the course has used the NodeRED rapid application development environment. This unit looks at how to program for the Internet of Things platform using more traditional programming environments
   * About this course
        * [Welcome to A developer's guide to the Internet of Things 3 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/01_WelcomeToAdevelopersGuideToTheIoT_3min.mp4)
        * [Course Prerequisites 3 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/02_Course_Prerequisite_3min.mp4)
        * [Summary of the lessons 4 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/03_SummaryOfTheLessons_4min.mp4)
        * [What practical work is in this course? 2 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/04_WhatPracticalWorkIsinThisCourse2min.mp4)
        * [Learning module summary: About this course (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/05_Learning%20ModuleSummary_AboutThisCourse_Coursera.pdf)

   * What is the Internet of Things?
        * [Overview of Internet of Things 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/05_Overview_IoT6min.mp4)
        * [Quiz: IoT Quiz5 questions (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/Week01_Quiz_Coursera_100Passed.pdf)
        * [Learning module summary: What is the Internet of Things? 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/08_Learning%20module%20summary_%20What%20is%20the%20Internet%20of%20Things_%20_%20Coursera.pdf)

## Week 02. Rapid application development in the cloud
 * An Internet of Things solution usually requires a back-end server to receive and process data coming from sensors. Cloud platforms allow new solutions to be created and deployed very rapidly without having to worry about how to host the application. This series of lessons introduces you to a cloud based Platform as a Service and an open source rapid application development environment called NodeRED.
    * Introduction to a Platform as a Service - IBM Bluemix
        * [Introduction to IBM Bluemix - Agenda 27 sec (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/06_IntroductionToIBMBluemixAgenda_27sec.mp4)
              1. Cloud computing
              2. What is IBM Bluemix?
              3. A tour of IBM Bluemix
              
        * [Overview of Cloud Computing 3 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/07_OverviewOfCloudComputing_3min.mp4)
              1. IaaS(Infrastructure as a Service)
              2. PaaS(Platform as a Service)
              3. SaaS(Software as a Service)
              ![CloudComputing.png](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/01_Lecture_Notes/ImageFiles/CloudComputing.png)
              
        * [What is IBM Bluemix? 4 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/08_WhatIsIBMBluemix_4min.mp4)
              ![IBM_Bluemix.png](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/01_Lecture_Notes/ImageFiles/IBM_Bluemix.png)
              ![IBM_Bluemix_DevOps_Services.png](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/01_Lecture_Notes/ImageFiles/IBM_Bluemix_DevOps_Services.png)
        * [A tour of IBM Bluemix 8 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/09_A%20tour%20of%20IBM%20Bluemix8min.mp4)
        * [IBM Bluemix Summary 35 sec (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/10_IBM%20Bluemix%20Summary_35sec.mp4)
        * [Learning module summary: Introduction to Platform as a Service - IBM Bluemix 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/11_Learning%20module%20summary-%20Introduction%20to%20Platform%20as%20a%20Service%20-%20IBM%20Bluemix_10%20min.pdf)

    * Rapid application development for Internet of Things
        * [Introduction to NodeRED-1 11 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/06_IntroductionToIBMBluemixAgenda_27sec.mp4)
              * Node-RED is a visual tool for wiring together hardware devices, APIs and online services – for wiring the [Internet of Things](https://en.wikipedia.org/wiki/Internet_of_things). Node-RED provides a browser-based flow editor that makes it easy to wire together flows using the wide range nodes in the palette. Flows can be then deployed to the runtime in a single-click. JavaScript functions can be created within the editor using the a rich text editor. A built-in library allows you to save useful functions, templates or flows for re-use.
              The light-weight runtime is built on [Node.js](https://en.wikipedia.org/wiki/Node.js), taking full advantage of its event-driven, non-blocking model. This makes it ideal to run at the edge of the network on low-cost hardware such as the [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) as well as in the cloud. With over 120,000 modules in Node's package repository, it is easy to extend the range of palette nodes to add new capabilities. 
              The flows created in Node-RED are stored using [JSON](https://en.wikipedia.org/wiki/JSON) which can be easily imported and exported for sharing with others. An online flow library allows you to share your best flows with the world.
              
              ![NodeRED_terms.png](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/01_Lecture_Notes/ImageFiles/NodeRED_terms.png)
        * [Deploy NodeRED to Bluemix using a Boilerplate - step by step 10 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/12_Deploy%20NodeRED%20to%20Bluemix%20using%20a%20Boilerplate_step%20by%20step_10min.mp4)
        * [Introduction to NodeRED-2 7 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/13_Introduction%20to%20NodeRED_7min.mp4)
        * [Adding a new node - step by step 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/14_Adding%20a%20new%20node%20-%20step%20by%20step%2010%20min.pdf)
        * [Learning module summary: Rapid application development for Internet of Things 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/08_Learning%20module%20summary_%20What%20is%20the%20Internet%20of%20Things_%20_%20Coursera.pdf)
    
    * NodeRED function node
        * [The NodeRED Function node part 1 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/14_The%20NodeRED%20Function%20node%20part_1_06min.mp4)
        * [Function node - step by step 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/16_Function%20node%20-%20step%20by%20step_10%20min.pdf)
        * [The NodeRED Function node part 2 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/15_The%20NodeRED%20Function%20node%20part2_6min.mp4)
        * [The NodeRED Function node part 3 5 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/16_The%20NodeRED%20Function%20node%20part3_5min.mp4)
        * [Making packages available to the function node - step by step 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/17_Making%20packages%20available%20to%20the%20function%20node%20-%20step%20by%20step10min.pdf)
        * Quiz: Using the function node 5 questions
        * Submitting your first assignment 10 min 
        * Programming Assignment: Your First NodeRED application 3h
        * [Learning module summary: NodeRED function node 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/20_Learning%20module%20summary_%20NodeRED%20function%20node%20_%20Coursera.pdf)
        
    * Additional NodeRED nodes
        * [NodeRED Additional node part 1 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/17_NodeRED%20Additional%20node%20part1_6min.mp4)
        * [NodeRED Additional node part 2 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/18_NodeRED%20Additional%20node%20part2_6min.mp4)
        * [Template node sample flow 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/21_Template%20node%20sample%20flow_10min.pdf)
        * [NodeRED Additional node part 3 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/19_NodeRED%20Additional%20node%20part3_6min.mp4)
        * [Controlling a node using input data 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/22_Controlling%20a%20node%20using%20input%20data_10min.pdf)
        * [NodeRED Additional node part 4 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/20_NodeRED%20Additional%20node%20part4_6min.mp4)
        * Programming Assignment: NodeRED application3h
        * Learning module summary: Additional NodeRED nodes 10 min

## Week 03. Rapid application development on a Raspberry Pi
* This unit looks at how to add a device to your solution. Creating an application on a Raspberry Pi and establishing secure, trusted communication between your cloud application and devices
    * Raspberry Pi and SenseHAT
          * [A quick look at devices and sensor options 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/21_A%20quick%20look%20at%20devices%20and%20sensor%20options_6min.mp4)
          * [Setting up a Raspberry Pi and Raspberry Pi Sense Hat 9 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/22_Setting%20up%20a%20Raspberry%20Pi%20and%20Raspberry%20Pi%20Sense%20Hat_9min.mp4)
          * [Setting up your Raspberry Pi - step by step 10 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/25_Setting%20up%20your%20Raspberry%20Pi%20_step%20by%20step_10min.pdf)
          * [Extra resource – (for Windows) Install the Raspbian Jessie OS on an SD Card 1 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/23_Extra%20resource%20%E2%80%93%20(for%20Windows)%20Install%20the%20Raspbian%20Jessie%20OS%20on%20an%20SD%20Card_1min.mp4)
          * [Learning module summary: Raspberry Pi and SenseHAT 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/26_Learning%20module%20summary_Raspberry%20Pi%20and%20SenseHAT_10min.pdf)
          * [Schematic of Raspberry Pi2](https://github.com/leehaesung/A-developer-s-guide-to-the-IoT-by-IBM/blob/master/03_RaspberryPi2/Raspberry-Pi-B-Plus-V1.2-Schematics.pdf)
          * [Schematic of SenseHAT](https://github.com/leehaesung/A-developer-s-guide-to-the-IoT-by-IBM/blob/master/04_Pi_Sense_HAT/Sense-HAT-V1_0.pdf) 
          
    * Rapid Application Development with NodeRED on a Raspberry Pi
          * [NodeRED on Raspberry Pi part 15 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/24_NodeRED%20on%20Raspberry%20Pi%20part1_5min.mp4)
          * [NodeRED on Raspberry Pi part 2 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/25_NodeRED%20on%20RaspberryPi%20part2_6min.mp4)
          * [QuickStart flow - step by step 10 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/27_QuickStart%20flow_step%20by%20step_10min.pdf)
          * [Programming Assignment: QuickStart flow on Raspberry Pi 3h (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/28_01_Programming%20Assignment_QuickStart%20flow%20on%20Raspberry%20Pi_3h.pdf)
          * [Learning module summary: Rapid Application Development with NodeRED on a Raspberry Pi 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/29_Learning%20module%20summary_Rapid%20Application%20Development%20with%20NodeRED%20on%20a%20Raspberry%20Pi_10min.pdf)

    * Introduction to the Watson Internet of Things Platform
          * [Watson Internet of Things platform 5 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/26_Watson%20Internet%20of%20Things%20platform_5min.mp4)
          * [Devices, Applications and Gateways part 1 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/27_Devices%2C%20Applications%20and%20Gateways%20part1_6min.mp4)
          * [Devices, Applications and Gateways part 2 7 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/28_Devices%2C%20Applications%20and%20Gateways%20part2_7min.mp4)
          * Quiz: Using the NodeRED flow editor with your own Watson IoT platform 5 questions
          * [Learning module summary: Introduction to the Watson Internet of Things Platform 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/30_Learning%20module%20summary_Introduction%20to%20the%20Watson%20Internet%20of%20Things%20Platform_10min.pdf)
    
    * Controlling a device
          * [Sending commands to a device 4 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/29_Sending%20commands%20to%20a%20device_4min.mp4)
          * [SenseHAT and SenseHAT simulator nodes in NodeRED 3 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/30_SenseHAT%20and%20SenseHAT%20simulator%20nodes%20in%20NodeRED_3min.mp4)
          * [Programming Assignment: End-to-end scenario 3h (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/31_01_Programming%20Assignment-End-to-end%20scenario_3h.pdf)
          * [Learning module summary: Controlling the device 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/32_Learning%20module%20summary_Controlling%20the%20device_10min.pdf)
          

## Week 04. Lower level programming for the Internet of Things
* Up to now the course has used the NodeRED rapid application development environment. This unit looks at how to program for the Internet of Things platform using more traditional programming environments
    * Watson IoT APIs
          * [IoT platform APIs 3 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/31_IoT%20platform%20APIs_3min.mp4)
          * [Official GitHub: iot-python](https://github.com/ibm-watson-iot/iot-python)
          * [SenseHAT python API 4 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/32_SenseHAT%20python%20API_4min.mp4)
          * [Programming Assignment: SenseHAT python API 3h (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/33_01_Programming%20Assignment_SenseHAT%20python%20API_3h.pdf)
          * [Learning module summary: Watson IoT APIs 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/34_Learning%20module%20summary_Watson%20IoT%20APIs_10min.pdf)

    * MQTT(Message Queue Telemetry Transport)
          * [MQTT 5 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/33_MQTT_5min.mp4)
            * “MQTT(Message Queue Telemetry Transport) is a machine-to-machine (M2M)/”Internet of Things” connectivity protocol. It was designed as an extremely lightweight publish/subscribe messaging transport.” 
              * Small Code footprint
              * Low Powe consumption
              * Low network bandwidth
              * A pub-sub system
              
          * This differs from peer-to-peer communication, like email or SMS texting, where the sender sends a message to a specified receiver. 
          * ![MQTT02.png](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/01_Lecture_Notes/ImageFiles/MQTT02.png)
          
          * In pop sub communication, there is a broker in the middle on the sender, publishes data to the broker against a topic. So you can think of it almost like a bulletin board. Where the sender is not really aware of who is going to consume the data. The advantages of the coupling, the sender and receiver means that a message can be sent to multiple recipients without the sender needing to know who those recipients are. 
          *![MQTT01.png](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/01_Lecture_Notes/ImageFiles/MQTT01.png)
          
          * Quiz: MQTT in Watson IoT Platform 5 questions
          * [MQTT Exercise 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/35_MQTT%20Exercise_10min.pdf)
          * [You reached the end of this learning module. You are now able to: 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/36_MQTT%20Exercise_10min.pdf)
          * (Additional material) IoT 101 Network Diagram 
           ![IOT-101-Network-Diagram](https://github.com/leehaesung/A-developer-s-guide-to-the-IoT-by-IBM/blob/master/01_Lecture_Notes/ImageFiles/IOT-101-Network-Diagram-FINAL-01.png)
           
    * Deploying Applications to Bluemix
          * [Deploying an application to Bluemix part 1 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/34_Deploying%20an%20application%20to%20Bluemix%20part1_6min.mp4)
          * [Application development for Bluemix - basic server step by step 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/37_Application%20development%20for%20Bluemix_basic%20server%20step%20by%20step_10min.pdf)
          * [Deploying an application to Bluemix part 2 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/35_Deploying%20an%20application%20to%20Bluemix_part2_6min.mp4)
          * [Application development for Bluemix - deploy to Bluemix step by step 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/38_Application%20development%20for%20Bluemix_deploy%20to%20Bluemix%20step%20by%20step_10min.pdf)
          * [Deploying an application to Bluemix part 3 6 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/36_Deploying%20an%20application%20to%20Bluemix%20part3_6min.mp4)
          * [Application development for Bluemix - accessing services step by step 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/39_Application%20development%20for%20Bluemix_accessing%20services%20step%20by%20step_10min.pdf)
          * [Programming Assignment: Using the IoT APIs in a Bluemix application 3h (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/40_01_Programming%20Assignment_Using%20the%20IoT%20APIs%20in%20a%20Bluemix%20application_3h.pdf)
          * [Learning module summary: Deploying Applications to Bluemix 10 min (pdf)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/41_Learning%20module%20summary_Deploying%20Applications%20to%20Bluemix_10min.pdf)
  
    * Wrap up
          * [Course summary 2 min (mp4)](https://github.com/leehaesung/A_Developer_Guide_To_the_IoT_IBM/blob/master/02_Lecture_Videos/37_Course%20summary_2min.mp4)


## Useful Web Site
* [What is npm?](https://docs.npmjs.com/getting-started/what-is-npm) NPM makes it easy for JavaScript developers to share and reuse code, and it makes it easy to update the code that you're sharing.
* [Watson IoT Platform Documentation](https://console.ng.bluemix.net/docs/services/IoT/index.html)
* [YouTube: How It Works: Internet of Things](https://youtu.be/QSIPNhOiMoE)
* [Watson IoT Academy](https://www.iot-academy.info/)
* [To learn JavaScript](http://www.w3schools.com/js/)
* [NodeRED](http://nodered.org/docs/)
* [Node-RED: A visual tool for wiring the Internet of Things](http://nodered.org/?cm_mc_uid=06583862420914669164974&cm_mc_sid_50200000=1469855535)
* [Node.js](https://nodejs.org)
* [Introducing JSON](http://www.json.org/)
* [JASON Standard pdf file](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)
* [Python.org](https://www.python.org)
* [IBM Bluemix](https://www.bluemix.net)
* [Bluemix Platform as a Service functionality](http://docs.cloudfoundry.org)
* [CloudFoundry Command Line Interface tool](https://github.com/cloudfoundry/cli/releases)
* [SenseHAT Python API](http://pythonhosted.org/sense-hat/)
* [IoT on Raspberry Pi By IBM](http://www.ibm.com/internet-of-things/ecosystem/devices/raspberry-pi/)
* [Raspberry Pi: Find IoT projects at Raspberry Pi.](https://www.raspberrypi.org/?s=IoT&cm_mc_uid=06583862420914669164974&cm_mc_sid_50200000=1469855535)
* [MQTT Connectivity for Gateways
(IBM)](https://docs.internetofthings.ibmcloud.com/gateways/mqtt.html)
* [raspberry-pi-tightvnc-server](http://raspberrypihelp.net/raspberry-pi-tightvnc-server/)
* [IBM Watson: Using the Visual Recognition service to classify Dog Breeds!](https://youtu.be/FYZld6SSCnY)
* [IBM Watson, Machine Learning: How to use the "Retrieve and Rank" service in IBM Bluemix!](https://youtu.be/xeMYyog6icQ)

## Useful GiTHub of using the IBM BlueMix with Raspberry Pi
* [GitHub: Official iot-python](https://github.com/ibm-watson-iot/iot-python)
* [Serach 'IBM IoT Raspberry Pi' in GitHub](https://github.com/search?utf8=%E2%9C%93&q=IBM+IoT+Raspberry+Pi&type=Repositories&ref=searchresults)
* [Connecting Raspberry Pi devices to the IBM Internet of Things Foundation](https://github.com/ibm-messaging/iot-raspberrypi)
* [IoT Demo: Use the IBM Watson Speech to Text service to make a Raspberry Pi speak the current time and weather](https://github.com/watson-developer-cloud/raspberry-pi-time-weather-demo)
* [Demo de una aplicación de IoT usando la plataforma IBM IoT Foundation, una Raspberry Pi y Python](https://github.com/betabeers/ibm-iot-raspberry-python)
* [Raspberry Pi, IBM IoT Watson, and Node.js Experiments](https://github.com/edm00se/iot-pi)
* [Connect Raspberry Pi to IBM Internet of Things in Bluemix](https://github.com/hansb001/IoTRaspberryPiBluemix)
* [C++0x sample for connecting Raspberry Pi Model B devices to the IBM Internet of Things Cloud 'Quickstart' service.](https://github.com/nweedon/iot-raspberrypi-0x)
* [Coursera Raspberry Pi IoT IBM Bluemix
](https://github.com/juanjordaan/courseraIoT)
* [tsl2561 light sensor on a raspberry pi feeding sensordata to IBM IoT platform written in C](https://github.com/pmvester/tsl2561)
* [A Tutorial how to use a bluetooth device on a Raspberry PI to send proximity data to IBM Watson IoT Platform to let a car switch an appliance on and off](https://github.com/joetriskaide/car-meets-home)
* [MQTT at GitHub](https://github.com/mqtt/mqtt.github.io/wiki)
* [Questions in Internet of Things space](https://developer.ibm.com/answers/smartspace/internet-of-things/)
## Useful NPM Site
* [Installing Node.js and updating npm](https://docs.npmjs.com/getting-started/installing-node)
* [Installing npm packages locally](https://docs.npmjs.com/getting-started/installing-npm-packages-locally)

## Useful Blogs
* [knolleary
knolleary is awesome!](http://knolleary.net/projects/)
    
  < END >  
