---
name: Eventbrite
x-slug: eventbrite
description: Eventbrite believes that anyone can be an event organizer. That&rsquo;s
  why they offer tools that make it easy to sell tickets to all kinds of events whether
  it&rsquo;s a photography class or a sold-out concert, an inspiring conference or
  an air-guitar competition. With Eventbrite, organizers can create a customizable
  event page; spread the word with social media; collect money; and gain visibility
  into attendees and sales. Eventbrite is for anyone planning or attending an event.
  It empowers event organizers to become more efficient and effective when bringing
  people together. And people everywhere are searching Eventbrite to discover great
  events that matter to them.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
x-kinRank: "9"
x-alexaRank: ""
tags: Eventbrite
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/apis.md
specificationVersion: "0.14"
apis:
- name: Eventbrite Add Events
  x-api-slug: eventbrite
  description: Makes a new event, and returns an event for the specified event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/events-post-openapi.md
- name: Eventbrite Get Events Search
  x-api-slug: eventbrite
  description: Allows you to retrieve a paginated response of public event objects
    from across Eventbrite?s directory, regardless of which user owns the event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/search/
  tags: Events,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventssearch-get-openapi.md
- name: Eventbrite Get Events
  x-api-slug: eventbrite
  description: Returns an event for the specified event. Many of Eventbrite?s API
    use cases resolve around pulling details of a specific event within an Eventbrite
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsid-get-openapi.md
- name: Eventbrite Add Events
  x-api-slug: eventbrite
  description: Updates an event. Returns an event for the specified event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsid-post-openapi.md
- name: Eventbrite Get Categories
  x-api-slug: eventbrite
  description: |-
    Returns a list of category as categories, including
    subcategories nested.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//categories/
  tags: Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/categories-get-openapi.md
- name: Eventbrite Get Categories
  x-api-slug: eventbrite
  description: Gets a category by ID as category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//categories/{id}/
  tags: Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/categoriesid-get-openapi.md
- name: Eventbrite Get Subcategories
  x-api-slug: eventbrite
  description: Returns a list of subcategory as subcategories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//subcategories/
  tags: Subcategories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/subcategories-get-openapi.md
- name: Eventbrite Get Subcategories
  x-api-slug: eventbrite
  description: Gets a subcategory by ID as subcategory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//subcategories/{id}/
  tags: Subcategories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/subcategoriesid-get-openapi.md
- name: Eventbrite Get Checkout Settings Countries Currencies
  x-api-slug: eventbrite
  description: Get the countries and currencies which are supported by Eventbrite
    for ticket payment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//checkout_settings/countries_currencies/
  tags: Checkout,Settings,Countries,Currencies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/checkout-settingscountries-currencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/checkout-settingscountries-currencies-get-openapi.md
- name: Eventbrite Get Checkout Settings Methods
  x-api-slug: eventbrite
  description: Get the available checkout methods to do payments given a country and
    a currency.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//checkout_settings/methods/
  tags: Checkout,Settings,Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/checkout-settingsmethods-get-openapi.md
- name: Eventbrite Get Checkout Settings
  x-api-slug: eventbrite
  description: Searches and returns a list of checkout_settings for the current user
    as the key checkout_settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//checkout_settings/
  tags: Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/checkout-settings-get-openapi.md
