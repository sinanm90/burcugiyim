<?php
//Instagram Feed
function fetchInstagram($url){
  $ch = curl_init();
  curl_setopt($ch, CURLOPT_URL, $url);
  curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
  curl_setopt($ch, CURLOPT_TIMEOUT, 20);
  $result = curl_exec($ch);
  curl_close($ch); 
  return $result;
}
$count    = 1;
$user_id  = "2127137581";
$access_token  = "2127137581.1677ed0.ae9646babed1422b8df5f3ed27ec8c8d";
$display_size  = "standard_resolution";
$ig_feed  = "https://api.instagram.com/v1/users/$user_id/media/recent?count=$count&access_token=$access_token";
$result = fetchInstagram($ig_feed);
$result = json_decode($result);
foreach ($result->data as $photo) {
  $img = $photo->images->{$display_size};
  echo "<img src='{$img->url}' />";
}
?>
