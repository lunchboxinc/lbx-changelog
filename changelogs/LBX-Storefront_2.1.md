## v1.1.3 - <span class="utc-date">2025-06-10T20:17:08Z</span>

LBX-23413 - Custom Terms & Conditions

## v1.1.2 - <span class="utc-date">2025-06-03T13:52:50Z</span>

LBX-23897 - replace cdn.mydelish.menu with cdn-branding.lunchbox.io in branding URLs

## v1.1.1 - <span class="utc-date">2025-06-02T12:12:31Z</span>

LBX-22291,LBX-22613,LBX-23379 - Order Scheduler

## v1.0.16 - <span class="utc-date">2025-05-29T14:55:42Z</span>

LBX-23785 - fix: prevent custom tip amount from exceeding 100% of order subtotal

## v1.0.15 - <span class="utc-date">2025-05-28T16:49:53Z</span>

LBX-23792 - fix: normalize modifier quantities to match confirmation display in PDF output

## v1.0.14 - <span class="utc-date">2025-05-28T15:35:48Z</span>

LBX-23803 - fix: long password input overflow issue with proper alignment for password toggle icon 


## v1.0.13 - <span class="utc-date">2025-05-28T09:14:53Z</span>

LBX-23449 - show test stores only for loggedIn users with management rights

## v1.0.12 - <span class="utc-date">2025-05-28T09:13:46Z</span>

LBX-23449 - added missing info modal

## v1.0.11 - <span class="utc-date">2025-05-27T10:44:52Z</span>

LBX-23220 - item information in confirmation mapped to cartView


## v1.0.10 - <span class="utc-date">2025-05-23T09:57:09Z</span>

LBX-23788 - don't open picklist modal if order pick list is empty

## v1.0.9 - <span class="utc-date">2025-05-22T17:25:19Z</span>

LBX-23776, LBX-23780 - DOMNodeInserted is no longer used, so it has been replaced with MutationObserver, and a few console errors have been fixed.



## v1.0.9 - <span class="utc-date">2025-05-22T17:24:46Z</span>

LBX-23776, LBX-23780 - DOMNodeInserted is no longer used, so it has been replaced with MutationObserver, and a few console errors have been fixed.

## v1.0.9 - <span class="utc-date">2025-05-22T17:23:26Z</span>

LBX-23776 and LBX-23780

DOMNodeInserted is no longer used, so it has been replaced with MutationObserver, and a few console errors have been fixed.

## v1.0.9 - <span class="utc-date">2025-05-22T17:22:26Z</span>

LBX-23776 and LBX-23780 

DOMNodeInserted is no longer used, so it has been replaced with MutationObserver, and a few console errors have been fixed.

## v1.0.9 - <span class="utc-date">2025-05-22T17:21:44Z</span>

LBX-23776 and LBX-23780 -- DOMNodeInserted is no longer used, so it has been replaced with MutationObserver, and a few console errors have been fixed.

## v1.0.9 - <span class="utc-date">2025-05-22T17:21:13Z</span>

LBX-23776 and LBX-23780 -- DOMNodeInserted is no longer used, so it has been replaced with MutationObserver, and a few console errors have been fixed.

## v1.0.8 - <span class="utc-date">2025-05-14T10:36:23Z</span>

LBX-23520 - ensure bulk modifier validation checks only related child items

## v1.0.7 - <span class="utc-date">2025-05-14T07:51:07Z</span>

LBX-23254 - The Favorites category is now only displayed on the web when the toggle in the admin panel is enabled. The category name is no longer hardcoded — it is now dynamically retrieved from the admin panel and can be customized.

## v1.0.6 - <span class="utc-date">2025-05-12T14:23:48Z</span>

LBX-23530 add + sign to the left of price for items with additional cost

## v1.0.5 - <span class="utc-date">2025-05-09T13:34:02Z</span>

LBX-22737 remove duplicate items from favorite items based on item_id

## v1.0.4 - <span class="utc-date">2025-05-06T15:17:29Z</span>

LBX-23435 - Special Instructions now support dynamic character limits with input/textarea switching and 120-char fallback.

## v1.0.3 - <span class="utc-date">2025-05-06T12:30:29Z</span>

LBX-23501 --- If the user's session is active and the disable_login value returns true, the session will be terminated and the login button will no longer be displayed. The login button will also remain hidden when the session is inactive.



## v1.0.3 - <span class="utc-date">2025-05-06T12:29:07Z</span>

LBX-23501 --- If the user's session is active and the disable_login value returns true, the session will be terminated and the login button will no longer be displayed. The login button will also remain hidden when the session is inactive.