- name: Eventbrite Add Checkout Settings
  x-api-slug: eventbrite
  description: Creates a new checkout_settings object belonging to the current user.
    Two common settings are Eventbrite Payment Processing ( checkout_method = &#8220;eventbrite&#8221;
    ) and PayPal ( checkout_method = &#8220;paypal&#8221; ). In addition to the checkout_method
    you must provide the country and currency proceeds from the event should be paid
    to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//checkout_settings/
  tags: Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/checkout-settings-post-openapi.md
- name: Eventbrite Get Checkout Settings Checkout Settings
  x-api-slug: eventbrite
  description: Get a specific checkout_settings object by ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//checkout_settings/:checkout_settings_id/
  tags: Checkout,Settings,Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/checkout-settingscheckout-settings-id-get-openapi.md
- name: Eventbrite Get Events Event  Checkout Settings
  x-api-slug: eventbrite
  description: Gets and returns a list of checkout_settings associated with a given
    event by its event_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/checkout_settings/
  tags: Events,Event,,Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idcheckout-settings-get-openapi.md
- name: Eventbrite Add Events Event  Checkout Settings
  x-api-slug: eventbrite
  description: Associate a single or set of checkout_settings with a given event by
    its event_id. This does not add more checkout settings to the event, but instead
    replaces all checkout settings for the event with the one(s) submitted. The JSON
    post body is a string list of the checkout_settings IDs you want to associate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/checkout_settings/
  tags: Events,Event,,Checkout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idcheckout-settings-post-openapi.md
- name: Eventbrite Get Events Event  Payout Settings
  x-api-slug: eventbrite
  description: Gets and returns the payout_settings (user instrument ID) associated
    with a given event by its event_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/payout_settings/
  tags: Events,Event,,Payout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idpayout-settings-get-openapi.md
- name: Eventbrite Add Events Event  Payout Settings
  x-api-slug: eventbrite
  description: Associate a payout user instrument ID with a given event, or clear
    the association by passing a null value for the user instrument ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/payout_settings/
  tags: Events,Event,,Payout,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idpayout-settings-post-openapi.md
- name: Eventbrite Get Discounts Discount
  x-api-slug: eventbrite
  description: Returns the cross_event_discount with the specified :discount_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//discounts/:discount_id/
  tags: Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discountsdiscount-id-get-openapi.md
- name: Eventbrite Add Discounts
  x-api-slug: eventbrite
  description: Creates a discount. Returns the created cross_event_discount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//discounts/
  tags: Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discounts-post-openapi.md
- name: Eventbrite Add Discounts Discount
  x-api-slug: eventbrite
  description: Updates the discount with the specified :discount_id. Returns the updated
    cross_event_discount. The fields sent are the ones that are going to be updated,
    the fields that are not sent will be unchanged. The same conditions and notes
    for the discount creation apply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//discounts/:discount_id/
  tags: Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discountsdiscount-id-post-openapi.md
- name: Eventbrite Delete Discounts Discount
  x-api-slug: eventbrite
  description: |-
    Deletes the cross_event_discount with the specified :discount_id.
    Only unused discounts can be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//discounts/:discount_id/
  tags: Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/discountsdiscount-id-delete-openapi.md
- name: Eventbrite Get Events
  x-api-slug: eventbrite
  description: "Returns an event for the specified event. Many of Eventbrite\u2019s
    API use cases revolve around pulling details\nof a specific event within an Eventbrite
    account. Does not support fetching a repeating event series parent\n(see GET /series/:id/)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsid-get-openapi.md
- name: Eventbrite Add Events
  x-api-slug: eventbrite
  description: |-
    Updates an event. Returns an event for the specified event. Does not support updating a repeating event
    series parent (see POST /series/:id/).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsid-post-openapi.md
- name: Eventbrite Add Events  Publish
  x-api-slug: eventbrite
  description: |-
    Publishes an event if it has not already been deleted. In order for publish to be permitted, the event must have all
    necessary information, including a name and description, an organizer, at least one ticket, and valid payment options.
    This API endpoint will return argument errors for event fields that fail to validate the publish requirements. Returns
    a boolean indicating success or failure of the publish.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/publish/
  tags: Events,,Publish
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublish-post-openapi.md
- name: Eventbrite Add Events  Unpublish
  x-api-slug: eventbrite
  description: |-
    Unpublishes an event. In order for a free event to be unpublished, it must not have any pending or completed orders,
    even if the event is in the past. In order for a paid event to be unpublished, it must not have any pending or completed
    orders, unless the event has been completed and paid out. Returns a boolean indicating success or failure of the
    unpublish.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/unpublish/
  tags: Events,,Unpublish
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidunpublish-post-openapi.md
- name: Eventbrite Add Events  Cancel
  x-api-slug: eventbrite
  description: |-
    Cancels an event if it has not already been deleted. In order for cancel to be permitted, there must be no pending or
    completed orders. Returns a boolean indicating success or failure of the cancel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/cancel/
  tags: Events,,Cancel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidcancel-post-openapi.md
- name: Eventbrite Add Events  Copy
  x-api-slug: eventbrite
  description: Creates a duplicate version of the event being copied. Returns the
    event object for the newly created event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/copy/
  tags: Events,,Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidcopy-post-openapi.md
- name: Eventbrite Delete Events
  x-api-slug: eventbrite
  description: |-
    Deletes an event if the delete is permitted. In order for a delete to be permitted, there must be no pending or
    completed orders. Returns a boolean indicating success or failure of the delete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsid-delete-openapi.md
- name: Eventbrite Get Events  Display Settings
  x-api-slug: eventbrite
  description: Retrieves the display settings for an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/display_settings/
  tags: Events,,Display,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddisplay-settings-get-openapi.md
- name: Eventbrite Add Events  Display Settings
  x-api-slug: eventbrite
  description: Updates the display settings for an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/display_settings/
  tags: Events,,Display,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddisplay-settings-post-openapi.md
- name: Eventbrite Get Events  Ticket Classes
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response with a key of
    ticket_classes, containing a list of ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/
  tags: Events,,Ticket,Classes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classes-get-openapi.md
- name: Eventbrite Add Events  Ticket Classes
  x-api-slug: eventbrite
  description: |-
    Creates a new ticket class, returning the result as a ticket_class
    under the key ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/
  tags: Events,,Ticket,Classes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classes-post-openapi.md
- name: Eventbrite Get Events  Ticket Classes Ticket Class
  x-api-slug: eventbrite
  description: |-
    Gets and returns a single ticket_class by ID, as the key
    ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/:ticket_class_id/
  tags: Events,,Ticket,Classes,Ticket,Class
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classesticket-class-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classesticket-class-id-get-openapi.md
- name: Eventbrite Add Events  Ticket Classes Ticket Class
  x-api-slug: eventbrite
  description: Updates an existing ticket class, returning the updated result as a
    ticket_class under the key ticket_class.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/:ticket_class_id/
  tags: Events,,Ticket,Classes,Ticket,Class
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classesticket-class-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classesticket-class-id-post-openapi.md
- name: Eventbrite Delete Events  Ticket Classes Ticket Class
  x-api-slug: eventbrite
  description: 'Deletes the ticket class. Returns {&quot;deleted&quot;: true}.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_classes/:ticket_class_id/
  tags: Events,,Ticket,Classes,Ticket,Class
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classesticket-class-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-classesticket-class-id-delete-openapi.md
- name: Eventbrite Get Events  Canned Questions
  x-api-slug: eventbrite
  description: 'This endpoint returns canned questions of a single event (examples:
    first name, last name, company, prefix, etc.). This endpoint will return question.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/canned_questions/
  tags: Events,,Canned,Questions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidcanned-questions-get-openapi.md
