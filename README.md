# data-interview

In this repository, you'll find a Docker Compose file that allows you to run JupyterLab. We have provided you with a notebook called "questions," which contains all the questions we'll ask during the interview. You can use it to prepare for the interview. You can bring it to the interview to have a fallback solution in case you get stuck.

In the `tables` folder, you can find three CSV files that are needed to answer the questions:

- sales.csv
- customers.csv
- marketing.csv

## Requirements

### Docker

Docker is a platform that allows developers to easily create, deploy, and run applications in containers. Containers provide a lightweight, efficient way to package and isolate application code and dependencies, allowing applications to run consistently across different environments.

To install Docker, follow the instructions on [docker.com](https://www.docker.com/). Once installed, make sure that it's running.

## Building & Running the Environment

While in this repository, run

```bash
$ docker compose up
```

In your command line, follow the provided link that looks like this: `http://127.00.1:8888/lab?token=XXXXX`. You should see the JupyterLab workspace in your browser.
