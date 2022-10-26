<h1>Music Library, Backend</h1>

<a href="https://github.com/NFMatten/Project_MusicLibrary_Frontend">Music Library Frontend Repo</a>

<h2>User Stories</h2>
<ul>
    <li>As a developer, I want to make good, consisten commits.</li>
    <li>As a developer, I want to create an ERD for the API's Model, showing proper fieldtypes.</li>
    <li>As a developer, I want to create an app named 'songs' based around a model named 'Song'. Property names must be in snake_case and match the following exactly: title - CharField, artist - CharField, album - CharField, release_date - DateField, genre - CharField</li>
    <li>As a developer, I want my API to serve content on the following URLs paths: (Paths must match these exactly) 'api/music/' and 'api/music/<int:pk>/'.</li>
    <li>As a developer, I want to build a REST web API in Django REST Framework, so that I can make HTTP requests interact with the data set.</li>
    <li>As a developer, I want to create a GET enpoint that responds with a 200 success status code and all of the songs within the music table.</li>
    <li>As a developer, I want to create a GET by id endpoint that does the following: Accepts a value from the request's URL (the id of the song to retrieve), Returns a 200 status code, Responds with the song in the database that has the id that was sent through the URL.</li>
    <li>As a developer, I want to create a POST endpoint that does the following: Accepts a body object from the request in the form of a Song model, Addes the new song to the database, Returns a 201 status code, Responds with the newly created song object.</li>
    <li>As a developer, I want to create a PUT enpoint that does the following things: Accepts a value from the request's URL (the id of the song to be updated, Accepts a body object from the request in the form of a Song model, Finds the song in the Music table and updates that song with the properties that were sent in the request's body, Returns a 200 status code, Responds with the newly updated song object)</li>
    <li>As a developer, I want to create a DELETE endpoint that does the following things: Accepts a value from the requet's URL, Deletes the object from the database, Returns a 204 (NO CONTENT) status code</li>
    <li>As a developer, I want to use Postman to make a POST, PUT, DELETE and both GET requests (get by id and get all) request to my REST web API, save it to a collection and then export it as a JSON from Postman.
</ul>
