# LCP Builder

Write custom LANCER NPC features, templates and classes, preview them on cards
modelled on COMP/CON, and download a `.lcp` content pack to import.

It is one self-contained `index.html`: no build step, no dependencies and no
network calls. Your work stays in your browser's local storage.

## Using it

1. Add a feature, and a template for it to belong to.
2. Clear anything listed under **Checks**.
3. Download the `.lcp` and import it in COMP/CON's content manager.
4. Add your template to an NPC, then pick the feature from its optional features.

**Open .lcp** reopens a pack for editing, and keeps any files in it that this
tool doesn't edit.

## Format

Packs use the older NPC format: capitalised feature types and `origin` objects.
It imports and displays correctly on COMP/CON v3. Required fields follow the
schemas in Massif Press's
[content tools](https://github.com/massif-press/vscode-comp-con-content-authoring).

## Notes

The V3 and V2 previews are matched by eye from screenshots and only approximate
COMP/CON, so importing is still the real test. Full-action and free-action
Systems in V3, V2 Tech and Reaction cards, role colours other than V2 Support,
and the class radar chart are the least certain parts.

A pack's cover image is the manifest's `image_url`. A public link is the most
reliable choice. An image chosen from your computer is shrunk and stored inside
the pack, so check that it shows in COMP/CON before sharing.

Unofficial fan tool, not affiliated with Massif Press. LANCER and COMP/CON belong
to their respective owners.
