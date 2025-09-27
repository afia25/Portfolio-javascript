# Crowdfunding-Platform-with-Integrated-Software-Testing

1. Project Output: Sampradan (A Block-Chain based Crowdfunding Web Platform) will be a website where people can donate and get donations easily.

2. Requirement Analysis: Our platform will provide increased transparency, decentralization, smart contract automation, lower fees, and global reach. These project outputs can help organizations achieve their fundraising goals more effectively and efficiently. There are two types of requirements in our project.
   
Basic Requirement: The basic requirements for our blockchain-based crowdfunding system can include the following:
● User registration: Users should be able to create an account and provide their personal information, including their name, email address, and payment information. 
● Campaign submission: Campaign creators should be able to submit their crowdfunding campaigns and include information such as campaign description, funding goal, duration, and rewards for backers.

● Payment processing: The system should be able to handle payment processing securely using cryptocurrencies or fiat currencies.

● Smart contracts: Smart contracts should be developed to automate the crowdfunding process, ensuring that funds are released only when certain conditions are met.

● Campaign progress tracking: The system should allow campaign creators to track the progress of their crowdfunding campaign, including the amount of funds raised and the percentage of the funding goal achieved.
● Transparency and security: The system should be designed to provide transparency and security for all stakeholders, including project creators, backers, and the platform operator.
● Platform fees: The system should allow the platform operator to charge fees for using the platform.
● Reporting and analytics: The system should provide reporting and analytics functionality to allow campaign creators and the platform operator to track key metrics such as the success rate of crowdfunding campaigns.

Functional Requirements: Functional requirements for a blockchain-based crowdfunding system could include:
● User authentication: The system should allow users to authenticate themselves to access their accounts and perform various actions within the system, such as creating and backing projects.
● Campaign creation: The system should allow project creators to create and submit their crowdfunding projects, including details such as the project name, description, funding goal, duration, and rewards for backers.
● Campaign browsing: The system should allow users to browse and search for campaigns based on various criteria, such as campaign category, funding goal, and duration.
● Smart contract execution: The system should use smart contracts to automatically execute crowdfunding agreements, releasing funds to campaign creators only when specific conditions are met, such as the campaign reaching its funding goal.
● Payment processing: The system should enable secure and transparent payment processing, allowing users to make payments using cryptocurrencies or fiat currencies.
● Feedback and ratings: The system should allow users to provide feedback and ratings on projects and project creators, helping to build trust and transparency within the community.
● User management: The system should allow platform operators to manage user accounts, including adding or removing users, modifying user details, and managing user roles and permissions.
● Reporting and analytics: The system should provide reporting and analytics functionality to allow project creators and platform operators to track key metrics such as the success rate of crowdfunding campaigns, the number of backers, and the amount of funds raised.

3. Methodology: MVC design pattern is a software architecture pattern that separates an application into three interconnected components: the model, the view, and the controller.

    Model: The model represents the data and business logic of your application. It manages the interaction with the blockchain and handles tasks such as project creation, donation management, and transaction processing. The model includes:
    Campaign Model: Manages the data and operations related to crowdfunding campaigns. It handles tasks such as creating new campaigns, updating campaign information, and retrieving campaign details.
    Donation Model: Handles the donation-related operations, including accepting donations, managing donor information, and tracking the total amount raised for each project.
    Transaction Model: Handles the processing transactions, verifying donations, and updating the ledger.

    View: The view is responsible for presenting the data to the users and handling user interactions. In your case, the view will include various web pages and interfaces that allow users to browse projects, make donations, and view project updates. The view includes:
    ProjectListingView: Displays a list of available projects, including their titles, descriptions, and funding progress. It allows users to browse through the projects and select one for donation.
    DonationView: Provides a form or interface for users to enter donation details, such as the amount they want to contribute and the payment method they prefer.
    ProjectDetailsView: Displays detailed information about a selected project, including updates from the project initiator, transaction history, and progress towards the funding goal.

    Controller: The controller acts as an intermediary between the model and the view. It handles user input, updates the model accordingly, and ensures the appropriate view is displayed. The controller includes:
    ProjectController: Manages the flow of information and actions related to projects. It handles tasks such as creating new projects, updating project information, and retrieving project details to display on the views.
    DonationController: Handles user interactions related to donations, including accepting donation details from the view, updating the donation model, and processing the transaction using the transaction model.
    ViewController: Controls the navigation between different views based on user actions, such as selecting a project, making a donation, or viewing project details.

