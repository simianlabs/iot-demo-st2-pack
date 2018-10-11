# iot-demo-st2-pack

Pack for StackStorm which include workflows and rules to set up environment with terraform and aws IoT buttom.

### Set up

Download pack and place it in your StackStorm instance packs, usually `/opt/stackstorm/packs`.
2. Import rules and actions with
```
$ st2ctl reload --register-all
```
3. Modify placeholders in workflows or customize pack accoridng your needs.

### Maintainer
Stefan Monko || smonko@simianlabs.io  
`Simian Labs` - (https://github.com/simianlabs)  
http://simianlabs.io || sl@simianlabs.io