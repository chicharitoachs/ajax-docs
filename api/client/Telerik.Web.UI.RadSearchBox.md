---
title: Telerik.Web.UI.RadSearchBox
page_title: Client-side API Reference
description: Client-side API Reference
---

# Telerik.Web.UI.RadSearchBox : Telerik.Web.UI.RadWebControl 

## Methods

### set_enableAutoComplete

Sets whether the AutoComplete functionality of the SearchBox is enabled

#### Parameters

##### value `Boolean`

 Indicates whether the AutoComplete functionality of the SearchBox is enabled. 

#### Returns

`None` 

### get_dropDownElement

Gets the root DOM element of the RadSearchBox's drop-down.

#### Parameters

#### Returns

`Element` The root DOM element of the RadSearchBox

### set_emptyMessage

Sets the value of the RadSearchBox's EmptyMessage property.

#### Parameters

##### value `String`

value

#### Returns

`None` 

### get_text

Gets the text in the input field.

#### Parameters

#### Returns

`String` The text in the input field.

### get_inputElement

Gets the input DOM element of the RadSearchBox.

#### Parameters

#### Returns

`Element` The input DOM element of the RadSearchBox. 

### repaint

Refreshes the RadSearchBox UI

#### Parameters

#### Returns

`None` 

### get_filter

Gets the Filter criteria of RadSearchBox.

#### Parameters

#### Returns

`Telerik.Web.UI.SearchBoxFilter` 

### get_emptyMessage

Returns the value of the RadSearchBox's EmptyMessage property.

#### Parameters

#### Returns

`String` The value of the RadSearchBox

### set_clientTemplate

Sets the value of the RadSearchBox's ClientTemplate property.

#### Parameters

##### value `String`

value

#### Returns

`None` 

### get_clientTemplate

Returns the value of the RadSearchBox's ClientTemplate property.

#### Parameters

#### Returns

`String` The value of the RadSearchBox

### get_enabled

Gets the value of the Enabled property

#### Parameters

#### Returns

`String` 

### get_childListElement

Gets the UL DOM element of the RadSearchBox's drop-down

#### Parameters

#### Returns

`Element` The UL DOM element of the RadSearchBox

### saveClientState

Saves the client state to the client state hidden field

#### Parameters

#### Returns

`None` 

### query

If AutoComplete is enabled,the search string exists and it is longer than the min filter length set, a search operation is performed. The second parameter defines whether all results should be shown in the drop-down.

#### Parameters

#### Returns

`None` 

### get_searchContext

Gets the SearchContext's object

#### Parameters

#### Returns

`Telerik.Web.UI.SearchContext` 

### get_enableAutoComplete

Gets a value indicating whether the AutoComplete functionality of the SearchBox is enabled

#### Parameters

#### Returns

`Boolean` Value indicating whether the AutoComplete functionality of the SearchBox is enabled

### clear

Clears the search results and closes the drop-down.

#### Parameters

#### Returns

`None` 

### set_enabled

Toggles the enabled state of the RadSearchBox.

#### Parameters

#### Returns

`None` 

### set_filter

Sets the Filter criteria of RadSearchBox.

#### Parameters

##### value `Telerik.Web.UI.SearchBoxFilter`

 The Filter criteria. 

#### Returns

`None` 

### commitChanges

Writes the changes to the searchBox that were made since a previous call to trackChanges, so that they are preserved over post-backs.

#### Parameters

#### Returns

`None` 

### get_buttons

Gets a collection with all buttons

#### Parameters

#### Returns

`Telerik.Web.UI.SearchBoxButtonCollection` 

## Events

### load

Occurs after the RadSearchBox has been fully initialized on the client-side. 

#### Event Data

##### sender `Telerik.Web.UI.RadSearchBox`

The RadSearchBox instance raised the event.

##### args `Sys.EventArgs`

The arguments of the Load event.


### search

Occurs when the search button is clicked, Enter is pressed, or an item from the searchBox dropdown is clicked.

#### Event Data

##### sender `Telerik.Web.UI.RadSearchBox`

The RadSearchBox instance raised the event.

##### args `Telerik.Web.UI.SearchBoxSearchEventArgs`

The arguments of the Search event.

dataRequesting

### dataRequesting

Occurs when a new text is entered and a request for items is about to be sent. 

#### Event Data

##### sender `Telerik.Web.UI.RadSearchBox`

The RadSearchBox instance raised the event.

##### args `Telerik.Web.UI.SearchBoxDataRequestingEventArgs`

The arguments of the DataRequesting event

### buttonCommand

Occurs when a new text is entered and a request for items is about to be sent. 

#### Event Data

##### sender `Telerik.Web.UI.RadSearchBox`

The RadSearchBox instance raised the event.

##### args `Telerik.Web.UI.SearchBoxButtonCommandEventArgs`

The arguments of the ButtonCommand event