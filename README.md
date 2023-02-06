# Azure Image Builder

Azure Image Builder requires a User-Assigned Managed Identity to do all of its work.  This Identity requires certain RBAC permissions.

This repo contains JSON files that you can use to create the custom RBAC roles that are required by this Identity.
- Make sure to update the `assignableScopes` in the JSON files to match your environment
- The custom Virtual Network role is only required if you configure Azure Image Builder to use your own existing Virtual Network

For more information see:
- [https://www.nathannellans.com/post/azure-vm-image-builder-part-1](https://www.nathannellans.com/post/azure-vm-image-builder-part-1)
- [https://www.nathannellans.com/post/azure-vm-image-builder-part-2](https://www.nathannellans.com/post/azure-vm-image-builder-part-2)
