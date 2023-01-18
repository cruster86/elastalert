<details><summary>Состав проекта:</summary>

    ├── .gitlab-ci.yml
    ├── README.md     
    ├── deploy
    │   └── helm
    │       ├── Chart.yaml
    │       ├── conf
    │       │   ├── corp
    │       │   │   ├── modules.yaml    
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   ├── cpm
    │       │   │   ├── modules.yaml
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   ├── cpm-dev
    │       │   │   ├── modules.yaml
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   ├── sirius
    │       │   │   ├── modules.yaml
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   └── univ
    │       │       ├── modules.yaml
    │       │       ├── rules.yaml
    │       │       ├── config.yaml
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

<details><summary>Настройки:</summary>

  - Настройка параметров: `conf/${CLUSTER_NAME}/values.yaml`
  - Настройка конфига: `conf/${CLUSTER_NAME}/config.yaml`
  - Настройка правил: `conf/${CLUSTER_NAME}/rules.yaml`
  - Настройка модулей: `conf/${CLUSTER_NAME}/modules.yaml`
</details>