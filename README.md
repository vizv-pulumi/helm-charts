# Helm Charts for Viz's Homelab<br>用于 Viz Homelab 的 Helm Charts

A collection of Helm charts used by Viz's Homelab.
<br>包含了一系列用于 Viz Homelab 的 Helm Charts。

The chart repository is available at [https://vizv-pulumi.github.io/helm-charts](https://vizv-pulumi.github.io/helm-charts), all charts are automatically synced from upstream repositories.
<br>Chart 仓库的地址为 [https://vizv-pulumi.github.io/helm-charts](https://vizv-pulumi.github.io/helm-charts)，所有的 charts 都同步自上游的代码仓库。

## Branches<br>分支

* [main](https://github.com/vizv-pulumi/helm-charts/tree/main) branch is used to display this README file
<br>[main](https://github.com/vizv-pulumi/helm-charts/tree/main) 分支用于展示此 README 文件
* [workflows](https://github.com/vizv-pulumi/helm-charts/tree/workflows) branch contains GitHub Actions release workflow
<br>[workflows](https://github.com/vizv-pulumi/helm-charts/tree/workflows) 分支包含了 GitHub Actions 发布流程
* [release](https://github.com/vizv-pulumi/helm-charts/tree/release) branch contains charts files of current Helm repository
<br>[release](https://github.com/vizv-pulumi/helm-charts/tree/release) 分支包含了当前 Helm 仓库的所有 chart 文件
* [gh-pages](https://github.com/vizv-pulumi/helm-charts/tree/gh-pages) branch is the GitHub Pages branch to publish the Helm repository
<br>[gh-pages](https://github.com/vizv-pulumi/helm-charts/tree/gh-pages) 分支是用于发布 Helm 仓库的 GitHub Pages 分支

## Charts

Currently contains:
<br>当前包含：

* [local-path-provisioner](https://github.com/rancher/local-path-provisioner)
* [metallb](https://github.com/metallb/metallb)
* [ingress-nginx](https://github.com/kubernetes/ingress-nginx)

License information for these projects can be found in their repositories.
<br> 这些项目的许可证信息可以在他们的代码仓库中查到。

## Notes<br>附注

This repository is created for my Homelab Pulumi projects as some open-source projects (such as [local-path-provisioner](https://github.com/rancher/local-path-provisioner)) doesn't provide an official repository.
<br>这个仓库是为了我的 Pulumi Homelab 项目所创建 ，因为有些开源项目（如 [local-path-provisioner](https://github.com/rancher/local-path-provisioner)）不提供官方仓库。

You are welcome to use this chart repository however it's encouraged to fork this repository for your own use as I may delete or update some charts from time to time, and I may apply some unofficial patches for other charts in the future.
<br>欢迎每个人使用这个 chart 仓库，但是自用时请尽量 fork 一个自己的仓库。因为我会时不时的删除或更新一些仓库中的 charts，而且可能会对其中的某些 charts 打非官方的补丁。

Lastly, this repository uses [WTFPL](LICENSE), so just do whatever you want with it.
<br>最后想说一下这个仓库使用 [WTFPL](LICENSE) 许可，所以你可以可劲儿造。

**Happy hacking!**
<br>**造的愉快！**
