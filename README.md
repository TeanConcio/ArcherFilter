# ArcherFilter

![Gmail Filters](https://img.shields.io/badge/Gmail-Filters-blue.svg)

## Description

The **ArcherFilter** repository is a collection of Gmail Email Filters that aims to make your email-management experience smoother and more organized, especially when dealing with the flood (spam) of emails from different offices within De La Salle University. The repository includes a consolidated XML file of Email Filters that can be easily imported into your Gmail account to set up Labels for sorting and managing your incoming emails.

## Included Offices (As of: 9/12/2024)

Please refer to "Included DLSU Colleges and Offices.txt".
Also includes miscellaneous filters like for Canvas, Active Directory, and DLSU Cashier.

## Disclaimer

If you have any ideas, requests, or bugs, please do not hesitate to reach out to me.

These filters are provided as-is and might not cover all scenarios or specific use cases. Make sure to review the filters after importing to ensure they match your preferences and requirements.

Please note that this repository is still currently a work in progress. New offices and filters will be added from time to time to provide a comprehensive set of filters that cover various aspects of university communication. Features to consider:

- Specific College Departments
- Research Centers

We are not liable for any damages, risks, or problems associated with using the Email Filters.

## Credits

I would like to give credits to [zelkim](https://github.com/zelkim) for being the first to create a repository for [DLSU Email Filters](https://github.com/zelkim/DLSU-Mail-Filter). His work was the one that inspired me to create this project.

---

## How to Use

1. **Download the Email Filters**
- Download the `mailFilters.xml` file from the repository

2. **Navigate to Gmail's Filter Settings**

- Open Gmail in your web browser.
- Go to `Settings` (the gear icon in the upper-right corner).
- Click `See All Settings` to go to Gmail's Main Settings Page.
- Navigate to the `Filters and Blocked Addresses` tab.

3. **Import and Load Filters**:

- Scroll down top the bottom of the page and click on `Import filters`.
- Click `Choose File`, select the downloaded `mailFilters.xml` file, and click `Open file`.
- Select the desired Email Filters from specific colleges/offices to import, or just keep them all selected.
- Click `Create Filters` to start importing the Email Filters
  - You can also select `Apply new filters to existing email.` before running to apply the filters to existing emails too. (Note: This will take a while)

**Note**:

- In case the importing freezes due to the sheer amount of Email Filters being added:
  - Refresh the page (Ignore the saving warning).
  - Go back to Gmail's Main Settings Page.
  - Navigate to the `Labels` tab.
  - Check what was the last imported Label.
  - Repeat step 3, but unselect all Email Filters until the last imported Label you saw.
  - Click `Create Filters`.
  - Repeat the process if it freezes again.

**Tips**:

- You can edit Email Filters to automatically do tasks such as:
  - Archiving emails from colleges/offices you don't want to hear from.
  - Marking emails from essential colleges/offices as important.
- You can give the generated Labels colors for better visualization.
- The TAB and SPACE Keys can help you navigate selecting or unselecting Email Filters to include.
  