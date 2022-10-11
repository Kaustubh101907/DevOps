## Day 01 (8-10-2022)
- Devops is a cultural practice  in an organisation by development team to use each other's tool, to smooth out the process of software delivery.

- Plan -> Code -> Build -> Test -> Release -> Deploy -> Operate -> Monitor

- Operations team uses a lot of dev tools.

- If you want to implement DevOps in any organisation, we need to learn:
    -> Core Values
    -> Core Ideas
    -> Methods
    -> Practices
    -> Tools

- Why should you learn DevOps:
    -> DevOps is 50% faster
    -> Less failure
    -> Better recovery time

- Team thinks its a complete process (Frontend, Backend, QA, DB Admins, Network Admins)

- DevOps CAMS
    -> C = Culture
    -> A = Automation
    -> M = Measurement
    -> S = Sharing
    
        1. Culture -> Talk to other people.
            -> People over Process over Tools.

        2. Automation -> not just Chef or Puppet or Pulumi or Terraform.
            -> Thousands of servers are impossible to manage, but the question is do you really need thousands of servers?
            -> How much do you automate?
            -> Should you automate?

            We should only switch on to another tool if and only if it is needed. We should not automate because some other person is using some other tech.

        3. Measurement -> measure to improve.
            -> It is not about infrastructure management, business measure, client activity and other pointers.
            -> Recovery time and cycle time are obvious but its important to measure and incentivise it.

        4. Sharing -> share your goals.
            -> Share responsibility, share ownership.
            -> There shall be no escape goat.
            -> Feedback loop is important.

- There are three ways to implement DevOps in your Organisation:
    1. Flow thinking -> Development team talks to the operations team.
    (not recommended)
    image.png

    2. Amplify feedback -> Development and operations team talk to each other.
    (usually used)
    image.png

    3. Experiment and Learn -> Development and operations team talk to each other using many different tools everytime.
    (risky but you get to learn many tools)
    image.png

- Analysis ∝ Paralysis
    Analysis is good but sometimes trying only gives answers. What suits for others might now suit your organisation. Don't hesitate to experiment in work flows.

- Big overview to remember:
    -> People over process over tools.
    -> Continious Delivery.
    -> Lean management.
    -> Infrastructure as code.

- IT Divide:
    -> Developers want to deliver features fast and deploy them quickly.
    -> Operations team wants system to be stable and uptime is most important to them.

- DevOps Jargons:
    1. Provisioning -> Server is ready with OS, software and networking.
    
    2. Deployment -> Adding and updating softwares on the server.

    3. Orchestration -> Coordinated operations on multiple systems.

    4. Configuration management -> Managing server configuration via files such as ram, space, dependency software etc.

    5. Imperative (procedural) -> Commands to produce desired state.

    6. Declarative (procedural) -> Desired state is defined and tools will achieve it.

    7. Idempotent -> repeat execution and same result.

    8. Blue-Green Deployment -> Identical deployment, used as switch.
        -> suppose you have two servers, Server A will host the application while Server B will recieve updates, when Server B is updated then Server B is now the main server and Server A will now be recieving the next updates.

    9. Continuous Integration -> Build and unit test at every checkin.

    10. Continuous Delivery -> Deploy on prouction live enviroment at every checkin.

    11. Continuous Deployment -> After unit testing, deploy changes to production in small batches.