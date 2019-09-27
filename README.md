# Add Holidays to Calendar

This project improves the process of creating a business calendar. It utilizes the [nager](https://date.nager.at/Api) API to automatically populate your business calendar with a new exception for every holiday for the given country. 

This project was developed to accompany a Labs blog post and be a simple example of using an external REST API from within Aras Innovator. 

## History

Release | Notes
--------|--------
[v1.0](https://github.com/ArasLabs/add-holidays-to-calendar/releases/tag/v1.0) | Initial Release

### Supported Aras Versions

Project | Aras
--------|------
[v1.0](https://github.com/ArasLabs/add-holidays-to-calendar/releases/tag/v1.0) | 12.0, 12 SP1

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\addHolidaysToCalendar\Import\imports.mf` file in the Manifest File field.
6. Select **aras.labs.addHolidaysToCalendar** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Usage

1. Create a new business calendar
2. Set the year and country on the form
3. Save the business calendar

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Created by AJ Sebastian, Aras Labs.

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
