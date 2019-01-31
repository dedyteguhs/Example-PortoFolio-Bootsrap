# portofolio

echo "# ajaxdinamis" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:dedyteguhs/ajaxdinamis.git
git push -u origin master


Recovery Pending

ALTER DATABASE HRD   
    MODIFY FILE ( NAME = db_hrd,   
                  FILENAME = 'F:\db\HRDPbk1.mdf');  
GO
 
ALTER DATABASE HRD   
    MODIFY FILE ( NAME = db_hrd_log,   
                  FILENAME = 'F:\db\HRDPbk_log1.ldf');  
GO

SELECT name, physical_name, state_desc FROM sys.master_files;

ALTER DATABASE HRD SET ONLINE;  
GO
