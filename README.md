# A Collection of Prayers 
Catholic Prayers and Devotions:<br />
Christian prayers, Devotions and audios.

A web services for developers.

I am primarily maintaining this repository for my own use cases. 

## How to
 *(A fork is a copy of a repository)*.
1. Fork the repository in your account [Click here](https://github.com/erickouassi/openPrayers/fork)
2. Clone your repository to make a local copy
3. Use your own data (`.json`, `.jpg`, `.png`, and `.mp3`)
   
Note:  Your URL will be `https://your-username.github.io/openPrayers`

Direct link of the file with extension `.json`, `.jpg`, `.png`, and `.mp3`

`https://github.com/your-username/your-repo/blob/main/your-file-name?raw=true`

or 

`https://raw.githubusercontent.com/your-username/your-repo/main/your-file-name`

## <> Available resources
### Endpoints
The API style has several endpoints to assist developers. Note that all the endpoints return JSON and are available over https. This API takes no inputs.<br />


- Basic Prayers [./basic_prayers.json](https://raw.githubusercontent.com/erickouassi/openPrayers/main/basic_prayers.json)
- Rosary Prayer Calendar 2022 [./dailyrosary_2022.json](https://raw.githubusercontent.com/erickouassi/openPrayers/main/rosary/dailyrosary_2022.json)
- Rosary Prayer 7-day Audios [./rosary_day.json](https://raw.githubusercontent.com/erickouassi/openPrayers/main/rosary/rosary_day.json)
- The Stations of the Cross [./stations_of_the_cross.json](https://raw.githubusercontent.com/erickouassi/openPrayers/main/stations_of_the_cross.json)
- Saints of the Roman Calendar [./saints-en.json](https://raw.githubusercontent.com/erickouassi/openPrayers/main/saints-en.json)
- Saints of the Roman Calendar (French) [./saints-fr.json](https://raw.githubusercontent.com/erickouassi/openPrayers/main/saints-fr.json)

### Use in your own language

I prefered javascript(Fetch) but you can use PHP, Python, Java, etc

``` 
var requestOptions = {
    method: 'GET',
    redirect: 'follow'
  };

  fetch("myURL", requestOptions)
    .then(result => console.log(result))
    .catch(error => console.log('error', error));
```

#### feature requests
- The verse of the day `Coming soon!`
- Divine Mercy Novena `Coming soon!`

## Projects using openPrayers
Do you want to list your own project here? 
[contact me here](https://erickouassi.com/contact.html) to add your own project now.

- Daily Rosary Prayer: [https://dailyrosary.cf/](https://dailyrosary.cf/)
- Daily Audio Catholic mass reading: [https://dailyaudio.cf/](https://dailyaudio.cf/)


## Bugs and feature requests
Any problem? Please report it: all bugs, feature requests, pull requests, feedback, etc., are welcome!

First search for [existing and closed issues](https://github.com/erickouassi/openPrayers/issues?utf8=%E2%9C%93&q=is%3Aissue). <br />
If your problem or idea is not addressed yet, please [open a new issue](https://github.com/erickouassi/openPrayers/issues/new/choose).

**If you have questions:**  [erickouassi.com/contact](https://erickouassi.com/contact.html)


If you want any help setting your rosary web app for yourself, group or church, I’d love to help! [contact me here](https://erickouassi.com/contact.html).


##### Buy me a coffee 🥤¶
If this project help you reduce time to develop, please consider [buying me a coffee](https://github.com/sponsors/erickouassi) :)


Note: I am occasionally updating the code.

Happy Coding