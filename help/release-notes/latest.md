---
title: View the current Customer Journey Analytics release notes
description: Latest CJA release notes
---

# Current Customer Journey Analytics release notes

| Feature | Description | Targeted Date |
| ----------- | ---------- | ----- |
|[!UICONTROL Persistence] options for binding dimensions and binding metrics| When creating or editing a data view, you can bind the persistence of a dimension to another dimension or metric. This concept is known as _merchandising_ in Reports & Analytics, and is now supported in CJA. [Learn more](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#binding-dimension)| January 19, 2022 |
| [!UICONTROL First Known] and [!UICONTROL Last Known] allocation models | These two new allocation models take the first or last observed value for a dimension within a specified persistence scope (session, person, or custom time period with look-back.) Then they apply the allocation model to all events within the specified scope. [Learn more](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-settings/persistence.html#allocation-settings)| January 19, 2022 |
| [!UICONTROL PersonID] and [!UICONTROL PersonID namespace] as dimensions | Exposes the `personID` (or `customerID`, or whatever ID you are using for merging data sets in a connection) as a dimension in data views. This enhancement makes it easier for you to include the `personID` as a dimension in your data view by pulling it in from the connection. [Learn more](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dataviews/component-reference.html?lang=en#optional-standard-components)| January 19, 2022|

{style="table-layout:auto"}

>[!MORELIKETHIS]
>[Customer Journey Analytics documentation updates](/help/doc-changes.md)