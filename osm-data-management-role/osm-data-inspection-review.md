# OSM Data Inspection / Review

## OSM Data Inspection / Review

This unit will teach how to quickly assess the state of the OSM data and whether or not data needed by first responders or aid organizations can be obtained via OSM and/or HOT Activation.

### Items to Read

#### LearnOSM: Reviewing the Data

[The Reviewing OSM Data module in LearnOSM](http://learnosm.org/en/coordination/review/) provides a great resource for Data Role folks and touches on how you would support the Reporting and Validation and Usability roles in providing high quality data.

### Rapid Inspection

At least one Activator in the Data role will be inspecting the data from before the Activation is declared until its conclusion, sometimes that inspection needs to be done quickly.

#### Initial Inspection

Sudden onset events require rapid assessment of the situation and delaying the decision to activate could have serious impact on the quickness of aid being delivered to those in need. In any situation the Data Activator\(s\) need to be able quickly assess the area of interest for completeness of the map for [Common Operational Datasets \(COD\) or Fundamental Operational Datasets \(FOD\)](http://learnosm.org/en/beginner/glossary/) requested by our partner organizations.

#### Identifying Needs

The Activation Lead\(s\) may do this themselves but often task the data role with identifying the needs that HOT can assist with. If it is unclear or no requests have been made for specific features to mapped, this is a good 'rule of thumb' priorities for COD:

* Road network - depending on the geographic scope of the event either major roads connecting the population centers may be most important or if localized like a landslide, all minor roads might be important - or both.
* Populated places - for disaster response, sometimes this is more important than roads and are often tasked together.
* Building footprints - building footprints are always useful, but will take a lot more time to map and much harder to maintain high quality input; but often for events like typhoons they eventually become FOD for partner organizations estimating damage and prioritizing resource deployment.

It will also be important to work with and help review Imagery to determine if the data can be captured from available imagery or if new imagery should be requested or alternatives way to capture the data.

#### Keeping Bad Data Out

Sometimes well meaning contributors will want to add data to OpenStreetMap, that while good for disaster response, just does not belong in OpenStreetMap. Use the general 'rules of thumb' for whether the data can legally be added \(licensing, privacy, etc.\), and if it is verifiable \(i.e. can be surveyed on the ground\). Sometimes someone will have a great dataset that is acceptable in license terms, but they don't follow the import process and often Data Activators have to explain why the data was removed and how to properly import.

#### Review

Which of the following is not something that needs to be reviewed to determine whether there are COD/FOD needs that HOT can generate in the area of interest?

* The number of new mappers in the area of interest.
* The existing OSM data in the area of interest.
* The imagery available in the area of interest.

## Providing the Best Image

This unit will explain the process\(es\) that HOT uses when imagery is lacking in the AOI, how to request imagery as well as how to host and use imagery once provided.

Items to Read

* [LearnOSM: WMS Configuration](http://courses.hotosm.org/mod/url/view.php?id=129)

### Requesting Imagery

So how does HOT get imagery if it's not already available from the usual sources?

#### HOT Imagery Coordination Group

HOT has a group of core imagery experts and partner liaisons that have built a great collaboration with a variety of imagery providers. As an Imagery Activator, you might not be invited to discussions until you have built up some trust with the imagery coordination group, however you may be assisting with identifying the bounds of the area of interest and need to know the basics of the request process.

#### Request Process

At the time this lesson was built, HOT was still drafting a more robust Imagery Request process, currently there is a short [process outlined in the Activation wiki-page](http://wiki.openstreetmap.org/wiki/HOT_activation#Imagery_Coordination).

#### Review

All official HOT imagery requests need to come from the Imagery Coordination Group.

* True
* False

People reading this material for credit on [the HOT Courses website](http://courses.hotosm.org/) should share their answer in the \#courses slack channel on HOT's Slack \( [Request Invite](http://slack.hotosm.org) \) If anyone has any question about the correct answer to a Review question, please ask in the \#courses channel of HOT's Slack.

### Providing Imagery

Most new mappers are not going to know how to get new imagery and often imagery providers are not sure how to make their imagery available for tracing, this lesson will teach how to get new imagery to the mappers.

#### Adding Imagery in JOSM

To understand the 'full' process of getting an outside source of imagery, including having to agree to sign an agreement with the provider, there is a good google document for [adding OrbView Imagery into JOSM](https://docs.google.com/document/d/1MB8h-5oyvygEHl213OzkMWN-HpV83b4bb0xzzDXffO4/edit).

#### Adding Imagery via Tasking Manager

To make it as simple as possible for the new mapper, you can add 'remote control' linkage directly into the project on the Tasking Manager. Work with the Tasking Activator\(s\) to set-up the project, only certain end-point/RESTful services work, so alternatives may need to be explored.

#### Adding Imagery to QGIS

Imagery Activators may also be asked to assist first responder or partner organizations to utilize imagery outside of OSM editing. The process should be very similar to getting imagery into JOSM, but HOT is working to make it even simpler to do by developing a [plug-in for importing imagery from OpenAerialMap into QGIS](https://github.com/hotosm/oam-qgis-plugin); potentially this tool could be developed further to allow importing of imagery outside of OAM.

#### Review

Match the appropriate tool with the following objectives, OAM Plugin QGIS, OpenAerialMap, OSM Tasking Manager.

* A non-profit drone club has imagery they are willing to license openly, but need help with hosting and sharing.
* A partner organization has imagery hosted as TMS, but wants mappers to agree to not use it for any other purpose.
* First responders have sensitive data that they want to overlay on top of new drone imagery recently added to OpenAerialMap.

People reading this material for credit on [the HOT Courses website](http://courses.hotosm.org/) should share their answer in the \#courses slack channel on HOT's Slack \( [Request Invite](http://slack.hotosm.org) \) If anyone has any question about the correct answer to a Review question, please ask in the \#courses channel of HOT's Slack.

