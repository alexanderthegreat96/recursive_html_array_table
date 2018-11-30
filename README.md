# recursive_html_array_table
Simple function that allows developers to test their array structure by automatically generate tables from arrays.

Features:
 - works with both plain and nested arrays
 - ease of use
 - it is recursive, meaning it applies to every array inside your actual array
 
 HOW TO USE:
 
Simply require the file 


require "array_debug.php";

$my_multi_dimensional_array = array(1=> array("data" => "1" ,"value" => "1")));

//Always use dump_array($data);
echo dump_array($my_multi_dimensional_array);


Enjoy!

