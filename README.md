# Intro to GCP with Rails

This project is following the GCP with Rails tutorial found [here](https://cloud.google.com/ruby/rails/appengine).  The intention behind starting this project is to get introductory practice with the Google Cloud Platform.

### Challenges
Following this tutorial, I ran into the problem that my deployment was timing out.  To get around this, I configured an extended timeout.  Diving deeper, I hope to find a better solution for this problem, but this works for now.

```
gcloud config set app/cloud_build_timeout 1000
```
