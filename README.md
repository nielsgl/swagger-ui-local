# swagger-ui-local
Docker container for running local swagger definitions

## Commands

```bash
docker run -p 80:80 -v $(pwd):/app/swagger nielsgl/swagger-ui-local
```

and then you can access the swagger docs [here](http://127.0.0.1)

---

Inspired by: [swagger-ui](https://github.com/schickling/dockerfiles/tree/master/swagger-ui)
