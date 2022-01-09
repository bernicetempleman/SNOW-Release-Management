# SNOW-Release-Management

-	Release Management encompasses the planning, design, build, configuration and testing of hardware and software releases to create a defined set of release components.

-	ServiceNow handles releases using the task record system. Each planned feature is generated through a variety of means as a task record, populated with the pertinent information in individual fields. These tasks can be assigned to appropriate release management team members, who will deal with the task as appropriate until the release has been properly deployed.

-	Release Management can be effectively used to coordinate releases as a vehicle for planning releases, composed of individual features. Once a release is finalized, a Change Item can be generated, allowing the implementation and deployment of a release to be handled within the change management process.

## Concepts
	Release Management consists of the following tables:

- Products - represent the hardware or software for which releases will be built. A product can be linked with a Business Service in the CMDB to link it with other ITIL processes.

- Releases - represent a planned release for a product. The content of a release is defined by the features (and associated Requests for Change) that it implements.

- Features - represent the individual changes being made to the product. A feature may be associated with a configuration item or with a change request, and to a parent release.

- Release Phases - represent the planned phases that a release will have, which are used to group the tasks required to carry out the release.

- Release Tasks - represent any of the tasks required to implement a feature of a product!
- Note: Customers and Partners receive at least 30 days notice before an upgrade.
- ServiceNow has introduced a new naming convention, starting with ASPEN, which is based on an alphabetical system using names of world cities.

## Release Terminology
![image](https://user-images.githubusercontent.com/12488769/148684741-da784617-d353-4548-bf37-d4d339209633.png)

## Release Cycle
![image](https://user-images.githubusercontent.com/12488769/148684751-8e9c3d69-7c21-43b4-8a16-97ad8a466c42.png)

= Note: Above is a hypothetical release cycle based on the types of releases that ServiceNow offers. Interim releases include Hot fixes and Patch releases









