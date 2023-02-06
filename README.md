# Azure Image Builder

Azure Image Builder uses a User-Assigned Managed Identity in order to do its work.  The Identity requires certain RBAC permissions in order to operatore.  This repo contains the custom RBAC roles and permissions that are required by the Identity.

Make sure to update the `assignableScopes` to match your environment
