#### NPM

To use the local registry just run the below command.

```sh
    npm set registry http://localhost:4873

```

To remove the registry after the hackathon run this.

```sh
    npm config delete registry http://localhost:4873

```


## Docker

### Windows

### Mac

### Linux

```sh
sudo nano /etc/docker/daemon.json
```

```json
{
  "registry-mirrors": ["http://192.168.1.50:5000"]
}
```

```sh
sudo systemctl restart docker
```
