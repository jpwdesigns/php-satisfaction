PHP Library for the Get Satisfaction API
========================================

This is just a collection of the PHP files needed to use the Get Satisfaction API.

Example usage
------------------
require_once("Satisfaction.php");
require_once("HTTP_Request_Oauth.php");

$sfn_root = "http://community.yourdomain.com/";
$method = 'POST';
$req_params = array();
$query_params = array();
$consumer_data = array(
    'key' => 'yourkey',
    'secret' => 'yoursecret'
);


$request_tokens = get_oauth_request_token($consumer_data);




In addition to these files you will need to install the PEAR library [HTTP_Request](http://pear.php.net/package/HTTP_Request/).

Libraries included
------------------

* [hkit](http://code.google.com/p/hkit/)
* [HTTP_Request_Oauth](http://teczno.com/HTTP_Request_Oauth.phps)