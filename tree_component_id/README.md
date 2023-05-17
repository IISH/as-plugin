# tree_component_id

**The functionality in this plugin was to have been incorporated into ArchivesSpace core code as of v3.1.0 - see https://github.com/archivesspace/archivesspace/pull/2220 for details**

Displays component IDs in the Resource tree in ArchivesSpace (versions 2.0+).

Two files here: an extension to *backend/model/large_tree.rb* to include the component IDs (id_0 from the Resource, component_id from the Archival Objects), and a re-write of the container summary populator on the frontend to make sure they display.

Questions: kevin.clair at du.edu

---

Cambridge additions: tweaking Kevin's code so it only shows the top container type if it exists, and adding the same component ids to the PUI collection organisation section
