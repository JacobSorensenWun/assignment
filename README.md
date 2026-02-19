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



## Interview Questions

We would also like you to consider the following situations and be prepared to discuss how you would handle these situations. You do not need to provide written answers here, just be prepared to discuss.


#### Question 1
A stakeholder from the Marketing team pings our slack channel saying the 'Total Ad Spend' in the dashboard is 20% lower than what they see in the Facebook Ads UI. You built this pipeline using DLT and DBT that supplies the golden layer. Walk us through your communication process from the moment that message arrives. How do you manage the stakeholder’s expectations while you investigate? If the error was caused by a logic mistake you made in a DBT model, how do you communicate that to the team? 
 
#### Question 2
 Every company has a different 'way of working.' You might notice that our current DBT project structure or our GCP scheduling could be more efficient, or perhaps our naming conventions are inconsistent. If you identify an area where our technical standards or workflows could be improved, how do you go about proposing that change to the team? Describe a time you successfully convinced a remote team to change a process or a tool.
 
#### Question 3
 You are implementing an API integration for TikTok. You come across a naming discrepancy between the required fields documentation provided by the product expert vs the api field names. This occurs at 09:30 your time and the product expert wont be on line for 4 hours. What do you do next? 
