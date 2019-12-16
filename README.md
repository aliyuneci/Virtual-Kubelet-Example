## Virtual-Kubelet-Example

### [Virtual Kubelet](https://github.com/virtual-kubelet/virtual-kubelet)
Virtual Kubelet is an open source [Kubernetes kubelet](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet/) implementation that masquerades as a kubelet for the purposes of connecting Kubernetes to other APIs. This allows the nodes to be backed by other services like ACI, AWS Fargate, Hyper.sh, IoT Edge etc. The primary scenario for VK is enabling the extension of the Kubernetes API into serverless container platforms like ACI, Fargate, and Hyper.sh, though we are open to others. However, it should be noted that VK is explicitly not intended to be an alternative to Kubernetes federation.

Virtual Kubelet features a pluggable architecture and direct use of Kubernetes primitives, making it much easier to build on.

We invite the Kubernetes ecosystem to join us in empowering developers to build upon our base. Join our slack channel named, virtual-kubelet, within the Kubernetes slack group.

Please note this software is experimental and should not be used for anything resembling a production workload.

The best description is "Kubernetes API on top, programmable back."

### Alibaba Cloud ECI Provider
You can find more details in the Alibaba Cloud ECI provider documentation.

#### Configuration File
The alibaba ECI provider will read configuration file specified by the --provider-config flag.

The example configure file is providers/alibabacloud/eci.toml.
