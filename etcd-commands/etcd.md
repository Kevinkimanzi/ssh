#### Note that any key that was created using the v2 API will not be able to be queried via the v3 API. A v3 API etcdctl get of a v2 key will exit with 0 and no key data, this is the expected behaviour

 '''bash
 export ETCDCTL_API=3
 '''
 
#### version

 '''bash
 etcdctl version
 '''
 
#### Here is the command to set the value of key foo to bar

 '''bash
 etcdctl put foo bar
 '''

