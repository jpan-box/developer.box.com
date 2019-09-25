---
rank: 3
related_endpoints:
  - delete_folders_id
related_guides:
  - basics/folders/create-a-folder
required_guides:
  - basics/folders/create-a-folder
alias_paths: []
---

# Delete a folder

To remove a folder in Box you will need to provide our API with the ID of the folder.

<Samples id='delete_folders_id' />

<Message>
  # Deleting non-empty folders
  
  When deleting a folder, you can pass in the `recursive` parameter to
  force a folder to be deleted even if it is not empty. This will delete all
  items within this folder, including any of their descendants.
</Message>