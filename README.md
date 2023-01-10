# nginx-otel-instrumentation
We will be instrumenting Nginx using Otel and will see output on AppDynamics and Zipkin UI

Once you checkout the code by

```
git clone https://github.com/mithun100/nginx-otel-instrumentation.git
```
Navigate inside the folder, ensure to put correct value in the otel-collector-config.yaml file, which is marked as XXXX.

You can run the 

```
docker-compose up
```

Once you want to stop it

```
docker-compose down
````

```
docker ps
```

It will show the collector up and running, if everything is running as expected.

Reference:- https://opentelemetry.io/blog/2022/instrument-nginx/ and there are some extra parameters from the AppDynamics.

If you want to just have the OTel without AppDynamics details then checkout the main branch.