- name: Eventbrite Add Events  Canned Questions
  x-api-slug: eventbrite
  description: Creates a new canned question; returns the result as a question.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/canned_questions/
  tags: Events,,Canned,Questions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidcanned-questions-post-openapi.md
- name: Eventbrite Get Events  Questions
  x-api-slug: eventbrite
  description: |-
    Eventbrite allows event organizers to add custom questions that attendees fill
    out upon registration. This endpoint can be helpful for determining what
    custom information is collected and available per event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/questions/
  tags: Events,,Questions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidquestions-get-openapi.md
- name: Eventbrite Add Events  Questions
  x-api-slug: eventbrite
  description: Creates a new question; returns the result as a question as the key
    question.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/questions/
  tags: Events,,Questions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidquestions-post-openapi.md
- name: Eventbrite Get Events  Questions
  x-api-slug: eventbrite
  description: This endpoint will return question for a specific question id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/questions/{id}/
  tags: Events,,Questions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidquestionsid-get-openapi.md
- name: Eventbrite Get Events  Attendees
  x-api-slug: eventbrite
  description: Returns a paginated response with a key of attendees, containing a
    list of attendee.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/attendees/
  tags: Events,,Attendees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidattendees-get-openapi.md
- name: Eventbrite Get Events  Attendees Attendee
  x-api-slug: eventbrite
  description: Returns a single attendee by ID, as the key attendee.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/attendees/:attendee_id/
  tags: Events,,Attendees,Attendee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidattendeesattendee-id-get-openapi.md
- name: Eventbrite Get Events  Orders
  x-api-slug: eventbrite
  description: Returns a paginated response with a key of orders, containing a list
    of order against this event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/orders/
  tags: Events,,Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidorders-get-openapi.md
- name: Eventbrite Get Events  Discounts
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/discounts/
  tags: Events,,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscounts-get-openapi.md
- name: Eventbrite Add Events  Discounts
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/discounts/
  tags: Events,,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscounts-post-openapi.md
- name: Eventbrite Get Events  Discounts Discount
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/discounts/:discount_id/
  tags: Events,,Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscountsdiscount-id-get-openapi.md
- name: Eventbrite Add Events  Discounts Discount
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/discounts/:discount_id/
  tags: Events,,Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscountsdiscount-id-post-openapi.md
- name: Eventbrite Delete Events  Discounts Discount
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/discounts/:discount_id/
  tags: Events,,Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsiddiscountsdiscount-id-delete-openapi.md
- name: Eventbrite Get Events  Public Discounts
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/public_discounts/
  tags: Events,,Public,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discounts-get-openapi.md
- name: Eventbrite Add Events  Public Discounts
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/public_discounts/
  tags: Events,,Public,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discounts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discounts-post-openapi.md
- name: Eventbrite Get Events  Public Discounts Discount
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/public_discounts/:discount_id/
  tags: Events,,Public,Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-get-openapi.md
- name: Eventbrite Add Events  Public Discounts Discount
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/public_discounts/:discount_id/
  tags: Events,,Public,Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-post-openapi.md
- name: Eventbrite Delete Events  Public Discounts Discount
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/public_discounts/:discount_id/
  tags: Events,,Public,Discounts,Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidpublic-discountsdiscount-id-delete-openapi.md
- name: Eventbrite Get Events  Access Codes
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/users/#ebapi-get-users-user-id-discounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/access_codes/
  tags: Events,,Access,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidaccess-codes-get-openapi.md
- name: Eventbrite Add Events  Access Codes
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-post-discounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/access_codes/
  tags: Events,,Access,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidaccess-codes-post-openapi.md
- name: Eventbrite Get Events  Access Codes Access Code
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/access_codes/:access_code_id/
  tags: Events,,Access,Codes,Access,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidaccess-codesaccess-code-id-get-openapi.md
- name: Eventbrite Add Events  Access Codes Access Code
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-get-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/access_codes/:access_code_id/
  tags: Events,,Access,Codes,Access,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidaccess-codesaccess-code-id-post-openapi.md
- name: Eventbrite Delete Events  Access Codes
  x-api-slug: eventbrite
  description: Please use https://www.eventbrite.com/developer/v3/endpoints/cross_event_discounts/#ebapi-delete-discounts-discount-id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/access_codes/
  tags: Events,,Access,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidaccess-codes-delete-openapi.md
