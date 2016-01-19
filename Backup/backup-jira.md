#Backing Up JIRA 
This page is under construction and this note will be removed when the document is complete.

JIRA is our corporate issue tracking software. It tracks our job, tasks, development, proposals, or anything else that we need to do. It also captures the history of what we do. If CI Wise has issue tracking software, it's JIRA and it will always be our tracking software of choice. We've been a registered customer with Atlassian for over 10 years.

This page is written to define the operating process of backing up JIRA. The instructions here are high-level in nature, however they are clear and will provide sufficient instruction to the individual assigned this responsibility. Currently, this responsibility is mine. I am the CEO and Principal Consultant for CI Wise Inc. Responsibility may change in the future and this document will be revised as such. And, as the company grows, each critical process will have an assigned individual attached to this process.

##Process
Backing up JIRA consists of backing up the contents of its database and also protecting the filesystem contents that contain any added images, avatars, etc. Atlassian does not store images in the database and therefore, complete restoration of JIRA or any other Atlassian product would require the physical graphic files as well as the textual data captured in the database dump.

##Current Notes and Responsibility 
David is currently responsible for this. It's being done manually on a daily basis. CI Wise is using a PostgreSQL database because this installation did not require a JDBC driver to be found externally and installed for MySQL. It's our assumption that Atlassian prefers PostgreSQL over MySQL. The JIRA installation is being hosted on a laptop now but treated as a production instance. This will change soon. 
