## My name is juliuspeter Outcomer and please file below my submission

## Kubernetes, Docker, Containerisation and Virtualisation

1. Containers and virtual machines are two popular approaches to deploying applications, each with its own advantages and disadvantages. Here are the key characteristics of each:

Advantages of Containers:
Portability: Containers are highly portable and can run consistently across different environments, such as development, testing, and production, minimizing issues related to environment-specific dependencies.
Efficient resource utilization: Since multiple containers can run on a single host, resources are utilized more efficiently, maximizing the usage of the underlying infrastructure.

Disadvantages of Containers:
Performance overhead: Although containers are lightweight, they still introduce some performance overhead compared to running applications directly on the host operating system.
Dependency management: Managing dependencies within containers can be challenging, especially when dealing with complex application stacks and multiple containers interacting with each other.

Advantages of Virtual Machines:

Isolation: Each VM runs on its own virtualized hardware, providing strong isolation from other VMs on the same host, which enhances security and stability.
Flexibility in operating systems: VMs can run different operating systems, allowing more flexibility in choosing the most suitable OS for each application.

Disadvantages of Virtual Machines:

Resource overhead: VMs require more resources (CPU, memory, storage) than containers because each VM runs a separate operating system instance.
Slower startup time: VMs need to boot the entire operating system, which can result in slower startup times compared to containers.

A Docker image is a lightweight, standalone, and executable package that includes everything needed to run a piece of software, including the code, runtime, system tools, libraries, and dependencies. It provides a consistent and reproducible environment for running applications across different systems.

Docker images are created using a declarative file called a Dockerfile, which contains instructions on how to build the image. The process involves the following steps:

Define a Dockerfile: Create a text file named "Dockerfile" (without any extension) in the root directory of your project. The Dockerfile contains a series of instructions that Docker will follow to build the image.
Specify a base image: The Dockerfile starts with specifying a base image, which serves as the foundation for your image. The base image typically includes the operating system and other fundamental components required by your application.
Add dependencies and configure the environment: Use Dockerfile instructions like RUN, COPY, and ADD to install dependencies, copy application code into the image, and configure the runtime environment. For example, you can use RUN to execute commands, COPY to copy files, and ENV to set environment variables.
Define runtime behavior: Use the CMD or ENTRYPOINT instructions to specify the command that should be executed when a container is created from the image. This command typically starts your application or any required services.
Build the image: Open a terminal or command prompt, navigate to the directory containing the Dockerfile, and use the docker build command to build the image. This command reads the Dockerfile, executes the instructions, and creates the image layer by layer.
Tag and optionally push the image: Once the image is built, you can tag it with a name and version using the docker tag command. Additionally, you can push the image to a container registry, such as Docker Hub or a private registry, to make it available for deployment on other systems.

## Linux administration and shell scripting

## CICD, Infrastructure as as Code (IaC), Terraform, Packer and Ansible

1. Idempotence: is any function that can be executed several times without changing the final result beyond its first iteration. Idempotence is a technical word, used in mathematics and computer science, that classifies a function’s behavior.

2. Faster, better product delivery.
   Faster issue resolution and reduced complexity.
   Greater scalability and availability.
   More stable operating environments.
   Better resource utilization.

3. Terraform is a tool designed to help with the provisioning and deprovisioning of cloud infrastructure using an infrastructure as code approach. It is highly specialized for this purpose. On the other hand, Ansible is a more general tool that can be used for automation across various domains. Both Terraform and ansible have strong open-source communities and commercial products that are well supported.

4. Like many other automation solutions, Ansible and Terraform can both define configurations and apply them to various infrastructure targets. However, their approach to configuration management differs. Terraform uses an approach called declarative programming, which tries to preserve the configuration of an IT infrastructure by defining a desired state. Ansible uses a procedural (or imperative) programming approach, which tries to preserve the configuration of an IT infrastructure by defining the steps to reach a desired state.

5. Mutable and immutable infrastructure are two design paradigms used in the field of software development and deployment. Here's a brief comparison and contrast of these two approaches:

Comparison:

- Mutable infrastructure can have evolving state as changes are made to running instances. In contrast, immutable infrastructure is typically designed to be stateless, with persistent data stored separately.
- Mutable infrastructure allows for on-the-fly changes and updates to the system configuration, providing greater flexibility. In contrast, immutable infrastructure requires creating new instances for modifications, which is less flexible.

Contrast:

- Mutable infrastructure focuses on modifying existing instances directly, while immutable infrastructure promotes the creation of new instances with desired configurations.
- Mutable infrastructure employs configuration management tools to update live instances. Immutable infrastructure relies on provisioning new instances with pre-configured images, minimizing the need for configuration management.
  both mutable and immutable infrastructure have their advantages and are used in different contexts. Mutable infrastructure offers flexibility and easier maintenance, while immutable infrastructure provides consistency, reproducibility, and scalability benefits.

6.

- AWS (Amazon Web Services): AWS is a cloud computing platform offering various services, including storage, compute power, and database management. It is recommended for businesses requiring scalable and flexible cloud infrastructure to host their applications and services.

- Google Analytics: Google Analytics is a web analytics tool that provides insights into website traffic, user behavior, and conversions. It is recommended for businesses looking to understand their online audience, track marketing performance, and optimize website experiences.

## System Architecture and Application Design, Cloud Computing (AWS)

1. XXXX

## Site Reliability Engineering (SRE), Troubleshooting, Observability

1. XXXX

## DevOps and Agile Transformation principles and methodology

1. DevOps combines development and operations, emphasizing automation, collaboration, and continuous integration. It improves software delivery and quality through shared responsibility and frequent feedback.

2. Agile transforms organizations by adopting iterative and adaptive practices. It prioritizes customer collaboration, iterative development, and responsiveness to change.

3. Principles: Continuous improvement drives both DevOps and Agile, fostering learning, evolution, and refinement of processes and deliverables.

4. Methodology: DevOps integrates teams, automates workflows, and implements continuous integration and deployment. Agile follows iterative cycles, with practices like daily meetings and prioritized backlogs, to deliver value quickly and adapt to changing needs.

## New commands logs - Enter up to ten new commands you have learnt this week

| Number |                Commands                | What does it do and how might you check its effect         |
| :----- | :------------------------------------: | :--------------------------------------------------------- |
| 1      |               cat TARGET               | Show the content of TARGET                                 |
| 2      |       cp -r "old name/new name/"       | rename a subderictory                                      |
| 3      |                mkdir -p                | Create a new empty directory                               |
| 4      |                   cd                   | Change into a directory                                    |
| 5      |               echo TEXT                | Change into the parent directory                           |
| 6      | rm -rf "name of the derictory or file" | delete                                                     |
| 7      |                 ls -la                 | List all the contents of a folder with info                |
| 8      |               git status               | check the status of you derictory before push it to github |
| 9      |                 clear                  | Clear the terminal window                                  |
| 10     |                 code .                 | lauch vs code .                                            |

## Glossary of the week - Enter new technical words you have learnt this week and their meanings.

| Number |    Word     | Meaning                                                                                                                                                                                                                            |
| :----- | :---------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | Idempotence | is any function that can be executed several times without changing the final result beyond its first iteration. Idempotence is a technical word, used in mathematics and computer science, that classifies a function’s behavior. |
| 2      |   caching   | is the process of storing data in a cache which is a temporary storage area that facilitates faster access to data with the goal of improving system performance.                                                                  |
| 3      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 4      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 5      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 6      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 7      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 8      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 9      |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
| 10     |  XXXXXXXX   | YYYYYYYY                                                                                                                                                                                                                           |
