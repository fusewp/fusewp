=== FuseWP ===
Tags: user sync, user roles, automation, mailchimp, constant contact, campaign monitor, memberpress, woocommerce memberships, activecampaign, WooCommerce Subscriptions
Requires at least: 4.9
Requires PHP: 7.4
Tested up to: 6.8
Stable tag: 2.1.19.0
License: GPL-2.0+

Sync WordPress users with your email marketing software

== Description ==

[FuseWP](https://fusewp.com/) lets you sync WordPress users and profile updates with your email marketing software.

== Frequently Asked Questions ==

Please visit the [plugin page](https://fusewp.com/) with any questions.

== Changelog ==

= 2.1.19.0 =
* Added [GiveWP integration](https://fusewp.com/article/sync-givewp-email-marketing/?ref=prochangelog).
* Added [Salesforce integration](https://fusewp.com/article/connect-wordpress-with-salesforce/?ref=prochangelog).
* Added [beehiiv integration](https://fusewp.com/article/connect-wordpress-to-beehiiv/?ref=prochangelog).
* Added product_attributes to WooCommerce mappable data.
* Added logging of failed queue jobs.
* Added filter flag to enable adding Klaviyo profile to Lists without explicit consent.
* Fixed: Function _load_textdomain_just_in_time was called incorrectly.
* Fixed bug in IP address detection.

= 2.1.18.0 =
* Added [Google Sheets integration](https://fusewp.com/article/connect-wordpress-with-google-sheets/?ref=prochangelog).
* Added [Encharge integration](https://fusewp.com/article/connect-wordpress-to-encharge/?ref=prochangelog).
* Added WPForo integration.
* Added payment subscription syncing support for WPForms.
* Added search to sync log page.
* Increased lifespan of AWeber caches.
* Increase ActiveCampaign tag fetching limit to 1k.

= 2.1.17.1 =
* Added support for Klaviyo custom property field mapping via code.
* Fixed bug with Flodesk during bulk-sync due to invalid IP.
* Fixed bug where Brevo might not correctly add users to list.
* Fixed DB error.
* Improved MemberPress bulk-syncing.

= 2.1.17.0 =
* Added [Keap integration](https://fusewp.com/article/connect-wordpress-to-keap/?ref=prochangelog).
* Added [Zoho Campaigns integration](https://fusewp.com/article/connect-wordpress-to-zoho-campaigns/?ref=prochangelog).

= 2.1.16.1 =
* Added tool for cleaning up bulk sync queued jobs.
* Improved caching of HubSpot API data to avoid rate limiting.
* Fixed bug with incorrect insertion of ob_start().

= 2.1.16.0 =
* Added [Tutor LMS integration](https://fusewp.com/article/sync-tutor-lms-email-marketing/?ref=prochangelog).
* Added [FluentCRM integration](https://fusewp.com/article/connect-wordpress-to-fluentcrm/?ref=prochangelog).
* Improve queue system to prevent unsubscription and resubscription loop.

= 2.1.15.0 =
* Added [WPForms integration](https://fusewp.com/article/sync-wpforms-email-marketing/?ref=prochangelog).
* Added Queue system for processing sync actions.
* Improve bulk-syncing by showing processing status and skipping processed records.
* Added coupon ID and code to MemberPress field mapping data.
* Added fusewp_should_process_sync_immediately filter.
* Enhancement: Add data as custom properties in Klaviyo without a mapped corresponding field.
* Fixed a bug where the Gravity Form Leead Email Address field was showing for other integrations.
* Fixed bug where empty field value didn't update in HubSpot.
* Fixed bug with fusewpEmail included in sync payload.
* Remove deprecated jQuery codes.

= 2.1.14.0 =
* Added [Gravity Forms integration](https://fusewp.com/article/sync-gravity-forms-email-marketing/?ref=prochangelog).
* Added [GetResponse integration](https://fusewp.com/article/connect-wordpress-to-getresponse/?ref=prochangelog).
* Added [Mailjet integration](https://fusewp.com/article/connect-wordpress-to-mailjet/?ref=prochangelog).
* Added tag as segmentation support to Mailchimp integration.
* Fixed bug where some CRM integrations didn't fetch all lists, tags, and custom fields.
* Fixed N+1 DB query issue by introducing Source Item row to Sync rule page.
* Fixed bug where Mailchimp integration can empty out subscriber tags.
* Added caching to the AWeber email list and custom field methods.
* Reduced Bulksync cron schedule from 5 to 1mins.

= 2.1.13.0 =
* Added [EmailOctopus integration](https://fusewp.com/article/connect-wordpress-to-emailoctopus/?ref=prochangelog).
* Added [Drip integration](https://fusewp.com/article/connect-wordpress-to-drip/?ref=prochangelog).
* Added [Omnisend integration](https://fusewp.com/article/connect-wordpress-to-omnisend/?ref=prochangelog).

= 2.1.12.0 =
* Added [Zoho CRM integration](https://fusewp.com/article/connect-wordpress-to-zoho-crm/?ref=prochangelog).
* Added [Easy Digital Downloads integration](https://fusewp.com/article/sync-easy-digital-downloads-email-marketing/?ref=prochangelog).
* Added WooCommerce product IDs and names to field mapping data.
* Added context to error logs.
* Fixed bug where bulk-sync processed items from newest to oldest instead of the opposite.

= 2.1.11.0 =
* Added [MailerLite integration](https://fusewp.com/article/connect-wordpress-to-mailerlite/?ref=prochangelog).
* Added [HighLevel integration](https://fusewp.com/article/connect-wordpress-to-highlevel/?ref=prochangelog).
* Enhancement: Sync actions are now executed on PHP shutdown.
* Added filter to sync roles of users.
* Fixed bulk sync bug with ANY rule in MemberPress.

= 2.1.10.1 =
* Fixed bug where Hubspot fails to add contacts to lists.

= 2.1.10.0 =
* Added more WooComerce Order data for field mapping.
* Added subscription data from WooCommerce Subscriptions for field mapping.
* Added membership data from WooCommerce Memberships for field mapping.
* Added extra subscription and transaction data from MemberPress for field mapping.
* Added subscription data from ProfilePress for field mapping.
* Added membership data from Paid Memberships Pro for field mapping.
* Added course/group data from LearnDash for field mapping.
* Added course/membership data from LifterLMS for field mapping.
* Added Corporate Account Type from MemberPress for field mapping
* Added WooCommerce guest checkout sync support.
* Fixed bug where ANY level rule didn’t work for Paid Memberships Pro sync.
* Fixed bug where Klaviyo only returned 10 lists.
* Fixed bug where multi select field was not clearing in Campaign Monitor Sync.
* Added setting to enable/disable external sync on profile update.
* Added filter to bulk sync record limit.
* Ensure Klaviyo adds users to the correct list even if they already exist as profiles.
* Fixed bug with sync causing issues when users are added from wp-admin.
* Fixed PHP Warning: Attempt to read property "ID" on bool.

= 2.1.9.0 =
* Added [WooCommerce Sync](https://fusewp.com/article/sync-woocommerce-email-marketing/?ref=prochangelog).
* Added [Klaviyo integration](https://fusewp.com/article/connect-wordpress-to-klaviyo/?ref=prochangelog).
* Added [Flodesk integration](https://fusewp.com/article/connect-wordpress-to-flodesk/?ref=prochangelog).
* Use tagging for segmentation in ConvertKit.
* Declared HPOS support for WooCommerce.
* Added ANY source rule support for bulk sync.
* Fixed a couple of PHP Warnings.

= 2.1.8.1 =
* Fixed PHP fatal error on user role sync.

= 2.1.8.0 =
* Added [ConvertKit integration](https://fusewp.com/article/connect-wordpress-to-convertkit/?ref=prochangelog).
* Added [ACF integration](https://fusewp.com/article/advanced-custom-fields/?ref=prochangelog).
* Added "ANY" criteria to supported sources.
* Added sync support when user role changes.
* Added bulk action to delete all logs.
* Added user and integration sync on profile update.
* Added Memberpress ReadyLaunch support.
* Added rate limiting to CC custom app to avoid constant token refresh requests.
* Fixed bug with MemberPress checkboxes field not syncing.
* Fixed bug with CC custom app not correctly refreshing token.


= 2.1.7.0 =
* Added [HubSpot integration](https://fusewp.com/article/connect-wordpress-to-hubspot/?ref=prochangelog).
* Added [ProfilePress integration](https://fusewp.com/article/sync-profilepress-email-marketing/?ref=prochangelog).
* Added [Restrict Content Pro integration](https://fusewp.com/article/sync-restrict-content-pro-email-marketing/?ref=prochangelog).

= 2.1.6.0 =
* Added Bulk-sync feature for syncing historical/existing records.

= 2.1.5.0 =
* Added [LifterLMS integration](https://fusewp.com/article/sync-lifterlms-email-marketing/?ref=prochangelog).
* Added [Sendy integration](https://fusewp.com/article/connect-wordpress-to-sendy/?ref=prochangelog).
* Added [Constant Contact - Custom App](https://fusewp.com/article/connect-wordpress-to-constant-contact/?ref=prochangelog#Connecting_Constant_Contact_via_Custom_App) integration.
* Sync support for Ultimate Member.
* Fixed bug with AWeber not updating a subscriber that exists.
* Fixed memory issue on user sync table display.

= 2.1.4.0 =
* Added [Paid Memberships Pro integration](https://fusewp.com/article/sync-paid-memberships-pro-email-marketing/?ref=prochangelog).
* Added [AWeber integration](https://fusewp.com/article/connect-wordpress-to-aweber/?ref=prochangelog).
* Fixed bug where contacts might be unsubscribed when they should be subscribed.
* Fixed bug where ActiveCampaign jobTitle value could be Array.

= 2.1.3.0 =
* Added [LearnDash integration](https://fusewp.com/article/sync-learndash-email-marketing/?ref=prochangelog)
* Added [Brevo (Sendinblue integration)](https://fusewp.com/article/connect-wordpress-to-brevo/?ref=prochangelog)
* Add support for syncing MemberPress profile updates.
* Added support for syncing WooCommerce My Account user updates.
* Added support for mapping WooCommerce checkout fields during sync setup.
* Fixed fatal error in MemberPress sync integration.

= 2.1.2.0 =
* Added [WooCommerce Subscriptions integration](https://fusewp.com/article/sync-woocommerce-subscriptions-email-marketing/?ref=prochangelog)
* Added [ActiveCampaign integration](https://fusewp.com/article/connect-wordpress-to-activecampaign/?ref=prochangelog)
* Fixed bug where an empty error could be logged.

= 2.1.1.0 =
* Added [MemberPress integration](https://fusewp.com/article/sync-memberpress-email-marketing/?ref=prochangelog)
* Added [Campaign Monitor integration](https://fusewp.com/article/connect-wordpress-to-campaign-monitor/?ref=prochangelog)
* Added "any roles" support to user role sync.
* Fixed bug where mailchimp subscription fails on empty merge fields.
* PHP 8 improvements.
* Fixed bug where disabled sync rules might still be triggered.
* Fixed bug where integration select-dropdown included unconnected integrations.
* Fixed bug where Add new sync rule page left the menu inactive.

= 2.1.0.0 =
* The genesis
