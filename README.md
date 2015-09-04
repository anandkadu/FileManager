# FileManager
It is example of spring rest service and extjs. Search functionality to search file

It has mainly two service 
1. Get file and folder for given directory path which will be available on deployment on say tomcat
http://localhost:8080/nuanceexplorer/fileexplorer/filesAndDirectories?path={directoryPath}&start=0&limit=3&page=1
Pagination is given from UI perspective.Replace directoryPath with actual path on your system

2. Get File details for given file path which will be available on deployment on say tomcat
http://localhost:8080/nuanceexplorer/fileexplorer/file?path={filePath}
Replace filePath with actual path on your system

