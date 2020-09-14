# gd-imp

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

[![gd-imp](https://miro.medium.com/max/300/1*nhPJU_eguAWn9BeE2febpQ.png)](https://medium.com/@yashkrishan/transfer-data-from-google-drive-to-google-drive-b5c2e98af583)

A simple solution to copy folders from a Google Drive

1. Import the Google Drive library and authenticate and mount drive it. You need to authenticate drive B.
2. We only need the shortcuts that we created so this command will write all of them to a file
3. We read this file and store folder names and their paths in lists
4. We need to create a folder within the drive where we'll store the copied folders. This is important for isolation and to prevent any infection of the drive contents due to human negligence. (Sauce: https://www.coronatracker.com)
5. Finally, we run the cell that writes the folders to your drive B.

For complete walkthrough visit: https://medium.com/@yashkrishan/transfer-data-from-google-drive-to-google-drive-b5c2e98af583