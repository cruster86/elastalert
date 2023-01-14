<details><summary>Состав проекта:</summary>
    .

    ├── deploy
    │   └── helm
    │       ├── Chart.yaml
    │       ├── conf
    │       │   ├── corp
    │       │   │   └── values.yaml
    │       │   ├── cpm
    │       │   │   └── values.yaml
    │       │   ├── cpm-dev
    │       │   │   └── values.yaml
    │       │   ├── sirius
    │       │   │   └── values.yaml
    │       │   └── univ
    │       │       └── values.yaml
    │       ├── templates
    │       │   ├── _helpers.tpl
    │       │   ├── config.yaml
    │       │   ├── deployment.yaml
    │       │   ├── modules.yaml
    │       │   ├── podsecuritypolicy.yaml
    │       │   ├── role.yaml
    │       │   ├── rolebinding.yaml
    │       │   ├── rules.yaml
    │       │   ├── secret.yaml
    │       │   └── serviceaccount.yaml
    │       └── values.yaml
    └── scripts
        └── helm_deploy_and_wait.sh
</details>

Original chart (deprecated project): https://github.com/jertel/elastalert-docker/tree/master/chart/elastalert
