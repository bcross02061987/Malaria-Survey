VILLAGE HOUSEHOLD SURVEY – VERSION 5

QUESTIONNAIRE
Household information:
1. Name of Village.
2. Name of Head of Family.
3. Number of family members (including Head of Family).

For every member, including the Head of Family, collect the member's name and: 4. Age; 5. Sex; 6. Educational Qualification; 7. Main Occupation; 8. Secondary occupation (optional); 9. Months spent in farm/Jhum; 10. Usual return-home frequency (Daily, Every 2–3 days, Weekly, Monthly, Irregular with specification); 11. Currently away during visit; 12. Fever during the 14 days before survey; 13. Ever had malaria. The Head of Family name automatically fills Member 1's name, which can be edited if needed.

DATA
One row is exported per family member. Each row includes Village name, Head of Family, Household ID, member name and individual answers. JSON backup/import supports merging collectors' data; duplicate survey IDs are skipped.

GITHUB PAGES INSTALLATION
1. Extract this ZIP.
2. Open your GitHub repository (for example, village-survey).
3. Choose Add file > Upload files.
4. Upload these six files directly into the repository root, replacing the previous versions. Do not upload the ZIP itself.
5. Commit changes.
6. In Settings > Pages, choose Deploy from a branch, branch main, folder /(root), then Save.
7. Wait for GitHub Pages to publish. Open https://YOUR-USERNAME.github.io/village-survey/ in Chrome.
8. On Android, open the URL while online, then Chrome menu > Install app (or Add to Home screen). Open once online on every phone before going offline.

COLLECTOR WORKFLOW
Each phone stores data locally. Export a JSON backup from each collector phone. Import all backups on the central phone, then export the combined Excel workbook.

PRIVACY AND BACKUP
Explain the survey purpose and obtain consent. Names and fever/malaria answers are sensitive. Keep exported files secure and share only with authorised people. Do not upload survey responses to public GitHub. Export backups before clearing browser data, uninstalling, or replacing app versions. The app does not send survey responses to a server.


Version 6 update: Collector setup now requires a valid 10-digit Indian mobile number instead of an assigned village/area. The collector phone number is included in exported Excel rows. The survey questionnaire still separately asks for Name of Village.