- name: Eventbrite Get Events  Transfers
  x-api-slug: eventbrite
  description: Returns a list of transfers for the event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/transfers/
  tags: Events,,Transfers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidtransfers-get-openapi.md
- name: Eventbrite Get Events  Teams
  x-api-slug: eventbrite
  description: Returns a list of attendee-team for the event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/teams/
  tags: Events,,Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidteams-get-openapi.md
- name: Eventbrite Get Events  Teams
  x-api-slug: eventbrite
  description: Returns information for a single attendee-team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/teams/{id}/
  tags: Events,,Teams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidteamsid-get-openapi.md
- name: Eventbrite Get Events  Teams  Attendees
  x-api-slug: eventbrite
  description: Returns attendee for a single attendee-team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/teams/{id}/attendees/
  tags: Events,,Teams,,Attendees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidteamsidattendees-get-openapi.md
- name: Eventbrite Get Events Event  Ticket Groups
  x-api-slug: eventbrite
  description: |-
    Get the list of ticket_group for the event with the specified :event_id.
    By default, only the ticket groups that are live are shown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_groups/
  tags: Events,Event,,Ticket,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-groups-get-openapi.md
- name: Eventbrite Add Events Event  Ticket Classes Ticket Class  Ticket Groups Ticket
    Group
  x-api-slug: eventbrite
  description: Add the Ticket Class with the specified :ticket_class_id that belongs
    to the event with :event_id to the Ticket Group identified by :ticket_group_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/:ticket_group_id/
  tags: Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups,Ticket,Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-post-openapi.md
- name: Eventbrite Delete Events Event  Ticket Classes Ticket Class  Ticket Groups
    Ticket Group
  x-api-slug: eventbrite
  description: Remove the Ticket Class with the specified :ticket_class_id that belongs
    to the event with :event_id from the Ticket Group identified by :ticket_group_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/:ticket_group_id/
  tags: Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups,Ticket,Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groupsticket-group-id-delete-openapi.md
- name: Eventbrite Get Events Event  Ticket Classes Ticket Class  Ticket Groups
  x-api-slug: eventbrite
  description: |-
    Get the Ticket Groups for Ticket Class with the specified :ticket_class_id that belongs to the event with :event_id.
    By default, only the ticket groups that are live are shown.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/
  tags: Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idticket-classesticket-class-idticket-groups-get-openapi.md
- name: Eventbrite Get Events  Ticket Buyer Settings
  x-api-slug: eventbrite
  description: Returns a ticket_buyer_settings for an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_buyer_settings/
  tags: Events,,Ticket,Buyer,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-buyer-settings-get-openapi.md
- name: Eventbrite Add Events  Ticket Buyer Settings
  x-api-slug: eventbrite
  description: Updates the ticket buyer settings for an event. Returns a ticket_buyer_settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/{id}/ticket_buyer_settings/
  tags: Events,,Ticket,Buyer,Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsidticket-buyer-settings-post-openapi.md
- name: Eventbrite Get Formats
  x-api-slug: eventbrite
  description: Returns a list of format as formats.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//formats/
  tags: Formats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/formats-get-openapi.md
- name: Eventbrite Get Formats
  x-api-slug: eventbrite
  description: Gets a format by ID as format.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//formats/{id}/
  tags: Formats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/formatsid-get-openapi.md
- name: Eventbrite Get Media
  x-api-slug: eventbrite
  description: Return an image for a given id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//media/{id}/
  tags: Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/mediaid-get-openapi.md
- name: Eventbrite Get Media Upload
  x-api-slug: eventbrite
  description: See Media Uploads.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//media/upload/
  tags: Media,Upload
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/mediaupload-get-openapi.md
- name: Eventbrite Get Users Me Notifications
  x-api-slug: eventbrite
  description: Gets a paginated response of notification objects for a determined
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/me/notifications/
  tags: Users,Me,Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersmenotifications-get-openapi.md
- name: Eventbrite Get Orders
  x-api-slug: eventbrite
  description: Gets an order by ID an order object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//orders/{id}/
  tags: Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/ordersid-get-openapi.md
- name: Eventbrite Get Users User  Organizations
  x-api-slug: eventbrite
  description: |-
    Returns a continuated list of organizations
    accessible to the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/organizations/
  tags: Users,User,,Organizations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-idorganizations-get-openapi.md
- name: Eventbrite Add Organizers
  x-api-slug: eventbrite
  description: Makes a new organizer. Returns an organizer as organizer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//organizers/
  tags: Organizers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizers-post-openapi.md
- name: Eventbrite Get Organizers
  x-api-slug: eventbrite
  description: Gets an organizer by ID as organizer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//organizers/{id}/
  tags: Organizers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizersid-get-openapi.md
- name: Eventbrite Add Organizers
  x-api-slug: eventbrite
  description: Updates an organizer and returns it as as organizer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//organizers/{id}/
  tags: Organizers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizersid-post-openapi.md
