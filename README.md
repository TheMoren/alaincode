alaincode
=========

Checker proxy, brute force with the open source

Settings config.php >

$Host - Action form adress.

//CFG Data
$dataMode = (true/false). Reads the data for a post request from config.
$data = "login=admin&pass=123456". (example)

//Brute Force
$loginFile = "base/login.txt" (File login)
$passwordFile = "base/password.txt" (File password)
$resultFile = "base/result.txt" (File result)
$inputLogin = "login" (Form input "Login")
$inputPass = "pass" (Form input "Password")
$mode = 1 //(1-2)
/*
Mode 1 - Brute force by login and password.
Mode 2 - Brute force password for one login.
*/
$delayMode = (true/false). (Delay brute force)
$delay = 0 //(Second)

//Proxy
$proxyFile = "proxy/proxy.txt" (File proxy)
$proxyGood = "proxy/good.txt" (File save good proxy)

//Logs (Affects the speed of the script)
$logsMode = (true/false).
$logsFile = "log.txt" (File log)

Command console > 

/status - Check status.
/curltest - Check cURL.
/setdata - To set your data.
/deletedata - Delete data.
/home - To home page.
/clearlog - Clear log file.
/start bruteforce - Start brute force.
/check proxy - Check proxy.
/open result - Open result file brute force.
/testpost - Test post request.
/sendpost - Post request on the specified host with the specified data.
