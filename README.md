# Ansible Execution Environment with Kustomize, OCM PolicyGenerator plugin, and Helm

An [Ansible Execution Environment](https://docs.ansible.com/ansible/latest/getting_started_ee/index.html) with:
* [kustomize](https://github.com/kubernetes-sigs/kustomize)
* [helm](https://github.com/helm/helm)
* [Open Cluster Management PolicyGenerator kustomize plugin](https://github.com/open-cluster-management-io/policy-generator-plugin)

## Building
```bash
ansible-builder build -v3
```

## Using
```bash
ansible-navigator --eei quay.io/itewk/ee-kustomzie-with-ocm-policygenerator-plugin-and-helm:1 run MY-PLAYBOOK.yaml
```
