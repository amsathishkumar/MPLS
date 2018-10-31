# MPLS
MultiProtocolLabelSwithcing
# VNF and PNF
A Virtual Network Function (VNF) is a logical outcome of Network Functions Virtualization (NFV).
Traditional network functions are deployed on hardware/servers - and this is referred to as “bare metal” deployment, and technically we refer to such network functions as Physical Network Functions (PNFs).
When we virtualize and pool our hardware resources in the data center by using a hypervisor technology such as KVM or VMware - we are essentially de-coupling the hardware from the netowork functions software that may run on it.
This is done by running the network functions inside Virtual Machines, which are then managed by the hypervisor - for allocation of virtual resources such as CPU, Memory etc.
The network functions that run inside virtual machines (VMs) and are known as Virtual Network Functions (VNFs).
A Virtual Network Function (VNF) can utilise multiple virtual machines to achieve its functionality. Such individual VMs are known as Virtual Network Function Components (VNFCs)
