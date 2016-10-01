# Mall Santa App Brainstorm

Disclaimer: I have never spoken to anyone who runs these kinds of operations.
I've been a consumer (I have kids) so I can imagine a bit of what this might
be like. I am probably totally wrong.

## Overview

This brainstorm attempts to capture all of the key needs (jobs), action points
(actions) that trigger (events) things to happen in the business. They are
grouped into sections by jobs. Each bullet point describes an action that
then generates at least one event. Each event can have multiple sub-actions
that are triggered and then generate their own events. This looks like:

Job to be done:
 * Action -> event =>
   * Sub-action -> event =>
     * Child sub-action -> event =>
   * Sibling-sub-action -> event =>

Every action always generates an event. This makes it easy to add new actions
later w/out needing to change the original action.

## Business Workflow

Not a lot would need to be modified for this to work for any boutique portrait
photography business.

Weeks before the event, create photo shoot in backend:
 * Schedule photoshoot location -> location scheduled =>
   * Send staff reminder email -> staff reminder email sent =>
   * Record date/location in google calendar -> calendar entry recorded =>
   * Auto configure day before reminder email -> day before reminder created =>
   * Send marketing email to customers who previously bought at this location -> marketing email sent =>
   * Post to twitter/FB page -> posted =>

Automatically remind staff the day before:
  * Automatically end staff reminder email -> day before reminder email created =>

Kiosk uploads photos, generates an ID to be given to customers:
 * Create Customer -> Customer ID Generated =>
   * Track customers entered

Photos are taken:
 * Upload Photos to customer ID -> Photos Uploaded =>
    * Process photos -> Photos processed =>
      * track # photos created
      * Generate Gallery -> Gallery generated =>
        * Send email -> Email sent =>
          * track emails sent
        * share on social media (if agreed - see below) -> shared on social media =>
          * track social media shares -> social media shares tracked =>

Customer agrees to let the photos be shared on social media:
 * Customer agrees -> Customer agreed =>
   * record agreement -> agreement recorded =>

User shares photos:
  * Share on FB/Twitter/Instagram/email -> Image shared =>
    * Track sharing
  * Share by email -> Shared by email requested =>
    * Send email -> Email shared =>
      * Track emails sent

User selects and buys prints from website:
 * User buys prints -> purchase received =>
   * reserve payment -> payment reservation accepted =>
     * send fulfillment request -> fulfillment request sent =>
       * send fulfillment ID/tracking email -> fulfillment tracking email sent =>
   * send thankyou email -> thankyou email sent =>

Photo printing fulfillment:
 * Photos being processed by fulfillment lab =>
   * Send tracking email -> tracking email sent =>
   * Update order tracking record
   * Process payment -> payment finalized =>
     * Disable order cancellation -> order cancellation disabled =>
     * Send final invoice email -> final invoice email sent =>
 * Photos fulfilled (external event) =>
   * Send tracking email -> tracking email sent =>
   * Update order record
   * Update business metrics
