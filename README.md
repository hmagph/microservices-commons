# microservices-commons


- add dockerfiles
- build image jobs
- one appname (online-store) and derived microservices names
- internal routing between microservices, not using external app routes
- one external service to ui
- figure how to do unit tests ?
- figure how to do global functional tests ?


CI: build/unit tests-->build image-->deploy single chart to dev-->func test per microservice-->publish image into chart
CD: staging gate-->deploy solution chart to staging-->integration testing-->prod gate-->deploy to prod