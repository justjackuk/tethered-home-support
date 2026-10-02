# Tethered Home Privacy Policy

Last updated 2 October 2026

Tethered Home is designed to keep household information under the control of the people using the app

## Information you choose to add

The app can store household names, member and pet profiles, optional profile pictures, cars, shopping items, meals, household routines, jobs, school items and project progress, care appointments, car reminders, household notes and deliveries. Personal goals, wellbeing routines, fitness progress, hydration progress and awards remain on the person’s device. School-project milestone points are shared with the household so the child’s progress appears consistently to household members

This information is stored on the device and, when iCloud sharing is used, in the household owner’s private CloudKit database and the invited household share

## Optional profile details, cleaning and budgeting

Display names and opted-in birthdays can be included in the private household share. Birth year is optional. Ordinary dietary preferences can be shared separately; medical information should not be entered in shared preference fields. Household roles shown in a profile do not change invitation, access-revocation or leaving controls.

Local-only health correction (in preparation, not yet released): the corrected app excludes food-allergy details and human care appointments, including medication support and medical appointments, from household CloudKit uploads. These entries remain in local app storage; assigning a responsible adult does not send that person a care reminder. Pet care remains household-shared. This describes the corrected candidate, not a guarantee that previously installed versions behave this way.

Earlier versions could include opted-in food allergies and human care appointments in household iCloud records. The correction does not silently delete those records: if legacy health information is detected, household uploads are paused and a status message explains why. Existing cloud records are preserved, and an additive local preservation copy is retained on iPhone. Previously saved independent copies cannot be recalled. Legacy health data can therefore remain in iCloud until a separately authorised remediation is completed; this is an unresolved release gate. App Privacy continues to declare Health while legacy cloud storage remains possible. Local app storage is distinct from Apple system device backups; exclusion of health information from those backups is still under verification.

Custom room names, cleaning schedules and completion records are shared with accepted household members. Completion contributes to the existing household points, history and reward goals. Reminder and gentle-display preferences remain personal to the device.

Home budget entries, income, expenses, savings allocations and currency remain in local app storage and are not included in the household CloudKit share or shown on the TV. The feature does not connect to bank accounts, initiate payments or store bank login details. Optional budget explanations use an on-device language model where available; no external AI provider receives budget prompts. Calculations are performed by the app, not the language model, and generated explanations do not change saved amounts. It is a planning feature, not professional financial advice.

Life admin subscription records, including recorded costs, billing frequencies and recorded cancellation status, are household-shared like other Life admin information. Linking one to a budget creates a private on-device budget entry; it does not make the original Life admin record private. Cancelling a record in Tethered Home never cancels a subscription with its provider.

## Apple services

Tethered Home requests access only when a feature needs it

- Calendar and Reminders access supports plans and reminders
- Health access supports an explicitly logged water quantity and fitness workouts deliberately started and timed on Apple Watch. Outdoor dog walks can include a workout route when authorised
- Location access supports local animal-walk weather checks, optional dog-walk route recording and optional live walk sharing
- Apple Music access supports authorised music suggestions and playback
- Notifications provide selected household and routine reminders
- Camera access is used only when the user chooses to photograph ingredients for on-device meal recognition
- Photos access is limited to pictures the user selects for household profiles or a local walk memory
- iCloud and CloudKit provide private sync and invited household sharing
- Widgets display a limited household summary from the app’s shared on-device container
- Live Activities display the status of a workout the user has deliberately started on Apple Watch

Access can be declined or changed in Apple Settings

## Household sharing

Only people invited through the household’s iCloud share can access shared household records

Health records, workout history, complete workout routes, personal goals, wellbeing routines, personal fitness progress, streaks and awards are not copied into iCloud or the household share

Live walk location sharing is off by default. A user must first enable the master control and then separately choose to share each individual walk. While sharing is active, Tethered Home displays a persistent warning and provides an immediate Stop Sharing control on Apple Watch and iPhone

Only the latest temporary location, activity name, member display name and expiry time are placed in the private household CloudKit share. Only accepted household participants can access that record. It stops being displayed after three minutes without an update and is cleared from the shared payload when sharing stops, the workout completes or is cancelled, or an app next detects that it has expired

Names and photos attached to completed dog walks remain in local app storage on that device and are not placed in CloudKit. A user may explicitly export a summary and optional photo using the system share sheet. Raw GPS coordinates are not included in that export

Hydration entries and hydration targets stay on the device and are not included in household CloudKit sync. Checking off a fitness item on iPhone does not create a workout; workouts are recorded only after the user deliberately starts and times an eligible activity on Apple Watch

Profile pictures are cropped and compressed on the device before being stored with household data. Other selected photos, including dog-walk memory photos and ingredient photos, remain local unless the user explicitly exports them with the system share sheet

Profile and pet photos are optional. A small cropped JPEG is included in the household owner’s private CloudKit share, visible to accepted household members on supported devices, including the Tethered Home TV app. Choose only pictures you have permission to share. Selecting a profile photo does not grant access to your entire photo library.

Photos can be changed or removed in My profile or household setup. Removal is synchronised to participating devices when they next connect. Leaving a household or confirmed loss of access hides shared profile photos in the app; retained local app data can be removed using Reset This Device. Access revocation stops future cloud access but cannot recall screenshots or copies independently saved by another person. Tethered Home does not upload these photos to a developer-operated server.

## On-device intelligence

Where supported, Tethered Home uses Apple Foundation Models on the device for optional positive reflections, goal guidance, meal inspiration and household budget explanations

Tethered Home does not send these prompts to a developer-operated AI server and Bark & Tide does not receive a compute bill for their use

## External links

Opening supermarket, takeaway, NHS or other external links is governed by the destination provider’s privacy policy

## Purchases

Subscriptions and introductory offers are processed by Apple through StoreKit

Tethered Home does not receive or store payment-card details

An accepted iCloud household invitation provides access through the shared household while that membership remains valid. This access is separate from purchasing or sharing an Apple subscription and does not create a subscription in the invited person's Apple Account. Leaving the household or confirmed revocation removes household access. Apple Family Sharing, where enabled, is a separate way to share a verified StoreKit subscription entitlement.

## Tracking and advertising

Tethered Home does not use third-party advertising, cross-app tracking or developer-operated analytics

## Retention and control

Users can stop live walk sharing at any time, remove local app data, leave a shared household or ask the household owner to revoke their access from Settings

The household owner controls the shared CloudKit record and invited participants through iCloud sharing

Reset This Device removes local Tethered Home information and private document copies from that device. Delete All Tethered Home Data clears the shared household payload and local Tethered Home data when the reset reaches participating devices. Original files imported from elsewhere are not deleted. Deleting the app does not automatically remove records retained in iCloud or cancel an active Apple subscription

## Contact

For privacy questions or support, email byteandtide@outlook.com
