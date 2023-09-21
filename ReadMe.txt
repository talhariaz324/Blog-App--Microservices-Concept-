In this we are going to learn skaffold. Earlier we we do some change in our code then we have to build the image again and
do restart the deployment. But how much would it will be easy for us in the development process if we just change the file
and it do all the things at back. This is skaffold.

skaffold is cli tool.

it is also used to shift from one project of k8s to other. As when moving we stop the skaffold so it delete all its pods etc. and we can use the new project of k8s. (Locally we have only 1 cluster)


install: curl -Lo skaffold https://storage.googleapis.com/skaffold/releases/latest/skaffold-linux-amd64 && \
sudo install skaffold /usr/local/bin/


run: skaffold -->gives you some command,, means installed.



all will be live watching. But make sure your express uses nodemon for auto restart onChange and react create app by default restart onChange so no need for it.






