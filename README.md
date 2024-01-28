# AI TEACHER

Welcome to AI Teacher - your comprehensive tool for preparing for IELTS exams and learning English effectively.

## Project Overview

This project aims to assist you in various ways:

### Dictionary Feature:

Utilize our dictionary for meanings, grammatical structures, and examples of usage.

![Dictionary](https://github.com/mirafzal114/AiTeacher/assets/136591233/11a05fa6-2e21-46b5-9c24-87072f66b3f7)

### Essay Checking:

Submit your essays for review and receive an approximate IELTS score. Get detailed feedback highlighting your mistakes.

![Essay Checking](https://github.com/mirafzal114/AiTeacher/assets/136591233/baead5cd-de53-4b40-88e7-cfe9fdf54576)

### Sample Essay Writing:

Receive professionally written sample essays for your chosen topics.

### Help with Ideas:

Submit your topic for review and receive more ideas. Get more information about your topic.

![Help with Ideas](https://github.com/mirafzal114/AiTeacher/assets/136591233/960fc123-776f-451c-b96a-a8b10ec25a29)

![More Ideas](https://github.com/mirafzal114/AiTeacher/assets/136591233/be71df4c-bd13-4579-8a78-a899c8b0cf86)

### Additional Functions:

Explore more functions that are very useful for you.

![Additional Functions](https://github.com/mirafzal114/AiTeacher/assets/136591233/a70dad47-4fb3-442a-9373-9ec3e4cfa78c)

### Provide Feedback:

You can write to us and share your feedback.

![Provide Feedback](https://github.com/mirafzal114/AiTeacher/assets/136591233/3959e6aa-59e1-479a-b825-814706ca83bf)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/mirafzal114/AiTeacher.git
  


## Project using Docker
### Now if you have Docker, see the project to use it with.

This project uses Docker to manage its environment. To run it locally, follow these steps:

### Steps to start the project

### Install Docker

1. Make sure you have Docker installed on your computer.
2. If Docker is not installed, you can download it [from here](https://docs.docker.com/get-docker/) and install it according to the instructions for your operating system.

### Start the project
### We have already entered the repositories with `pipenv` before, now we will continue with the next one, but you first enter your `Docker Desktop` application if you do not have `Linux` of course:
1. Create a Docker image by running the command: 
    ```
    $ docker build -t aiteacher .
    ```
2. Once the image has been successfully created, start the container: 
    ```
    $ docker run -p 1212:8000 aiteacher
    ```
3. Check ``Dockerfile`` if you do not have an image download from ``Docker Hub``:
    ````bash
    $ docker pull python:3.11-alpine
    ````

Your project should now be available in your browser at `https://localhost:1212/posts`. - Here `posts/` means this from application Django.

5. Home Page:
    ```
    https://localhost:1212/
    ```
