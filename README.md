[![Board Status](https://dev.azure.com/foamgaby/97885a67-eef4-49aa-a12e-d76a06491134/566afe1a-52b8-41c8-ac91-80e4cd564a98/_apis/work/boardbadge/92bdd072-a636-45ef-94e9-a3d5caf66a7d)](https://dev.azure.com/foamgaby/97885a67-eef4-49aa-a12e-d76a06491134/_boards/board/t/566afe1a-52b8-41c8-ac91-80e4cd564a98/Microsoft.RequirementCategory)
# Kubernetes Examples

This directory contains a number of examples of how to run real applications
with Kubernetes.

Refer to the [Kubernetes documentation] for how to execute the tutorials.

### Maintained Examples

Maintained Examples are expected to be updated with every Kubernetes release, to
use the latest and greatest features, current guidelines and best practices,
and to refresh command syntax, output, changed prerequisites, as needed.

|Name | Description | Notable Features Used | Complexity Level|
------------- | ------------- | ------------ | ------------ |
|[Guestbook](guestbook/) | PHP app with Redis | Deployment, Service | Beginner |
|[Guestbook-Go](guestbook-go/) | Go app with Redis | Deployment, Service | Beginner |
|[WordPress](mysql-wordpress-pd/) | WordPress with MySQL | Deployment, Persistent Volume with Claim | Beginner|
|[Cassandra](cassandra/) | Cloud Native Cassandra | Daemon Set, Stateful Set, Replication Controller | Intermediate

> Note: Please add examples that are maintained to the list above.

See [Example Guidelines](guidelines.md) for a description of what goes
in this directory, and what examples should contain.

[Kubernetes documentation]: https://kubernetes.io/docs/tutorials/

### Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for instructions on how to contribute.
