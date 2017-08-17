# Old Information
The following info is provided for historical purposes only. It is no longer
relevant, and probably does not even work

## V3 Beta 4 (DEPRECATED)
The following is an overview of the OpenShift features covered in beta 4:
- Features of Beta 1, Beta 2 and Beta 3
- Improvements and enhancements in the CLI and UI
- Expanded documentation/explanations
- Integrated sdn into OpenShift
    - No separate openshift-sdn-node and openshift-sdn-master packages or services
      You should remove openshift-sdn-master and openshift-sdn-node packages or
      preferably reprovision your environment when installing Beta 4
    - Openvswitch based implementation provided via 'openshift-sdn-ovs' plugin
      package and configuring `networkPluginName: redhat/openshift-ovs-subnet` on
      master and nodes. Ansible does this for you by default.

[The specific documentation for beta 4 is here.](beta-4-setup.md)

## V3 Beta 3 (DEPRECATED)
The following is an overview of the OpenShift features covered in beta 3:
- Features of Beta 1 and Beta 2
- Templates/Quickstarts from the console
- Improvements and enhancements in the CLI and UI
- "Regions" and "Zones"
- Quota enforcement
- Beginnings of user/team management
- Internal service DNS
- Expanded documentation/explanations

[The specific documentation for beta 3 is here.](beta-3-setup.md)

## V3 Beta 2 (DEPRECATED)
The following is an overview of the OpenShift features covered in beta 2:
- Features of Beta 1
- User authentication
- Project quotas (display)
- Rollback / Activate
- Complex / Tiered app deployment
- Arbitrary docker image deployment
- "integration" / webhooks
- Ansible-based installer (non-interactive)

[The specific documentation for beta 2 is here.](beta-2-setup.md)

## V3 Beta 1 (DEPRECATED)
The following is an overview of the OpenShift features covered in beta 1:

- Installation and configuration of OpenShift and openshift-sdn
- Adding nodes to the master
- Web console and project basics
- Extensive command line use
- Basic HTTP/S (only) routing. 
- Work with supplied example applications
    - Includes STI (source-to-image) build examples

[The specific documentation for beta 1 is here.](beta-1-setup.md)

