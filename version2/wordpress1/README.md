NOTE:

Please take care of the default.conf. In this file should be specified the servers:

upstream wordpress {
  server wordpress1_wordpress_1;
  server wordpress1_wordpress_2;
}

 The server name should match with the service_name. Remember, the service name is created according to the folder where you are located. In this case wordpress1_wordpress_1
