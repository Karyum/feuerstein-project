# Feuerstein Dynamic Assessment (LPAD)

> This repository exists for the sole reason of showing my work on the Feuerstein project details in my CV, since the code is private and the website is quite complex I thought I would introduce some of the work using GIFs

### What is it ?
The LPAD is a comprehensive and adaptable dynamic assessment designed to determine an individual’s cognitive strengths and weaknesses. Its purpose is to pinpoint areas requiring further development to enhance cognitive abilities. By providing insight into an individual’s cognitive profile, LPAD results help direct individual and group FIE studies, making it a valuable tool for classrooms and individuals.



- Teachers and examiners can create classes and initiate cognitive assessments
![Teacher Class Creation](assets/teacher-class-creation2.gif)



- Students log in and are automatically directed to their current examination, resuming from their assigned test
![Raven Test](assets/student-raven.gif)
![Organizer Test](assets/student-organizer.gif)
![Numerical Test](assets/student-numerical.gif)


The examination features 15 different test types, with each test being dynamically customized based on the teacher's assessment goals and the individual student's needs. Students don't necessarily complete all 15 tests, as the system adapts the examination flow accordingly.

Upon completion of the examination, a comprehensive report is automatically generated after analyzing all student responses, with particular emphasis on **incorrect answers**. These incorrect responses provide valuable insights into the student's cognitive processes and thinking patterns.

The generated reports vary significantly based on multiple criteria including the student's age, school context, geographical location, primary language, specific project requirements, learning disabilities, completed test modules, and additional contextual data provided by educators.

[Sample Report](assets/report.pdf)

---

*Note: The LPAD system includes many additional features and capabilities that are difficult to demonstrate through static documentation. This overview provides just a glimpse into the comprehensive functionality of the platform.* 

## Technical Implementation

### My Contribution
I built this comprehensive educational platform from the ground up as a complete system rebuild. The client had an existing legacy system, but I was tasked with creating a modern, scalable solution due to significant technical debt and maintainability issues in the previous implementation.

### Technology Stack

**Frontend Development:**
- **React/Next.js** - Modern React framework for server-side rendering and optimal performance
- **TypeScript** - Type-safe development ensuring code reliability and maintainability  
- **Ant Design** - UI component library for consistent design patterns
- **SASS** - Advanced CSS preprocessing for scalable styling architecture
- **Socket.IO** - Real-time bidirectional communication for live teacher-student interactions

**Backend Development:**
- **Node.js/Express.js** - Scalable server-side JavaScript runtime and web framework
- **TypeScript** - Full-stack type safety and enhanced development experience
- **SQL Database** - Structured data storage for user management, assessments, and results
- **MongoDB** - NoSQL database for flexible document storage and real-time data
- **Puppeteer** - Automated PDF report generation with custom formatting
- **AWS SDK** - Cloud service integration for scalable infrastructure management

**Infrastructure & DevOps:**
- **AWS Cloud Platform** - Comprehensive cloud infrastructure with auto-scaling capabilities
- **Vercel** - Optimized Next.js deployment with global CDN distribution
- **AWS Elastic Beanstalk** - Application deployment and management service
- **AWS CodePipeline** - Automated CI/CD pipeline for seamless deployments
- **Staging Environment** - Dedicated testing environment on AWS for quality assurance



# Feuerstein Instrumental Enrichment (FIE)


### What is it ?
Feuerstein Instrumental Enrichment (FIE) is a cognitive intervention program that helps improve thinking and learning skills. It includes various tasks specifically designed to be done in a classroom, group, or individual setting. FIE focuses on different mental skills and provides a structured approach to problem-solving. By participating in FIE, learners can enhance their understanding and elaboration of information.

The program consists of an extensive collection of worksheets, each bundled into modules designed for specific cognitive development purposes. The materials are adaptable for a wide age range (10-70 years old) and target various cognitive skills - some worksheets focus on enhancing memory, others assess logical reasoning abilities, and many more address different aspects of cognitive function. 

> Pages are changing in the GIFs because there is a second window where the teacher is controlling the currently viewed worksheet

![Points org](assets/points-org.gif)
![Analytical Perception](assets/ap.gif)


The system currently contains approximately 80 worksheets, with functionality to assign homework to students. Teachers can provide real-time intervention through the platform itself, offering guidance to help students answer questions or better understand the worksheet content.

## Technical Implementation

### My Contribution & Team Leadership
The FIE platform was developed as a collaborative effort where I led a team of two developers, working closely with a junior developer who was an alumnus from a coding bootcamp I was facilitating ([Check my LinkedIn for further details](https://www.linkedin.com/in/mario-s-853802aa/)).

**Project Architecture & Setup:**
The FIE system utilized the same technology stack and infrastructure as the LPAD platform, ensuring consistency and maintainability across both applications.

As the senior developer, I took responsibility for:

- **Code Quality & Standards:** Established and enforced industry-standard coding practices
- **Git Workflow Management:** Implemented Git workflows with feature branches, pull request reviews
- **Architecture Guidance:** Designed scalable component structures and database schemas while teaching clean architecture principles
- **Security Implementation:** Ensured proper authentication, authorization, and data validation practices throughout the application

**Collaborative Development Process:**
- **Code Reviews:** Conducted thorough code reviews to maintain quality while providing learning opportunities
- **Pair Programming Sessions:** Regular collaborative coding sessions to tackle complex features and share knowledge