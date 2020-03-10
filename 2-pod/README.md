# Pod

### commands

* `kubectl run --generator=run-pod/v1 nginx --image=nginx` สร้าง pod

* `kubectl get pods` ดู pod ที่ใช้งานอยู่

* `kubectl get pods --all-namespaces` ดู pod ทั้งหมดจากทุก namespaces

* `kubectl get pods --namespace=kube-system` ดู pod ทั้งหมดจากทุก namespaces ที่ระบุไว้

* `kubectl describe pod {pod-name}` แสดงรายระเอียดของ pod

* `kubectl logs {pod-name}` แสดง log ของ pod

* `kubectl edit po {pod-name}` แก้ไข config ของ pod

* `kubectl delete po {pod-name}` ลบ pod
