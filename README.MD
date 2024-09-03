## Project description

This is a landing page project using Next.js with Typescript, containerized and deployed in AWS ECS. This repository is the deployed version to AWS ECS.

Basically, the final result is the same as the below project:

https://github.com/markwongwkh-code/landing-page2

The only difference is deployment strategy. One is by AWS Amplify. Another one is by AWS ECS.

## Getting Started

To regenerate this project in local environment, download this repository to your machine. Run the below command sequentially:

```bash
# Open terminal. In root folder of repository, create image by running the below command.
docker-compose up
```

Container image will be build and run in port 3000. Visit "http://localhost:3000" in local machine to see the website.

## Disclaimer

This repository is for demo purpose only. All data included is testing data. It has no relation with any person or company.