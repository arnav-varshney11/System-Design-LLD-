# Low-Level Design (LLD)

## What is LLD?
Low-Level Design (LLD) is the process of designing the internal logic, classes, methods, and interactions for a software system. It focuses on how individual components are implemented, ensuring the system's requirements are met at a granular level.

## Advantages of LLD
- Provides detailed blueprint for developers
- Improves code maintainability and readability
- Helps identify potential issues early
- Facilitates easier debugging and testing

## Real-life Example
Designing a ride-sharing app:  
LLD would involve defining classes like `User`, `Driver`, `Ride`, their attributes, and how they interact (e.g., how a ride is requested, matched, and completed).

## Example: DSA-only vs. DSA + LLD

**Structuring Differences:**

- **DSA-only:**  
    - Focuses on algorithms and data structures.
    - Lacks emphasis on how components interact.
    - May write code that works but is hard to maintain or scale.

- **DSA + LLD:**  
    - Designs classes, interfaces, and their relationships.
    - Plans interactions and responsibilities before coding.
    - Produces modular, extensible, and maintainable code.

    
 ## Individual A (Knows only DSA) | Individual B (Knows DSA + LLD) 

 1. Alice (RiderApp Developer: Knows only DSA)
  - Can implement algorithms for matching riders and drivers. 
  - Focuses mainly on data structures and algorithms. 
  - May write code that works but is hard to maintain or scale. 
  - Lacks emphasis on how components like `User`, `Driver`, and `Ride` interact. 
  - May struggle with building a robust, real-world ride-sharing application. 

 2. Bob (RiderApp Developer: Knows DSA + LLD)  
  - Can solve problems and design scalable, maintainable systems for RiderApp. 
  - Focuses on system structure, class design, and interactions (e.g., how `User` requests a ride,   how `Driver` is matched). 
  - Produces modular, extensible, and maintainable code. 
  - Plans interactions and responsibilities before coding. <br>

## Difference: LLD vs. DSA

- **DSA (Data Structures & Algorithms):** Focuses on problem-solving, efficiency, and logic.
- **LLD:** Focuses on translating requirements into class diagrams, relationships, and code    structure.


### Point-wise Difference: LLD vs. HLD

- **Level of Detail:**
    - LLD: Focuses on detailed class, method, and logic design.
    - HLD: Focuses on overall system architecture and module division.

- **Audience:**
    - LLD: Used mainly by developers for implementation.
    - HLD: Used by architects and leads for planning.

- **Technology Focus:**
    - LLD: Technology and implementation specific.
    - HLD: Technology agnostic, more abstract.

- **Purpose:**
    - LLD: Guides actual coding and development.
    - HLD: Guides system structure and integration.

- **Artifacts Produced:**
    - LLD: Class diagrams, sequence diagrams, pseudo-code.
    - HLD: Block diagrams, data flow diagrams, architecture diagrams.

## Summary
LLD bridges the gap between high-level architecture and actual code, ensuring that software is well-structured, maintainable, and scalable.

## Conclusion
Mastering LLD is essential for building real-world software systems, as it complements DSA and HLD skills.

## Key Points
- LLD details the internal design of software components.
- It is crucial for maintainability and scalability.
- Complements DSA and HLD in the software development process.



> "Good design is as little design as possible." – Dieter Rams
