---
title: Roadmap
taxonomy:
    category: docs
    tag: [gantry5]
---

Gantry 5's beta, launching initially for the Joomla platform, is a multi-phase plan that includes key milestones leading up to the full initial release. With the initial beta already available, we are providing this document to clarify which milestones we have planned for the next major beta release, followed by the initial release candidate.

>>> This information is fluid and subject to change as we receive feedback from open beta participants and discover additional opportunities for improvement.

Beta 1 (Current Phase)
-----

| Category                         | Milestone                                                                                                                        | Completed                                             |
| :-----                           | :----                                                                                                                            | :-----:                                               |
| Collections                      | Implement Collections including hidden JSON field.                                                                               | <span style="color:green" class="fa fa-check"></span> |
|                                  | Parent Recognition when Editing Single Item                                                                                      | <span style="color:green" class="fa fa-check"></span> |
|                                  | Implement Validations as it is in Layout Manager.                                                                                | <span style="color:green" class="fa fa-check"></span> |
|                                  | Make Content Savable Regardless of State                                                                                         | <span style="color:green" class="fa fa-check"></span> |
|                                  | Update Form Fields with Values from POST Rather Than the Ones Saved                                                              | <span style="color:green" class="fa fa-check"></span> |
| Presets                          | Load Preset Images                                                                                                               | <span style="color:green" class="fa fa-check"></span> |
|                                  | Hook Up Events for Repopulating Fields with Preset Values                                                                        | <span style="color:green" class="fa fa-check"></span> |
| Clear Cache Button               | Add Clear Cache Button                                                                                                           | <span style="color:green" class="fa fa-check"></span> |
|                                  | Create Method for Calling Ajax with Notification Feedback                                                                        | <span style="color:green" class="fa fa-check"></span> |
| Variations (Module Suffixes)     | Add Template-defined Variations to Selectize Fields for Easy Use Alongside CSS Classes                                           | <span style="color:green" class="fa fa-check"></span> |
| Layout Switcher                  | Ability to Change the Layout Based on Different Configurations or Presets as Well as Clearing the Whole Layout                   | <span style="color:green" class="fa fa-check"></span> |
| Assignments                      | Implement Assignments for Joomla.                                                                                                | <span style="color:green" class="fa fa-check"></span> |
|                                  | Load Correct Configuration Based on Assignment in Front End                                                                      | <span style="color:green" class="fa fa-check"></span> |
| Updater                          | Hook Up Update Button in Joomla.                                                                                                 | <span style="color:green" class="fa fa-check"></span> |
|                                  | Implement Update Button in Hydrogen Theme                                                                                        | <span style="color:green" class="fa fa-check"></span> |
| Language                         | Integrate Language Support Across Gantry                                                                                         |                                                       |
|                                  | Twig support                                                                                                                     | <span style="color:green" class="fa fa-check"></span> |
| Hydrogen                         | Template completed with demo content that showcases what's possible with Gantry 5                                                |                                                       |
| Menu                             | Refine menu items settings to match what Gantry 5 will require, and what the user would need.                                    | <span style="color:green" class="fa fa-check"></span> |
|                                  | Rework the front-end menu JS                                                                                                     |                                                       |
|                                  | Update menu structure to follow the new configuration options                                                                    | <span style="color:green" class="fa fa-check"></span> |
| Builder                          | Create a Builder for Gantry to Generate Packages for Platforms                                                                   | <span style="color:green" class="fa fa-check"></span> |
| Docs                             | Make documentation available covering basic use cases, and add to it throughout the duration of the beta period.                 |                                                       |
| How to get Started               | Create a simple page that documents how to get started with Gantry so that people can play with                                  |                                                       |
|                                  | Document how people should contribute                                                                                            |                                                       |
| File Picker                      | Finish up file picker with upload, ability to remove just uploaded files and implement streams with merged folders/files         |                                                       |
|                                  | We need to handle better streams but it can go to beta 2                                                                         |                                                       |
| HTML/Markdown Field and Particle | A field that inherits from textarea and adds HTML editor and a field that adds Markdown editor - with live previews              |                                                       |
|                                  | Particle that allows edit switching between formats (textarea, HTML, Markdown) with a live preview storing data as compiled HTML |                                                       |

Beta 2
-----

| Category                            | Milestone                                                                              | Completed |
| :-----                              | :----                                                                                  | :-----:   |
| Configurations Page                 | Enable configuration management within Gantry admin (admin, add, delete, rename, copy) |           |
| Menu Editor Particle/Module Support | Drag-and-drop support of Particle and Modules from Menu Editor and Deletion Capability |           |
| Layout Manager                      | Ratio grid calculations for adding/removing particle from grid                         |           |
| Dev/Prod                            | Hook up Dev and Prod Toggler                                                           |           |
| Performance Optimization            | Caching                                                                                |           |
| Menu                                | Base path should be a dropdown listing the menu items based on the Menu Type picked    |           |
|                                     | Start Level should be dropdowns with the proper min/max limit                          |           |
| Security Spoofing                   | Protect admin actions                                                                  |           |
| Style Management                    | Change styles from frontend by session/cookies (ala Gantry 4)                          |           |
| Revert to Default                   | Ability to reset a Configuration parameter to the main default value                   |           |


Beta X
-----

| Category | Milestone                      | Completed |
| :-----   | :----                          | :-----:   |
| Testing  | Test until comfortable with RC |           |

Release Candidate
-----

| Category      | Milestone                                                                                | Completed |
| :-----        | :----                                                                                    | :-----:   |
| Import/Export | Ability to Import/Export data across the whole admin setup (Layout, Menu, Settings, etc) |           |
| Site and Docs | New Gantry website with Docs restyled accordingly                                        |           |
| Builder       | We need a builder for Gantry to generate packages for platforms                          |           |
