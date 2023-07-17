### ARG 

ARG is usefull for passing the variables to image while creating.

### ARG and ENV
we can use both ENV and ARG in Dockerfile for best results.

1.create one ENV variable and assign the value to ARG
2.Then we can access the ARG values theough ENV  in both image and container.