<?xml version="1.0" encoding="utf-8"?>
<!--
  For more information on how to configure your ASP.NET application, please visit
  http://go.microsoft.com/fwlink/?LinkId=301880
  -->
<configuration>
  <configSections>
    <!-- For more information on Entity Framework configuration, visit http://go.microsoft.com/fwlink/?LinkID=237468 -->
    <section name="entityFramework" type="System.Data.Entity.Internal.ConfigFile.EntityFrameworkSection, EntityFramework, Version=6.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" requirePermission="false" />
  </configSections>
  <connectionStrings>
    <add name="DefaultConnection" connectionString="Data Source=(LocalDb)\v11.0;AttachDbFilename=|DataDirectory|\aspnet-MapfreHSBC-20161127105303.mdf;Initial Catalog=aspnet-MapfreHSBC-20161127105303;Integrated Security=True" providerName="System.Data.SqlClient" />
  </connectionStrings>
  <appSettings>
    <!-- Envio de correo-->
    <add key="ServidorSMTP" value="ironport" />
    
    <!--Conexiones a BD-->
    <add key="CONPRUEBATW" value="User ID=;password=;Data Source=10.98.76.67;Persist Security Info=True;Connection Lifetime=10;Enlist=false;Max Pool Size = 20;Min Pool Size=0;Pooling=true;" />    
    <add key="CONPRUEBATWDDES" value="User ID=;password=;Data Source=10.34.76.18;Persist Security Info=True;Connection Lifetime=10;Enlist=false;Max Pool Size = 20;Min Pool Size=0;Pooling=true;" />
