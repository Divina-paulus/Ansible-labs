## Task1
### Install Apache on two machines
- Install Apache on two machines
- change port from 80 to 8090 , adjust security group to allow traffic on port 8090
- change custom page of apache

<img src="https://user-images.githubusercontent.com/92440274/218450137-3dca8cc3-d4dc-4884-a9dc-e27f94f0aa86.png">

```
   ansible-playbook playbook.yaml -i inventory.txt
```

<img src="https://user-images.githubusercontent.com/92440274/218450412-3c748d14-be4e-4bef-806f-d186bdde95dc.png">

```
  systemctl status apache2
  curl http://34.224.6.176:8090
```
<img src="https://user-images.githubusercontent.com/92440274/218450715-4bfce150-4209-43cf-b68c-e4cb1e7fa964.png">

<img src="https://user-images.githubusercontent.com/92440274/218451265-5cf1f137-a9e9-41c3-b830-7c156f5f40ab.png">
