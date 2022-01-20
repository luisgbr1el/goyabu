# goyabu
A easy and simple way to get data from <a href="https://goyabu.com">Goyabu.com</a>.

<a href="https://github.com/luisgbr1el/goyabu/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/luisgbr1el/goyabu?style=flat-square"></a>
<a href="https://github.com/luisgbr1el/goyabu/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/luisgbr1el/goyabu?style=flat-square"></a>
<a href="https://github.com/luisgbr1el/goyabu"><img alt="GitHub license" src="https://img.shields.io/github/license/luisgbr1el/goyabu?style=flat-square"></a>

Note that the package only catches the first result, so if you want the second season of **Shingeki no Kyojin**, for example, you need to put `Shingeki no Kyojin 2`.

- The package doesn't have a **error callback**.

# Install (with NPM)
```javascript
npm i goyabu
```

# Usage
```javascript
const goyabu = require("goyabu");

goyabu.animeSearch('dragon ball super').then(results => {
    console.log(results)
});
```

The result will be:
```javascript
{
  title: 'Dragon Ball Super ',
  episodes: 131,
  views: 7184,
  alternativeName: 'Dragon Ball Super',
  status: 'Completo',
  genres: [
    'Action',
    'Adventure',
    'Comedy',
    'Super Power',
    'Martial Arts',
    'Fantasy',
    'Shounen'
  ],
  description: [
    ` Seven years after the events of Dragon Ball Z, Earth is at peace, and its people live free from any dangers lurking in the universe. However, this peace is short-lived; a sleeping evil awakens in the dark reaches of the galaxy: Beerus, the ruthless God of Destruction. Disturbed by a prophecy that he will be defeated by a "Super Saiyan God," Beerus and his angelic attendant Whis start searching the universe for this mysterious being. Before long, they reach Earth where they encounter Gokuu Son, one of the planet's mightiest warriors, and his similarly powerful friends. [Written by MAL Rewrite] `
  ],
  coverUrl: 'https://goyabu.com/capas/dragon-ball-super-episodios.jpg'
}
```

# Author
<a href="https://github.com/luisgbr1el">luisgbr1el</a>
