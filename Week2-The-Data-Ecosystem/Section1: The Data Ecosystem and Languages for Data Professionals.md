# The Data Ecosystem and Languages for Data Professionals
### Summary and Highlights

In this lesson, you have learned the following information: 

A data analyst ecosystem includes the infrastructure, software, tools, frameworks, and processes used to gather, clean, analyze, mine, and visualize data.  

Based on how well-defined the structure of the data is, data can be categorized as:

- Structured Data, that is data which is well organized in formats that can be stored in databases.

- Semi-Structured Data, that is data which is partially organized and partially free form.

- Unstructured Data, that is data which can not be organized conventionally into rows and columns.

Data comes in a wide-ranging variety of file formats, such as delimited text files, spreadsheets, XML, PDF, and JSON, each with its own list of benefits and limitations of use.  

Data is extracted from multiple data sources, ranging from relational and non-relational databases to APIs, web services, data streams, social platforms, and sensor devices. 

Once the data is identified and gathered from different sources, it needs to be staged in a data repository so that it can be prepared for analysis. The type, format, and sources of data influence the type of data repository that can be used. 

Data professionals need a host of languages that can help them extract, prepare, and analyze data. These can be classified as:  

- Querying languages, such as SQL, used for accessing and manipulating data from databases. 

- Programming languages such as Python, R, and Java, for developing applications and controlling application behavior.

- Shell and Scripting languages, such as Unix/Linux Shell, and PowerShell, for automating repetitive operational tasks.

1.get-command (gcm) gets all commands

2.get-help + command to get command help

3.clear-host (cls) clears the screen

4.get-location (gl /pwd) gets the current location

5.set-location Set the path cd..Enter the upper-level directory cd+directory Enter the subdirectory

6.get-childitem (ls /dir) gets all child items

7.get-item+filename displays file information

8.new-item+filename new file

9.mkdir (md) + directory name create new directory

10.move-item (mi) + file name (to be moved) + directory name/

11.copy-item + file name + directory Copy the file to the directory

12.rename-item + original file name + file name to be changed to change the name

13.remove-item directory/file name (rm directory/file name) deletes files in the directory

14.add-content file name + "content" adds content to the file, which is an append form.

15.set-content file name + "content" adds content to the file as a replacement form

16.clear-content file name clears file content

17.get-service (gsv) Gets the service running in the local system

18.get-progress (gps/ps) gets the current process

19.convertto-html>"File name.html" converts the object into a web page file

20.export-csv "process.csv" exports the process csv file

Note: Open in Python's virtual isolation environment. You need to add the .ps1 suffix after activate.

# Understanding Data Reponsitiries and Big Data Platforms

- One of the most significant advantages of the relational database approach is its ability to create meaningful information by joining tables. Some of its other advantages include: Flexibility: Using SQL, you can add new columns, add new tables, rename relations, and make other changes while the database is running and queries are happening. Reduced redundancy: Relational databases minimize data redundancy. For example, the information of a customer appears in a single entry in the customer table, and the transaction table pertaining to the customer stores a link to the customer table. Ease of backup and disaster recovery: Relational databases offer easy export and import options, making backup and restore easy. Exports can happen while the database is running, making restore on failure easy. Cloud-based relational databases do continuous mirroring, which means the loss of data on restore can be measured in seconds or less.

- ACID-compliance: ACID stands for Atomicity, Consistency, Isolation, and Durability. And ACID compliance implies that the data in the database remains accurate and consistent despite failures, and database transactions are processed reliably. Now we’ll look at some use cases for relational databases: Online Transaction Processing: OLTP applications are focused on transaction-oriented tasks that run at high rates. Relational databases are well suited for OLTP applications because they can accommodate a large number of users; they support the ability to insert, update, or delete small amounts of data; and they also support frequent queries and updates as well as fast response times. Data warehouses: In a data warehousing environment, relational databases can be optimized for online analytical processing (or OLAP), where historical data is analyzed for business intelligence. IoT solutions: Internet of Things (IoT) solutions require speed as well as the ability to collect and process data from edge devices, which need a lightweight database solution. This brings us to the limitations of RDBMS: RDBMS does not work well with semi-structured and unstructured data and is, therefore, not suitable for extensive analytics on such data. For migration between two RDBMSs, schemas and type of data need to be identical between the source and destination tables. Relational databases have a limit on the length of data fields, which means if you try to enter more information into a field than it can accommodate, the information will not be stored. Despite the limitations and the evolution of data in these times of big data, cloud computing, IoT devices, and social media, RDBMS continues to be the predominant technology for working with structured data.

Data Pipeline, sometimes used interchangeably with ETL, encompasses the entire journey of moving data from the source to a destination data lake or application, using the ETL process.  

Big Data refers to the vast amounts of data that is being produced each moment of every day, by people, tools, and machines. The sheer velocity, volume, and variety of data challenge the tools and systems used for conventional data. These challenges led to the emergence of processing tools and platforms designed specifically for Big Data, such as Apache Hadoop, Apache Hive, and Apache Spark.
