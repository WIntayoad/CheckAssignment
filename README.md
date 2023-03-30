# Assignement& Lab Marker
Running
- use LabMarker for marking lab
- use AsgMarker for marking assignment
## Marking
- Change parent_folder_url to local directory. This is where the projects are cloned to local.
- Change RESOURCE_PATH to where the repo file are. You need to download grade from Github classroom and put it as "lab[no]-repo.csv" or "asg[no]-repo.csv" such as `lab1-repo.csv`
- Change MAVEN_HOME to where maven is installed

running LabMarker/AsgMarker gives `***-grade.csv`

# Logging for section
- put file `section[no]-id.txt` containing id for each section (see `section2-id.txt` for a sample)
- Change section in main method in LabRecorder. specify startlab and lastlab parameter, For example, startlab:1 and lastlab:6. This logs grades for lab 1 to lab 6.
- change `type` variable to `lab` or `asg` for assignment
- change `LATE_PENALTY` 0 for marking late submission as 0 and 0.5 as half grade.
- run LabRecord.java. it generate file such as `section2-lab1-6-grade.csv` and `section4-lab1-6-grade.csv`


