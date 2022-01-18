# MYsystemdesing
* Netflix and Video streimg Desing 

FR -
1) Upload video's.
2) Home page and search future.
3) playing videos' .
4) support multiple devices.
5) user/admin/client login/Registration.

NFR -
1) No buffer - low latency and increase the availability.
2) user's session time.

used search engine - Elastic search
used database - Mysql for user information, and Cassandra for storing information of file and file system because using Cassandra is much easier to use while you have a lot of query happing and also that is increasing it handles it very well.
used Kafka As a data painpaline
AWS S2 as a file system for storing the video, image etc.
build content process for processing media and filtering offensive content.

most of the things are clear by the diagram try to put some of the most important points
![Netflix desing](https://raw.githubusercontent.com/Akhilleshgoswami/MYsystemdesing/master/Netflixsystemdesing/Video%20Streaming%20Platform_cleanup.png)