- name: Eventbrite Get Organizers  Events
  x-api-slug: eventbrite
  description: Gets events of the organizer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//organizers/{id}/events/
  tags: Organizers,,Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizersidevents-get-openapi.md
- name: Eventbrite Get Pricing Fee Rates
  x-api-slug: eventbrite
  description: |-
    Returns a list of fee_rate objects for the different
    currencies, countries, assortments and sales channels we sell through
    today and in the future.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//pricing/fee_rates/
  tags: Pricing,Fee,Rates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/pricingfee-rates-get-openapi.md
- name: Eventbrite Get Refund Requests
  x-api-slug: eventbrite
  description: Gets a refund-request for the specified refund request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//refund_requests/{id}/
  tags: Refund,Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/refund-requestsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/refund-requestsid-get-openapi.md
- name: Eventbrite Add Refund Requests
  x-api-slug: eventbrite
  description: Update a refund-request for a specific order. Each element in items
    is a refund-item
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//refund_requests/{id}/
  tags: Refund,Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/refund-requestsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/refund-requestsid-post-openapi.md
- name: Eventbrite Add Refund Requests
  x-api-slug: eventbrite
  description: Creates a refund-request for a specific order. Each element in items
    is a refund-item
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//refund_requests/
  tags: Refund,Requests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/refund-requests-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/refund-requests-post-openapi.md
- name: Eventbrite Get Reports Sales
  x-api-slug: eventbrite
  description: Returns a response of the aggregate sales data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//reports/sales/
  tags: Reports,Sales
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/reportssales-get-openapi.md
- name: Eventbrite Get Reports Attendees
  x-api-slug: eventbrite
  description: Returns a response of the aggregate attendees data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//reports/attendees/
  tags: Reports,Attendees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/reportsattendees-get-openapi.md
- name: Eventbrite Get System Timezones
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response with a key of timezones,
    containing a list of timezones.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//system/timezones/
  tags: System,Timezones
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/systemtimezones-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/systemtimezones-get-openapi.md
- name: Eventbrite Get System Regions
  x-api-slug: eventbrite
  description: |-
    Returns a single page response with a key of regions,
    containing a list of regions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//system/regions/
  tags: System,Regions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/systemregions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/systemregions-get-openapi.md
- name: Eventbrite Get System Countries
  x-api-slug: eventbrite
  description: |-
    Returns a single page response with a key of countries,
    containing a list of countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//system/countries/
  tags: System,Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/systemcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/systemcountries-get-openapi.md
- name: Eventbrite Get Ticket Groups Ticket Group
  x-api-slug: eventbrite
  description: Returns the ticket_group with the specified :ticket_group_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//ticket_groups/:ticket_group_id/
  tags: Ticket,Groups,Ticket,Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/ticket-groupsticket-group-id-get-openapi.md
- name: Eventbrite Delete Ticket Groups Ticket Group
  x-api-slug: eventbrite
  description: |-
    Deletes the ticket_group with the specified :ticket_group_id.
    The status of the ticket group is changed to deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//ticket_groups/:ticket_group_id/
  tags: Ticket,Groups,Ticket,Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/ticket-groupsticket-group-id-delete-openapi.md
- name: Eventbrite Add Ticket Groups
  x-api-slug: eventbrite
  description: |-
    Creates a ticket group and returns the created ticket_group.
    Only up to 200 live ticket groups may be created; those with archived or deleted status are not taken into account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//ticket_groups/
  tags: Ticket,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/ticket-groups-post-openapi.md
- name: Eventbrite Add Ticket Groups Ticket Group
  x-api-slug: eventbrite
  description: Updates the ticket group with the specified :ticket_group_id. Returns
    the updated ticket_group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//ticket_groups/:ticket_group_id/
  tags: Ticket,Groups,Ticket,Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/ticket-groupsticket-group-id-post-openapi.md
- name: Eventbrite Add Tracking Beacons
  x-api-slug: eventbrite
  description: Makes a new tracking beacon. Returns an tracking_beacon as tracking_beacon.
    Either event_id or user_id is required for each tracking beacon. If the event_id
    is provided, the tracking pixel will fire only for that event. If the user_id
    is provided, the tracking pixel will fire for all events organized by that user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/
  tags: Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beacons-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beacons-post-openapi.md
- name: Eventbrite Get Tracking Beacons Tracking Beacons
  x-api-slug: eventbrite
  description: Returns the tracking_beacon with the specified :tracking_beacons_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/:tracking_beacons_id/
  tags: Tracking,Beacons,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-get-openapi.md
- name: Eventbrite Add Tracking Beacons Tracking Beacons
  x-api-slug: eventbrite
  description: Updates the tracking_beacons with the specified :tracking_beacons_id.
    Though event_id and user_id are not individually required, it is a requirement
    to have a tracking beacon where either one must exist. Returns an tracking_beacon
    as tracking_beacon.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/:tracking_beacons_id/
  tags: Tracking,Beacons,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-post-openapi.md
- name: Eventbrite Delete Tracking Beacons Tracking Beacons
  x-api-slug: eventbrite
  description: Delete the tracking_beacons with the specified :tracking_beacons_id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//tracking_beacons/:tracking_beacons_id/
  tags: Tracking,Beacons,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/tracking-beaconstracking-beacons-id-delete-openapi.md
