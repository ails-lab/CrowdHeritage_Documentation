# CrowdHeritage Introduction

## What is CrowdHeritage?
CrowdHeritage is an online crowdsourcing platform for enriching the metadata of digitized cultural heritage material. The platform was developed under the Europeana Generic Services project [CrowdHeritage](https://pro.europeana.eu/project/crowd-heritage).

# Navigating CrowdHeritage Website

## Sign in / Sign up
Visit `https://crowdheritage.eu/` and click on the **Sign in** button on the top right. A pop-up will appear asking for your preferred sign in method, or giving you the option to create an account if you don't already have an account.
You can browse thought the Campaigns and Collections without logging in, but you will not be able to contribute.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image1.jpg" width="auto">

## Choosing a Campaign
Once you have entered your credentials, you will now be able to see your username on the top right.
Scroll down through the Campaign list on the main page and enter any Campaign you would like to contribute to. In this example, we will select the *Scenes and People from China* Campaign.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image2.jpg" width="auto">

## Entering a Collection
Each Campaign consists of one or more Collections. You can view those Collections under the Campaign information, by scrolling down further. Each listed Collection has a title, the number of items it contains, the name of its curator and a thumbnail made of some sample images form that Collection. Select the collection you are interested in and click on it to enter it.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image3.jpg" width="auto">

## Selecting an Item
Within the Collection, you will be presented with a description of that Collection and the Items it contains. You can choose which items you want to see, by selecting one of the *ALL ITEMS*, *MY ANNOTATED ITEMS*, *NOT ANNOTATED ITEMS* options on the selector.

<img src="_media/collection-editor-view-options.png" width="auto">

You can also sort the Items by *CONTRIBUTIONS COUNT* to focus on the collection items with the least contribution.

<img src="_media/collection-editor-sort-by-contribution.png" width="auto">

By hovering on the thumbnail of an Item, you can either click on it to enter the Item or click on the *eye* icon on the top left of each image in order to preview it - like so:

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image5.jpg" width="auto">

If you want to create annotations for am Item, click on it to access its page.

## Annotating an Item
There are three annotation types one can add to an Item.

1. **Tags**
2. **Comments**
3. **Geotags**
4. **Colortags**
5. **Imagetags**

### 1. TAGS
The first annotation type on the right sidebar are **tags**. Tags are predefined categories that can describe an Item. You can either *Upvote*, *Downvote* or *Remove* an existing tag by clicking the thumbs-up, thumbs-down or "X" icon next to that tag, respectively.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image6.jpg" width="auto">

There is also the option to add a new tag by typing it in the input field. Since tags are predefined, once a user starts inserting text inside the input field, a list of relevant tags will appear in a drop-down list for the user to select most appropriate one.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image7.jpg" width="auto">

### 2. COMMENTING
The second annotation type is a **comment**. Comments are text annotations, just like tags, with the essential difference that they are a free-text strings instead of predefined strings. If a user feels that the information contained in the tags is not adequate, they can add a custom text that conveys the information they want to add as an annotation.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image8.jpg" width="auto">

Comments can also be *Upvoted*, *Downvoted* or *Removed* by other users. 

### 3. GEOTAGGING
**Geotagging** is a special kind of tag that refers specifically to a location. A user can start typing the location name in the input field under the map, and then select the appropriate location from the suggested ones on the drop-down below. Geotags can also be validated by the supported feedback methods (upvoting or percentage rating).

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image9.jpg" width="auto">

### 4. COLORTAGGING

**Colortagging** is a special kind of tag that refers to color. A user can select the color from a predefined color pallette. Colortags can also be validated by the supported validation methods (upvoting or percentage rating).

<img src="_media/annotating-colortagging.png" width="auto">

### 5. IMAGETAGGING

**IMAGETAGGING** is a special kind of tag that refers to tagging images. A user can see the original image along with algorithm-generated ones (e.g. by Super-Resolution models). The user can then click *Compare* to start the comparison.

<img src="_media/annotating-image-tagging.png" width="auto">

The original image is displayed at the top of the screen and below it (from left to right) the first algorithm-generated image, the original image in the same size as the computer-generated ones and the second algorithm-generated image. The user can zoom in a smaller window of the original image at the top and automatically the images at the bottom are displaying this smaller window. If the user wants to see the full images again he can stop the zoom process.

<img src="_media/annotation-image-tagging-zoom.png" width="auto">

The user can then rank the images by clicking the image that most reliably sharpens and enlarges the original image. Then, we move on to the next comparison (6 comparisons in total). When the user finishes with all the comparisons, they submit them. After the submit, the user can see the results of their comparisons in the item view, where the number of “victories” are displayed for each algorithm.

<img src="_media/annotation-image-submitted-ranking.png" width="auto">


# Campaign Organizers' Tools
As a Campaign Organizer you have the additional capabilities to create and edit Campaigns, Collections, Vocabularies and Usergroups. As well as access to Campaign statistics and other moderating tools. We will first go through the **Dashboard** and then take a look on the **Moderating tools**.

## Dashboard
To access the dashboard, a signed-in Campaign Organizer should click on his username on the top right of the Navbar and then click on *Dashboard*.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image10.jpg" width="auto">

Within the Dashboard, a user can view all the Campaigns, Collections, Vocabularies and Usergroups - each under the respective tab - as well as create new ones or edit existing ones.

<img src="_media/dashboard-editors.png" width="auto">

### Create/Edit Campaign
To create a new Campaign, click on the *+ New Campaign* button on the top right of the **Campaigns** tab (as seen on the above screenshot). A sidebar will appear on the right, asking to choose the Campaign's shortname. If the shortname already exist, you will be notified to select another.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image12.jpg" width="auto">

Once you click on the *Create* button, your new Campaign will appear on the Campaigns list and you can click on it to edit any or all of the *Campaign Details*. You can also configure the *Campaign Annotating*, *Campaign Access* and *Campaign Base Annotations* sections.

#### Campaign Details Section

This is a long list of input fields like: Visibility, Start/End Dates, Input Language, Banner, Description and so on. There are buttons to *Preview* and/or *Save* the Campaign after you are done.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image13.jpg" width="auto">

The input fields marked as *(multilingual)* can be edited in multiple languages by selecting their appropriate language on the **Input Language** dropdown menu on top. This way, whenever a user views a Campaign, it will appear in their own language if the Campaign Owner has added the relevant text in the user's language.

#### Campaign Annotating Section

Here the user can target the collections they want to annotate.
The can also select the *campaign purpose, orientation, feedback method and motivations* (see "Annotating an Item").

In case the user has selected *Tagging* as the campaign motivation they can set the *Semantic Tagging Vocabularies* to be used in the campaign.
And if they want to connect different vocabularies per tag type, they can use *Semantic Tag Groupings*.

<img src="_media/campaign-editor-campaign-annotating.png" width="auto">

#### Campaign Access Section

Here, the user can select the campaign moderators and the usergroups they want to target for the campaign. Both fields offer auto-complete functionality.

<img src="_media/campaign-editor-campaign-access.png" width="auto">

#### Campaign Base Annotations Section

In this section the user can import annotations to be used as *campaign base annotations*. Then they can run the campaign based on these annotations. The annotations can either be imported from MINT or by uploading a JSON with the appropriate format.

<img src="_media/campaign-editor-campaign-base annotations.png" width="auto">



### Create/Edit Collection
Creating a Collection is a similar process as creating a Campaign. The user has to navigate on the **Collections** tab and click on the *+ New Collection* button. 

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image14.jpg" width="auto">

Then fill the requested information, and select the newly created Collection to import Items in.

<img src="_media/collection-editor-import.png" width="auto">

There are four options to import items when clicking the *Import Items* button.

1. Europeana Gallery - Import a whole gallery by entering the Europeana Gallery ID for that gallery
2. Europeana Search - Import a selected number of Items that contain a desired Search Term.
3. Europeana Items - Import specific Europeana Items by giving a list of those Items' URLs.
4. MINT Dataset - Import specific MINT Items by giving the MINT dataset's URL.


### Create/Edit Vocabulary
Creating a Vocabulary is a similar process. The user has to navigate on the **Vocabulary** tab and click on the *+ New Vocabulary* button. Name the vocabulary and click on the edit icon in order to add terms to it.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image16.jpg" width="auto">

The terms can be either added one-by-one or batch imported as a CSV. They can also be Downloaded as a CSV. You can view all options by clicking *Manage Terms*.
<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image17.jpg" width="auto">

### Create/Edit Usergroup
Lastly, we have Usergroups which follow a similar process. The user has to navigate on the **Usergroup** tab and click on the *+ New Usergroup* button to give the usergroup a name and description.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image18.jpg" width="auto">

Once the group is created, click on the edit icon and add users in that group under the *Manage Users* section on the right sidebar.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image19.jpg" width="auto">

## Moderate Campaign
When a Campaign Owner visits a Campaign page, a button named "Moderate Campaign" appears to him between the Campaign information and the Campaign's Collections.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image20.jpg" width="auto">

This button navigates to a Campaign Validation page which provides some tools that only a Campaign Owner has access to.

<img src="_media/campaign-moderate.png" width="auto">

### Statistics
By clicking the *Statistics* button, the Campaign Owner can view some statistics about that specific Campaign, like total items, total annotations, annotation upvotes etc.

<img src="_media/campaign-moderate-statistics.png" width="auto">

### Validation
By clicking the *Validation* button the Campaign Owner can validate the campaign annotations. By typing or selecting one of the available tags, like "Bass saxophone", a list of Items annotated with the chosen tag will appear.

<img src="_media/campaign-moderate-validation.png" width="auto">

### Publish Criteria
The *Publish Criteria* button opens a pop-up page which allows the Campaign Owner to configure the criteria the published annotations need to fulfil.

<img src="https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image24.jpg" width="auto">

### Data Export
By clicking the *Data Export* button, the Campaign Owner can see the two campaign export options, *EXPORT CONTRIBUTORS* and *EXPORT ANNOTATIONS*.

These two buttons allow the Campaign Owner to export the contributing users and the annotations of the Campaign, as a JSON file.

<img src="_media/campaign-moderate-data-export.png" width="auto">

#### Export Annotations for MINT
The MINT tool supports controlled import of the annotations exported from CrowdHeritage.

Once you import the exported annotations in MINT the Campaign Owner can see a statistical overview of the annotations and filter the annotations you want to ingest into MINT by various options. For detailed information check the tool's respective documentation.



<!-- 
local image example URL: "./_media/image1.jpg"
live image example URL: "https://raw.githubusercontent.com/ails-lab/CrowdHeritage_Documentation/main/docs/_media/image1.jpg"
-->
