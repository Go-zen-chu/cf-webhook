# cf-webhook

 <img src="https://github.com/adnanh/webhook/raw/development/docs/logo/logo-128x128.png" alt="Webhook" align="left" />
 
 [webhook][w] on CF. That's it :)

 You can see the detail of what webhook does in [webhook][w].  

## Changes made for Cloud Foundry App

- create manifest for cf. binary_buildpack
- create hook.json file for default, and it is loaded in binary_buildpack exec command.

### deploy
```
$ make cf-build
$ cf push
```


[w]: https://github.com/adnanh/webhook
