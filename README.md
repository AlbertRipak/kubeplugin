# Kubeplugin
Kubeplugin is a Kubernetes statisctics of Pods.
This is a simple plugin written in a bash script.
You can use this to get CPU and memory usage statisctics of a Pods.

## Install 
```shell
git clone https://github.com/AlbertRipak/kubeplugin.git
cd kubeplugin
chmod +x kubeplugin
```

## Usage
To use Kubeplugin you need add 2 parameters.
This is a "pod" resource type and namespace such as "kube-system".
![Image](./data/kubeplugin.gif)