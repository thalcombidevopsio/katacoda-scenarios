Setup:
npm i katacoda-cli --global

Create a lesson:
katacoda courses:create

Create a scenario:
$ katacoda scenarios:create
? Friendly url:  abc-k8s
? Scenario Title:  ABC's of Kuberenetes
? Scenario Description:  Introductory lesson to Kuberenetes and Kubectl
? Difficulty Level:  Beginner
? Estimated time: (Please specify in minutes or hours e.g. 2 hours) 20
? Number of Steps (Not including intro & finish):  3
? Image:  Minikube (Already Configured)
? Layout:  Terminal
Scenario created successfully.

List sencarios:
find ./ -type f | grep index.json