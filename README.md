```heat stack-create -f stacksallthewaydown.yaml -P discovery_token_url=`curl -q https://discovery.etcd.io/new?size=3` stacksallthewaydown```

`ssh -o "UserKnownHostsFile /dev/null" core@<IP of CoreOS SSH Access shown in heat stack-show>`
