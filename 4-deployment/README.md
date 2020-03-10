# Deployment

#### commands

* `kubectl run --generator=deployment/apps.v1 nginx --image=nginx` สร้าง deployment

* `kubectl get deployment` ดู deployment

* `kubectl scale deployment {name} --replicas=4` เพิ่ม/ลดจำนวนของ pod ผ่าน deployment

* `kubectl set image deployments/my-deployment nginx=nginx:1.17-alpine` อัพเดตเวอร์ชั่นของ image

* `kubectl edit deployment {name}` แก้ไข config ของ deployment

* `kubectl describe deployment {name}` แสดงรายระเอียดของ deployment

* `kubectl delete deployment {name}` ลบ deployment

https://www.weave.works/blog/kubernetes-deployment-strategies
