# Outlook add-in API Preview requirement set

The Outlook add-in API subset of the JavaScript API for Office includes objects, methods, properties and events that you can use in an Outlook add-in.

> **Note**: This documentation is for a **preview** [requirement set](tutorial-api-requirement-sets.html). This requirement set is not fully implemented yet, and clients will not accurately report support for it. You should not specify this requirement set in your add-in manifest. Methods and properties that are introduced in this requirement set should be individually tested for availability before using them.

The Preview Requirement set includes all of the features of [Requirement set 1.5](../1.5/index.md). 

## Features in preview

The following features are in preview.

- [Event.completed](Event.md#completed) - A new optional parameter `options`, which is a dictionary with one valid value `allowEvent`. This value is used to cancel execution of an event.

## Additional resources

- [Outlook add-ins](../../../docs/outlook/outlook-add-ins.md)
- [Outlook add-in code samples](https://dev.outlook.com/MailAppsGettingStarted/Samples)
- [Get started](https://dev.outlook.com/MailAppsGettingStarted/GetStarted)