## v1.0.2 - <span class="utc-date">2025-04-30T13:25:18Z</span>

LBX-23369 added city to the address in the confirmation page

## v1.0.1 - <span class="utc-date">2025-04-29T15:11:09Z</span>

## What's Changed
* fix: LBX-23417 cart addition issue resolved 

## v1.0.0 - <span class="utc-date">2025-04-29T15:00:02Z</span>
## Initial Release Notes:
* Service type id added when getting the stores in add new credit card modal 
* Update index.js 
* Validate inputs on mobile payments 
* Merge categories 
* Pre selected size logic added 
* Don't add marker to map if lat lng is missing 
* Hide price if zero option added 
* Chain name added to auto login payload 
* User details added to full story 
* Logo redirect url added for the logo on top left 
* Quantity part in item modals changed to an input 
* Get missing branding data from default data 
* Revert "Quantity part in item modals changed to an input" 
* Revert "Revert "Quantity part in item modals changed to an input"" 
* item_config_id check fixed 
* Min max modifier control updated 
* New cart design 
* Hide hidden child items in cart and order details 
* Gift cards page display bug is fixed in profile dropdown 
* Postal code bug for Canadian addresses is fixed 
* Show remove item from cart button if minimum quantity is reached 
* Content hub feature 
* Customer id change when a guest user uses an existing guest user's email 
* Display company info input in Sign up and Add new address modal 
* Toaster visibility bug is fixed 
* Item note input default label changed 
* Hide progress bar if last tier is reached 
* Don't update customer info if api returns an error 
* CSS fix for rewards page 
* New animations added for quick add 
* Quick add on loader bug fix 
* Remove item modal removed when item is removed through menu page 
* Popular items section customization bug fixes 
* Fly to cart animation bug fix 
* Custom pop up key changed 
* Sentry added for tracking errors 
* Allergy icons and tooltip added 
* Popular items change to support adding it from the new admin 
* Hide CVV if it is not required 
* Sentry debug code removed 
* Hide $0 prices in upsells and popular items if hide_price_if_zero is true  
* Email option key changed to true everywhere 
* Navigation arrows added to upsells in cart 
* Gift card hide security code if not necessary and design changes 
* Show discount_code if name is null for rewards 
* Show CVV field for Square always 
* Show Select Another Location button in address is outside of delivery zone in date and time selection modal 
* Add guest count input when creating order and to checkout page LBX-2551 
* Item loader bug fixed - LBX-10011 
* Bug fix for displaying store hours - LBX-3929 
* Display hours based on the selected service type - LBX-9547 
* Marketing box disable bug fix - LBX-10221 
* Marketing box bug fix 
* Show routes for profile pages - LBX-3249 
* Routing conditions updated - LBX-3249 
* Direct users from order quote emails to the new storefront UI - LBX-9347 
* Add phone number validation for phone numbers that starts with 1 - LBX-9584 
* Font loading logic changed - LBX-7843 
* Add navigation guard to profile pages if the user is not logged in - LBX-10380 
* Google pay branding guidelines changes - LBX-10419 
* Use configuration endpoint instead of theme config to display or hide order and item notes - LBX-10457 
* Multi nested modifier quantity bug - LBX-9949 
* Change active page color to primary color on the left side in profile page / LBX-10611 
* Curbside checkin feature - LBX-5072 
* Apple Pay and Google Pay support for Finix - LBX-5102 
* Show 'Your Cart' text at the top of cart on checkout page - LBX-10642 
* Show allergen icon and tooltip in item modal and modifiers - LBX-10529 
* Rewards page loyalty tracker bug fix - LBX-10624 
* Separate CSS code from components to their own CSS files - LBX-10643 
* Content hub hub marketing item button bug is fixed - LBX-11080 
* Modifier image design update on grid modifiers - LBX-10901 
* Rewards page ability to hide lifetime points and displaying customer sign up date - LBX-10619 
* Menu design change under 600px - LBX-10904 
* Rewards logic rewrite - LBX-10624 
* Loyalty bug fixes 
* Internal Service Type bug fix - LBX-10187 
* Suggestions list CSS updates - LBX-11122 
* Make pickup the first service type if it is available - LBX-10580 
* Order checkin url handled for sign in with security token 
* Gift card page impovements 
* Add ability to expand collapse modifiers - LBX-11483 
* Bareburger bug fixes 
* Quantity selector icon change - LBX-11828 
* Back button logic change in Accounts page - LBX-11795 
* Show 3 lines of item description in menu page - LBX-11976 
* Get the next tier's info if there is no conversion perk - LBX-11721 
* Show location name in the order confirmation page - LBX-11800 
* Nested modifier bug fixed - LBX-12218 
* Gift card input type changed to text 
* Show Purchase Requirements error as a modal - LBX-12359 
* Item level deep link - LB-10938 
* Keep cart modal open after upsell is clicked - LBX-12443 
* If auto: true for an item, hide Modify, Edit buttons and quantity selector on cart 
* Item image is hidden on cart if item has auto true 
* Square - Get app id and location id from configuration endpoint 
* Get order comment for reorder on checkout page - LBX-12491 
* Update order info banner for mobile - LBX-9463 
* Change locality to neighborhood for city - LBX-11703 
* External Links added to Account page - LBX-12620 
* Text 'Other' changed to 'Custom' in tip section - LBX-12724 
* Support dark background colors - LBX-10679 
* Secondary button UI bug is fixed 
* Revert "Change locality to neighborhood for city - LBX-11703" 
* Try to get city from neighborhood first if it is available 
* Revert "Try to get city from neighborhood first if it is available" 
* Lbx 11921/optin 
* email optin and phone optin bug fixed 
* Apple sign in bug fix 
* Dark mode UI fixes 
* Email optin issue on SSO login - LBX-13130 
* Dark mode UI fix 
* Show order errors on menu page when Checkout button is clicked - LBX-12381 
* Revert "Show order errors on menu page when Checkout button is clicked - LBX-12381" 
* New control added for all menu item images - LBX-13147 
* Modifiers scroll after selecting Required - LBX 12846 
* Filter out the menus that does not have any categories - LBX-10850 
* Selected modifier icon color change - LBX - 13194 
* Console error fix when checking for errors 
* Guest count company name changes - LBX-10924 
* Show order errors when checkout button is clicked on cart - LBX-12381 
* version 1.2.05 
* Loyalty progress bar display issue - LBX-11150 LBX-13289 
* Email verification logic - LBX-13264 
* Customer data null check 
* Don't show if company_name is 'null' - LBX-13382 
* Company name null fix - LBX-13382 
* Logo redirect url changes - LBX-13456 
* Display manage payments option added to Design - Web - Display Options - LBX-13457 
* Tip calculation logic change - LBX-12005 
* Hide confetti option added - LBX-13474 
* Sms optin and email optin check added - LBX-13603 
* Display addresses in profile - LBX-13473 
* Show api error message instead of static message in password reset page - LBX-13616 
* Max qty check on quick add - LBX-13393 
* Max qty order level error message 
* Store image changes - LBX-13458 
* Generic error modal bug fix 
* Menu disclaimer added to the footer - LBX-13470 
* Menu disclaimer bug fix 
* check min qty deleted 
* tipping issue fixed 
* Lbx 13828/last menu category 
* tip's showing conditions have changed 
* LBX-13977/giftCardTextFix 
* Lbx 14238/cvc 
* Lbx 10315/upsell flow alternative 
* item qty loader bug fixed 
* contenthub page bug fixed 
* Lbx 14304/modifier bug 
* changed service_type_id hard code 
* changed reload amount values 
* changed gift card label 
* changed font weight of the dollar amount 
* if this.normalizedAddons.sizes false return normalizedAddons.nutrition 
* promo code discount line bug fixed 
* added balance value for checkout page(gift cards) 
* visible in cart 
* Radar map integration 
* Lbx 16160/dropdown fonts 
* changed calculateChoicesPrice func 
* added radarautocomplete for giftcard 
* changed giftcard image for buygiftcard 
* if require cvv=false only on new cards 
* Lbx 13981 
* Lbx 14301/pay proc 
* changed primary-text-color 
* edit modifiertype color 
* edit upsell items 
* Hide store address 
* added showAddress for infowindow 
* added hide_store_address for dateandtimemodal 
* Lbx 16615/custom tipping 
* added hide_store_address for card and checkout 
* when no lat/lng nor address is provided we sort by name, if lat/lng o… 
* added subtitle 
* edit scrollToTheStore 
* mobile web to display order breakdown request 
* added hide_store_address 
* and rewards 
* added compcards 
* added few font-family 
* edit getTheLowestPrice 
* Lbx 14208/require guest phone verification 
* [LBX-16986] Error on Cart add on after 15 mins 
* edit auto_login 
* added extra links 
* edit subtitle 
* added store.extra.icon 
* changed conditions for guest count input 
* added error message for giftcardmodal 
* Lbx 16897/order throttling 
* Fraud detection 
* edit payer_authentication 
* Lbx 16117/include utensils 
* edit selectedMenuIndex 
* Meta location name 
* minimize clicks for cartview 
* added login page 
* edit location name 
* added okta 
* edit calculateChoicesPrice func 
* added addressSelected event 
* edit quickAddable 
* Lbx 16837/invalid name 
* edit allergens and itemclasses 
* edit allergens 
* added control to data 
* Lbx 19665/reorder button 
* handle quantity changes correctly for selected choices 
* Lbx 18499/return urls 
* if dark mode is on, the background-color of the radar is set to primary color 
* Lbx 19858/guest phone verified 
* edit formatEmailWhileTyping 
* Lbx 19644/location hero images 
* Lbx 16201/cart icon 
* edit dropdown z-index 
* If allow_guest_orders is off, it cannot proceed to the checkout page … 
* Lbx 19371/birthdate year validation 
* edit birthdate validations 
* [LBX-19829] use schema id to map tiers 
* requirement for being logged in 
* added meta pixel script 
* added facebook pixel events 
* fbq bug fix 
* save button text overflow issue by adding ellipsis for long text 
* Lbx 20463/drop off instructions 
* added min-width: 0 to .gridChoiceWrapper in ChoiceCell.css 
* Lbx 20795/payment methods 
* [LBX-15951] disable future order feature 
* Lbx 18594/hide phone number 
* transfer of hours to the next day when exceeding 24 hours and prevent… 
* Lbx 20972/full card number 
* Lbx 20885/remove lunchbox logo 
* Lbx 20873/tax exempt 
* [LBX-20678] giftcard reload amount dynamic 
* Lbx 21318/expand required collapse optional picklists 
* [LBX-21201] dynamic parent qty to child 
* Lbx 20873/tax exempt 
* new branch for launch darkly 
* LBX-18543 - Apple Pay Cert With Netlify Function 
* Lbx 21501/gift cards 
* LBX-18543 - Apple Pay Cert - Added New Redirect 
* ensure only missing branding properties are set to default values 
* edit taxexempt css 
* edit branding settings 
* Lbx 20774/max qty 
* [LBX-21327] renamed points value displayed at loggedout 
* Added new url in _redirects file for finix apple payment 
* allow spaces in first and last name inputs 
* Lbx 21630/responsive title modal 
* Lbx 21631/numerical keyboard pın input 
* hide gift card image on mobile when displaying full card number 
* fix birthdate input formatting and deletion handling 
* fix favorite location sorting on the web for registered users 
* Lbx 21377/support image custom popup 
* improvements to bulk rolled back 
* Lbx 21015/radar map 
* set "display_promos_and_rewards_on_cart" to false by default 
* add conditional rendering for item note label with multiple fallbacks 
* validate latitude and longitude values to prevent "Invalid LngLat obj… 
* fix: handle multiple opening hours by using start_time of first and e… 
* Lbx 22103/guest checkout terms 
* Lbx 20871/today hours 
* LBX-22156 - Added New Url 
* remove default "Hand to me" value for drop-off instructions 
* add sorting of items by price and free_up_to value 
* [LBX-20583] add try catch to gtm 
* Lbx 21713/email validation 
* Lbx 21201/handle bulk modifiers 
* Rokt 
* bulk conditions changed 
* LBX-22354 - Fixed Google GTM Code 
* Rokt new variables 
* remove unused watchers orderData and loggedIn from Rokt.vue 
* Lbx 20777/new parameters for pixel 
* Clear cart button 
* added errros to error check in check payment 
* Remove LD checks for Rokt 
* Lbx 22557/unverified user url access 
* Use config googlemaps 
* add check for paymentWallet in localStorage to set paymenttype 
* set country code from config for radar autocomplete 
* [LBX-21843] Add fav section on menu category 
* LBX-21843 withdrawn 
* update rewards flow to match app layout 
* fix inconsistent email display in account subheader 
* fix unresponsive back to locations button 
* Lbx 21620/email validation gift card 
* prevent reload of gift card without selecting an amount to avoid spin… 
* [LBX-22801] Dynamic character limit on guest notes 
* Lbx 22702/remove perks toggle 
* [LBX-21843] add fav section on menu 
* merge to master 
* Lbx 22987/fix bulk modifier quantity 
* fix: display prices for bulk items and items with quantity greater th… 
* LBX-23141 Hide vehicle info when displayoptions.hide_vehicle_info is set 
* Fix bulk prices 
* fix: ensure only visible services are selected as default 
* fix: correct final price calculation for bulk and non-bulk modifiers 
* use hide_tiers 
* fix: correct schema comparison for filtering payment methods 
* clear stores by setting them to null 
* add gitaction for release notes 
* fix UI discrepancy in address dropdown on checkout page 
* refactor item and modifier lookup to use selectedUpsellData in the va… 