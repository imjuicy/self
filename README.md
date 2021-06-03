**<h1>KING-SelfBot</h1>**


* 1- ouvrir install.bat 
* 2- ouvrir update.bat 
* 3- ouvrir start.bat 

![ScreenShot](https://cdn.discordapp.com/attachments/846067759241625684/846067772554870834/unknown.png)

* entrez 2 puis entrée pour commencer la configuration du selfbot

* remplissez tout correctement ps: pour le token ne mettez pas les "" qui sont au debut et a la fin du token

![ScreenShot](https://cdn.discordapp.com/attachments/846067759241625684/846067772554870834/unknown.png)

<b>Pour avoir votre token vous pouvez copier coller ce script dans la console f12 (inspecter l'ellement)</b>
```js
getYourToken();

function getYourToken() {
    var req = webpackJsonp.push([
        [], {
            extra_id: (e, _t, r) => e.exports = r
        },
        [
            ["extra_id"]
        ]
    ]);
    for (let e in req.c)
        if (req.c.hasOwnProperty(e)) {
            let t = req.c[e].exports;
            if (t && t.__esModule && t.default)
                for (let e in t.default)
                    "getToken" === e && (token = t.default.getToken());
        }
    console.log("Votre token : " + `${token}`);
}
```
quand vous avez tout fait correctement, il vous reste plus qu'a lancer le selfbot

* fermez le cmd

* relancez start.bat

* entrez 1 puis entrée

* Voila le selfbot est a vous !

![ScreenShot](https://media.discordapp.net/attachments/846067759241625684/846070561435287612/unknownz-redacted_dot_app-redacted_dot_app.png)

https://youtu.be/O13mZZBCuys
