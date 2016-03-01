# Ludobox Borgia

These are clean files for the Borgia game. It can be used as a sample to distribute your games using the [Ludobox](https://github.com/ludobox/ludobox) .


Each of your game should be made of :

* a folder named with the name of your game in lowercase and slugified - ex : ```borgia-le-jeu-malsain```
* a JSON file containing information about your game - ex. ```/borgia-le-jeu-malsain/game-info.json```
* any files attached to the game as one big zip file - ex. ```/borgia-le-jeu-malsain/borgia-le-jeu-malsain-files.zip```

### Data model

Model of a JSON game description

    {
        "type": "game",
        "genres": {"fr":["social", "stratégie"]},
        "title": {"fr":"Borgia, le jeu malsain"},
        "description": {"fr":"Grâce à ce jeu de carte fabuleusement illustré et immoralement conçu, vous allez, si tant est que vous soyez majeur, partager le sort de l’une des personnalités qui vécue en 1492, au côté du Pape Alexandre VI, dans la Rome des Borgia."},
        "themes": {"fr":["Médiéval", "Salopard", "Religion"]},
        "publication_year": 2012,
        "publishers": ["Les Chiens de l'Enfer"],
        "authors": ["Julien Maudet", "Mary Christides"],
        "illustrators": ["Aurélien Biard", "Mary Christides"],
        "audience": "adults",
        "players_min": 3,
        "players_max": 6,
        "fab_time": 120,
        "duration": 60,
        "requirements": {"fr":["imprimante"]},
        "source": "http://leschiensdelenfer.org/editions-chiens-de-lenfer/borgia-le-jeu-malsain/",
        "license": "CC BY-NC-SA 4.0",
        "languages": ["fr"],
        "ISBN": [],
        "timestamp_add": "10/10/2015 14:52:35"
    }
