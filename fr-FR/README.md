# Easy TwitchAdBlocker

Une solution simple pour bloquer les publicités Twitch en utilisant [uBlock Origin](https://ublockorigin.com/fr/)

## Putting a script in uBlock Origin

1. Accéder au tableau de bord des paramètres d'uBlock Origin

![Step 1](../assets/step-1.png)

2. En dessous de `Mes filtres`, écrit `twitch.tv##+js(twitch-videoad)`

![Step 2](../assets/step-2.png)

3. En dessous de `Paramètres`, dans la section `Avancés`, cochez la case `Je suis un utilisateur avancé`, puis cliquez sur les engrenages qui apparaissent.

![Step 3](../assets/step-3.png)

4. Modifiez la valeur de userResourcesLocation de unset à `https://github.com/MoulinLouis/Easy-TwitchAdBlocker/raw/master/ublock.js` et cliquez sur le bouton `Appliquer`.

![Step 4](../assets/step-4.png)

5. C'est bon, profite de https://www.twitch.tv/