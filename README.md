Ravelin Code Test For DevOps
============================

## Intructions
- Work through the questions, in order.
- Please do not spend more than 40 mins on any one problem.
- Spend a maximum of 3 hours on the test.
- Once you have completed the test please submit a readme. Ensure to include the IP address of the server and a readme of the things you tried for each question, even if you were unable to solve the problem.

## Setup
* Provider your GCP email address to Ravelin
* Check you have access to the image
* `gcloud compute images list --project ravelin-code-test`
* Create a new image
```
create MY-INSTANCE --project MY-PROJECT --image ravelin-code-test-image --image-project ravelin-code-test --zone us-east1-a --machine-type f1-micro
```

## Problems
1. Nginx has been configured by a developer; however, it seems to be broken. Please ssh into the box and fix the issue. It is suppose to be listerning to https://XX.XX.XX.XX

2. The application is failing to connect to api.ravelin.com. e.g. `curl api.ravelin.com` but it seems to be working from the developers local code and machine. Please ssh into the box and has a look and fix.

3. This particular server seems to have higer CPU utilisation and if effecting performance. It can't be the application as it is running ok on other servers. Please fix.

4. A developer is working remotely from Tuvalu; however, is unable to gain SSH access. Please can you find the problem and fix it for them.

5. Similarly to the problem connecting to api.ravelin.com, the application cannot connect to `https://api.github.com/`. Please see if you can fix this.
