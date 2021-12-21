# DataStage-API-Tutorials
# NextGen DataStage - Authenticating with the Python API

With the release of Next Generation DataStage, we've released a brand new set of APIs that allow users to interact with their DataStage projects on Cloud Pak for Data using their choice of Python, Java, Node, and Curl. From my background in Montessori education, I've always been a huge fan of interactive learning with tools like Jupyter Notebooks. Therefore, the following tutorial series will be written in Python.

So, great. There's an open API and SDK. But why would you use it when there is a beautiful web UI?

The API offers the ability to authenticate programmatically, enabling functionality for a few key use cases: Manipulating flows, manipulating sub flows, and running or scheduling jobs. Large-scale enterprise DataStage users might have dozens of jobs, each with dozens of associated jobs. When total job count grows into the thousands, it can become difficult to manage your DataStage portfolio using the UI. Therefore, the API offers developers the flexibility to bulk-edit flows, sub flows, and jobs. When you consider all of the other functionality a language like Python can provide, you can see how one would be able to write code for bulk edits, custom job schedulers using date & time, and much more.

Let's get started: Here's step 0!
- Clone this repo
- Open the notebook, and follow the steps I've provided

What should you expect from this tutorial?
- You'll authenticate with DataStage using IBM Cloud
- You'll use the DataStage Python client library to connect to your instance and list your Project's flows

If you've never used Jupyter Notebooks before, check out this great resource on getting started: . If you would like to explore some of the DataStage APIs, visit this link from ibm cloud.

Let us know what you think - we want to hear your feedback on what we can do better - so reach out to us on our Community Forum. To find out more about DataStage on Cloud Pak for Data, reach out to your IBM team.

Jupyter notebooks: https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html

DataStage APIs: https://dataplatform.cloud.ibm.com/data_intg/v3/ds_apidoc/api/explorer/

Community Forum: https://community.ibm.com/community/user/dataops/communities/community-home?CommunityKey=3bfc9f2f-4a5e-470a-9295-4b7cc90c9518

