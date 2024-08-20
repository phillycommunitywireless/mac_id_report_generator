# mac_id_report_generator

<br/> - This program uses Jupyter Notebooks in order to determine unique MAC ID's on the network by the day.
<br/><br/> - We use the list_users file in the linode.
<br/><br/> - It is important to note that you must download the necessary .json files from the Linode and have them available locally. The filepath of the data will be the same as the filepath of where the notebook is located.
<br/><br/> - Follow comments/directions written in the code to adjust for necessary time frames.
<br/><br/><br/> **** Note that the .json files in the PCW Linode are organized by days. However, you can find multiple dates in a single date folder. Be aware this may impact the measurements. It may be necessary to include a wider date range in the initial downloading of all files. Afterwards, you can filter down to get the exact data you want in the code itself. This way you can avoid missing any data that may be stored in "future dates".
