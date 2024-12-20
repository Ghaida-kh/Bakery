<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">

</head>

<body>


  <?php

  $host = "127.0.0.1";
  $user = "root";
  $pass = "";
  $dbname = "bakery";

  $DB = new mysqli($host, $user, $pass, $dbname);

  if ($DB)
    echo " success in connect to database";
  else
    echo "error";

  $name = $_POST['name'];
  $pass = $_POST['pass'];






  try {
    $connection = new PDO("mysql:host=$host;dbname=$dbname", $user, $pass);
    $connection->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
    $Sqlcode = "INSERT INTO Client(name,pass)VALUES('$name','$pass')";
    $connection->exec($Sqlcode);
    echo 'Rows inserted in the table client_inf';
  } catch (PDOEXCEPTION $e) {
    echo 'echec in connection:' . $e->getMessage();
  }
  try {
    $connection = new PDO("mysql:host=$host;dbname=$dbname", $user, $pass);
    $connection->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
    $query = $connection->prepare(" SELECT * From Client");
    $query->execute();
    $result = $query->fetchall();
  } catch (PDOEXCEPTION $e) {
    echo 'echec in connection:' . $e->getMessage();
  }
  try {
    $connection = new PDO("mysql:host=$host;dbname=$dbname", $user, $pass);
    $connection->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);

    $query = $connection->prepare(" SELECT * From Client");
    $query->execute();
    $result = $query->fetchall();
    echo '<pre>';
    print_r($result);
    echo '</pre>';
  } catch (PDOEXCEPTION $e) {
    echo 'echec in connection:' . $e->getMessage();
  }

  ?>
</body>

</html>