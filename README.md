# JasperReportsViewer
Java report that will allow you to execute a .jasper file or from a URL and extract it in PDF format. There is also a built-in PDF Viewer using Acrobat
<br><br>
If you want to view a PDF using URL<br>
java -jar JasperViewer "URL of the PDF"
<br><br>
If you want to execute a .jasper file then do below:<br>
     * Program Arguments:<br>
     * args[0] - .jasper file path<br>
     * args[1] - report output path and filename<br>
     * args[2] - parameter(s), if multiple it should be pipe delimited "TEST:1|TEST:2"<br>
     * args[3] - JDBC connection "jdbc:oracle:thin:@192.222.4.239:1521/ADSD"<br>
     * args[4] - Database User<br>
     * args[5] - Database Password<br>
