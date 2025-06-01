# ckad-notes
List of resources and notes for passing the Certified Kubernetes Application Developer (CKAD) exam.

- [CNCF Official CKAD Main](https://www.cncf.io/certification/ckad/)
- [CNCF Official CKAD Exam Tips](https://www2.thelinuxfoundation.org/ckad-tips)
- [CNCF Official CKAD Candidate Handbook](https://www.cncf.io/certification/candidate-handbook)
- [CNCF Kubernetes Curriculum Repo](https://github.com/cncf/curriculum)
- [CKAD Exam Practice Questions](https://github.com/dgkanatsios/CKAD-exercises)

# Current Progress
The list below is based on the curriculum v1.0. Once you have mastered a section, check it off and move on to the next. You need to understand them ALL very well. The Core Concepts piece is kind of vague, but the others are defined well enough that it is easy to prepare for with a hands-on work through the tasks offered at kubernetes.io. The rest of this document follows this same outline of curriculum.

- [ ] __Core Concepts - 13%__
  - [ ] API Primitives
  - [ ] Create and Configure Basic Pods
- [ ] __Configuration - 18%__
  - [ ] Understand ConfigMaps
  - [ ] Understand SecurityContexts
  - [ ] Define App Resource Requirements
  - [ ] Create and Consume Secrets
  - [ ] Understand Service Accounts
- [ ] __Multi-Container Pods - 10%__
  - [ ] Design Patterns: Ambassador, Adapter, Sidecar
    - [ ] - Sidecar Pattern
    - [ ] - Init Containers
- [ ] __Pod Design - 20%__
  - [ ] Using Labels, Selectors, and Annotations
  - [ ] Understand Deployments and Rolling Updates
  - [ ] Understand Deployment Rollbacks
  - [ ] Understand Jobs and CronJobs
- [ ] - __State Persistence - 8%__
  - [ ] - Understand PVCs for Storage
- [ ] __Observability - 18%__
  - [ ] Liveness and Readiness Probes
  - [ ] Understand Container Logging
  - [ ] Understand Monitoring Application in Kubernetes
  - [ ] Understand Debugging in Kubernetes
- [ ] __Services and Networking - 13%__
  - [ ] Understand Services
  - [ ] Basic Network Policies

  # Tasks from Kubernetes Doc
The following are primarily links to either the 'concepts' or 'tasks' section of the kubernetes.io documentation. The 'task' items are very useful to use as labs. I've tied them directly to the curriculum to ensure they are appropriate study material for the exam.

## Core Concepts and Kubectl

- [Tasks -> Accessing Multiple Clusters](https://kubernetes.io/docs/tasks/access-application-cluster/configure-access-multiple-clusters/)
- [Tasks -> Accessing Cluster with API](https://kubernetes.io/docs/tasks/access-application-cluster/access-cluster/)
- [Tasks -> Port Forwarding](https://kubernetes.io/docs/tasks/access-application-cluster/port-forward-access-application-cluster/)
- [Tasks -> Shell to Running Container (exec)](https://kubernetes.io/docs/tasks/debug-application-cluster/get-shell-running-container/)

## Configuration

- [Task -> Config Maps](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/)
- [Task -> Security Contexts](https://kubernetes.io/docs/tasks/configure-pod-container/security-context/)
- [Tasks -> Assigning Memory Resources to Pods](https://kubernetes.io/docs/tasks/configure-pod-container/assign-memory-resource/)
- [Tasks -> Assigning CPU Resources to Pods](https://kubernetes.io/docs/tasks/configure-pod-container/assign-cpu-resource/)
- [Tasks -> Pod QOS](https://kubernetes.io/docs/tasks/configure-pod-container/quality-service-pod/)
- [Tasks -> Credentials using Secrets](https://kubernetes.io/docs/tasks/inject-data-application/distribute-credentials-secure/)
- [Tasks -> Project Volume w/Secrets](https://kubernetes.io/docs/tasks/configure-pod-container/configure-projected-volume-storage/)
- [Tasks -> Setting Service Account](https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/)

## Multi-Container Pods

- [Tasks -> Init Containers](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-initialization/)
- [Concepts -> Logging Architecture](https://kubernetes.io/docs/concepts/cluster-administration/logging/)

## Pod Design
- [Concepts -> Assign Pods to Nodes - Selectors](https://kubernetes.io/docs/concepts/configuration/assign-pod-node/)
- [Concepts -> Annotations](https://kubernetes.io/docs/concepts/overview/working-with-objects/annotations/)
- [Concepts -> Labels and Selectors](https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/)
- [Tasks -> ReplicaSet Rolling Updates](https://kubernetes.io/docs/tasks/run-application/run-stateless-application-deployment/)
- [Concepts -> Deployments, Rollouts, and Rollbacks](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)

### CRON
- [Tasks -> Automated Tasks with Cron Jobs](https://kubernetes.io/docs/tasks/job/automated-tasks-with-cron-jobs/)
- [Tasks -> Parallel Jobs with Expansions](https://kubernetes.io/docs/tasks/job/parallel-processing-expansion/)
- [Tasks -> Course Parallel Processing with a Work Queue](https://kubernetes.io/docs/tasks/job/coarse-parallel-processing-work-queue/)
- [Tasks -> Fine Parallel Processsing with a Work Queue](https://kubernetes.io/docs/tasks/job/fine-parallel-processing-work-queue/)

## State Persistence
- [Concepts -> Persistent Volumes](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
- [Tasks -> Configuring PVCs](https://kubernetes.io/docs/tasks/configure-pod-container/configure-persistent-volume-storage/)

## Observability
- [Tasks -> App Introspection and Debugging](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application-introspection/)
- [Tasks - Liveness and Readiness Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/)
- [Tasks -> Debugging Pods](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-pod-replication-controller/)
- [Tasks -> Troubleshooting Applications](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application/)
- [Tasks -> Debugging Services](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-service/)
- [Tasks -> Debugging Services Locally](https://kubernetes.io/docs/tasks/debug-application-cluster/local-debugging/)
- [Tasks -> Tools for Monitoring Resources](https://kubernetes.io/docs/tasks/debug-application-cluster/resource-usage-monitoring/)

## Services and Networking

- [Concepts -> Connecting Apps with Services](https://kubernetes.io/docs/concepts/services-networking/connect-applications-service/)
- [Tasks -> Declare Network Policy](https://kubernetes.io/docs/tasks/administer-cluster/declare-network-policy/)