- name: Eventbrite Get Events Event  Tracking Beacons
  x-api-slug: eventbrite
  description: Returns the list of tracking_beacon for the event :event_id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//events/:event_id/tracking_beacons/
  tags: Events,Event,,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idtracking-beacons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/eventsevent-idtracking-beacons-get-openapi.md
- name: Eventbrite Get Users User  Tracking Beacons
  x-api-slug: eventbrite
  description: Returns the list of tracking_beacon for the user :user_id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/tracking_beacons/
  tags: Users,User,,Tracking,Beacons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-idtracking-beacons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-idtracking-beacons-get-openapi.md
- name: Eventbrite Get Users
  x-api-slug: eventbrite
  description: Returns a user for the specified user as user. If you want to get details
    about the currently authenticated user, use /users/me/.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersid-get-openapi.md
- name: Eventbrite Get Users  Orders
  x-api-slug: eventbrite
  description: Returns a paginated response of orders, under the key orders, of all
    orders the user has placed (i.e. where the user was the person buying the tickets).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/orders/
  tags: Users,,Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidorders-get-openapi.md
- name: Eventbrite Get Users  Organizers
  x-api-slug: eventbrite
  description: Returns a paginated response of organizer objects that are owned by
    the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/organizers/
  tags: Users,,Organizers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidorganizers-get-openapi.md
- name: Eventbrite Get Users  Owned Events
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response of events, under
    the key events, of all events the user owns (i.e. events they are organising)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/owned_events/
  tags: Users,,Owned,Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidowned-events-get-openapi.md
- name: Eventbrite Get Users  Events
  x-api-slug: eventbrite
  description: Returns a paginated response of events, under the key events, of all
    events the user has access to
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/events/
  tags: Users,,Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidevents-get-openapi.md
- name: Eventbrite Add Organizations  Events
  x-api-slug: eventbrite
  description: Creates new events objects under an organization and returns it as
    event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//organizations/{id}/events/
  tags: Organizations,,Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizationsidevents-post-openapi.md
- name: Eventbrite Get Users  Venues
  x-api-slug: eventbrite
  description: Returns a paginated response of venue objects that are owned by the
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/venues/
  tags: Users,,Venues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidvenues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidvenues-get-openapi.md
- name: Eventbrite Add Organizations  Venues
  x-api-slug: eventbrite
  description: Creates new venue objects under an organization and returns it as venue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//organizations/{id}/venues/
  tags: Organizations,,Venues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizationsidvenues-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/organizationsidvenues-post-openapi.md
- name: Eventbrite Get Users  Owned Event Attendees
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response of attendees,
    under the key attendees, of attendees visiting any of the events the user owns
    (events that would be returned from /users/:id/owned_events/)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/owned_event_attendees/
  tags: Users,,Owned,Event,Attendees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidowned-event-attendees-get-openapi.md
- name: Eventbrite Get Users  Owned Event Orders
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response of orders,
    under the key orders, of orders placed against any of the events the user owns
    (events that would be returned from /users/:id/owned_events/)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/owned_event_orders/
  tags: Users,,Owned,Event,Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidowned-event-orders-get-openapi.md
- name: Eventbrite Get Users  Contact Lists
  x-api-slug: eventbrite
  description: |-
    Returns a list of contact_list that the user owns as the key
    contact_lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/
  tags: Users,,Contact,Lists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-lists-get-openapi.md
- name: Eventbrite Add Users  Contact Lists
  x-api-slug: eventbrite
  description: |-
    Makes a new contact_list for the user and returns it as
    contact_list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/
  tags: Users,,Contact,Lists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-lists-post-openapi.md
- name: Eventbrite Get Users  Contact Lists Contact List
  x-api-slug: eventbrite
  description: Gets a user&#8217;s contact_list by ID as contact_list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/:contact_list_id/
  tags: Users,,Contact,Lists,Contact,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-listscontact-list-id-get-openapi.md
- name: Eventbrite Add Users  Contact Lists Contact List
  x-api-slug: eventbrite
  description: Updates the contact_list and returns it as contact_list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/:contact_list_id/
  tags: Users,,Contact,Lists,Contact,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-listscontact-list-id-post-openapi.md
- name: Eventbrite Delete Users  Contact Lists Contact List
  x-api-slug: eventbrite
  description: 'Deletes the contact list. Returns {&quot;deleted&quot;: true}.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/:contact_list_id/
  tags: Users,,Contact,Lists,Contact,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-listscontact-list-id-delete-openapi.md
- name: Eventbrite Get Users  Contact Lists Contact List  Contacts
  x-api-slug: eventbrite
  description: |-
    Returns the contacts on the contact list
    as contacts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/:contact_list_id/contacts/
  tags: Users,,Contact,Lists,Contact,List,,Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-listscontact-list-idcontacts-get-openapi.md
- name: Eventbrite Add Users  Contact Lists Contact List  Contacts
  x-api-slug: eventbrite
  description: 'Adds a new contact to the contact list. Returns {&quot;created&quot;:
    true}.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/:contact_list_id/contacts/
  tags: Users,,Contact,Lists,Contact,List,,Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-listscontact-list-idcontacts-post-openapi.md
