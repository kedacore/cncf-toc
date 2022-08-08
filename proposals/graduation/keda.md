# Kubernetes Event-driven Autoscaling (KEDA) Graduation Proposal

_TODO @tomkerkhove - Insert introduction. See previous proposals for examples. This section should address from a broad perspective why the project feels they are ready to graduation and can state any major accomplishments or milestones._

## Graduation State Criteria
_Project should address each graduation criteria listed below_

### * Have committers from at least two organizations.

KEDA has maintainers from 4 different companies (Microsoft, Lidl, Red Hat & Snowflake - See [maintainers.md](https://github.com/kedacore/governance/blob/main/MAINTAINERS.md)) and contributions from a variety of companies, as per the [CNCF DevStats](https://keda.devstats.cncf.io/d/5/companies-table?orgId=1).

### * Have achieved and maintained a [Core Infrastructure Initiative Best Practices Badge](https://bestpractices.coreinfrastructure.org/).

<a href="https://bestpractices.coreinfrastructure.org/projects/3791"><img src="https://bestpractices.coreinfrastructure.org/projects/3791/badge"></a>

### * Have completed an independent and third party security audit with results published of similar scope and quality as [this example](https://github.com/envoyproxy/envoy#security-audit) which includes all critical vulnerabilities and all critical vulnerabilities need to be addressed before graduation.

The security audit has been started with OSTIF and is ongoing.

### * Explicitly define a project governance and committer process. The committer process should cover the full committer lifecycle including onboarding and offboarding or emeritus criteria. This preferably is laid out in a GOVERNANCE.md file and references an OWNERS.md file showing the current and emeritus committers.

This is documented in our governance documentation available [here](https://github.com/kedacore/governance/blob/main/GOVERNANCE.md) as well as our [contribution guide](https://github.com/kedacore/keda/blob/main/CONTRIBUTING.md) for making contributions.

We have also introduced [scaler governance](https://github.com/kedacore/governance/pull/65) which defines when they become part of our core, or when we recommend our community to build external scalers and to list them on Artifact Hub.

### * Explicitly define the criteria, process and offboarding or emeritus conditions for project maintainers; or those who may interact with the CNCF on behalf of the project. The list of maintainers should be preferably be stored in a MAINTAINERS.md file and audited at a minimum of an annual cadence.

This is documented in our governance documentation available [here](https://github.com/kedacore/governance/blob/main/GOVERNANCE.md).

### * Have a public list of Project adopters for at least the primary repo (e.g., ADOPTERS.md or logos on the Project website). For a specification, have a list of adopters for the implementation(s) of the spec. Refer to [FAQs](https://github.com/cncf/toc/blob/main/FAQ.md#what-is-the-definition-of-an-adopter) for guidelines on identifying adopters.

KEDA provides a full overview of publicly listed end-users on [its website](https://keda.sh/community/), but there are others that we are not allowed to list but can be interviewed.

Here's a quick overview of the end-users at the time of writing:

![End-users](https://raw.githubusercontent.com/kedacore/governance/main/cncf/graduation/end-users-august-2022.png)

## Incubation Details

### * Link to Incubation Due Diligence(DD) Document

The Incubation Due Diligence(DD) document can be found [here](https://docs.google.com/document/d/16iqSoPiOe7N0jNevuXvan31ut3MocGLz-I9yTLGaSdM/edit?usp=sharing).

### * Address any concerns or recommendations from the TAG and/or TOC sponsor(s) from the DD Document

> KEDA is currently on track for Incubation status. During the due diligence process we identified a number of recommendations that we would like to see addressed in the future on the path to gradation. 
> - Documenting the release versioning scheme, which is currently in progress as described in the [Incubation Criteria Summary](https://docs.google.com/document/d/16iqSoPiOe7N0jNevuXvan31ut3MocGLz-I9yTLGaSdM/edit#heading=h.vtd7sw8micdq), should be completed before the TOC votes on KEDA Incubation. Meanwhile, this DD document can be opened for public comment to check for any other blocking criteria. 
>   - Update: this is now documented [here](https://github.com/kedacore/governance/blob/main/RELEASES.md)
> - We do not believe that any of the other recommendations described in this document are requirements for Incubation stage. 
> Additionally, we recommend that the Kubernetes and TOC community consider the alignment between KEDA and Kubernetes autoscaling, as described in [KEDA and Kubernetes HPA](https://docs.google.com/document/d/16iqSoPiOe7N0jNevuXvan31ut3MocGLz-I9yTLGaSdM/edit#heading=h.ptwd2hpk90m6). There are no known issues or conflicts, simply a question of whether there should be a single community interested in Kubernetes autoscaling. Although this question was highlighted by the DD process, it is beyond the scope of the KEDA project alone, and should not block Incubation. 
