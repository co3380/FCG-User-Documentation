# Financial Code Generation

New financial codes can be generated by logged in users with the
`Primary`, `Manager`, or `Owner` application roles. This is done on
the  `New Code` page, which can be reached by the `New Code` link in
the header menu. The link only appears when a user is logged in and
has the permission to generate financial codes.

## Information Gathered

For each financial code, there are two separate groups of
information. The first contains details about the fire incident itself, such
as its name, the state it occurred in, and the date the fire was
discovered. This information is automatically populated from IRWIN,
and is entered in the `IRWIN Information` section of the form.

The second set of information contains the information that is required by
Montana DNRC business practices and are generated by the FCG user. This
information is entered in the `Agency Information` section of the form.

## Generating A New Financial Code

Before any information can be entered, the fire year of the IRWIN
incident that the financial code will be generated for must be
selected using the `Fire Year` dropdown box at the top of the
form. Since this defaults to the current fire year, most users won't
be able to change it; it will be the only option available to
them. For users with the Owner role however, they can use this
dropdown to select a previous fire year. This ensures that the agency
information and IRWIN incidents for that year will appear as the only
options in the form.

### Searching and Selecting the IRWIN Incident

In the IRWIN Information section, there is a search bar that can be
used to search by either the incident name or unique fire
identifier. After pressing the search button, if there is only one
incident that matches the given criteria, it will automatically be
selected. If there is more than one result,
a dialog will appear listing the search results. After a incident is
selected, the search controls will disappear, and some data
fields from IRWIN will be displayed in its place. If the selected
incident needs to be changed, press the `Choose Another Incident`
button to clear out the current selection and make the search controls
appear again.

### Entering Agency Information

DNRC-specific information is entered using the `Agency Information` section
of the form. Here's a brief explanation of what each field should
contain:

+ __Short Description__: A short title for what this financial code
  will be used for. This field is required to generate a financial  code.
+ __Activity Role__: The activity role type that will be associated
  with the incident. This field is required to generate a financial code.
+ __Area__: The DNRC area that is handling the incident.
+ __Unit__: The DNRC unit that is handling the incident.
+ __Business Action__: A specific type of business action that can be
  associated with an incident.
+ __Additional Agency Information__: This text box should contain
  free-form information about other agencies that may be involved in
  the incident.
+ __Remarks__: This text box should contain any general remarks to be
  associated with the IRWIN incident.