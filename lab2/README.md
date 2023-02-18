## lab2
<img src="https://user-images.githubusercontent.com/92440274/219900112-30c1e646-3bf0-49aa-ab84-9d78aba1bcce.png">


-------------------------------------------------------------------------------
- create instaces from aws console

<img src="https://user-images.githubusercontent.com/92440274/219899846-f0742fc4-2c5d-48a8-af21-038a43ade29c.png">

-  Load Balancer, Target Group and Security Groups

<img src="https://user-images.githubusercontent.com/92440274/219900596-38283ba2-8bb4-440f-9c2c-03a411c5257f.png">

<img src="https://user-images.githubusercontent.com/92440274/219900664-34123296-27f3-41b5-b120-8aa5a48f1df8.png">

<img src="https://user-images.githubusercontent.com/92440274/219900830-fe470c4a-42c4-4642-87c1-fc583b709bce.png">

- Add config file in ~/.ssh/
```
cat ~/.ssh/config
```
<img src="https://user-images.githubusercontent.com/92440274/219901153-84d132ab-db2d-4fa8-afe0-ce8c186fbd9d.png">

- Install nexus

```
ansible-playbook -i inventory.ini nexus.yaml
```
<img src="https://user-images.githubusercontent.com/92440274/219901073-959ccd38-9f13-4826-935a-cea08f6ea8f2.png">

```
ssh -o ProxyCommand="ssh -W %h:%p -q jump" -i ~/ansible-labs/lab2/ansible-key.pem ec2-user@10.0.1.235
```

<img src="https://user-images.githubusercontent.com/92440274/219901374-39a4f7b6-a513-46a2-a17a-cbe6c000d37b.png">

<img src="https://user-images.githubusercontent.com/92440274/219901435-1f83b239-45b3-4474-8528-5bfabe7a190e.png">

- nexus page
<img src="https://user-images.githubusercontent.com/92440274/219901469-72399236-f0bb-42b8-9225-969b5f0a3635.png">
