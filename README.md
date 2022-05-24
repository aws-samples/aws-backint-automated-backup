## Automatically Backup SAP HANA databases using Systems Manager and Amazon EventBridge

    This pattern describes how to automate SAP HANA database backups using AWS Systems Manager, Amazon Event Bridge, Amazon Simple Storage Service (Amazon S3), and AWS Backint Agent for SAP HANA. 
    This pattern provides a shell script-based approach using the BACKUP DATA command and removes the need to maintain scripts and job configurations for each OS instance across numerous systems.

Kindly refer to json file HDB_Backup_SSM_Document.json

The code in this repository helps you set up the following target architecture.

<img width="698" alt="image" src="https://user-images.githubusercontent.com/98596200/169990084-2c9c4f1b-d855-49a2-b222-b765d733745e.png">

For prerequisites and instructions for using this AWS Prescriptive Guidance pattern, see [Automatically Backup SAP HANA databases using Systems Manager and Amazon EventBridge](https://apg-library.amazonaws.com/content/0aa22a27-d100-483d-95f9-c3101f40402c).

