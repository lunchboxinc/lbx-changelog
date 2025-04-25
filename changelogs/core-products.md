## Initial Release Notes:
* NDExternal: Update order status when pos_status 
* Update NdCustomer with Square 
* Expose payment handler 
* Worldpay: only recall gateway for timeout reversals 
* GrubHub v3 initial merge 
* LBX-1630 Add images to GH menus 
* Lbx 925 import menu keith hubbard 
* fix rounding issue 
* Simphony clean-ups from testing with Torchy's menu 
* Send is_time_bump with Confirm Changes in Call Center 
* Mgmt api 
* Simphony: import unavailable items list 
* Fix Simphony item name with placeholder 
* [LBX-2475] Add fetch credential to return api-key for loyalty provider 
* NDMenuEngine: Pass min/max quantity to doordash 
* fix(simphony): set "cat_uid: None" for PL trigger (LBX-1989) 
* feat: implement Square menu import 
* LBX-2192_Simphony-Default-Modifiers-Not-Set-Upon-Menu-Import_Keith-Hubbard 
* NDMenuEngine: add multi select on modifiers uber 
* Storing 'isMultiSelect' prop as 'show_qty' for toast 
* fix: don't "keyError" when items don't have taxes 
* Agent: control menu packs via agent_export_control 
* fix: small change to setdefault on quantity_info as well 
* LBX-2650: add schedule implementation 
* Lbx 2685 implement get schedule 
* LBX-2686: add update schedule with validation 
* LBX-2639: don't add non-item "modifier_option"s 
* Toast: disable show_qty if a modifier does not allow it 
* NCR: encode item name on import 
* LBX-2724 add get business_hours 
* LBX-2837: add get endpoint for tax rules 
* Lbx 2866 get order details 
* LBX-2828 Bring chain config options into DB 
* Authorize the requests library in Zope 
* Lbx 2866 get orders 
* Update Billing Address and zip code to be optional 
* Square payment 
* add ability to choose the quantity of items from a modifier picklist/modifier prompt in Grubhub 
* fix: send correct params to get_available_balances 
* feature: add delete and clear 
* fix: remove extra "merge_requires" from Square menu import 
* Support using SLUs as categories in Simphony menu import (LBX-3144) 
* fix: cast unicode slu to integer 
* Square: add missing docstring 
* SquarePayment: send method and log payload/response for create card 
* fix: encode item names into unicode strings 
* NDMenuEngine fix uber modifier quantity to send correct maxcount 
* LBX-2498: Order voided because of partial payment 
* NDExternal - lbx-3385 fix issue with loyalty inquire 
* added open_value 
* [LBX-2037] Feature: redeem coupon instore 
* increase synchronous timeout 
* [LBX-3185] make delivery radius optional in chain config 
* NDConfig: adding some defaults to schema.yaml 
* fix: guard against duplicate modifier catitems 
* Fix: handle birthdate JSON serializable error 
* Don't create loyalty account until phone is verified 
* Create theme config API for app and site 
* LBX-3387: support Square sizing in menu imports 
* NDExternal store configuration setting add enable_instore_reward_rede… 
* NDMenuEngine fix grubhub issue when the store is closed for 
* Chain config schema 
* NDCustomer fix login issue 
* Feature/lbx 2248 
* fix: add per-size modifier list triggers (LBX-3545) 
* Worldpay: update masking and remove logging; read R009 and use G012 
* Ord Eng: return error if geocoding saved address fails 
* OwG: add file spool for Google menu feeds 
* NDConfigurations: add default fields to schema 
* Add theme config public API (with LBX-3614) 
* [ LBX-2895] Feature: add GET service groups and restaurant classes 
* E card integration 
* Lbx 2724 menu set use local hours 
* Create file-management API in management API 
* Order processing and order throttling  APIs (LBX-3652) 
* fix: filter taxes by location presence 
* Mercury pay void sale 
* NDExternal: update sqlLookUpItem to be able to lookup by alternateex… 
* Fix/LBX-3893 Verify duplicate phone number 
* LBX_3893: Update response to throw error 
* fix: disambiguate size-based item variants 
* Feature/lbx 2977 Import toast service type and service type configs 
* LBX-3893: Add phone validation to POST customer 
* Feature/lbx 4003 Automatic Reset Password for Imported Users 
* LBX-3893-part3: Validate existing phone verifieds 
* LBX-3900: Wing Shack Wings - Order Agg - Doordash / UberEATS orders failing price validation (from 3PD) 
* NCR: distinguish child price overrides by modifier 
* Worldpay void capture 
* fix(Square): don't KeyError on modifier lists (LBX-4213) 
* Worldpay: sort payment transactions in gateway not handler 
* Removing optional fields and fixed item description for grubhub menu 
* Paytronix gift card 
* fix(Square): look in correct place for tax presence 
* Ext order: add explicit error for missing service schedule 
* Square: exception handling to get oauth token 
* Fixed more than one row returned by a subquery used as an expression 
* Agent: getOrder: retry if replica out of sync 
* feat:update get_delivery_provider_config 
* Square refund update 
* fix(customerio): fix "customer_registered" "device_info" race condition (LBX-1328) 
* Delivery APIs (LBX-4397) 
* Update by creating new record in theme config API 
* Coupon bank update issue 
* Fixed UnicodeDecodeError while logging 
* Add menu list API for select box 
* fix(Square): honor item variations' location presence 
* Updating chain config schema 
* fix(Toast): default to extant coupon val/pct (LBX-4191) 
* NDConfiguration: tax_fudge_cents default text type 
* Call center tax exempt choice 
* LBX-573 Google Pay 
* NDConfiguration adding ccprocessing to schema.yml 
* Disable service type's config pulling from Toast for specific chains 
* All service type APIs WIP 
* Business hours APIs (LBX-3903, LBX-4118, LBX-3649) 
* ECard: mask rawTransactionReturn for DB 
* fix: remove dead code causing "KeyError" (LBX-4759) 
* Ord Eng: add loyalty coupons to order_changed hook 
* fix(Square): add default "size_name" for variants (LBX-4759) 
* feat:adding delivery area sync option 
* add enforce_unique_phone_number 
* NDMenuEnginer fix grubhub menu mapping submodifier only returning 1 i… 
* LocationSearch: add membership_term to sql_get_available_memberships 
* Feature/lbx 4849 Added default_modifiers for grubhub menu 
* LBX-2661: Order Engine: clean up abandoned orders (loyalty reversal) 
* Feature/lbx 2405 1 
* Cust eng: fix failing membership query 
* Minor changes for migration 
* Coupon management API 
* Loyalty API-KEY get api 
* Fix delivery rule create error 
* Order throttling rule sorting 
* Order APIs (LBX-4043) 
* LBX-576 match google pay sdk format khubbard 
* Fix service type schedule API's issues 
* Add other font file types 
* Settings API 
* Staff user APIs 
* Location APIs 
* Customer management APIs (LBX-4522) 
* Payment Types and Gateways APIs 
* fixed function name 
* [ LBX-2721] Feature: add all GET methods for providers under integration Tab (LBX-4009) 
* Feature/lbx 2405 1 bug fixes 
* Adding itemClasses to getOrder 
* Fix close location issue 
* Add Pagination to Discount Customer API 
* fix(AgentServer): use "or" default, not "get" 
* Grubhub ST Exclusion hours not being adhered to in API Data/Upload 
* Added apple provider for foreign auth 
* Fix delivery rule update issue 
* Feature/lbx 2405 1 
* Worldpay: logging update and masking pac 
* Google pay 
* Pass Google Pay 3DS cryptogram along with payment 
* Remove required validator 
* Add payment_token to endpoing for instore 
* Added new endpoint for in-store orders 
* Add customer roles to customers/me API 
* Feature/lbx 2405 1 Create menu modes for each location 
* Square precision 
* Fix IndexError in the payment update API 
* Fix remove all customer issue 
* Fix customer order list API issue 
* Finix Integration 
* Change Finix prod API URL 
* Store username and password in the ZMI 
* Fix customer email update issue 
* All Grubhub Clients - Grubhub Pickup Orders are not passing the Tip through to the POS - LBX-4939 
* All Grubhub Clients - Grubhub Pickup Orders are not passing the Tip through to the POS - LBX-4939  
* Add first_name and last_name to staff user detail 
* Fix the error after the update 
* NDExternal ensure only call handle_loyalty_inquiry when validate_only… 
* NDMenuEngine: wipe references to nonexistent images during import (LBX-5270) 
* API: teach incoming webhooks to use NDQ-over-Redis 
* Prep Time Rule Page APIs 
* Fix KeyError in the service type API 
* Add control to gateway params second index 
* ECardv2: support purchase/refill/save gift cards 
* LBX-5219: Fix mapping conditional tax 
* NDMenuEngine - add modifier_qty extra check in get_raw_simple_menus t… 
* Finix capture issue 
* Order Search API 
* Fix new admin permissions issue 
* Add subscriptions to order provider detail 
* fix(AgentServer): fix typo in func invocation 
* update broken in-store endpoints 
* Feature/LBX-1195 Apple pay integration 
* update schema for instore 
* Add payment_id to be return with order 
* NDMenuEngine: wipe references to nonexistent images during import (LBX-5270) 
* CustomerEngine: always filter on membership item 
* LBX-52: Adding the same modifier option to different categories at different prices. 
* added apple pay configs to schema 
* feat(CustomerEngine): add "customer_updated" to device endpoint (LBX-5651) 
* NDCustomerEngine: add "device_info" to customer_login payload (LBX-5652) 
* AgentServer: Guard against duplicate store_ids (LBX-5549) 
* AgentServer: Guard against duplicate store_ids (LBX-5549) 
* fix: properly name fn call 
* Changed eci value according to card type 
* fix(NDCustomerEngine): don't sent stringified device_info (LBX-5651) 
* fix(NDApi): add Deliverect module (LBX-7146) 
* LBX-5554 - Aloha / BSL quick-combos 
* Add secret fields in the chain config 
* LBX-7738 - combine pick list target item configs for 3rd menu exports 
* lbx-5388 AgentServer: add flag for disable_prep_time_import 
* NDMenuEngine - mod quantity  doordash 
* NCR(BSL): import menu hours 
* fix/update instore edit 
* Call Center:Customer Notes - LBX-3203  
* Toast payments - LBX-5004 
* Added enable_instore_reward_redemption key to chain config schema 
* Reports APIs 
* Task/LBX-4720 exclude dinein order history 
* Update guest_count in the order table 
* [AKIN]: Order Aggregation: Reflect 3PD Promos On Orders - (LBX-5384) 
* fix(AgentServer): catch & skip failed combo group references (LBX-9502) 
* Onboarding: Deploy Website / Upload App from Admin Dashboard - LBX-3229 
* LBX-9512 LOCATIONSEARCH Fix issue with hours not correctly returning to the api. 
* Implement 'InStorePaymentBypassPriceCheck' flag for seamless in-store payments 
* HOTFIX: NDExternal - remove comma passed in params in sql_insert_prov… 
* Feature/lbx 5042 : Coupon migration 
* Feature/LBX-6207: Migrate Item Global Availability 
* update external_ids if the customer is exists, create menusavail for master location and fixed time difference issue for orders pull/360
* LBX-4937: Support 3PD external payments 
* Order search API fix time out issue (LBX-8408) 
* Login with the security code via API 
* fix(Square): propagate item taxes to mods/vars (LBX-5394) 
* NDMenuEngine: LBX-9787 handle deduping items for grubhub menu 
* Toast Denied message - LBX-9678 
* Square: Support Placing Orders Across Multiple Square Accounts - LBX-5301 
* Finix UnicodeDecodeError  
* Add Netlify Env APIs 
* Add Lunchbox AI GET Api-Key API LBX-9779 
* LBX-9523: Added chain config for submitting orders Later/Earlier than standard hours of operation 
* Toast Payments: auth balance amount, less tip - LBX-9970 
* [AKIN]: Added authorization default value into the schema.yml 
* LBX-8411 
* LBX- 7716/fix cross mode picklist default deletion 
* fix(LocationSearch): add distance to deliveryrule ordering (LBX-8653) 
* fix(Square): allow children to inherit parent tax info (LBX-5394) 
* LBX-10188: Menu engine: fix Flyt menu export 
* Gift card range update LBX-9192 
* Use quote quick link for new UI link - LBX-9755 
* ToastPayments: overwrite error message TRANS DENIED - LBX-10317 
* fix(NDOrderEngine): revamp generic_p construction (LBX-10194) 
* Ios key, android key updated in schema.yaml file - LBX-3229 
* [AKIN]: customers table external_id field new structure solution without migration script. 
* Clear user detail cache after password update LBX-9950 
* Accept all gift card schemes LBX-10346 
* LBX-9442: Curbside: allow check-in info to be set before check-in 
* Redis integration in square global access token - LBX-5301  
* Add empty control for the range value LBX-10346 
* fix(NDOrderEngine): handle AttributeErrors during customer checkin (LBX-10382) 
* Loyalty: call lookup with accurate guest/non-guest flag (LBX-5368) 
* NDPaymentGateway2: re-add request_pos_order method 
* fix(AgentServer): .get(...) to prevent KeyError (LBX-10439) 
* skip avs/cvv check if google/apple transaction ( LBX-9667 ) 
* Sales tax page APIs  LBX-5328 
* Environment variable name changed to environments and is_expand set false - LBX-3229 
* nit: handle nonexistent key, don't expect AttributeError 
* Create CODEOWNERS - LBX-9793 
* chore(NDOrderEngine): send generic_provider_rest info in get_order (LBX-10462) 
* fix(NDOrderEngine): use .update properly 
* LBX-6205 : Menu hours migration 
* fix(NDOrderEngine): only search generic provider if checkin provider is configured 
* Square Guest User Payment Problem FIX - LBX-5301 
* Expose pos logs in new admin and event logging APIs LBX-9790 
* Command center APIs 
* fix(AgentServer): fix unicode/ascii encoding (LBX-10438) 
* Create Toast pick list triggers by category (LBX-5199) 
* LBX-9952 Service type and order throttling API issues 
* Add item_name filter to coupon list API LBX-9323 
* Lbx 5102 tozenized finix(LBX-5102) 
* Agent: avoid clashes in temporary import store IDs (LBX-10300) 
* Finix: add instrument type for non google/apple payment(LBX-5102) 
* LBX-10583 Add missing coupon APIs 
* Finix: add chain config settings for finix(LBX-5102) 
* LBX-10644 Add created date to customer/me response payload 
* Finix: allowing editing this will make testing prod in a dev env possible(LBX-5102) 
* LBX-10760 3rd party report total issue on the report page 
* Finix: logging for API calls to finix(LBX-5102) 
* Lbx 5102 tozenized finix(LBX-5102) 
* Order refund API LBX-10479 
* LBX-10893 Add netlify site report API 
* Unable to add card/checkout some locations - Night Swim (Square) - LBX-4803 
* LBX-10916 add cards_only filter to payment protocol list API 
* Lbx 8413 
* LBX-10807 coupon page api changes 
* LBX-11085 Change access token default value and hide the field on the settings page 
* LBX-10937 add update_category_descriptors 
* LBX-10920: limit changes to orders with loyalty redemptions 
* Fixed toast same guid different category price issue - LBX-5783 
* LBX-8413 
* Worldpay: set transactionstatus for timeouts; return 1 status for credits- LBX-10347 
* Toast: use amount passed to authOnly(LBX-11170) 
* Null check for geo, search existing order before creating. 
* feat(Square): handle "sold_out" item variations (LBX-11365) 
* LBX-11545 Fix web vs app report issue 
* NDMigration - Find correct service type 
* Bulk insert for order items migration 
* Bugfix/migration Dicrease chunk size 
* typo in chain_identity_id(LBX-5102) 
* LBX-4803 - SAVED CARDS FLOW CHANGES(Square Gateway) 
* LBX-11908 Add service type filter to order search API 
* LBX-4803 - Production Test Hotfix (card_check and global_token) 
* LBX-12127 Sales tax delete issue 
* LBX-11904 add additional fields to service type 
* LBX-11171 Add display_name to order detail SQLs 
* LBX-12379 Customer Hash Endpoint For Intercom 
* LBX-12439 Add company_name field to customer update endpoint 
* fix(AgentServer): order menus' modes by external_id 
* Feature/LBX-4431 Disable service type name import from toast if chain config is True.  
* [AKIN]: Defined square default configurations into the schema.yml - LBX-12450 
* LBX-12450 - Square Default values(MerchantId and LocationId, AppId) added to get_configuration function. 
* LBX-3684 
* Bugfix/lbx 10459 schema yaml 
* LBX-10454: menu import: consider category when disabling items 
* LBX-3946: Toggle Loyalty Accrual/Redemption by Service Type 
* LBX-10283: do not ignore coupons removed/adjusted during payment 
* Lbx 9556 
* LBX-10647 Cleanjuice sync menu images 
* Paytronix comp cards(LBX-5648) 
* LBX-10333 Add services to account (Phase 1) 
* LBX-12207 : Added update_restaurant_name into chain config yaml 
* LBX-11779-Farmside Kitchen - Menu Image quality 
* LBX-12215 order search endpoint changes 
* LBX-3684-sms_optin for guest registration 
* LBX-10892 Sales tax APIs issue 
* LBX-3684 
* LBX-12874: Flybuy: include SDK status in theme-config 
* LBX-10911 - FHS: Promo,  passing to the POS 
* LBX-13011 Add marketing optin to store configuration API 
* LBX-5494-Add to calendar email link enable/disable. 
* LBX-12793 Add companyname to customer detail endpoint 
* LBX-12487 Fix AttributeError on the tax rate API 
* LBX-13011 Add separate fields for sms and email 
* LBX-12794 Service type global update error 
* LBX-12211 add missing keys to customers put endpoint 
* Toast Cancelled Payments(LBX-12908) 
* LBX-11158 -Square Refunds 
* WIP: make is_open accurate w/ ovn. business hours 
* LBX-9669 
* add comment to update toast service if changing toast authOnly(LBX-12908) 
* LBX-12873 Add date range filter to order API 
* Bugfix/lbx 4433 deleting account 
* removed incorrect comma 
* LBX-12339 Add service availability APIs 
* LBX-13421 Remove faulty SQL block 
* Lbx 12496 
* LBX 13307/remove master requirement for ST conf updates 
* Square/AgentServer: Remove dead discount code (LBX-13290) 
* Finix: send gateway_merchant_id to get_payment_request(LBX-5102) 
* LBX-13310: LS: use affects_display_hours for weekly hours 
* Adding is_billing_address_enabled_for_call_center key value 
* LBX-13393 : Added max_qty for base menu item data 
* LBX-3577: Open API POS menu and restaurant importing 
* feat(Revel): import sizes 
* Org Eng: use tip suggestion from delivery provider 
* Finix hotfix: index error in gateway_params 
* API: load order if necessary for get available_discounts 
* LBX-3577: use lowercase for generated Agent staff users 
* Toast: Automatically setup unknown imported menus (LBX-9782) 
* LBX-13271 Add store_image field to location APIs 
* fix: switch "insert_generic_import_data" -> "import_menus" to avoid KeyErrors 
* add hints; add apple public key; remove finix default 
* LBX-13593: publish change event for in-process orders on login or register 
* feat(Agent): extract low inventory threshold (LBX-13541) 
* LBX-13551: Revert Changes to submit order redeem_coupons 
* LBX-13794: fallback to restaurant phone number for provider deliveries of external orders 
* LBX-12436 Add unavailable items and categories API 
* LBX-9675 Add e-contact based on service type 
* LBX-13683 Create bulk staff user creation API 
* LBX-5575 Adjusting migration order dates to location's timezone 
* feat(Agent): add flag to control imported menu activation (LBX-13826) 
* revert use return from pricing_provider to call comp card provider(LBX-5648) 
* LBX-4190 DoorDash: Self-Service Onboarding 
* CallCenter: query for earliest day(LBX-14048) 
* LBX-2579: assume prep time includes estimated delivery time for provider deliveries 
* missed file(LBX-14048) 
* start_order.coffee indentation(LBX-14048) 
* LBX-13945 Order search endpoint performance improvement 
* LBX-14233 Adding provider_pricing, status update log when emailing Quote 
* LBX-13897 -Ability to Disable Packing Lists 
* Feature/LBX-13951: Allow adding fixed type tax rate (Toast). 
* CallCenter: use restaurants today, when updating order time(LBX-14048) 
* LBX-13447 Doordash menu min_option_choice_quantity to = min_qty inste… 
* LBX-14272: Encode address for geocode searching 
* Agent: modify auto-created mode nomenclature 
* Task/lbx 13447 - Revert min_option changes 
* LBX-14006 Coupon restaurant availability APIs 
* LBX-4539 menu management phase 1 
* LBX-13803 - House account billing uses auth amount rather than capture amount 
* Query parameter type changes in sqlGetPaymentsWithTransactionType.sql  
* LBX-15989: fix import merge task cycle for NorthStar 
* LBX-14291 Order search endpoint to return limited orders per day 
* LBX-16041 Order search endpoint to return isdelivery 
* LBX-14283: Menu Engine: fix setting special query settings 
* Fetch coupon bank item without rest id filter 
* LBX-13903 Ability to Upload a CSV with Multiple CLUs to a Single Coupon 
* LBX-16060 : Incorrect sql parameter name during security code creation 
* sort restaurants if no search_criteria(LBX-12726) 
* LBX-16096: remove problematic decorator from "merge_import_menu" 
* LBX-13901  enable/disable gift card pin 
* LBX-16047: Menu Enging: cache publish image fileames to use across ZODBs 
* LBX-16088: Grubhub v2 menu export: handle defaults 
* Fix DoorDash SSIO menu name issue 
* LBX-15968 Schema.yaml Web Deployment Authorization Field Removed from Excluded option list on API 
* LBX-13890 LBX-13891 LBX-13892 Enable POS/Delivery/Order Aggregation Providers 
* Agent(fixup): actually modify auto-created mode nomenclature 
* Sift fraud events(LBX-14246) 
* LBX-16119 - Hurts Donust Menu  
* LBX-16151: fix menu category image import 
* LBX-16122 NDCustomerEngine: add a query search for a customer record … 
* Sift: do not send order_changed or check_score events to sift for order provider orders 
* add to sqlquery 
* Fix: sql_get_user_info dtml expr for conditional external_id and prov… 
* changed the sql condition to just  for external_id 
* LBX-16179: re-acquire import merge lock after commits 
* LBX-9782: fix Toast menu creation with existing menus 
* LBX-14245 Matching new admin (Analytics>Sales) query with old admin (Reports>Sales by Source) 
* LBX-16148: import item allergens and calories (initially for Open-API POS) 
* LBX-16310 Remove left join  on mgmt_restaurants_view 
* fix doing two calls to save_order 
* NDConfiguration LBX-16256 remove merchant_id google_pay 
* Okta: add okta and foreign auth providers(LBX-13697) 
* LBX-16609 Add enable_loyalty field to service type config API 
* LBX-13682 Change role column type 
* Okta: get config fields from provider section; lowercase okta for chainConfig(LBX-13697) 
* LBX-16382 Change event type name 
* LBX-16364 Customer edit error 
* LBX-16069: Add POST customers/{customer_id}/payment_token/tip 
* LBX-16622 Add order_comments on start_order for new admin 
* LBX-16656: Fix response value order 
* Revert "NDConfiguration LBX-16256 remove merchant_id google_pay" 
* LBX-13448: Menu import: track and manage pick list defaults 
* fix(Agent): subtract provider-paid taxes from tax_cents [LBX-13944] 
* Load gift card fix(LBX-3783) 
* Sift: do NOT send order_changed events(LBX-16698) 
* LBX-16683 start_order deleted/changed item bug fix 
* Paytronix: update host connection when reversing transaction if balance < order total(LBX-14011) 
* LBX-13448: Menu import: clean pick lists with no defaults 
* fix: add missing comma (LBX-13944) 
* fix: disambiguate "paid_cents" column, fix syntax (LBX-13944) 
* Feature/LBX-13939 : Added alcohol info to uber menu 
* Feature/LBX-13938 Added alcohol info to grubhub menu 
* LBX-16102: menu import: fix pick list triggers for multiple menus 
* NDCustomerEngine: LBX-16719 pass cid and token_lifetimee on mail_newu… 
* RPC-QUEUE: create timed variable to update rpc subscriptions more often in prod(LBX-13611) 
* LBX-16910 Allow search by company name 
* LBX-16690 Fix Finix ASCII error 
* feat(NDExternal): add "order_placed" hook to SFL/Toast instore "ndxtal/submitOrder" orders (LBX-16376) 
* LBX-16354 Fix report manager role issue 
* LBX-16945: fix service type updates for non-Admin users 
* LBX-16980 DoorDash SSIO API changes 
* LBX-17045, LBX-17047 intercom customer hash changes 
* LBX-16943: include the list of available menus in menu caching ETag 
* LBX-16912 When service type has requires_guest_count set to true, enforce guest count on call center. 
* LBX-16132  LBX-16129 Add new fields to the extra column in the restaurants table 
* LBX-16969: Open API POS: import item classes 
* LBX-13902 Gift card setup and configuration 
* LBX-9486- Doordash Delivery Provider not changig in location update 
* AgentServer: LBX-14517 Add daas orderitem when there is daas_pickup_t… 
* AgentServer: format date string to display better readable timestamp 
* LBX-13902 Missing model 
* LBX-17082: clear allergen and nutrition import data 
* AgentServer: convert zope DateTime to datetime 
* LBX-16852 Fix report manager permission issue 
* Bugfix/LBX-16834 Revel retrieve child items pick lists from raw_attributes. 
* LBX-16969: support importing non-reserved item classes 
* LBX-16732: Fixed final amount for migrated orders and some polishing. 
* Netlify Site Management & SSL Management - LBX-13918 
* Fix gift card configuration steps 
* LBX-17266 Change DoorDash SSIO even type name 
* LBX-17233 Change max_distance_miles field validator 
* LBX-13919 Location actions API 
* LBX-16944 service type api changes 
* feat(NDExternal): update "customer_info" for externally-placed orders 
* Netlify Site Management - Exist Environment problem & Response format 
* LBX-9486-Provider-Delivery-Soft-Delete 
* LBX-17278 Call center cannot edit order when order has no item 
* LBX-17298: API: cache all-stores searches 
* fix(Agent): restrict deletion of unavailable children to those present at the currently-importing rest 
* LBX-13906 Enable order in advance 
* Export simple Prometheus metrics 
* LBX-9486 Delivery Provider Soft Deleted Records 
* Bugfix/LBX-17476 Create menuitem object for combo modifiers [REVEL]. 
* LBX-17455 - NDExternal attempt to fetch loyalty config to make sure t… 
* Fix UnicodeError exception in the DoorDash SSIO API 
* LBX-11094 Add internal notes to an order 
* LBX-17392 Add fraud detection to Finix gateway 
* Task/lbx 16817 square payment reauth 
* always convert cnon token to ccof so it can be reused 
* LBX-17687 Add virtual brand support to DoorDash SSIO 
* LBX-17268-Forbidden: Security token is invalid or has expired (during password reset)  
* LBX-17578, LBX-17223 - Walk all attributes of matrix parents and fixed "KeyError". 
* Netlify Site Management Api - Revisions 
* LBX-12723: Update loyalty_coupon to return external_id 
* [AKIN]: Netlify Site Management Schema.yaml, Filter Changes 
* LBX-17762 Fix wrong menu generate problem 
* LBX-17762 Fix virtual provider unique key problem 
* LBX-17304 Fix the role superiority problem 
* NDExternal: add  instore_fixed_tip_cents list in get_configuration 
* LBX-17637 : Assign pick lists to combo product. 
* HOTFIX REVEL : Create distinct categories for targets belonging to multiple upsells 
* LBX-17475: Order Engine: enforce menu hours for time bumps 
* NDExternal: LBX-17569 handle_loyalty_inquire increase retry attempt f… 
* LBX-17268-Password Reset for imported users 
* LBX-18169: Agent: include refund details in orders 
* LBX-17329: fix ownership of proxy-guest CC accounts 
* LBX-13902 Fix gift card configuration issues 
* update instore_fixed_tip_cents defaults(LBX-17535) 
* fix(Revel): Improve combo product set modifier class picklists 
* Fix(Revel): Use unique keys for picklist default insertion 
* LBX-17470 nd-ordering client getting "The order has been updated since checkout started" for quote link check out 
* LBX-17678 redeeming gift card using scan to pay 
* LBX-18171 Customer List query filter on new admin customer screen 
* LBX-12826 Add order transfer APIs 
* LBX-18482 Add permission control to management APIs  
* LBX-17678 Redeeming gift card using scan to pay CC support 
* LBX-17014 Delivery Minimum 
* add missing foreign_auth_config_fields for okta(LBX-13697) 
* LBX-17080 Delivery order_minimum fix 
* LBX-18576: auto assign menus and fix importing subcategories for Open API POS 
* NDExternal: adjust the order of when external_order_id gets saved 
* hotfix: handle and log "AttributeError"s for nex-restaurants 
* LBX-18622: API: briefly cache rendered Grubhub v2 menus 
* Bugfix/LBX-19043 Assign default_item_size_uid for pick list defaults [TOAST] 
* LBX-18169: Fix resending voided/refunded orders to POS 
* Fix/LBX-16592 Changed initial pick list type for toast. 
* Agent: accept POS notification of resent order 
* Fix AttributeError in the service type config API 
* Get all money values in cents 
* Change the response of the payment-with-qr API 
* Payment with QR API changes 
* LBX-19144 Finix fraud detection issue 
* LBX-17522 Allow for multiple email recipients for Command Center (Call Center) orders 
* LBX-17913 Increase get_order retry number from slave 
* LBX-18578 Missing config for forgot password from email address 
* NDExternalOrdering: Add provider_order_number in handle_loyalty_inqui… 
* Edit Order - LBX-18575 
* LBX-19252 boaBuyPass Duplicate Transaction Error 
* LBX-17914 Edit Customer using Command Center UI is Missing Customer Fields 
* LBX-14005 Curbside Checking for Guest Accounts 
* LBX-11094 Add comments_to_store field to the order update API 
* Bugfix/LBX-19417 : [Simphony] Set free_up_to for combo item 
* LBX-17522 Allow for multiple email recipients for Command Center (Call Center) orders WIP 
* LBX-19259 Using new Admin to update 3PD integrations breaks settings 
* LBX-16950 Fix order cancellation email being sent twice 
* Add square foreign-auth schema to NDConfiguration 
* LBX-13903 Fix discount code not valid issue 
* LBX-17040: API: use variants in returned order-level pick lists 
* LBX-19506 Fix TypeError issue 
* fix schema hint for tax_fudge to correctly display half cent (.5 inst… 
* LBX-13919 Add missing fields in the location data 
* API: serialize ECard gift card balance inquiries 
* Fix ConflictErrors in ECard balance inquiries 
* LBX-12825 Exclude unused service types 
* LBX-19216 Add store manager permission to customer APIs 
* updating submit_externally_controlled_order and submitOrder 
* LBX-19251 Add restaurant_count on get_restaurant_classes so that online ordering can show when locations are assigned to class 
* Update submitOrder to manually set order to status 12 to await Instor… 
* LBX-19382 Location Menu Hero Image 
* LBX-19818: Update GET /loyalty to return schemaId 
* NDOrderEngine: fix issue with instore not closing an order 
* LBX-12825 Add contact_name to customer address API 
* [NDMigration] Strip phone number if it's starting with 1. 
* Logging: first pass at DataDog logging and instrumentation 
* LBX-l9886 NDConfiguration NDExternal: add a config flag for disable_l… 
* LBX-19251 reverting changes 
* Add cc email add and update APIs 
* Agent: fix strptime conversion failures 
* LBX-19802 save as quote query 
* Handle the decline error in Finix gateway 
* LBX-19415: Revel: import split modifiers as styles (sections) 
* fix: give datetime timezone context 
* LBX-19883 Allow delete override hours 
* LBX-19415: Revel: rework PL target generation for splits 
* LBX-19367 NDOrderEngine: Sort orderitems 
* fixed minor typo 
* GHv2 menu export: reduce memory usage 
* LBX-19798 Phone number duplicate check 
* Added update_pick_list_descriptors to schema yaml 
* LBX-19609 Add max subtotal field to service type config 
* Finix: Validate buyer identity fields(LBX-19876) 
* Revel: handle default split modifiers 
* Revel: use only free_up_to, not defaults_are_free 
* Finix: round total_fee for Finix(LBX-19954) 
* LBX-19882 Location update port,ip_address 
* LBX-19722 missing show_nutrition 
* LBX-19415: Revel: use default "0" split for combo modifiers 
* LBX-19415: Menu API: propagate use_variants to grandchildren 
* LBX-19640 Order Injection Rate Report 
* LBX-19585 Location availability API changes 
* Toast: record void payment 
* Fix the total rates calculate problems 
* LBX-16134 Add additional_hours_description field to location API 
* LBX-20160 Service type config changes 
* LBX-20308 Backend for Loyalty Manager roles permissions 
* Deploy/dev lb3 
* LBX-19975 - allow toggle for skipping creation of loyalty accounts for guests 
* LBX-20459: [Open-API-POS] import each menu with clean data 
* LBX-19639 86 item report API 
* LBX-20499: Initial Setup for Adyen Payment Gateway 
* LBX-19641 Export events 
* DI-1927: add resource to top-level DataDog span 
* Changed enable_split_modifiers_full_price_charge default value 
* config methods; some more boilerplate(LBX-20517) 
* Square: respect modifier list selection type when setting PL min/max 
* create revel endpoints for Instore Loyalty and a sync incoming endpoint 
* Call center tax exempt v2(LBX-20564) 
* Make child items unavailable for combo product modifiers. 
* Migrate preptimeminutes and preptimeasadditioanItem for order item 
* LBX-19721 Foxtail Coffee - Locations not importing the prep time lead time 
* [LBX-20568]: Updated get membership SQL query 
* LBX-20224 Guest account labeled as "Guest XXXX" instead of First and Last Name 
* LBX-19721 Foxtail Coffee - Locations not importing the prep time lead time 
* LBX-19929: parallel balance check and ECard speed up 
* [LBX-20516]: Adyen Integration 
* LBX-20829: Add enable_order_pass_through to True 
* LBX-19929: speed up gift card balance checks 
* LBX-19976: send a "ready for pickup" receipt when a KDS order-ready event is received 
* LBX-19929: restore chain config setting and extend to waitOnStatus 
* hiding expired coupons should not hide coupons without an end date 
* NDOrderEngine: LBX-20837 Add order_placed hook when Scan To Pay order… 
* LBX-20870: Update register to throw error 
* LBX-20843 Geo location flag to settings 
* pos_entry_mode reversal and credit(LBX-20647) 
* LBX-20683 Add new sort options to order list API 
* LBX-20910 add is_tax_exempt on customers/me 
* LBX-19977 Allow guests to edit scheduled orders 
* LBX-20702 Include Partially Paid and Admin Hold 
* NDOrderEngine: LBX-20789 add param arg skip_credentials_check to get_… 
* Adyen refund/void implementation(LBX-20520) 
* Returning gift full card number(LBX-20973) 
* Implemented email validation for user registration process(LBX-20788) 
* LBX-20404: Changing issue_date to Int 
* Upload apple pay certificates using settings. 
* LBX-21108 Ingnore end_of_day if hold_future_orders and hold_same_day_… 
* Apple Pay Developer Merchant ID Association API(LBX-20803) 
* LBX-20927 new role groups and permissions 
* LBX-20927 New role groups- typo fixed in DEFAULT_PERMS 
* Worldpay suggested changes for G037(LBX-20647) 
* LBX-20693 : Add pricing provider rest record during import 
* LBX-21250 sift_fraud_enabled added to store configuration endpoint 
* Implemented masking of sensitive data in logs(LBX-20698) 
* LBX-21387: Redis RPC: add DataDog spans for call and notify 
* Add rokt flag that mobile/web uses for rokt partnership sdk 
* LBX-20445 captured credit card report 
* Adyen: working apple/google pay(LBX-20521) 
* Formatted message for Finix payment failures(LBX-21270) 
* LBX-20383: Grubhub V2 menu: fix manual application of speedup 
* LBX-21430: Grubhub V2 menu: use unique ID for combo choices 
* LBX-20927 New management api endpoints added for not to call zmi functions directly from FE. 
* LBX-21212 Order injection reate report sql improvments 
* LBX-21587 Increase Captured Credit Card Report max_rows to 5000 
* LBX-20871 Add end_of_day on LocationSearch 
* LBX-21559: Revel: tweak show_qty import heuristic 
* LBX-20913: Revel: make a best-guess default tax class 
* LBX-20927-New role groups 
* LBX-21559: Revel: merge pick lists that are used in multiple ways, preserving fields like show qty 
* LBX-20913: create default taxes by service type 
* LBX-19411: Items Remain in Cart Despite Timeslot 
* LBX-19340 Menu API version fields input chaged to button. 
* LBX-21729: Revel: propagate parent tax classes to modifiers 
* LBX-21220 management api management/stores endpoint limit increase 
* New admin cancel delivery does not cancel delivery 
* LBX-21548 86 items report category list filter 
* Adyen: remove encrypted prefix on keys 
* LBX 21022/teach grubhub export to specify item timeslots 
* LBX-21686 doordash recipes 
* add enable_sort_defaults_to_top(LBX-21808) 
* MenuEngine: teach Grubhub to specify items' timeslot availability 
* Hotfix: Added custom JSON encode to handle custom types(LBX-21884) 
* LBX-21782: Fix replace unicode with encode 
* LBX-19411: removing original_order_details variable from _start_order… 
* LBX-21929: fix Revel tax import for duplicated service type UIDs 
* Agent(Square): merge modifier & modifier list availability 
* LBX-21183: Handle Revel webhooks 
* LBX-21219 Perms update 
* Included store ID in Adyen payment request(LBX-22077) 
* LBX-22115: add tax rules for split Revel modifiers 
* LBX-20927 Service Types endpoint perms 
* Revert "Merge pull request #1071" 
* Adyen: prevent pop from failing if key does not exist(LBX-22127) 
* Adyen: missing conditional for google/apple pay 
* Fiserv cardpointe 
* allow show_future_orders config; add amount of days_in_future to be configurable(LBX-21836) 
* fix: combo items used wrong modifier prompt IDs 
* LBX-22244:  use default tax class (-1) for Revel prevailing taxes 
* LBX-22027: support multiple instances of a pick list (Revel modifier sort order) 
* LBX-20874 Reporting perms added to business_hours 
* NDExternal: Additional keys to get_configuration 
* Cardpointe: add new required field ecomind 
* Update oms to OMS; make API settings script match zope chain_config_interface script(LBX-21836) 
* LBX-22296: Uber menus: cap default qty to max permitted 
* Customer registration validation update(LBX-21517) 
* LBX-22336: Grubhub hours in menu exports 
* LBX-23608: NDORDERENGINE-NDAPI add functionality of reopening order a… 
* LBX-22021 Enabling billing adress for call center default value update 
* LBX-16320: Toast: handle multiple sizes with same name 
* LBX-22434: Grubhub V2 menu: fix unique IDs for combo choices (i.e. VALIDATION_INVALID_REFERENCE errors) 
* LBX-22434:  More Grubhub duplicate ID fixes 
* LBX-22019 service type update 
* temporary prod smoke test cardpointe base url 
* Cardpointe: add default prod base url;add optional prod base url;add testing parameter 
* LBX-22540: Grubhub v2 menu export: fix max quantity for shared pick lists 
* DI-3721 Added circle-ci config 
* LBX-22523: Grubhub menu export for non-free defaults 
* NDOrderEngine: LBX-21871 pizza left/right validation 
* Fixes sales report. 
* Auto publish menus to providers when items are added/removed from unavailable_items (LBX-22648) 
* LBX-22452 enable fire order for new admin 
* Auto publish menus to providers when categories are added/removed from unavailable_items(LBX-22648) 
* NDMigration: LBX-22772 add apple/google SSO to externalids when impor… 
* LBX-22496 Add filter for discount codes in new admin 
* Task/agent server report pos response other 
* LBX-22504: Deleting adjustments before deleting delivery rule 
* Wait for Square order update before processing payment (LBX-22482) 
* LBX-22789 Tip Not Displayed in Itemized Breakdown After Switching from Delivery to Pickup 
* LBX-22510-Override local time slots 
* LBX-22101 platform 21 added to new_users_web field 
* Cherry-pick missing Subversion commits into master 
* LBX-22330 Gift card refund error 
* LBX-22442 Finix Fee Profile Integration. 
* updated circleci pipeline 
* implement api endpoints for working with multiple guests in house acts 
* Added disable_emails chain config under registration (LBX-23109) 
* Task/lbx 23030 3pd item time offset 
* LBX-21682: Bulk update override hours 
* LBX-22260: Fix time slot query 
* NDConfiguration: update enabled_rokt schema.yml. to show default as T… 
* NDApi: include restid when checking for duplicate coupon_avail(LBX-22335) 
* LBX-22910: Set error message for used copupons 
* LBX-23131 Platform parameter added to Service type report 
* LBX-23249: send order_update messages synchronously 
* LBX-23249: fix chain config lookup for mgmt/api 
* LBX-23249: Order engine: fix typo in flag lookup fix 
* LBX-23258 NDExternal: Fix issue when autoapply coupon that are not fo… 
* fix(OE): save order details to session during tip updates 
* LBX-23264: duplicated missing defaults 
* Added support for Modifier-Modifiers in AOO import (LBX-23018) 
* Sync subversion changes from George 
* LBX-22830: Fix discount to validate bank reward 
* git workflow - add git action for sync-release 

