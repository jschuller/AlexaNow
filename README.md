Welcome to the AWS CodeStar sample Alexa Skill
==============================================

This sample code helps get you started with a simple skill built with the
Amazon Alexa Skills Kit and deployed by AWS CloudFormation to AWS Lambda.
This skill enables you to create a fact skill using facts about space. 

https://github.com/alexa/skill-sample-nodejs-fact

What's Here
-----------

This sample includes:

* README.md - this file
* buildspec.yml - This YAML file is used by AWS CodeBuild to create an artifact
  that can be used to deploy to AWS Lambda through CloudFormation.
* index.js - This file contains the AWS Lambda code used to interact with Alexa.
* package.json - This file is used by NPM to package your Alexa skill.
* template.yml - This YAML file is used by AWS CloudFormation to update AWS Lambda
  and manage any additional AWS resources.

Getting Started
---------------

To work on the sample code, you'll need to clone your project's repository to your
local computer. If you haven't, do that first. You can find instructions in the
AWS CodeStar user guide.

Once you've created your project in AWS CodeStar, go to the Amazon Alexa Portal
and set up your skill to view it in action. Follow the tutorial provided on GitHub:

https://github.com/alexa/skill-sample-nodejs-fact

Since AWS CodeStar will create your AWS Lambda on your behalf, you can skip Step
2 of the tutorial. In Step 3, you can use the Project view in AWS CodeStar to
easily get the ARN of your AWS Lambda. Look for AWS Lambda under Type in the
Project Resources table.


What Do I Do Next?
------------------

Once you've tested your AWS Lambda function from the Amazon Developer Portal, we suggest
making a small change to index.js so you can see how changes pushed to your repository are
automatically picked up by your project pipeline and deployed to AWS Lambda. Once you've
seen how that works, start developing your own code, and have fun!

Learn more about AWS CodeStar by reading the user guide. Ask questions or make
suggestions on our forum.

User Guide: http://docs.aws.amazon.com/codestar/latest/userguide/welcome.html

Forum: https://forums.aws.amazon.com/forum.jspa?forumID=248