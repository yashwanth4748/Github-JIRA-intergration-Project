**Automate Jira Creation on GitHub event using Python**

Merge GitHub and JIRA effortlessly! No more scattered tasks or wasted time. Streamline your workflow, bridge the gap, and boost team collaboration!"


**How my project works:**
This project aims to streamline the collaboration process between GitHub and JIRA by creating a seamless integration between the two platforms using API's and Webhooks.

Whenever a user commits the code , a webhook is triggered and sends all the information about the change in JSON format to API(Python application which is created by us and converted to API using Flask) and this API makes a Post request to Jira.
