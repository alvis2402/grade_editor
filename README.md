# qub_grade_editor
QUB Grade Editor

Video showing functionality, code, execution: https://www.youtube.com/watch?v=sXR30z9MOBc&feature=youtu.be 

This project was developed on Queen's University student github which is now closed as I graduated and no longer have access to it. All of the code is commented to explain my thought process and what each function does for better understanding. Summary of the application: Every folder is individual docker container build, a front page passes requests to all other containers hosted on kubernetes, which are developed individually on different programming languages and frameworks as this work was done for university and that is how I achieved the maximum available grade on this assignment. Each docker responds with a JSON reply, each service has load balancing, error handling, and unit testing for code coverage.
