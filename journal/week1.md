# Week 1 — App Containerization

## Required Homework Challenges

### 1. Run the dockerfile CMD as an external script

![Docker External Script Execution](assets/week-1/docker-external-script-execution.png)

### 2. Push and tag a image to DockerHub (they have a free tier)
Initally I tagged the image and tried to push to my dockerhub account it failed with error ```denied: requested access to the resource is denied```
Then i realized that i have to login to dockerhub account from local.

![Docker Repo](assets/week-1/docker-repo.png)

Tagged the image as ``` docker tag hello-world 454598/cloud-bootcamp:first-image```

![Docker Push](assets/week-1/docker%20push.png)

The image pushed to my docker account

![Docker Repo view](assets/week-1/docker-repo-view.png)
