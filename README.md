<h1>Select Database Records From DB using RPA</h1> 
<ul>
  <li>Download <b>UiPath.Database.Activities</b> package(s)using managae package</li>
  <li>Then Create an activity using Database</li>
  <li>Connect your database using <b>Connect Activity of Database Activity</b></li>
  <li>Provied all creadentials for connecting the DB</li>
  <li>Store this connection in a particular variable so that we can this to perform DB operations</li>
  <li>Now use <b>ExecuteQuery activity from Databse Activity</b>.This will need a connection variable then we defined while creating connections, the SELECT query that we are going to perform</li>
  <li>Now store this data into some DataTable variable say <b>userDataTable</b></li>
  <li>To check whether we got the data use MessageBox and write <b>userDataTable.Rows.Count.ToString()</b><li>
  </ul>
