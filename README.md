<details><summary>Состав проекта:</summary>
    .

    ├── deploy
    │   └── helm
    │       ├── prod
    │       │   ├── Chart.yaml
    │       │   ├── conf
    │       │   │   ├── corp
    │       │   │   │   └── values.yaml
    │       │   │   ├── cpm
    │       │   │   │   └── values.yaml
    │       │   │   ├── sirius
    │       │   │   │   └── values.yaml
    │       │   │   └── univ
    │       │   │       └── values.yaml
    │       │   ├── templates
    │       │   │   ├── _helpers.tpl
    │       │   │   ├── clusterrole.yaml
    │       │   │   ├── clusterrolebinding.yaml
    │       │   │   ├── configmap.yaml
    │       │   │   ├── daemonset.yaml
    │       │   │   ├── deployment.yaml
    │       │   │   ├── role.yaml
    │       │   │   ├── rolebinding.yaml
    │       │   │   ├── secrert.yaml
    │       │   │   └── serviceaccount.yaml
    │       │   └── values.yaml
    │       └── stage
    │           ├── Chart.yaml
    │           ├── conf
    │           │   ├── corp
    │           │   │   └── values.yaml
    │           │   ├── cpm-dev
    │           │   │   └── values.yaml
    │           │   ├── sirius
    │           │   │   └── values.yaml
    │           │   └── univ
    │           │       └── values.yaml
    │           ├── templates
    │           │   ├── _helpers.tpl
    │           │   ├── clusterrole.yaml
    │           │   ├── clusterrolebinding.yaml
    │           │   ├── configmap.yaml
    │           │   ├── daemonset.yaml
    │           │   ├── deployment.yaml
    │           │   ├── role.yaml
    │           │   ├── rolebinding.yaml
    │           │   ├── secret.yaml
    │           │   └── serviceaccount.yaml
    │           └── values.yaml
    └── scripts
        └── helm_deploy_and_wait.sh
</details>

Original chart (deprecated project): https://github.com/jertel/elastalert-docker/tree/master/chart/elastalert
