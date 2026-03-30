## Book My Show Clone

Pages: 
    >> Home.Page.jsx 
    >> Movie.Page.jsx 
    >> Play.Page.jsx

HOC(Layouts): 
    >> Default.Hoc.jsx => Home.Page.jsx, Play.Page.jsx 
    >> Movie.Hoc.jsx => Movie.Page.jsx

Components: 
    >> Cast                    Cast.Component.jsx 

    >> Enternemaintent         EnternainmentCard.Component.jsx 
    
    >> HeroCarousel            HeroCarousel.Component.jsx 
                               Arrows.Components.jsx (Configuration File) 

    >> MovieHero               MovieHero.Component.jsx
                               MovieInfo.Component.jsx 
    
    >> Navbar                  Navbar.Component.jsx
                               MovieNavbar.Component.jsx 
    
    >> PaymentModal           Payment.Component.jsx
    
    >> PlayFilters            Filters.Component.jsx 
    
    >> Poster                 Poster.Component.jsx 
    
    >> PosterSlider           PosterSlider.Component.jsx

Note: install tailwind css



## Devops
Dev --> Development team


OPs --> Operations team


🚀 What is DevOps?

DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to shorten the development lifecycle and deliver high-quality software continuously.

It emphasizes:

Collaboration between teams
Automation of processes
Continuous monitoring and feedback

🎯 Goals of DevOps
Faster software delivery
Improved collaboration between teams
Higher deployment success rate
Reduced failure and recovery time
Continuous improvement through feedback

🔄 DevOps Lifecycle
DevOps follows an iterative lifecycle:

Plan – Define requirements and workflows
Develop – Write and manage code
Build – Compile and package the application
Test – Perform automated testing
Release – Prepare for deployment
Deploy – Push to production environments
Operate – Maintain and manage infrastructure
Monitor – Track performance and issues

⚙️ Key Principles of DevOps
1. Collaboration & Communication
Break down silos between development and operations teams
Encourage shared responsibility
2. Automation
Automate repetitive tasks like testing, deployment, and infrastructure provisioning
3. Continuous Integration (CI)
Frequently merge code changes into a shared repository
Automatically test each integration
4. Continuous Delivery / Deployment (CD)
Ensure code is always in a deployable state
Automate release pipelines
5. Infrastructure as Code (IaC)
Manage infrastructure using code instead of manual processes
Enables reproducibility and version control
6. Monitoring & Logging
Continuously track application performance
Use logs to detect and debug issues quickly

🧱 DevOps Toolchain (Conceptual Categories)
Version Control → Git-based systems
CI/CD Tools → Automate build and deployment
Containerization → Lightweight application packaging
Orchestration → Manage containers at scale
Configuration Management → Automate environment setup
Monitoring Tools → Track system health and performance
📦 Benefits of DevOps
🚀 Faster time to market
🔁 Continuous and reliable releases
🛠️ Improved system stability
🤝 Better team collaboration
📊 Enhanced monitoring and feedback
⚠️ Challenges in DevOps
Cultural resistance to change
Learning curve for tools and automation
Security concerns (DevSecOps needed)
Managing complex pipelines
🔐 DevSecOps (Extended Concept)

DevSecOps integrates security practices into the DevOps pipeline:

Security testing at every stage
Automated vulnerability scanning
Secure coding practices
🧠 Best Practices
Use version control for everything
Automate testing and deployments
Implement small, frequent releases
Monitor continuously and act on feedback
Maintain proper documentation
📌 Summary

DevOps is not just a toolset but a culture and mindset that promotes collaboration, automation, and continuous delivery to build reliable and scalable software systems.

## ***********************************
 # 🚀 DevOps Overview

This project follows **DevOps principles** to ensure fast, reliable, and scalable software delivery by integrating development and operations workflows.

---

## ⚙️ DevOps Toolchain Used

### 🧩 Version Control

* **Git**

  * Tracks changes in source code
  * Enables collaboration through branching and merging

* **GitHub**

  * Hosts repositories in the cloud
  * Supports pull requests, issues, and collaboration

---

### 🔄 Continuous Integration / Continuous Deployment (CI/CD)

