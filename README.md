<details><summary>Состав проекта:</summary>
    .

    ├── deploy
    │   └── helm
    │       ├── Chart.yaml
    │       ├── conf
    │       │   ├── corp
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   ├── cpm
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   ├── cpm-dev
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   ├── sirius
    │       │   │   ├── rules.yaml
    │       │   │   ├── config.yaml
    │       │   │   └── values.yaml
    │       │   └── univ
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

Настройки:
  - Настройка модулей: `templates/modules.yaml` ( общая для всех кластеров )
  - Настройка конфига: `conf/${CLUSTER_NAME}/config.yaml`
  - Настройка правил: `conf/${CLUSTER_NAME}/rules.yaml`

---

Original chart (deprecated): https://github.com/jertel/elastalert-docker/tree/master/chart/elastalert
