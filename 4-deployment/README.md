# Deployment

#### commands

* `kubectl get deployment` ดู deployment

* `kubectl describe deployment {name}` แสดงรายระเอียดของ deployment

* `kubectl scale deployment {name} --replicas=4` เพิ่ม/ลดจำนวนของ pod ผ่าน deployment

* `kubectl edit deployment {name}` แก้ไข config ของ deployment

* `kubectl set image deployments/my-deployment nginx=nginx:1.17-alpine` อัพเดตเวอร์ชั่นของ image

* `kubectl run --generator=deployment/apps.v1 nginx-2 --image=nginx` สร้าง deployment

* `kubectl delete deployment {name}` ลบ deployment

https://www.weave.works/blog/kubernetes-deployment-strategies
