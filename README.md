##Monitor System Resources Using Netdata.
---
Run Command To pull IMAGE

```docker run -d --name=netdata -p 19999:19999 netdata/netdata```

##Access The dashboard

Access at `http://localhost:19999`
---
Sign in on netdata
sign in using email or github.
run command :
```bash
docker exec -it netdata bash
cat /var/lib/netdata/netdata_random_session_id
```
copy key and paste it on netdata.
