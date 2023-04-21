# sap-template
SAP Template for running SAP Netweaver on a RHEL 8 VM in Openshift Virtualization

Modify parameters at end of file to set desired configurations.

## Start the VM from the template

Render the template locally and deploy it to the cluster:

```bash
oc process --local -f https://github.com/kazoconnor/sap-template/blob/main/sap-template.yaml | oc apply -n <namespace> -f -


