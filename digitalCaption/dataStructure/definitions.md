# Definitions
Internally, we refer to a record in the DC app as an `Entity`. An entity is a class of object that has the  elements listed below.

> See [Preparing Data](preparingData.md) for more detail on how to work with these definitions.

> See [Usage](usage.md) for more detail on where and how things show up in the app's user interface.

### id 
`Integer`

This is a unique number that the application uses internally to search for and load the entity. Typically, it is referred to in the **relatedItems** of another entity (i.e. an entity wouldn't typically be related to itself).

### type
`String`

This is the name of the type of record that the current entity represents. Currently, there are the following types

* object
* person
* video
* theme
* image
* unknown

> It is critical that this field be spelled correctly when entering data into the application's plist.

### title
`String`

The title of the entity.

### shorttitle
`String`

An alternate title that can be used in smaller UI elements.

### subtitle
`String`

The subtitle of the entity. This can be a multi-line piece of text.

### content
`String`

The primary body content for a record. This can be a multi-line piece of text.

### location
`String`

A string representing the location of the record.

### date
`String`

A string representing the date of the record.

### credit
`String`

A string representing credits for the record (e.g. contributors, donated by, etc.).

### imagesAndCaptions 
`[String : String]`

A set of 2-part entries that represent an image by it's file name, as well as a caption for the image.

For example, when specifying images you would provide:

`fileName: recordImage01.png`, and

`caption: This is an image of a record, taken from a camera, on a quiet day.`

### videoFilenames
`[String : String]`

A set of 2-part entries that represent an image by it's file name, as well as a caption for the image.

For example, when specifying images you would provide:

`fileName: video01.mov`, and

`caption: This is an interview with John.`

### relatedItems

A set of 2-part entries that represent the connections from the current record to other records.

Separate connections based on their type, like so:

`people: [0, 1, 3, 4]`

`themes: []`

`videos: [6]`

`objects: [12, 34, 2, 15]`