* **GitHub Actions**

  * Automates build, test, and deployment pipelines
  * Runs workflows on every push or pull request
  * Helps catch bugs early through automated testing

---

### 📦 Containerization

* **Docker**

  * Packages the application with all dependencies
  * Ensures consistency across development and production
  * Lightweight and portable

---

### ☸️ Container Orchestration

* **Kubernetes**

  * Manages and scales containerized applications
  * Handles load balancing, deployment, and recovery
  * Ensures high availability

---

### 🛠️ Configuration & Infrastructure

* **Terraform**

  * Defines infrastructure using code
  * Automates provisioning of cloud resources

* **Ansible**

  * Automates server setup and configuration
  * Ensures consistent environments

---

### 📊 Monitoring & Logging

* **Prometheus**

  * Collects real-time metrics from systems

* **Grafana**

  * Displays metrics using dashboards
  * Helps in performance analysis

---

## 🔄 DevOps Workflow in This Project

1. **Code Development**

   * Developers write code and push to GitHub

2. **Continuous Integration**

   * GitHub Actions automatically:

     * Builds the project
     * Runs tests

3. **Containerization**

   * Docker creates a container image

4. **Deployment**

   * Application is deployed using Kubernetes

5. **Monitoring**

   * Prometheus collects metrics
   * Grafana visualizes performance

---

## 🎯 Key DevOps Practices Followed

* ✔️ Continuous Integration & Deployment (CI/CD)
* ✔️ Infrastructure as Code (IaC)
* ✔️ Automated Testing
* ✔️ Containerized Applications
* ✔️ Continuous Monitoring

---

## 📈 Benefits for This Project

* 🚀 Faster and automated deployments
* 🔁 Reliable and repeatable builds
* 📦 Consistent environments across all stages
* 📊 Real-time monitoring and insights
* 🛡️ Improved scalability and fault tolerance

---

## 🧠 Summary

By integrating tools like GitHub Actions, Docker, and Kubernetes, this project achieves a **fully automated DevOps pipeline**, enabling efficient development, testing, deployment, and monitoring.

## *****************************************************

Devops and CI/CD (Docker and Kubernetes)

Dev----------------------------------------------------------> Ops
Write code + Share code--------------------------------------> Testing + Scaling + Bug Testing

Developer team ---> Operation Team ---> Testing Team

Complexity of appln more --> Then time reqd. to build appln will be more

Scenario:
    Team of 3 members
    >> All have different OS (Mac, Windows, Linux)
    
    Person-1                    Person-2                    Person-3
    (Windows)                   (Mac)                       (Linux)
    Packages                    

It works on my machine, but i dont know why its not working on your machine


BookMyShow Appln:
RAM: 4GB
ROM: 1TB
GPU: 2GB

to overcome this issue
## Virtualization
(I would be able to run virtual OS on my local OS)
Local OS in case of Person-2 => Mac
Virtualization:
Virtual OS => Windows

// We can run as many applications as we want, on as many virtual os 


Note: When we are making an appln, we are making it on the RAM 


Bsic Architecture:
Windows (RAM, ROM, GPU) || Virtual OS
---------------------------------------
OS                || Local OS




Adv Architecture:
Windows Virtual OS                          Unix Virtual OS
4gb, 500gb, 1gb                             4gb, 500gb, 1gb            || Internal resource sharing


Base/Local OS
8gb, 1tb, 2gb

// How to transfer resources from one virtual os to another ??

WE use Docker

## Containerisation (Docker)



Windows  Virtual OS(2Gb, 250gb)                       Unix Virtualisation OS ( 2gb, 250gb)
                            Docker Engine (4Gb, 500gb)
Base Local OS (8gb, 1tb)


// Book my show appln (To be run on both windows and unix(eg.)) (3gb)


Windows  Virtual OS(2Gb, 250gb)                       Unix Virtualisation OS ( 2gb, 250gb)
                            Docker Engine (4Gb, 500gb)
Base Local OS (8gb, 1tb)



// Docker >> EC2 Instance >> Image and Container
(In detail)


Kubernetes (Orchestra)   (In detail)
>> Nodes  >>
            >> Master Node(Person holding stick in orchestra | Lead)
            >> Child node(Group of people who will be following the lead guidance)

 
