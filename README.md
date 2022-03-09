# ⎈ Helm Charts ⎈

My collection of [Helm](https://helm.sh/) charts.

---

## :book: Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add cptchaos https://dcardellino.github.io/helm-charts/
helm repo update
```
You can then run `helm search repo cptchaos` to see the charts.

---

<h2><img src="https://github.com/pre-commit/pre-commit.com/raw/master/logo.svg" width="32" />Pre-commit hook</h2>

If you want to automatically generate `README.md` files with a pre-commit hook, make sure you
[install the pre-commit binary](https://pre-commit.com/#install), and add a [.pre-commit-config.yaml file](./.pre-commit-config.yaml)
to your project. Then run:

```bash
pre-commit install
pre-commit install-hooks
```

