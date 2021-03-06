# Changelog

## [Unreleased]

## 18.1.36-beta (2020-03-19)

### Gantt

#### New Features

- `#238591`,`#247663`,`#253913`,`#263052`,`F147148`,`F147548`,`F149280` - Provided support for PDF export which exports Gantt data to PDF format.
- `#258677`,`#264570`,`F149280` - Provided support for manual task scheduling which is used to scheduling the task manually without any dependency.
- `F146634` - Provided support for Resource Unit, which indicate the efficiency of resource by each task and Work mapping support which is used to allocate the total number of works to a task.
- `#245866`,`#252413`,`#262485`,`F147349` - Provided support for the Resource view which is used to visualize the list of tasks assigned to each resource in hierarchical order.

#### Bug Fixes

- `#263236` - Issue on multi-level dragged parent dropped into last index has been fixed.
- `#264099` - Issue in tab key action in edited state is fixed.

## 17.4.46 (2020-01-30)

### Gantt

#### New Features

- `F148795` - Provided custom editor support in dialog edit.
- `F149069` - Provided support to render parent as milestone.
- `#257320` - Provided support for 'zoom to fit' based on visible tasks alone.

#### Bug Fixes

- `F150408` - Baseline tooltip not rendered for milestone tasks has been fixed.
- `#260944` - Issue in preventing taskbar editing has been fixed.

## 17.4.44 (2021-01-21)

### Gantt

#### Bug Fixes

- `#260331` - Typescript declaration issue fixed.

## 17.4.41 (2020-01-07)

### Gantt

#### New Features

- `#253076` - Provided support to focus Gantt on tab key press.

## 17.4.40 (2019-12-24)

### Gantt

#### Bug Fixes

- `F149551` - Handled empty value while editing the numeric edit type field.

## 17.4.39 (2019-12-17)

### Gantt

#### Bug Fixes

- `F147793` - Context menu not closing issue while scrolling on the Gantt element has been fixed.

#### Breaking Changes

- Now `dateFormat`  default value has been changed to null and the value will be updated by given culture. It is also possible to override `dateFormat` property by custom value.

#### New Features

- `#253909` - Provided support for converting a task to milestone by method.
- `F148875` - Provided support for disabling column editing on dialog popup.
- `F146587` - Provided support for taskbarClick event in Gantt.
- `F146585` - Provided support for mouseHover event in Gantt.

## 17.3.30 (2019-12-03)

### Gantt

#### Bug Fixes

- `#253076` - Accessibility issues in Gantt has been fixed.

## 17.3.29 (2019-11-26)

### Gantt

#### Bug Fixes

- `F149069` - Parent taskbar alignment issue while rendering with single milestone child record has been fixed.
- `F149070` - Key navigation disable issue on Tree Grid section has been fixed.
- `#255266` - ParentID field not available in taskData field has been fixed.

## 17.3.28 (2019-11-19)

### Gantt

#### Bug Fixes

- `#253912` - Parent taskbar disappearance issue while deleting all its child records has been fixed.

## 17.3.19 (2019-10-22)

### Gantt

#### Bug Fixes

- `249581` - Browser hangs issue while change schedule mode to year has been fixed.
- `252195` - Issue on forEach method iteration in IE11 has been fixed.

- `252195` - Issue on forEach method iteration in IE11 has been fixed.

## 17.3.14 (2019-10-03)

### Gantt

#### Bug Fixes

- `F147755` - Chart part disappearing issue when splitter position value greater than control width has been fixed.

## 17.3.9-beta (2019-09-20)

### Gantt

#### Bug Fixes

- `#245866` - Alignment issue with `height` property value as `auto` has been fixed.
- `F145725` - Issue with cell editing on newly added record has been fixed.
- `#246761` - Issue while providing date field value with empty string value and invalid date values has been fixed.
- `#247124` - Issue while loading Gantt SB samples in Mobile devices has been fixed.
- `F147329` - Issue in progress calculation with unscheduled tasks has been fixed.
- `F147380` - Issue with prevent edit dialog has been fixed.

