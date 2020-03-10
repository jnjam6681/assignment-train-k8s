# Deployment

#### commands

* `kubectl run --generator=deployment/apps.v1 nginx --image=nginx` สร้าง deployment

* `kubectl get deployment` ดู deployment

* `kubectl scale deployment {name} --replicas=4` เพิ่ม/ลดจำนวนของ pod ผ่าน deployment

* `kubectl edit deployment {name}` แก้ไข config ของ deployment

* `kubectl describe deployment {name}` แสดงรายระเอียดของ deployment

* `kubectl delete deployment {name}` ลบ deployment
