# Azure Image Builder

Azure Image Builder requires a User-Assigned Managed Identity that it uses to do its work.  This Identity requires certain RBAC permissions.

This repo contains the custom RBAC roles and permissions that are required by this Identity.

Make sure to update the `assignableScopes` to match your environment
