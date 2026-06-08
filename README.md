# Stormwater Culvert Screening Dataset

This repository contains self-created synthetic input files for stormwater culvert asset screening, source reconciliation, hydraulic-condition screening, and maintenance-priority classification.

## Repository contents

- `stormwater_culvert_asset_register.csv`  
  Primary culvert asset register containing asset identifiers, culvert geometry, material, invert elevations, blockage observations, condition scores, overtopping status, backwater depth, inspection metadata, and maintenance status.

- `storm_event_and_maintenance_log.csv`  
  Storm-response, work-order, maintenance-closure, CCTV-follow-up, and geometry-follow-up evidence linked to selected culvert assets.

- `culvert_field_observation_index.csv`  
  Field-observation index containing inspection evidence for blockage, sediment depth, geometry verification, outlet condition, overtopping evidence, backwater depth, and accessibility.

- `culvert_screening_rules_and_source_hierarchy.pdf`  
  Controlling rule document defining source hierarchy, geometry derivation rules, slope validation, blockage and overtopping rules, maintenance chronology, priority classification, follow-up logic, and traceability requirements.

## Dataset description

The files are synthetic and self-created for controlled evaluation of rule-based engineering reconciliation. They are designed to resemble a stormwater culvert asset-management workflow, but they do not represent real municipal records, real field measurements, real infrastructure assets, private property, public-agency files, or confidential operational data.

The dataset is intended for tasks requiring cross-file reconciliation, source hierarchy application, calculation auditability, validation-rule checking, maintenance-priority classification, and audit-ready reporting.

## Technical grounding

The file structure and parameter ranges were designed to be technically plausible for culvert and stormwater asset-management workflows. Public culvert hydraulic-design, culvert inspection, blockage-management, and stormwater operation-and-maintenance guidance were used only as general technical background. No third-party tables, records, copyrighted manual text, municipal datasets, or public-agency asset records were copied into these files.

## License

This repository is released under the CC0 1.0 Universal Public Domain Dedication. The files may be copied, modified, distributed, and used for any purpose, including commercial use, without permission.

## Data-use note

Because the dataset is synthetic, it must not be used for real infrastructure design, regulatory reporting, public-safety decisions, flood-risk assessment, asset-maintenance planning, or engineering certification. It is intended only for controlled testing, benchmarking, training, and evaluation.
