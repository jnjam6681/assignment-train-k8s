# Replica Set

#### commands

* `kubectl get replicaset` ดู replicaset

* `kubectl edit replicaset {name}` แก้ไข config ของ replicaset

* `kubectl scale rs {name} --replicas=5` เพิ่ม/ลดจำนวนของ pod

* `kubectl delete replicaset {name}` ลบ replicaset

https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/
