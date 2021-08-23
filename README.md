# CS305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a company that is wanting to apply up-to-date standards for its software security. Their software is a RESTful web application that will handle the customization of individual financial plans. They are asking for an evaluation of the software as well as a mitigation plan.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I believe that the dependency check on the software was handled successfully. I was able to initiate the dependency check, highlight the vulnerabilities, and give good recommendations for mitigations. Secure code is important because we need to protect customers and stakeholders from damages. Unsecure code can lead to data leaks, loss in revenue, and loss in business.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most challenging aspect of the vulnerability assessment was manual reviews. I am inexperienced with reviewing software and will miss one or two vulnerabilities. In the Artemis Financial Vulnerability Assessment Report, I managed to miss a vulnerability in my manual review.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

When increasing layers of security, I first determined what would be appropriate for the task at hand. If there is not a need for cryptography, then implementation of it will be wasteful. I would then use the Areas of Security flow chart to determine some different layers. An example would be to start with quality code and then add input and data validation.

How did you ensure the code and software application was functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure that there was secure and functional code, I started with a manual review. I moved on to a dependency check that would test vulnerabilities. Next, I would run the software and perform a dynamic test. I would perform these same steps after every refactor to ensure that new vulnerabilities were not added.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The Areas of Security flowchart and dependency check were important tools that I will continue to use in the future. The Areas of Security flowchart outlines important areas that are within security. These include Code quality, Code Error, Cryptography, and Input Validation. A dependency check is a tool that checks the dependencies for vulnerabilities with the National Vulnerability Database.

Employers sometimes ask for examples of work that you have completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

This assignment highlights my ability to be detailed oriented and organized. In my assessment, I first started with an explanation of the client’s needs. This explanation details the different goals that the client has and how security will play a part in these goals. I then went on to identify areas of security that are relevant to the project at hand with explanations of why I believe these areas are important. Next, I had bullet points for both the static and manual reviews listing different vulnerabilities that were within the project. I went through and explained how these vulnerabilities affected or would affect the software. Finally, I made a step-by-step mitigation plan that went through the vulnerabilities and areas of security that needed to be addressed.
