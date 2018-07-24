# Processing Data

The goal of this document is to clearly outline how the various parts of a record's data show up in the interface of the DC app. To do so, we will break down the various components of a record into their visual representations in the UI.

> We are using the UI for the VHEC version as the basis of this document. 

### type
The type of an object doesn't explicitly show up in the UI, however, the processing and final representation is informed by this property.

#### Filtering
The most common use of the `.type` property is to filter a menu. In the images below you'll see 4 different cases of filtered content.

##### Main Menu Filtering
When the main menu is filtered, its excluded elements are omitted from view and the remaining elements animate into new positions.

![Main Menu with All Elements](images/mainMenuFiltering.png)

##### Submenu Filtering
When a sub menu is filtered, its excluded records are still visible – but with a significantly reduced opacity.

![Main Menu filtered All, Artefacts, Themes (left to right)](images/submenuFiltering.png)

### title
The title appears at the top of a record's text view. It is a larger font and wraps to become multi-line if needed.

![The location of the Title](images/title.png)

### subtitle
If a subtitle is present, it appears directly underneath the title in a smaller font (though still larger than the bodt content font).

![The location of the Subtitle](images/subtitle.png)

### content
If present, the primary body content appears below the subtitle.

![The location of the content](images/content.png)

### location
If present, the location is added as a small line of text between the title and subtitle.

![The location of the location](images/location.png)

### date
If present, the date is added after the location (separated by a comma).

![The location of the date](images/date.png)

### credit
If present, the credit appears at the bottom of the body content and uses a small font.

![The location of the credit](images/credit.png)

### imagesAndCaptions 
Images will be presented in the left-hand portion of the screen. If there are multiple images, the will be added to a scrollable collection view and a page counter will appear at the bottom of the view.

> There should always be at least 1 image – however a placeholder could be used if needed.

![An image in the carousel](images/image1.png)
![An image in the carousel](images/image2.png)
![An image in the carousel](images/image3.png)
![An image in the carousel](images/image4.png)
![An image in the carousel](images/image5.png)

### relatedItems
Related items are listed in a separate view from the record, accessible via an **Explore Further** button that appears only if there is at least 1 related item.

![Related Items](images/relatedItems.png)