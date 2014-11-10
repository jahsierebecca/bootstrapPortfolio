bootstrapPortfolio
==================

## Article

Description:

* Short to long form text with possible accompanying images of recent factual stories

Benefits:

* As a reader, I want the most up-to-date information about the state of the world so that I stay an informed citizen
* As a site owner, I want to increase traffic to our site during peak news stories so that we enhance our standing as a world leading news source

Value

* Reader benefit statement: 13
* Site Owner benefit statement: 3
* Nett Ad Revenue: 8
* Total Value: 24

Attributes:

* Title
  * Total: 1
  * Required: true
  * Type: text input
  * Character Limit: 127
  * Description: A descriptive title of the content
* Body
  * Total: 1
  * Required: true
  * Type: long text input
  * Character Limit: false
  * Description: Long Form text box of main content
* Author
  * Total: 1
  * Required: true
  * Type: reference (person)
  * Description: Author who wrote article
* Published Date
  * Total: 1
  * Required: true
  * Type: datestamp
  * Formatting: mm/dd/yyyy hh:mm
  * Description: Date, including hour and minute, of when article was published
* Summary
  * Total: 1
  * Required: true
  * Type: text input
  * Character Limit: 200
  * Description: Summary of article
* Primary Image
  * Total: 1
  * Required: false
  * Type: reference (image)
  * Description: Primary image for article
* Related Images
  * Total: multiple
  * Required: false
  * Type: reference (image)
  * Minimum: 0
  * Maximum: 5
  * Description: Images related to article
* Related Human Interest Story
  * Total: multiple (no limit)
  * Required: false
  * Type: reference (human interest story)
  * Minimum: 0
  * Maximum: 3
  * Description: Related Human Interest Story
* Taxonomy
  * Total: multiple
  * Required: true
  * Type: reference (term)
  * Minimum: 1
  * Maximum: 5
  * Description: Taxonomy allows content types to be related to each other in a meta sense


Relationships

* Person
* Image
* Term

## Human Interest Story

Description

* Short to long form text with primary media of emotional stories

Benefits:

* As a reader, I want to connect to the people effected by events in the world so that I can identify more closely with those events
* As a site owner, I want to provide additional engagement opportunities to readers so that I can reduce bounce rate and increase ad revenue

Value:

* Reader benefit statement: 8
* Site Owner benefit statement: 8
* Nett Ad Revenue: 3
* Total Value: 19

Attributes:

* Title
  * Total: 1
  * Required: true
  * Type: text input
  * Character Limit: 127
  * Description: A descriptive title of the content
* Body
  * Total: 1
  * Required: true
  * Type: long text input
  * Character Limit: false
  * Description: Long Form text box of main content
* Author
  * Total: 1
  * Required: true
  * Type: reference (person)
  * Description: Author who wrote article
* Published Date
  * Total: 1
  * Required: true
  * Type: datestamp
  * Formatting: mm/dd/yyyy hh:mm
  * Description: Date, including hour and minute, of when article was published
* Summary
  * Total: 1
  * Required: true
  * Type: text input
  * Character Limit: 200
  * Description: Summary of article
* Primary Media
  * Total: 1
  * Required: true
  * Type: reference (image, video, audio)
  * Description: Primary media for article
* Related Media Gallery
  * Total: 1
  * Required: false
  * Type: reference (media gallery)
  * Description: Related media gallery
* Taxonomy
  * Total: multiple
  * Required: true
  * Type: reference (term)
  * Minimum: 1
  * Maximum: 5
  * Description: Taxonomy allows content types to be related to each other in a meta sense

Relationships

* Person
* Image
* Video
* Audio
* Media Gallery
* Term