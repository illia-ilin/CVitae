# CVitae

Welcome to CVitae, a service designed to assist Ukrainians in Ireland in effortlessly crafting professional Curriculum Vitaes (CVs) for unqualified job positions in Ireland. Its mission is to simplify the process of CV creation, making it straightforward and accessible to everyone.

## Overview

The CVitae service is an application designed with microservices architecture. It takes user input, processes the data through a series of services, and generates a well-structured, professional CV in DOCX and PDF formats.

## Features

- User-friendly interface for data input.
- CV content generation with the assistance of AI (ChatGPT API).
- Notification system to inform users about the status of their CV creation.
- Downloadable CV in DOCX and PDF formats.

## Architecture

CVitae consists of several interconnected microservices:

- **Request Handler Service**: Accepts and validates user input.
- **CV Generator Service**: Uses ChatGPT API to generate professional CV content based on user input.
- **Document Generator Service**: Converts the generated content into DOCX and PDF formats.
- **Notification Service**: Notifies users about the completion of CV generation and provides download links.

These services are orchestrated using Kubernetes and communicate with each other using a message broker.

## Technologies

The project will use a variety of technologies, including Python, JavaScript, FastAPI, RabbitMQ, MongoDB, Docker, Kubernetes, and more.
