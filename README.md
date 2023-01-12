<details><summary>Состав проекта:</summary>
    .
    
    ├── deploy
    │   └── helm
    │       ├── Chart.yaml
    │       ├── conf
    │       │   ├── corp
    │       │   │   ├── config.yaml
    │       │   │   ├── rules.yaml
    │       │   │   └── values.yaml
    │       │   ├── cpm
    │       │   │   ├── config.yaml
    │       │   │   ├── rules.yaml
    │       │   │   └── values.yaml
    │       │   ├── cpm-dev
    │       │   │   ├── config.yaml
    │       │   │   ├── rules.yaml
    │       │   │   └── values.yaml
    │       │   ├── sirius
    │       │   │   ├── config.yaml
    │       │   │   ├── rules.yaml
    │       │   │   └── values.yaml
    │       │   └── univ
    │       │       ├── config.yaml
    │       │       ├── rules.yaml
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
    │       │   └── serviceaccount.yaml
    │       └── values.yaml
    └── scripts
        └── helm_deploy_and_wait.sh
</details>

Original chart (deprecated project): https://github.com/jertel/elastalert-docker/tree/master/chart/elastalert
