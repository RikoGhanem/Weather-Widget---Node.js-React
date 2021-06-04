
Weather widget that is built with Node.js, React and OpenWeatherMap API

How to run it:

Start first the Node.js API server
<br />
1. You have to edit api/routes/weatherAPI.js and insert the API Key in appid. eg: const appid = "166d00e26d3ff2c6149....";<br />
2. cd into the 'api' folder<br />
3. npm start<br /><br />
The server is now listening on: http://localhost:8888/weatherAPI


<br /><br />
You can now start React
<br />
1. cd into the 'client' folder<br />
2. npm start<br />
You can now access the widget from: http://localhost:3000<br />

Optional:<br />

3. You can run 'npm t' to start the unit tests<br />

4. You can edit client/src/index.js to change the api url<br />

5. You can edit client/public/index.html and change: 'data-default-city' attribute value to replace the default city on the initial page load

