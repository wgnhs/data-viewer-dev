# data-viewer-dev
Repository for deploying  a dev instance of the data viewer app from code on the dev branch of the data-pres-2018 repository.

Code from the `dev` branch of the production data viewer repository [wgnhs/data-pres-2018](https://github.com/wgnhs/data-pres-2018) is automatically deployed to the `gh-pages` branch in this repository.

Deployment uses a [Github Action Deploy to Github pages Dev](https://github.com/wgnhs/data-pres-2018/actions/workflows/deploy-pages-dev.yml) that triggers from the [wgnhs/data-pres-2018](https://github.com/wgnhs/data-pres-2018) repository when code is pushed or merged to the `dev` branch there.

**Do not edit code in this repository directly.**
