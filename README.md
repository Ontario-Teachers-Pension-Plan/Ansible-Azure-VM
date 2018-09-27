# Ansible-Azure-VM

This Repo Creates Azure VM. Azure Credentials is managed by Tower or AWX so it is not required as part of this Playbook. Just make sure you have the credentials selected as part fo the template.


## Required Variables

```javascript
{
Azure_Resource_Group: ''
Azure_IP_Name: ''
Azure_NIC_Name: ''
Azure_Subnet_Name: ''
Azure_VN_Name: ''
Azure_SG_Name: ''
Azure_VM_Name: ''
Azure_VM_Size: ''
Azure_SA_Name: ''
Azure_SC_Name: ''
Azure_SB_Name: ''
VM_ADMIN_NAME: ''
VM_ADMIN_PASWD: ''
VM_OS_TYPE: ''
VM_OS_VENDOR: ''
VM_OS_RELEASE: ''
VM_OS_VERSION: ''
}
```