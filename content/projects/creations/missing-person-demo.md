{
  "title": "Missing person Demo",
  "date": "2017-03-1",
  "image": "/img/missing-person-demo.png",
  "link": "",
  "description": "An aws/rekognition based prototype webapp for searching missing people.",
  "tags": ["AWS Recognition","Php", "Sqlite", "Bootstrap"],
  "fact": "",
  "featured":true
}

A demo implementation to search for missing people using aws rekognition. Personal data for missing people is entered into the website's database by an operator using a form on the website itself. Now, whenever a person's image is uploaded via the search page, the website searches for that person in it's image database and comes out with a list of all matching entries along with their personal information and other metadata. This website uses amazon's "rekognition" engine for it's backend to search for matching candidates.
