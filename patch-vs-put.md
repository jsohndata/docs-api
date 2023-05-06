# Patch vs Put

## Modifing resources
* `PUT` is a method used to completely replace the entire resource with a new version.
* `PATCH` is used to update parts of an existing resource without affecting the other properties.

<br>

## Handling missing resources
* `PUT` will create a new resource with the given identifier.
* `PATCH` will return an error since there is no existing resource to update.