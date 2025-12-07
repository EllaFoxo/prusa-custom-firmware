---
weight: 1
title: "Home"
# description: "Install and run custom firmware, such as Klipper/Kalico on your Prusa 3D printer."
date: "2025-12-07T00:10:31+01:00"
lastmod: "2025-12-07T00:10:31+01:00"
icon: "home"
draft: false
---


## Install Hugo

Install the [Hugo CLI](https://github.com/gohugoio/hugo/releases/latest), using the specific instructions for your operating system below:

{{< tabs tabTotal="4">}}
{{% tab tabName="Linux" %}}

Your Linux distro’s package manager may include Hugo. If this is the case, install it directly using your distro’s package manager – for instance, in Ubuntu, run the following command. This will install the extended edition of Hugo:

```shell
sudo apt install hugo
```

{{% /tab %}}
{{% tab tabName="Homebrew (macOS)" %}}

If you use the package manager [Homebrew](https://brew.sh/), run the `brew install` command in your terminal to install Hugo:

```shell
brew install hugo
```

{{% /tab %}}
{{% tab tabName="Windows (Chocolatey)" %}}

If you use the package manager [Chocolatey](https://chocolatey.org/), run the `choco install` command in your terminal to install Hugo:

```shell
choco install hugo --confirm
```

{{% /tab %}}
{{% tab tabName="Windows (Scoop)" %}}

If you use the package manager [Scoop](https://scoop.sh/), run the `scoop install` command in your terminal to install Hugo:

```shell
scoop install hugo
```

{{% /tab %}}
{{< /tabs >}}
