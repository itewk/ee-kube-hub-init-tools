# Ansible Execution Environment for initializing kubernetes hub cluster

An [Ansible Execution Environment](https://docs.ansible.com/ansible/latest/getting_started_ee/index.html) with:
* [kustomize](https://github.com/kubernetes-sigs/kustomize)
* [helm](https://github.com/helm/helm)
* [Open Cluster Management PolicyGenerator kustomize plugin](https://github.com/open-cluster-management-io/policy-generator-plugin)

## Using
```bash
ansible-navigator --eei quay.io/itewk/ee-kube-hub-init-tools:latest run MY-PLAYBOOK.yaml
```

## Building
```bash
ansible-builder build -v3
```
