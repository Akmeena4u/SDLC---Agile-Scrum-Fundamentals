
![image](https://github.com/Akmeena4u/SDLC-Agile-Scrum-Fundamentals/assets/93425334/1acfa24a-7a5e-411f-833c-80efe0c221b7)


1. Team Structure:
   - 9 Developers
   - Scrum Master
   - Project Manager
   - 2 UX/UI Designers
   - Client(s)

2. Development Workflow:
   a. Requirements Gathering:
      - Clients provide feature requests and requirements.
   b. Development:
      - Developers work on features in feature branches.
      - Pair programming, ensemble programming, or mob programming may be used.
   c. Code Review:
      - Pull requests are made for code review by 1-2 developers.
      - Feedback and corrections are incorporated.
   d. Merge to Main/Branch:
      - Approved features are merged into main or a dev branch.
   e. Automated Testing and Deployment:
      - CI/CD pipeline (e.g., GitHub Actions) triggers build, test, and deployment.
   f. Dev Environment:
      - AWS Dev environment is deployed for testing and integration.
   g. Staging Environment:
      - Staging environment with pre-prod data is deployed for user testing and load testing.
   h. Production Deployment:
      - Approved features are merged to a higher-tier environment (e.g., test, QA, staging).
      - Automated deployment to production environment.
   i. Multi-Region Deployment (if required):
      - Active-passive or active-active setup with data replication for resilience.

3. Bug Handling:
   - Users report bugs.
   - Bug tracking system (e.g., Jira) is used to log and prioritize bugs.
   - Developers debug and fix bugs in feature branches.
   - Code review and testing ensure bug fixes are integrated correctly.
   - Automated testing helps catch regression bugs.
   - Continuous monitoring and alerting in production for real-time issue detection.


