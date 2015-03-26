heat stack-create -f stacksallthewaydown.yaml -P discovery_token_url=`wget -q https://discovery.etcd.io/new?size=3 -O discoverytoken; cat discoverytoken ; rm -f discoverytoken` stacksallthewaydown

ssh -o "UserKnownHostsFile /dev/null" core@<IP of CoreOS SSH Access shown in heat stack-show>
