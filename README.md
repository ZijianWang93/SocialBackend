README
==========
This is the back end code for Social Network with events posting and searching functions. Source code of front end is stored in
```
https://github.com/ZijianWang93/Social
```

Demo Requirements
---------
1. The back end was deployed to GAE. And the project is active now.

Possible Issues
---------
1. The search function is supported by ElasticSearch. The server for ElasticSearch is active now. If the server is terminated, a new server with ElasticSearch is needed for online test and the link in main.go below this comment should be updated:
```
  // update if necessary
```

2. The function of BigTable is terminated due to the high cost, code related to this part is commented in file.
