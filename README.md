# overseerr

Using continuous integration with `Dockerfile` with cloud build times out. 


Navigate to the container registry in the Google cloud console and open cloud shell access to pull the portainer community editions from the docker. Lastly, push the portainer image to the container registry using the following commands.

```
docker pull sctx/overseerr
docker tag sctx/overseerr gcr.io/sinuk-343220/overseerr
docker push gcr.io/sinuk-343220/overseerr
```


^ Succesfully build and uploaded
Set port to 5055 and set Execution environment to `second gen`


But I get this error:

`A The /app/config volume mount was not configured properly. All data will be cleared when the container is stopped
or restarted.`
