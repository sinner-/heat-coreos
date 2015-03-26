```heat stack-create -f heat-template.yaml -P discovery_token_url=`curl -q https://discovery.etcd.io/new?size=3` coreos```

`ssh -o "UserKnownHostsFile /dev/null" core@<IP of CoreOS SSH Access shown in heat stack-show>`
