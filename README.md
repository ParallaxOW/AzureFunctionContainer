### Azure Function Container 

this an example Azure Function running in a container. I followed the documentation on MS Docs. 

- [Creating Azure Functions on Linux using a custom container](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-function-linux-custom-image?tabs=bash%2Cportal&pivots=programming-language-csharp){:target="_blank"}

This project also contains the necessary manifest files to deploy to a Kubernetes cluster.  I tested this using the cluster 
installed with Docker Desktop.  

After building the image, I pushed it to Docker Hub: 

- [rlangel/azfuncimage on hub.docker.com](https://hub.docker.com/repository/docker/rlangel/azfuncimage){:target="_blank"}



