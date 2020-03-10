# Minikube

#### commands

* `minikube start` เริ่มใช้งาน minikube
* `minikube dashboard` เปิดใช้งาน kube-dashboard

* `minikube addons` เรียกใช้งาน build-in addons ที่อยู่ภายใน
  * `minikube addons list` ดู addons ทั้งหมดที่มี
  * `minikube addons enable [add-on]` ใช้งาน addons

* `minikube service [service-name]` ดู service ที่ทำงานอยู่
* `minikube stop ` หยุดใช้งาน minikube
* `minikube delete` ลบ minikube

#### สร้าง object
* `kubectl create -f {yaml}` สร้าง object (ได้เพียงหนึ่งอัน)
* `kubectl apply -f {yaml}` อัพเดตและสร้าง object (ได้หลายอันพร้อมกัน)
* `kubectl delete -f  {yaml}` ลบ object

https://kubernetes.io/docs/tasks/tools/install-minikube/

https://kubernetes.io/docs/tutorials/hello-minikube/#create-a-minikube-cluster
