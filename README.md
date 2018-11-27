# murder-mystery-site

```npm install```
&
```npm start```
to get things started.

<br />

You will need your own uri for the sake of production, but if you would like to run it locally, replace the uri variable in the root folder's app.js with the mongodb connection url of your choice. If you want to run it in production, create a uri file as such: <br />
```
const uri =
  "<uri>";

module.exports.uri = uri;
```

<br />
 Character info is meant to be added via the mongo shell rather than via app.
