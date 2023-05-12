# Release notes

In this section, we have summarized the changes to Umbraco Workflow released in each version. Each version is presented with a link to the [Workflow issue tracker](https://github.com/umbraco/Umbraco.Workflow.Issues/issues) showing a list of issues resolved in the release. We also link to the individual issues themselves from the detail.

If there are any breaking changes or other issues to be aware of when upgrading they are also noted here.

## Release History

In this section, you can find the release notes for each version of Umbraco Workflow. For each major version, you can find the details about each release.

<details>

<summary>Version 11</summary>

#### [11.2.0](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F11.2.0) (May 9th 2023)

* **FEATURE** => Introduces [approval thresholds](getting-started/approval-thresholds.md).

#### [11.1.2](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F11.1.2) (April 18th 2023)

* **FEATURE** => Introduces optional configuration for mandatory comments
* **FEATURE** => Modifies content lock to allow edits until the first workflow action is completed
* Ensure notifications inheriting from ObjectNotification have a public Target property [#13](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/13)
* Improve UI notification when publish fails on workflow completion
* Improve logged messages when publish fails on workflow completion
* Renames `/App_Plugins/Backoffice` to `/App_Plugins/backoffice` for Linux file path resolution [#14](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/14)
* Ensure the `canEdit` flag is set correctly when the Workflow application state changes
* Ensure canceled workflows are never marked as actioned by admin when canceled by the original change requestor, regardless of their admin status

#### [11.1.1](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F11.1.1) (March 8th 2023)

* Fixes bug in workflow detail overlay [#12](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/12)

#### [11.1.0](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F11.1.0) (March 7th 2023)

* **FEATURE** => History cleanup and retention policies
* Fixes tree collision issue when multiple trees share class names [#11](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/11)
* Ensure the version number is included in the package manifest
* Improve UI/UX in submit workflow component
* Ensure notification emails are sent when a task is rejected [#9](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/9)
* Remove `async void` signatures
* Extends valid local license environment names
* Ensure signalR hub is not re-initialized once running

</details>

<details>

<summary>Version 10</summary>

#### [10.2.0](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F10.2.0) (May 9th 2023)

* **FEATURE** => Introduces [approval thresholds](getting-started/approval-thresholds.md)

#### [10.1.2](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F10.1.2) (April 18th 2023)

* **FEATURE** => Introduces optional configuration for mandatory comments
* **FEATURE** => Modifies content lock to allow edits until the first workflow action is completed
* Ensure notifications inheriting from ObjectNotification have a public Target property [#13](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/13)
* Improve UI notification when publish fails on workflow completion
* Improve logged messages when publish fails on workflow completion
* Renames `/App_Plugins/Backoffice` to `/App_Plugins/backoffice` for Linux file path resolution [#14](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/14)
* Ensure the `canEdit` flag is set correctly when the Workflow application state changes
* Ensure canceled workflows are never marked as actioned by admin when canceled by the original change requestor, regardless of their admin status

#### [10.1.1](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F10.1.1) (March 8th 2023)

* Fixes bug in workflow detail overlay [#12](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/12)

#### [10.1.0](https://github.com/umbraco/Umbraco.Workflow.Issues/issues?q=is%3Aissue+is%3Aclosed+label%3Arelease%2F10.1.01) (March 7th 2023)

* **FEATURE** => History cleanup and retention policies
* Fixes tree collision issue when multiple trees share class names [#11](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/11)
* Ensure the version number is included in the package manifest
* Improve UI/UX in submit workflow component
* Ensure notification emails are sent when a task is rejected [#9](https://github.com/umbraco/Umbraco.Workflow.Issues/issues/9)
* Remove `async void` signatures
* Extends valid local license environment names
* Ensure signalR hub is not re-initialized once running

</details>