NGINX (Light weight servers)


AWS >> EC2 (Virtual Machines) (in detail)

********************************************************

Docker
        >> Image
        >> Containers

Image(Parent)
Containers(Child)  || Server

(Parent can have n number of children)
(An image can have multiple servers)


Client-Server Architecture

////////////////////////////////////////////////

Kubernetes
    >> Docker Daemon ---> Server (Initialization)
    >> Docker Client ---> Client
    >> Docker Swarm ---> Master or Main node | Configuration


    >> Master Node
    >> Child Node 
            >> POD (Container)
            >> Development (Where it will keep a close eye/ monitor the POD) 



Example: I want to run a server in the Docker with 3 container(i.e 3 servers)

Docker- doesn't have internal development
    >> Image(Master)
        >> Cont 1 (child)
        >> Cont 2 (child)
        >> Cont 3 (child)

Kubernetes- has internal development
    >> Master Node    
        >> Child Node | POD-1
        >> Child Node | POD-2
        >> Child Node | POD-3


Master Node (manager)
        Child Node-1(emplyee)        Child Node-2(emp)            Child Node-3(emp)        Development (Team lead)

Develoment: Analyze and maintain all the PODs/Child nodes/Servers/ Containers

Docker > Kubernetes

*********************************************************

AWS (AMAZON WEB SERVICES)
    >> Service: EC2 (Virtual Machine) => Unix

    Base OS >> Windows

    Client 
                                Kubernetes
    Server

Serv1 (1000 requests/hr) => 200-300 similar reqs
Proxy Serv1

Client sends req -> Proxy Serv -> Serv1


NGINX (Light Weight Server)
        >> Reverse Proxy
        >> Load Balancing



*************************************************

## Resume worded.com

## Canva

## Take letter of recommendations from linkedin/email, other people etc. and add in your resume

## Job Platforms
>> LinkedIn
>> Naukri.com
>> Indeed
>> CutShort**
>> GeekTrust
>> AngelList
>> Monster Jobs
>> Internshala

********************************************************

## What next after Web Dev ?
>> **Next.js and Vue.j 
>> Three.js (for game development)
>> **Electron (Windows based application)
>> Java servlet
>> **React Native (app development)
>> GSAP or Framer Motion (Animations)
>> **Scaling and Devops | Sprint Review
>> **Testing for React or JS and Advanced Performance (basics)
>> DSA**


Technical Round For Coding Questions ?
1) Explain the Logic
2) Write the logic/code in Brute-force approach (Base level) approach
3) Later Optimise the code 
 
## Different Positions
1) Software Engineer
2) Software Developer
3) Web Full Stack Developer
4) Frontend dev
5) Backend dev
6) React js dev
7) Angular js dev
8) NodeJs dev
9) DBA (Data Base Administrator)
10) Automated Tester
11) Manual tester
12) UI/UX dev
13) Architect


*******************************************************
A) 
1) yt tutorials           2) projects-hackt,code contests,webinars etc.-resume,github,linkedIn        3) open source + freelance      
(For both web dev + ai + ml)

B) DSA

C) prompt engineering/gen and agentic ai (n8n)/ ai tools & chatgpt expert

D) aptitude+logical reasoning+ gd+ gk etc. ock tests/ computer netwroking + os + dbms + s/w engineering concepts etc.
********************************************************
## Github
>> Github profile readme generator

## Resume and LinkedIn profile
>> resumeworded.com
>> Canva- For resume template

## Sections of Resume
>> Name
>> Designation (Full stack intern at Devtown | Student | Fresher)
>> Experience(not intern experience) OR  Internship
>> Contact Details (Email, Phone No., LinkedIn)
>> Skills
>> Education Qualifications
>> Projects (github url)
>> Achievements (Any cultural actibities, sports, extra curricular, medals)

Experience/ Internship:
1) Full stack intern (MM/YYYY - MM/YYYY) - Devtown
Summary (I worked here as a Full stack intern for so & so period where i explored the full stack web dev with so & so technologies).
> Book My Show Clone (1-2 lines description)

> Project 2 (1-2 lines description)


2) Tester Intern - wipro



