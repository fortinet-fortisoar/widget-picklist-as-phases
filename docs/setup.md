| [Home](../README.md) |
|----------------------|
# Installation

1. To install a widget, click **Content Hub** > **Discover**.
2. Search for the **Picklist as Phases** widget.
3. Click the **Picklist as Phases** widget card.
4. Click **Install** on the lower part of the screen to begin installation.

# Configuration

The following table lays out necessary information to customize this widget.

| Fields            | Description                                                                                                                                                                                                                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Title             | Specify a title for the picklist as phases.                                                                                                                                                                                                                                                       |
| Choose a Picklist | Select a picklist field to display its values in the visual representation.                                                                                                                                                                                                                       |
| Read Only         | Select this checkbox to display the flow diagram in a *read-only* mode. In *read-only* mode, clicking the visualization has no effect.<br /><br />Clear this checkbox to disable *read-only* mode. In this mode, clicking a picklist value in the visualization, updates the record in real-time. |

## Add or Remove Picklist Phases

You can add or remove phases displayed by this widget.

1. Navigate to <picture><source media="(prefers-color-scheme: dark)" srcset="./res/icon-settings-light.svg"><source media="(prefers-color-scheme: light)" srcset="./res/icon-settings-dark.svg"><img alt="" src="./res/icon-settings-dark.svg"></picture> <picture><source media="(prefers-color-scheme: dark)" srcset="./res/icon-chevron-light.svg"><source media="(prefers-color-scheme: light)" srcset="./res/icon-chevron-dark.svg"><img alt="" src="./res/icon-chevron-dark.svg"></picture> **Modules**.

2. Select a *module* that uses the widget **Picklist as Phases**. For example. *Incidents*.

3. Click the tab **Fields Editor**.

4. Find and select the *`Phases`* field.

5. Under the *Properties* pane on the right, select the box **Configure Picklist Item Visibility**.

    - Select **Visible** against a phase for it to be visible in the module record's detailed view.
    - Select **Disabled** against a phase to disable selecting the phase in the module record's detailed view.
    - Select **Hidden** against a phase to hide it in the module record's detailed view.
    - Select **Conditionally Visible** against a phase for it to be visible in the module record's detailed view, *based on defined conditions*.
    - Select **Conditionally Enabled** against a phase to enable selecting the phase in the module record's detailed view., *based on defined conditions*.

6. Click **Apply** <picture><source media="(prefers-color-scheme: dark)" srcset="./res/icon-chevron-light.svg"><source media="(prefers-color-scheme: light)" srcset="./res/icon-chevron-dark.svg"><img alt="" src="./res/icon-chevron-dark.svg"></picture> **Save** <picture><source media="(prefers-color-scheme: dark)" srcset="./res/icon-chevron-light.svg"><source media="(prefers-color-scheme: light)" srcset="./res/icon-chevron-dark.svg"><img alt="" src="./res/icon-chevron-dark.svg"></picture> **Publish All Modules** to save your changes.

> [!NOTE]
> The conditions that affect the visibility and selection of a phase appear under that phase once **Conditionally Visible** or **Conditionally Enabled** is selected.


# Next Steps

| [Usage](./usage.md) |
|---------------------|
