# obiee soap report consumer

clone 
mvn clean install
Update required value in BiPublisherReportConsumer.java 

private static String SERVICE_URL = "https://xxxxxx/xmlpserver/services/v2/ReportService";

	private static String REPORT_PATH = "/xxxx/BIPReport.xdo";

	private static String REPORT_FORMAT = "csv";

	private static String USERNAME = "xxxxxx";

	private static String PASSWORD = "xxxxxx";
  
run BiPublisherReportConsumer.java 
