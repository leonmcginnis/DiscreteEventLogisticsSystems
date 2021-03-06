# Discrete Event Logistics Systems

## Overview
A discrete event logistics system (or DELS) can be described as:

*	a network of resources, arranged in a facility; each resource has one or more processing capabilities and for each capability, it has a capacity; 

*	a set of products flow through this network of resources, and are transformed by processes executed by the resources; a process may require the capabilities of more than one resource; the transformation can change location, age, or condition

## Project Overview
The goal of this project is to develop abstractions, model-libraries, and methodologies for applying them to support:
* **Communication** -- improve precision with which we describe these systems and harmonize terminology for both system and analysis modeling.

* **Interoperability** -- support developing integrated software and tools to support design, analysis, and operation

* **Analysis** --  increase accessibility of analysis methods through integrations and transformations from system models

* **Design** -- provide model-libraries to support development of conceptual models and functional architectures

## [Brief] Get-Started
_After you download the whole repository_, there are two basic ways to get started with the models. (Note: A more comprehensive guide is coming in the near future.)

1. Open **DiscreteEventLogisticsSystems.mdzip**. This will open the DELS model library and automatically import the Commodity Flow Network.
2. Open **DELSFramework.mdzip**. This will open the top-level model repository with all of the domain-specific model libraries. All domain-specific model libraries (except DELS and CFN) are work-in-progress or work-not-in-progress (stale projects).
3. Most of the domain-specific model libraries (e.g. **Manufacturing_RefArch.mdzip**) automatically import their dependency tree. So if you want to work with the Manufacturing libraries, you can simply open that library and it'll import both DiscreteEventLogisticsSystems and CommodityFlowNetwork.

**Note** These model libraries were created in NoMagic's MagicDraw 18.5 SP1 which implements SysML 1.4


## Disclaimers

The use of any software or hardware by the project does not imply a recommendation or endorsement by NIST.

The use of the project results in other software or hardware products does not imply a recommendation or endorsement by NIST of those products.

We would appreciate acknowledgement if any of the project results are used, however, the use of the NIST logo is not allowed.

NIST-developed software is provided by NIST as a public service. You may use, copy and distribute copies of the software in any medium, provided that you keep intact this entire notice. You may improve, modify and create derivative works of the software or any portion of the software, and you may copy and distribute such modifications or works. Modified works should carry a notice stating that you changed the software and should note the date and nature of any such change. Please explicitly acknowledge the National Institute of Standards and Technology as the source of the software.

NIST-developed software is expressly provided “AS IS.” NIST MAKES NO WARRANTY OF ANY KIND, EXPRESS, IMPLIED, IN FACT OR ARISING BY OPERATION OF LAW, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT AND DATA ACCURACY. NIST NEITHER REPRESENTS NOR WARRANTS THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT ANY DEFECTS WILL BE CORRECTED. NIST DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE OF THE SOFTWARE OR THE RESULTS THEREOF, INCLUDING BUT NOT LIMITED TO THE CORRECTNESS, ACCURACY, RELIABILITY, OR USEFULNESS OF THE SOFTWARE.

You are solely responsible for determining the appropriateness of using and distributing the software and you assume all risks associated with its use, including but not limited to the risks and costs of program errors, compliance with applicable laws, damage to or loss of data, programs or equipment, and the unavailability or interruption of operation. This software is not intended to be used in any situation where a failure could cause risk of injury or damage to property. The software developed by NIST employees is not subject to copyright protection within the United States.
