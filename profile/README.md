![Kubenet logo](https://github.com/kubenet-dev/docs/blob/main/assets/logos/Kubenet-logo-transparent-withname-100x123.png?raw=true)

[![Discord](https://img.shields.io/discord/860500297297821756?style=flat-square&label=discord&logo=discord&color=00c9ff&labelColor=bec8d2)](https://discord.gg/fH35bmcTU9)

# [Kubenet](https://learn.kubenet.dev/)

The Kubenet community has been created with the goal to help network engineers understand the potential of kubernetes for network automation. While we discuss networking, we are not talking about CNI(s) here, but about using `kubernetes` as an automation engine to manage physical, virtual or containerized NOS(s).

The environment is build such that can leverage multiple vendors. We use [srlinux][srlinux] for now as this is open to use, but we would welcome other vendors contributions.

If you are interested to learn and discuss [join us](https://discord.gg/fH35bmcTU9)

## Why

Kubernetes stands out as the most extensive and robust automation and orchestration system available today, already leveraged across many industries. The question to ask here is why is the networking industry not leveraging kubernetes for network automation. This community is setup to help understand the potential of kubernetes for network automation.

Here are some attributes to consider why kubernetes is a good automation platform:

- Open Source: As an open source platform, Kubernetes offers transparency, flexibility, and a collaborative community-driven approach. This fosters innovation and continuous improvement.
- Highly Extendable: Kubernetes is designed to be highly extendable, allowing for customization and integration with various tools and services to meet specific needs.
- Vast Ecosystem: The Kubernetes ecosystem is immense, with a wide range of tools, plugins, and extensions available. This ecosystem provides the resources needed to build comprehensive automation solutions.
- Declarative Model: Kubernetes uses a declarative model, making it easier to define and manage the desired state of network configurations.
- Event-Driven and Continuous Reconciliation: Kubernetes supports event-driven automation and continuous reconciliation, ensuring that the network’s state is consistently aligned with the defined configurations.
- Collaborative Approach with GitOps: Leveraging GitOps principles, Kubernetes enables a collaborative approach to network management. Changes can be tracked, reviewed, and deployed using version control systems, enhancing transparency and collaboration.
- Extensive Knowledge Base: The widespread adoption of Kubernetes means there is a vast knowledge base and a large community of experts. This allows organizations to leverage existing expertise to extend and optimize their automation systems.

## Repositories of the organisation

* **kubenet:** contains the kubenet artifacts
* **kubenetctl:** contains a CLI tool to help execute the kubenet exercises
* **examples:** holds somee examples to educate the networking community wrt kubernetes
* **docs:** contains the source of (learn.kubenet.dev)[https://learn.kubenet.dev/]

## Join us

Join us on this journey as we learn how to leverage kubernetes for network automation.

Have questions, ideas, bug reports or just want to chat? Come join [our discord server](https://discord.gg/fH35bmcTU9).

### License and governance

Code in the Kubenet repositories licensed with Apache License 2.0. At the moment the project is governed by the benevolent dictatorship of @henderiw @steiler @karimra and @hansthienpondt . On the long run we plan to move to a meritocracy based governance model.

[KRM]: https://github.com/kubernetes/design-proposals-archive/blob/main/architecture/resource-management.md
[GITOPS]: https://opengitops.dev
[YAML]: https://en.wikipedia.org/wiki/YAML
[srlinux]: https://learn.srlinux.dev