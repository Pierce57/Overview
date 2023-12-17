# Overview of my Repositories and their Respective Projects (if applicable)

## Repositories (sorted by programming language)

### C++
* ECE 309 - Data Structures and Object-Oriented Programming
  * <b> Monopoly – Board Game Design / Development </b>
    * Implemented a virtual Monopoly Board Game for up to 8 players using C++ in a team of four students. All rules and aspects of the game were simulated, and bot players were programmed to allow for solo play.
    * My role was to design the overall software architecture of the program (data structures, classes, header files, etc.), as well as the Bank and Bot 
      Player classes. Additionally, I developed high level logic for other aspects of the program like main, conducted comprehensive debug/code review sessions of the entire program, and managed/performed program-wide documentation.
* ECE 506 - Architecture of Parallel Computers
  * <b> Project 1: Scheduling in OpenMP Parallel Programming Model </b>
    *  Parallelized a fundamental linear algebra algorithm using OpenMP, a parallel programming model based on the Shared Memory Model.
    *  Compared timing results between multiple datasets using different scheduling policies, chunk sizes, and processor counts.
  * <b> Project 2: Coherence Protocols </b>
    * Created a 4-processor system simulator that implements and compares two different coherence protocol optimizations - Modified MSI and Dragon Protocol.
* ECE 563 - Microprocessor Architecture
  * <b> Project 1: Cache and Memory Hierarchy Simulator </b>
    * Implemented a flexible cache and memory hierarchy simulator and used it to compare the performance, area, and energy of different memory hierarchy configurations, using a subset of the SPEC 2006 benchmark suite, SPEC 2017 benchmark suite, and/or microbenchmarks.
  * <b> Project 2: Branch Predictor Simulator </b>
    * Implemented a branch predictor simulator and used it to evaluate different configurations of branch predictors (e.g. bimodal, gshare, and hybrid).
  * <b> Project 3: Superscalar Pipeline Simulator </b>
    * Implemented a simulator for an out-of-order superscalar processor that fetches and issues N instructions per cycle. Only the dynamic scheduling mechanism was modeled in detail, i.e., perfect caches and perfect branch prediction are assumed.
* ECE 566 - Compiler Optimization and Scheduling
  * <b> Project 1: The Matrix </b>
    * Implemented an LLVM bitcode generator for a simple programming language.
      * Supports floating point and basic matrix operations.
    * Gained experience reading and interpreting a language specification.
    * Gained experience implementing a simple programming language using parser generators: Flex & Bison.
    * Practiced code generation with LLVM and gain experience using the LLVM software infrastructure.
  * <b> Project 2: Common Subexpression Elimination Plus Simple Load/Store Optimization </b>
    * Implemented code that performs Common Subexpression Elimination.
    * Leveraged LLVM to perform simple instruction simplification and dead code elimination.
    * Performed a simple load-store optimization during the CSE traversal to find additional redundancy while preserving the order of memory operations.
  * <b> Project 3: Function Inlining Heuristics </b>
    * Implemented a function inlining heuristic.
    * Designed my own heuristic and reported the results.
### Java / Python / HTML / CSS
* ECE 484 - Senior Design I
  * <b> [Lively Locking Solutions](https://sites.google.com/ncsu.edu/ece-sd-project-pages-fall-23/project-53-lively-locking-solutions?authuser=0) </b>
    * My team of four engineers and I aim to create a system that controls and monitors storage units remotely at an affordable price.
    * Currently, we have divided this effort into six subsystems:
      * Locking System
      * Power
      * Camera System
      * 2FA
      * Management Software
      * Networking / Communications
    * My roles are:
      * Team Leader
      * Management Software Subsystem Lead
        * The Management Software subsystem aims to fill the remote requirement of this project. It encompasses a website that can be used by management (at storage facilities) to remotely monitor and control their storage units.
        * During the Fall 2023 semester, I was able to get a working prototype of this website, using Java, HTML, CSS, Spring MVC, Thymeleaf, and MySQL. Most notably, I was able to implement CRUD features, write a Python script to integrate the Camera System fulfilling the unit physical status requirement, and get a mock “test” unit working. More details on 
          the frontend/backend of this website, as well as its current features, can be found here in this [README](https://drive.google.com/file/d/1-WCKKwhsjLGRxM0DZmKxcpWUT_jx5IHf/view?usp=sharing).
      * Networking / Communications Subsystem Lead
        * The Networking/Communications subsystem aims to connect all of the subsequent subsystems and their devices to each other and the internet.
        * During the Fall 2023 semester, I was able to get a working test environment using a TP-Link TL-SG108PE 8 Port Gigabit PoE Switch. The environment was used to connect and test the Locking System, Camera System, and Management Software subsystems. This allowed me to confirm their functionality and connection to one another. Additionally, this 
          environment was fundamental in the development of the Management Software’s website prototype, as I was able to test and develop the Python script that integrates the Camera System and Management Software subsystems quickly and efficiently using this resource.
### C
* ECE 209 - Computer Systems Programming
  * <b> Project 1: Roots </b>
    * Built a program that computes the n-th root of an integer to a certain number of decimal digits using the sliding-digit algorithm.
  * <b> Project 2: Farkle </b>
    * Built a program that allows multiple users to play a dice game named Farkle.
  * <b> Project 3: Golf </b>
    * Built a program that reads information about a golf tournament and allows a user to view information about the course, the overall scores, and the individual players.
* ECE 306 - Introduction to Embedded Systems
    * <b> RC Car </b>
      * Built a custom RC Car using the TI MSP430 platform that can receive commands over a Wi-Fi connection and traverse a series of obstacle courses.
### VHDL
* ECE 310 - Design of Complex Digital Systems
  * <b> Simple CPU </b>
    * Completed a design involving separate control and datapath with multiple modules.
    * Completed a design that includes most of the elements to be used in the CPU.
### HTML / CSS
* E 115 – Introduction to Computing Environments
  * <b> Personal Website </b>
    * Made a webpage about myself that details who I am and what I hope to do at NC State.
### Java
* AP Computer Science Principles
* ECE 492 - Object-Oriented Application Programming with Java
### Verilog
* ECE 212 - Fundamentals of Logic Design
### MATLAB
* ECE 220 - Analytical Foundations of Electrical and Computer Engineering
* ECE 301 - Linear Systems