- `#245866` - Alignment issue with `height` property value as `auto` has been fixed.
- `F145725` - Issue with cell editing on newly added record has been fixed.
- `#246761` - Issue while providing date field value with empty string value and invalid date values has been fixed.
- `#247124` - Issue while loading Gantt SB samples in Mobile devices has been fixed.

#### New Features

- `#233407` - Provided support to perform Excel and CSV exporting in Gantt.

## 17.2.46 (2019-08-22)

### Gantt

#### Bug Fixes

- `F145733` -  Alignment issue with header and rows on splitter resizing has been fixed.
- `F146641` - Issue with indicators tooltip support has been fixed.

## 17.2.41 (2019-08-14)

### Gantt

#### Bug Fixes

- `#243770` - Issue in date picker with custom format has been fixed.
- `#243238` - Included current edited data in `actionComplete` event arguments.

- `#243238` - Included current edited data in `actionComplete` event arguments.

## 17.2.40 (2019-08-06)

### Gantt

#### Bug Fixes

- #F145936 -  Custom column values not updated in data source on Editing has been fixed.
- Lexical declaration issues in es2015 has been fixed.

## 17.2.36 (2019-07-24)

### Gantt

#### Bug Fixes

- #241781 - Gantt task-data property missing in template data issue has been fixed.

## 17.2.28-beta (2019-06-27)

### Gantt

#### Bug Fixes

- #238228 - Issue while rendering tooltip with smaller duration has been fixed.

#### New Features

- Now Gantt supports context menu to perform various action.
- Provided support to perform timeline zoom in, zoom out and zoom to fit actions in Gantt.
- Provided key interaction support in Gantt.

## 17.1.49 (2019-05-29)

### Gantt

#### Bug Fixes

- #F144145 - Task Id duplication issue while adding new record has been fixed.

## 17.1.47 (2019-05-14)

### Gantt

#### Bug Fixes

- #233041 - Alignment issue with timeline and vertical lines has been fixed.

#### New Features

- #F143360 - Provided support to refresh the `dataSource` dynamically.

## 17.1.43 (2019-04-30)

### Gantt

#### Bug Fixes

- Bug fixes included.

## 17.1.40 (2019-04-09)

### Gantt

#### Bug Fixes

- Internal bug fixes included.

## 17.1.32-beta (2019-03-13)

### Gantt

- **Data sources** – Bind hierarchical or self-referential data to Gantt chart with an array of JavaScript objects or DataManager.
- **Timeline** – Display timescale from minutes to decades easily, and also display custom texts in the timeline units. Timeline can be displayed in either one-tier or two-tier layout.
- **Customizable Taskbars** – Display various tasks in a project using child taskbar, summary taskbar and milestone UI, that can also be customized with templates.
- **Unscheduled tasks** – Support for displaying tasks with undefined start date, end date or duration in a project.
- **Baselines** – Display the deviations between planned dates and actual dates of a task in a project using baselines.
- **CRUD actions** – Provides the options to dynamically insert, delete and update tasks using columns, dialog and taskbar editing options.
- **Task dependency** – Define or update the dependencies between the tasks in a project with four types of task dependencies Finish – Start, Start – Finish, Finish – Finish, Start – Start.
- **Markers and indicators** - Support for displaying indicators and flags along with taskbars and task labels. Also map important events in a project using event marker.
- **Filtering** – Offers filtering the Gantt content using column menu filtering along with toolbar search box.
- **Customizable columns** – Customize the columns and add custom columns to Gantt chart at initialization through column property.
- **Enriched UI** – Support for Material, bootstrap, fabric and high contrast themes along with other UI options like holidays support, vertical and horizontal grid lines support and so on.
- **Localization** - Provides inherent support to localize the UI.


