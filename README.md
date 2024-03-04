# dex-samp-query

Perfect Query API for SAMP

```
npm install dex-samp
```

#### Usage

**Available options**

* host
* port - default: 7777
* timeout - default: 1000

```
var query = require('dex-samp-query')

var options = {
	host: 'play.dreamcityrp.tech'
}

query(options, function (error, response) {
	if(error)
		console.log(error)
	else 
		console.log(response)
})
```

#### Sample output
```
{ 
	address: 'play.dreamcityrp.tech',
	hostname: 'Dream City',
	gamemode: 'dcrp',
	mapname: 'San Andreas',
	passworded: false,
	maxplayers: 500,
	online: 12,
	rules: { 
		lagcomp: true,
		mapname: 'San Andreas',
		version: '0.3z',
		weather: 18,
		weburl: 'www.dreamcityrp.tech',
		worldtime: '12:00'
	},
	players: [
		{ id: 0, name: 'Killadi_Sk', score: 14735, ping: 51 },
		{ id: 1, name: 'Omega_Ftp', score: 26193, ping: 81 },
		{ id: 2, name: 'Tricky_God', score: 87211, ping: 41 },
		{ id: 3, name: 'Im_Chekuthan', score: 439313, ping: 45 },
		{ id: 5, name: 'Not_Kuppi', score: 14775, ping: 41 },
		{ id: 6, name: 'Killadi_Gt', score: 38914, ping: 66 },
		{ id: 7, name: 'Jacky_Williams', score: 2104, ping: 56 },
		{ id: 8, name: 'Najeem_Ikka', score: 29, ping: 56 },
		{ id: 9, name: 'Dark_Dev', score: 20354, ping: 45 },
		{ id: 10, name: 'Snuz_Willaims', score: 0, ping: 81 },
		{ id: 11, name: 'Not_Hikaru', score: 38886, ping: 56 },
		{ id: 12, name: 'Drp_Minnal', score: 0, ping: 51 }
	]
}
```


