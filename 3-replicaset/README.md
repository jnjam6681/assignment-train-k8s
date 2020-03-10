# Replica Set

#### commands

* `kubectl get replicaset` ดู replicaset

* `kubectl delete replicaset {name}` ลบ replicaset

* `kubectl edit replicaset {name}` แก้ไข config ของ replicaset

* `kubectl scale rs {name} --replicas=5` เพิ่ม/ลดจำนวนของ pod

https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/
