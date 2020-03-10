# Service

#### commands

`kubectl get service` ดู service

`kubectl edit service {name}` แก้ไข config ของ service

`kubectl expose deployment {name} --port=80 --type=NodePort` สร้าง service โดย expose มาจาก deployment

`kubectl delete service {name}` ลบ service

https://kubernetes.io/docs/concepts/services-networking/service/
