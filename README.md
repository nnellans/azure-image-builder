# Azure Image Builder

Azure Image Builder requires a User-Assigned Managed Identity that it uses to do its work.  This Identity requires certain RBAC permissions.

This repo contains the custom RBAC roles and permissions that are required by this Identity.
- Make sure to update the `assignableScopes` to match your environment
- The custom Virtual Network role is only required if you configure Azure Image Builder to use your own existing Virtual Network.
