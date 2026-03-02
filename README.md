
## Awesome OpenShift Console Plugins

Welcome to `awesome-openshift-console-plugins` repository. This repository is dedicated to curating a list of dynamic plugins that extend the functionality of the OpenShift Console. Whether you're looking to add new visual components, functionality, or integrate with external systems, this list can help you find the right plugins to enhance your OpenShift experience.

Please note that this is purely a list, and inclusion does not constitute an endorsement. Use any plugin based on your own risk and discretion.

## What is OpenShift?

[OpenShift](https://www.openshift.com/) is a Kubernetes distribution from Red Hat which provides developer and operational tools on top of Kubernetes. OpenShift Console provides a web-based administrative interface for managing resources in the cluster.

## What are Dynamic Plugins?

 are a new mechanism in OpenShift Console that allows developers to extend the user interface in a dynamic way, meaning plugins can be enabled, disabled, and upgraded without restarting the console.

[Dynamic plugins](https://docs.openshift.com/container-platform/4.21/web_console/dynamic-plugin/overview-dynamic-plugin.html) are an innovative feature in OpenShift Console. With the ability to register plugins at runtime using the ConsolePlugin custom resource, these plugins provide a seamless way to extend the console's interface without the need for restarts.
Key Features

Dynamic plugins offer the following customization possibilities:

- Add Custom Pages: Enhance the console with pages tailored to specific use cases.
- Extend Perspectives: Go beyond the default administrator and developer perspectives.
- Introduce New Navigation Items: Make navigation more intuitive and tailored to user needs.
- Incorporate Tabs & Actions: Enhance resource pages with additional tabs and actionable items.

You can also see [this repo template](https://github.com/openshift/console-plugin-template) to find out about its structure.

Below is the list of available OpenShift dynamic plugins. Feel free to contribute by adding more plugins to this list.

## Plugin List

- Openshift Monitoring: <https://github.com/openshift/monitoring-plugin>
- Openshift Logging View: <https://github.com/openshift/logging-view-plugin>
- Openshift Distributed Tracing: <https://github.com/openshift/distributed-tracing-console-plugin>
- OpenShift Lightspeed: <https://github.com/openshift/lightspeed-console>
- OpenShift Networking: <https://github.com/openshift/networking-console-plugin>
- Openshift Pipelines: <https://github.com/openshift-pipelines/console-plugin>
- Kubevirt UI: <https://github.com/kubevirt-ui/kubevirt-plugin>
- Kiali ServiceMesh: <https://github.com/kiali/openshift-servicemesh-plugin>

## Contributing

See [CONTRIBUTING](./CONTRIBUTING.md)

---

🌟 Don't forget to star the repository if you find it useful. Happy OpenShifting! 🌟
