mysqli-lightLib
===============

MySQLi-lightLib is a simple and little class with principal method for work with mysqli ( http://www.obiv.it/video-giornale/7-programmazione-oggetti-php-mysqli-class.html )


Usage: 

// require and create object
require_once 'mysqli.php';
$db = new Mysqlimproved;

// prepare query for execution
$db->prepare("SELECT * FROM `table` WHERE record='{$record}'");

// execute query
$db->query();

// fetch data
$row = $db->fetch('array'); 
// $db->fetch() accept to: 'object', 'allAssoc', 'assoc'
