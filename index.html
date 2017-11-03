<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 transitional//EN" "http://www.w3.0rg/TR/xhtml-transitional.dtd">
<html xmlns = "http://www.w3.org/1999/xhtml">
<head>
<meta http-equi = "content-Type" content= "text/html; charset=utf-8" />
<title>search</title>
</head>
<body align = "center">
<h1> CUAA CAMPUS DIRECTORY </h1>
<img class= "displayed" src="http://d21gd0ap5v1ndt.cloudfront.net/web04/cards/images_web/athletic_logo.png"alt="CUAA"align="center"style="width:150px;height:150px;">
<form action= "index.php" method= "post" align = "center" class = "wsite">
<input type = "text" name = "search" placeholder = "search for office_ext"/>
<input type= "submit" value= "go" />
</form>
<style>
body {
    font-family: 'Lato', sans-serif;
    color: #FFF;
    background: #e50000;
    -webkit-font-smoothing: antialiased;
}
.wsite {
    position: relative;
    margin-top:78px;
    margin-right:auto;
    margin-bottom:0px;
    margin-left:auto;
}
h1
{
  font-family: lobster, monospace;
  
}
.tfont {
    font-family: "Times New Roman", Times, serif;
	font-size: 50px;
}
IMG.dispalyed
{
  display: block;
  margin-left:  auto;
  margin-right: auto;
  border-left-radius:400px;
}


</style>


<?php
 mysql_connect("localhost","root","") or die(mysql_error());
 mysql_select_db("Concordia University_personnel") or die("could not find db!");
$output = '';
//collect
if(isset($_POST['search'])){
	$searchq = $_POST['search'];
	$searchq = preg_replace("#[^0-9a-z]#i","",$searchq);

	$querystr = 'SELECT * FROM employees1 WHERE (Firstname LIKE "%'.$searchq.'%") OR (Lastname LIKE "%'.$searchq.'%")';
	$query = mysql_query( $querystr ) or die(mysql_error());
	
	$count = mysql_num_rows($query);
	if(!$count){
		$output = "No results!";
		
	}
else{
	
	?>
	
<table align = "center">
		<tr>
		<th>First Name&nbsp;</th>
		
		<th>Last Name&nbsp;</th>
		
		<th>Office Extension&nbsp;</th>
		
		<th>Designation&nbsp;</th>
		
		<th>Office Location&nbsp;</th>
		
		<th>Email&nbsp;</th>
		</tr>	
	<?php
	while($row = mysql_fetch_array($query)){
		$fname = $row["Firstname"];
		$lname = $row["Lastname"];
		$ext = $row["Office_EXT"];
		$desg = $row["Designation"];
		$loc =$row["Office Location"];
		$email = $row["email"];
		?>
		
		<tr>
		<td><?php echo $fname  ?>&nbsp;</td>
		<td><?php echo $lname  ?>&nbsp;</td>
		<td class = "tfont"><?php echo $ext  ?>&nbsp;</td>
		<td><?php echo $desg ?>&nbsp;</td>
		<td><?php echo $loc  ?>&nbsp;</td>
		<td><?php echo $email  ?>&nbsp;</td>
		</tr>
		
		
		<?php
		//$output .= "<div> ".$fname."".$lname."".$ext."</div>";
	}
	?>
</table>	
	<?php
    }
	}
?>

</body>

</html>