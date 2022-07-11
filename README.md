# Figma<sub>links</sub> Dataset

This repository contains the dataset that was used for the research described
in the Aalto University master thesis "Predicting Links for Mobile GUI Prototyping"
by Christoph A. Johns at Deutsches Forschungszentrum für Künstliche Intelligenz GmbH
(DFKI) Standort ​Niedersachsen.

## Data Format

| Feature Name      | Type   | Content                                                       |
| ----------------- | ------ | ------------------------------------------------------------- |
| link_id           | string | identifier of the link (used in end-user research; -99=None)  |
| source_screen_id  | string | identifier of the source Figma frame (see view hierarchies)   |
| source_element_id | string | identifier of the source Figma element (see view hierarchies) |
| target_screen_id  | string | identifier of the target Figma frame (see view hierarchies)   |
| application_name  | string | name of the Figma application (see view hierarchies)          |
| label             | int    | 0=non-link; 1=link                                            |

This dataset contains 2,403 examples.
