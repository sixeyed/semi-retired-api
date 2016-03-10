
#Semi-retired API

Even the best APIs reach end-of-life. This sample shows how to gracefully retire an API into a read-only static version of its former self, so you can contiunue to support clients with minimal cost.

The semi-retired API runs as a static NGINX website in a Docker container.

##Try it out

```
docker run -p 8080:8080 sixeyed/semi-retired-api
curl http://localhost:8080/device/12345/news
```

##And read more 

The reasoning behind all this, together with the approach is here: [Semi-retirement for REST APIs with NGINX and Docker](https://blog.sixeyed.com/semi-retirement-for-rest-apis-with-nginx-and-docker).

