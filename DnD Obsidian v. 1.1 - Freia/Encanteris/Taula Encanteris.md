---

database-plugin: basic

---

```yaml:dbfolder
name: Taula d'encanteris
description: Taula d'encanteris
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    width: 202
    isSorted: false
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Escola:
    input: text
    accessorKey: Escola
    key: Escola
    id: Escola
    label: Escola
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 134
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Nivell:
    input: text
    accessorKey: Nivell
    key: Nivell
    id: Nivell
    label: Nivell
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: 1
    width: 158
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Practicants:
    input: text
    accessorKey: Practicants
    key: Practicants
    id: Practicants
    label: Practicants
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 414
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: false
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: query
  source_form_result: "FROM \"Encanteris/Llista d'Encanteris\""
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 200
  font_size: 13
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```