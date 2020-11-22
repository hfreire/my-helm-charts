# My :boat: Helm charts repository for Kubernetes applications

>

### Features
* Fluentd allows you to unify data collection and consumption for a better use and understanding of data

### How to deploy

#### Deploy it from your terminal
Deploying it in your terminal requires [Helm](https://helm.sh/) installed in your system.

##### Add the GitHub repository to Helm
```
helm repo add my-helm-charts https://github.com/hfreire/my-helm-charts
```

##### Install Fluentd chart
```
helm install --name 1.6 my-helm-charts/fluentd
```

##### Uninstall Fluentd chart
```
helm delete --release 1.6 purge
```

### How to contribute
You can contribute either with code (e.g., new features, bug fixes and documentation) or by [donating 5 EUR](https://paypal.me/hfreire/5). You can read the [contributing guidelines](CONTRIBUTING.md) for instructions on how to contribute with code.

All donation proceedings will go to the [Sverige för UNHCR](https://sverigeforunhcr.se), a swedish partner of the [UNHCR - The UN Refugee Agency](http://www.unhcr.org), a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people.

### License
Read the [license](./LICENSE.md) for permissions and limitations.
