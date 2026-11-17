# Migration readiness

Status: **prepared, not authorized for transfer**.

The current canonical repository is `fedhlab/cadmus-ndp-help`. A possible future location is `RinoFerrante/cadmus-ndp-help`, subject to an explicit decision by Rino Ferrante.

## GitHub Pages dependencies

The site currently depends on these owner-specific values:

- `README.md`: `https://fedhlab.github.io/cadmus-ndp-help/`
- `_config.yml`: `url: "https://fedhlab.github.io/cadmus-ndp-help"`
- `_config.yml`: repository link `https://github.com/fedhlab/cadmus-ndp-help`

Do not change them before the cutover. A repository redirect does not provide a substitute for validating and updating the published Pages address.

## Transfer checklist

1. Keep the repository public.
2. Record the source commit, Pages settings and current published-site result.
3. Inventory custom domains, DNS, Actions, environments, secrets, Apps and collaborators.
4. Create a verified backup.
5. Transfer only after Rino's explicit authorization.
6. Enable and verify Pages at the destination.
7. Update the owner-specific values in one dedicated pull request.
8. Test navigation, images, theme, Mermaid diagrams and external links.
9. Update inbound links and the canonical project documentation.
10. Do not recreate the old repository path after transfer.

No ownership, visibility, permission, DNS or Pages change is authorized by this document.
