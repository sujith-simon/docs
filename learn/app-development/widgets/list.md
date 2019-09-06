---
title: "List"
id: ""
---

**List widget** provides a list view of items from a data source. List data can be obtained from various Services like database, queries or web services through Variables. The list provides a variety of flexible templates for defining the display format of each item.

While designing the List following features can be set:

- define the number of items to be displayed per row,
- group data by the field of the underlying data source,
- order the data by the fields of the underlying data source,
- enable multiple selections of items in the list - for a multi-selection user can:
    - To select consecutive items, click the first item, press and hold down SHIFT, and then click the last item. Or press and hold down SHIFT, and use arrow keys to select next item.
    - To select nonconsecutive items, press and hold down CTRL, and then click each item.
    - For mobile: Press and hold the item for a second which enables multi-select then tap on other items to select more items in a List. (default behavior nonconsecutive selection)
- set the pagination style for multi-page data
- enable reorder property can be used to allow the user to reorder the list items at runtime
- list items can be selected by the user at run-time either
    - by a simple click of the mouse on the item or
    - _Up_ and _Down arrows_ can be used to traverse the list items. Pressing enter key on any focused item will select the item.

[![](../../assets/LL_Features.png)](../../assets/LL_Features.png)

Data Source >

[1\. Live & Data Widgets](/learn/app-development/widgets/widget-library/#data-live)

- [1.1 Cards](/learn/app-development/widgets/datalive/cards/)
- [1.2 Data Table](/learn/app-development/widgets/datalive/data-table/)
- [1.3 Form](/learn/app-development/widgets/datalive/form/)
- [1.4 List](/learn/app-development/widgets/datalive/list/)
    - [i. Data Source](/learn/app-development/widgets/datalive/list/list-data-source/)
    - [ii. Templates](/learn/app-development/widgets/datalive/list/list-templates/)
        - [○ Action List](/learn/app-development/widgets/datalive/list/list-templates/#action-list)
        - [○ Contact List](/learn/app-development/widgets/datalive/list/list-templates/#contact-list)
        - [○ Email List](/learn/app-development/widgets/datalive/list/list-templates/#email-list)
        - [○ Media List](/learn/app-development/widgets/datalive/list/list-templates/#media-list)
    - [iii. List Configuration](/learn/app-development/widgets/datalive/list/configuration/)
        - [○ Items per row](/learn/app-development/widgets/datalive/list/configuration/#items-per-row)
        - [○ Grouping & Ordering](/learn/app-development/widgets/datalive/list/configuration/#grouping-ordering)
        - [○ Pagination](/learn/app-development/widgets/datalive/list/configuration/#pagin)
        - [○ Message](/learn/app-development/widgets/datalive/list/configuration/#message)
    - [iv. List Behavior Settings](/learn/app-development/widgets/datalive/list/behavior-settings/)
        - [○ Selection Limit](/learn/app-development/widgets/datalive/list/behavior-settings/#selection-limit)
        - [○ Multiselect](/learn/app-development/widgets/datalive/list/behavior-settings/#multiselect)
        - [○ Item Reordering](/learn/app-development/widgets/datalive/list/behavior-settings/#item-reordering)
    - [v. Properties, Events & Methods](/learn/app-development/widgets/datalive/list/list-properties-events-methods/)
        - [○ Properties](/learn/app-development/widgets/datalive/list/list-properties-events-methods/#properties)
        - [○ Events](/learn/app-development/widgets/datalive/list/list-properties-events-methods/#events)
        - [○ Methods](/learn/app-development/widgets/datalive/list/list-properties-events-methods/#methods)
    - [vi. Use Cases](/learn/app-development/widgets/datalive/list/list-use-cases)
- [1.5 Live Form](/learn/app-development/widgets/datalive/live-form/)
- [1.6 Live Filter](/learn/app-development/widgets/datalive/live-filter/)