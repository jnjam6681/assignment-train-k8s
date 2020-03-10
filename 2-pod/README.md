# Pod

### commands

* `kubectl run --generator=run-pod/v1 nginx --image=nginx` สร้าง pod

* `kubectl get pod` ดู pod ที่ใช้งานอยู่

* `kubectl get pod --all-namespaces` ดู pod ทั้งหมดจากทุก namespaces

* `kubectl get pod --namespace=kube-system` ดู pod ทั้งหมดจากทุก namespaces ที่ระบุไว้

* `kubectl describe pod {pod-name}` แสดงรายระเอียดของ pod

* `kubectl logs {pod-name}` แสดง log ของ pod

* `kubectl edit pod {pod-name}` แก้ไข config ของ pod

* `kubectl exec -it {pod-name} /bin/bash` shell เข้าไป container ภายใน pod

* `kubectl delete pod {pod-name}` ลบ pod
