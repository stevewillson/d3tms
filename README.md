# D3TMS

## Quickly provide a summary of unit compliance with mandated training. This will summarize the information stored in DTMS.

1. Visit [DTMS](https://dtms.army.mil/DTMS/Default.aspx)
2. Select "Reporting" > "Report Center" > "Report List"
3. Select the "Grid Reports" tab and the "Task Completion Roster Report" and the "Soldier Roster Report"

Direct Links to export reports (Requires DTMS Access)

- [Task Completion Roster Report](https://dtms.army.mil/DTMS/GridReporting/DisplayReport?type=nFocus.Modules.Reporting.Mvc.Reports.TaskCompletionRosterReport%2C%20nFocus.Modules.Army.GridReportPlugins%2C%20Version%3D1.0.0.0%2C%20Culture%3Dneutral%2C%20PublicKeyToken%3Dnull)

- [Soldier Roster Report](https://dtms.army.mil/DTMS/GridReporting/DisplayReport?type=nFocus.Modules.Reporting.Mvc.Reports.SoldierRosterReport%2C%20nFocus.Modules.Army.GridReportPlugins%2C%20Version%3D1.0.0.0%2C%20Culture%3Dneutral%2C%20PublicKeyToken%3Dnull)

4. Generate the reports and export the information to Excel

5. Create a new Excel file that has the following columns:
- TaskNumber
- TaskName
- Frequency (in days)
- Audience (Soldiers, Civilians, Supervisors, or All)

6. Load all three files in D3TMS to gain better understanding of the information.

D3TMS will do all processing clientside and display a compliance chart.

Click on cells within the compliance chart to show who needs to conduct training.