- name: Eventbrite Delete Users  Contact Lists Contact List  Contacts
  x-api-slug: eventbrite
  description: |-
    Deletes the specified contact from the contact list.
    Returns {&quot;deleted&quot;: true}.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/contact_lists/:contact_list_id/contacts/
  tags: Users,,Contact,Lists,Contact,List,,Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidcontact-listscontact-list-idcontacts-delete-openapi.md
- name: Eventbrite Get Users  Bookmarks
  x-api-slug: eventbrite
  description: Gets all the user&#8217;s saved events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/bookmarks/
  tags: Users,,Bookmarks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidbookmarks-get-openapi.md
- name: Eventbrite Add Users  Bookmarks Save
  x-api-slug: eventbrite
  description: 'Adds a new bookmark for the user. Returns {&quot;created&quot;: true}.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/bookmarks/save/
  tags: Users,,Bookmarks,Save
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidbookmarkssave-post-openapi.md
- name: Eventbrite Add Users  Bookmarks Unsave
  x-api-slug: eventbrite
  description: 'Removes the specified bookmark from the event for the user. Returns
    {&quot;deleted&quot;: true}.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/bookmarks/unsave/
  tags: Users,,Bookmarks,Unsave
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidbookmarksunsave-post-openapi.md
- name: Eventbrite Get Users User  Ticket Groups
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response of ticket_group for the specified user.
    The alias me (/users/me/) may be used to refer to the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/ticket_groups/
  tags: Users,User,,Ticket,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-idticket-groups-get-openapi.md
- name: Eventbrite Add Users User  Events Event  Ticket Classes Ticket Class  Ticket
    Groups
  x-api-slug: eventbrite
  description: |-
    Add the Ticket Class with the specified :ticket_class_id of the event with :event_id that
    belongs to the user with :user_id to many Ticket Groups specified with ticket_group_ids.
    If the list provided is empty, remove this ticket class from every ticket group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/events/:event_id/ticket_classes/:ticket_class_id/ticket_groups/
  tags: Users,User,,Events,Event,,Ticket,Classes,Ticket,Class,,Ticket,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-ideventsevent-idticket-classesticket-class-idticket-groups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-ideventsevent-idticket-classesticket-class-idticket-groups-post-openapi.md
- name: Eventbrite Get Users User  Discounts
  x-api-slug: eventbrite
  description: |-
    Returns a paginated response of cross_event_discount for the specified user.
    This operation is only supported for the currently authenticated user. The alias me (/users/me/) may be used.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/:user_id/discounts/
  tags: Users,User,,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-iddiscounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersuser-iddiscounts-get-openapi.md
- name: Eventbrite Get Users  Assortment
  x-api-slug: eventbrite
  description: Retrieve the assortment for the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/assortment/
  tags: Users,,Assortment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidassortment-get-openapi.md
- name: Eventbrite Add Users  Assortment
  x-api-slug: eventbrite
  description: |-
    Set a user&#8217;s assortment and returns the assortment for the specified
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//users/{id}/assortment/
  tags: Users,,Assortment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/usersidassortment-post-openapi.md
- name: Eventbrite Get Venues
  x-api-slug: eventbrite
  description: Returns a venue object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//venues/{id}/
  tags: Venues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venuesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venuesid-get-openapi.md
- name: Eventbrite Add Venues
  x-api-slug: eventbrite
  description: Updates a venue and returns it as an object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//venues/{id}/
  tags: Venues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venuesid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venuesid-post-openapi.md
- name: Eventbrite Add Venues
  x-api-slug: eventbrite
  description: Creates a new venue with associated address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//venues/
  tags: Venues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venues-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venues-post-openapi.md
- name: Eventbrite Get Venues  Events
  x-api-slug: eventbrite
  description: Returns events of a given venue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//venues/{id}/events/
  tags: Venues,,Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venuesidevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/venuesidevents-get-openapi.md
- name: Eventbrite Get Webhooks
  x-api-slug: eventbrite
  description: Returns a webhook for the specified webhook as webhook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//webhooks/{id}/
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooksid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooksid-get-openapi.md
- name: Eventbrite Delete Webhooks
  x-api-slug: eventbrite
  description: Deletes the specified webhook object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//webhooks/{id}/
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooksid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooksid-delete-openapi.md
- name: Eventbrite Get Webhooks
  x-api-slug: eventbrite
  description: Returns the list of webhook objects that belong to the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//webhooks/
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooks-get-openapi.md
- name: Eventbrite Add Webhooks
  x-api-slug: eventbrite
  description: Creates a webhook for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//webhooks/
  tags: Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/webhooks-post-openapi.md
- name: Eventbrite Add Series
  x-api-slug: eventbrite
  description: Creates a new repeating event series. The POST data must include information
    for at least one event date in the series.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/
  tags: Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/series-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/series-post-openapi.md
