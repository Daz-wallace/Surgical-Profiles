# Surgical-Profiles

Surgical-Profiles is an attempt to take all the Configuration Profile payload options Apple present in their Profile Manager MDM solution, and turn them into more precise tools (hence the surgical)!

The intention is for the profiles to be usable with any solution that allows the uploading of custom (but complete) profiles, such as Munki or Jamf Pro.

## But why? - An example

You want to require that all of your macOS devices have FileVault enabled. Great, lets enable that in the 'Security & Privacy' area of Profile Manager. 
But what's this? In order to use this profile, you're now also enabling a ton of other options in the various other tabs, including (by default):
- Enabling the sending of diagnostic data to Apple and Developers (regardless of what you've set during the setup assistant)
- Disabling the local firewall (and stopping the user from enabling it themselves) 
- Disabling the requirement for a password after screensaver begins (and this is different from the out of box behaviour!)

Wouldn't it be great to be able to push out _only_ the FileVault enablement setting? That's the reason for this project.

## Usage
TODO

## Contributing 
TODO

### Creation
TODO

### Testing
TODO

### Documentation
TODO

