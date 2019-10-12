# palustris-ra-autocompletearrayinput
An enhanced &lt;AutocompleteArrayInput> component for React-admin, 

This is the original <AutocompleteArrayInput> from React-admin, but with the ability to add new items to the resource from which suggestions are fetched.

In addition to all the props listed in the React-admin documentation, this component can be passed the prop 'dataProvider'. If this is provided, and you set the prop 'limitChoicesToValue' to false, you can type in new tags, and when pressing enter, they will be created by the dataprovider, when created, they will be inserted in the field.

####TODO:
 There is a small delay when you press enter, where the entry is first cleared from the input, then an empty input-chip appears, and only then is the new tag loaded. Would be nice with some sort of placeholder that shows that the new tag is being created. 

