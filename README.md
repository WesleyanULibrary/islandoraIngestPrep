# islandoraIngestPrep
 A series of scripts we use to prepare objects for ingest to Islandora. These scripts have been pulled from other Islandora repos.
 
 1_validate_mods_xml.php
 
This script was found in the Move to Islandora Kit (MIK) repo where it is included as an extra script. We use it to run a final check on our metadata before ingest. This script references a local copy of the MODS 3.5 schema, make sure that they are stored in the same folder. Command structure is:
 
 $php path/to/validate_mods_xml.php path-to-folder-to-run-script-against
 
 2a_islandora_batch_import_setup.sh
 
 Have to track down where I got this script from!
 This script renames tiffs and puts them in the correct hierarchical subfolders by sequential number. Command structure is:
 
 $path/to/islandora-batch-import-setup.sh path-to-folder-to-run-script-against new-subfolder-for-renamed-tiffs
 
 2b_mods_islandora_batch_import_setup.sh
 
 Same as above but adapted to look for xml files. Command structure is:
 
 $path/to/mods_islandora_batch_import_setup.sh path-to-folder-to-run-script-against new-subfolder-for-renamed-xmls
 
 
 
 
 
 
