# hello-slim-jenkins-x

A simple example of slim framework running in kuberntes with jenkins-x
  
Watch pipeline activity via:  

    jx get activity -f hello-slim-jenkins-x -w

Browse the pipeline log via:

    jx get build logs consultorprofissional/hello-slim-jenkins-x/master

You can list the pipelines via: 

    jx get pipelines

When the pipeline is complete:

    jx get applications

To promotion to production environment run:

    jx promote --app hello-slim-jenkins-x --version v0.0.3 --env production

