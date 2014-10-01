<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Availability Monitor Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Availability Monitor Plugin</h1>
    <div class="section-2"  id="114557268_AvailabilityMonitorPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
The availability monitor can be used to test if a server can be pinged, and will also check to ensure that DNS and reverseDNS capabilities are functioning.    </p>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/114557268/Availability_Monitor_Settings.jpg" alt="images_community/download/attachments/114557268/Availability_Monitor_Settings.jpg" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/114557268/Availability_Monitor_Measures.jpg" alt="images_community/download/attachments/114557268/Availability_Monitor_Measures.jpg" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/114557268/Availability_Monitor_Dashboard.jpg" alt="images_community/download/attachments/114557268/Availability_Monitor_Dashboard.jpg" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="114557268_AvailabilityMonitorPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_114688041_2_com.mycompany.myplugin.AM_1.0.0.jar">Availablity Monitor Plugin 1.0.0</a> (compatible with dynaTrace 4.2+)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Derek Abing    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a><br/>If you have any questions or suggestions for these plugins, please add a comment to this page, use our <a href="https://community.dynatrace.com/community/pages/viewpage.action?pageId=46628918">forum</a>, or drop us an email at <a href="mailto:apmcommunity@compuware.com">apmcommunity@compuware.com</a>!    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2013-03-12 Initial Release<br/>2013-04-18 Updated Plugin    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="114557268_AvailabilityMonitorPlugin-ProvidedMeasures"  >
        <h2>Provided Measures</h2>
    <p>
<strong class=" ">DNS Resolved</strong>: Returns a 1 if the server DNS name is resolvable and a 0 if the server is not resolvable<br/><strong class=" ">Ping Check</strong>: Returns a 1 if the server is pingable and a 0 if the server is not pingable<br/><strong class=" ">Reverse DNS Resolved</strong>: Returns a 1 if the server DNS name is resolvable and a 0 if the server is not resolvable<br/><strong class=" ">TCP Check</strong>: Returns a 1 if the server is reachable on TCP port 7 and a 0 if the server is not reachable<br/><strong class=" ">TCP Lock Time</strong>: Returns the time taken to secure a Socket Lock on TCP Port 7    </p>
    </div>
    <div class="section-2"  id="114557268_AvailabilityMonitorPlugin-Configuration"  >
        <h2>Configuration</h2>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Value    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Max TCP Return Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The max allowed time for the response to the ping in ms    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="114557268_AvailabilityMonitorPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server. For details how to do this please refer to the <a href="https://community/display/DOCDT56/Plugins">dynaTrace documentation</a>.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>