- name: Eventbrite Get Series
  x-api-slug: eventbrite
  description: Returns a repeating event series parent object for the specified repeating
    event series.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/
  tags: Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesid-get-openapi.md
- name: Eventbrite Add Series
  x-api-slug: eventbrite
  description: |-
    Updates a repeating event series parent object, and optionally also creates more event dates or updates or deletes
    existing event dates in the series. In order for a series date to be deleted or updated, there must be no pending or
    completed orders for that date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/
  tags: Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesid-post-openapi.md
- name: Eventbrite Add Series  Publish
  x-api-slug: eventbrite
  description: |-
    Publishes a repeating event series and all of its occurrences that are not already canceled or deleted. Once a date is cancelled it can still be uncancelled and can be viewed by the public. A deleted date cannot be undeleted and cannot by viewed by the public. In order for
    publish to be permitted, the event must have all necessary information, including a name and description, an organizer,
    at least one ticket, and valid payment options. This API endpoint will return argument errors for event fields that
    fail to validate the publish requirements. Returns a boolean indicating success or failure of the publish.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/publish/
  tags: Series,,Publish
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidpublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidpublish-post-openapi.md
- name: Eventbrite Add Series  Unpublish
  x-api-slug: eventbrite
  description: |-
    Unpublishes a repeating event series and all of its occurrences that are not already completed, canceled, or deleted. In
    order for a free series to be unpublished, it must not have any pending or completed orders for any dates, even past
    dates. In order for a paid series to be unpublished, it must not have any pending or completed orders for any dates,
    except that completed orders for past dates that have been completed and paid out do not prevent an unpublish. Returns
    a boolean indicating success or failure of the unpublish.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/unpublish/
  tags: Series,,Unpublish
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidunpublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidunpublish-post-openapi.md
- name: Eventbrite Add Series  Cancel
  x-api-slug: eventbrite
  description: |-
    Cancels a repeating event series and all of its occurrences that are not already canceled or deleted. In order for
    cancel to be permitted, there must be no pending or completed orders for any dates in the series. Returns a boolean
    indicating success or failure of the cancel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/cancel/
  tags: Series,,Cancel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidcancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidcancel-post-openapi.md
- name: Eventbrite Delete Series
  x-api-slug: eventbrite
  description: |-
    Deletes a repeating event series and all of its occurrences if the delete is permitted. In order for a delete to be
    permitted, there must be no pending or completed orders for any dates in the series. Returns a boolean indicating
    success or failure of the delete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/
  tags: Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesid-delete-openapi.md
- name: Eventbrite Get Series  Events
  x-api-slug: eventbrite
  description: Returns all of the events that belong to this repeating event series.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/events/
  tags: Series,,Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidevents-get-openapi.md
- name: Eventbrite Add Series  Events
  x-api-slug: eventbrite
  description: |-
    Creates more event dates or updates or deletes existing event dates in a repeating event series. In order for a series
    date to be deleted or updated, there must be no pending or completed orders for that date.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3//series/{id}/events/
  tags: Series,,Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidevents-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/seriesidevents-post-openapi.md
- name: Eventbrite
  x-api-slug: eventbrite
  description: Eventbrite believes that anyone can be an event organizer. That&rsquo;s
    why they offer tools that make it easy to sell tickets to all kinds of events
    whether it&rsquo;s a photography class or a sold-out concert, an inspiring conference
    or an air-guitar competition. With Eventbrite, organizers can create a customizable
    event page; spread the word with social media; collect money; and gain visibility
    into attendees and sales. Eventbrite is for anyone planning or attending an event.
    It empowers event organizers to become more efficient and effective when bringing
    people together. And people everywhere are searching Eventbrite to discover great
    events that matter to them.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/eventbritelogoff8000gradient.png
  humanURL: http://developer.eventbrite.com/
  baseURL: https://www.eventbriteapi.com//v3
  tags: Eventbrite
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/eventbrite/master/_listings/eventbrite/openapi.md
x-common:
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/eventbrite/apidescription?format=internal&ver=1351170233000
- type: x-authentication
  url: https://developer.eventbrite.com/docs/auth/
- type: x-base
  url: https://www.eventbriteapi.com/
- type: x-blog
  url: http://blog.eventbrite.com/
- type: x-blog-rss
  url: http://blog.eventbrite.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/eventbrite
- type: x-developer
  url: https://developer.eventbrite.com/
- type: x-github
  url: https://github.com/eventbrite
- type: x-pricing
  url: http://help.eventbrite.com/customer/en_us/portal/articles/428604
- type: x-privacy
  url: http://www.eventbrite.com/privacypolicy
- type: x-sdksio
  url: https://sdks.io/SDK/View/eventbrite
- type: x-selfservice-registration
  url: https://www.eventbrite.com/signup/?referrer=%2F%3Fshow_onboarding%3D1&user_type=prebuyer&user_type_sig=AH_ElWGNJ_zHaAxwjzt5jiCRmvPvNBsy6w
- type: x-terms-of-service
  url: http://www.eventbrite.com/tos
- type: x-twitter
  url: https://twitter.com/EventbriteAPI
- type: x-website
  url: http://developer.eventbrite.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---