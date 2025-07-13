# factory-reset-switch

```
dir flash:
```
```
delete flash:/private-config.text
```
```
delete flash:/config.text
```
```
delete flash:vlan.dat
```
```
boot
```
```
show vlan
```
```
dir
```
```
write erase
```
```
copy run start
```
```
copy start run
```
```
write mem
```
```
write term
```
```
reload
```
