# Introduction to Google Cloud Bigtable
This file contains text you can copy and paste for the examples in Cloud Academy's _Introduction to Google Cloud Bigtable_ course.  

### Using Bigtable
```
curl -f -O https://storage.googleapis.com/cloud-bigtable/quickstart/GoogleCloudBigtable-Quickstart-1.0.0-pre2.zip
unzip GoogleCloudBigtable-Quickstart-1.0.0-pre2.zip
./quickstart.sh
```
HBase command to scan first 30 lines of _Table-Name_:  
scan '_Table-Name_', {LIMIT => 30}

HBase Shell Commands are at https://learnhbase.wordpress.com/2013/03/02/hbase-shell-commands.
