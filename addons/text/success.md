# Your ToolsCloud Environment is in the Cloud!

### Login Information

* **Admin UI**: [${env.url}](${env.url})
* **User**: ${globals.user}
* **Password**: ${globals.password}

### SSH Connection

Don't forget to upload your public key, if you didn't do yet. You can use Jelastic [SSH Gate](https://docs.jelastic.com/ssh-gate) to establish connection to any node within your account.

### Connect the engine to a swarm cluster

```
docker swarm join --token $TOKEN $HOST:$PORT
```
