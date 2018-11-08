> As a chrome extension: https://github.com/timqian/star-history-plugin/ 


## [Show cases: lodash vs underscore](http://www.timqian.com/star-history/#lodash/lodash&jashkenas/underscore)


![](./assets/lodashUnderscore.png)

## Installation

### Docker Installed
Simply run in your shell:
```
docker build -t star-history . && docker run -p 3000:3000 star-history
```

### No Docker Installed
You can use devspace an open-source project to deploy the application (Simply download the latest release from [devspace](https://github.com/covexo/devspace/releases) and put it in your path). Simply run in your shell:
```
devspace deploy
```

## Updates

- 2016-6-30: Alert to notie

- 2016-6-28: Add clear btn

- 2016-6-28: Better view for "many star" repos (use current star number as the last point on the graph)

- 2016-6-26: **Store repo info into url hash**

- 2016-6-26: **multiple kinds of input styles (eg: github.com/timqian/star-history, ...)**

- 2016-6-26: Better view for less star repos #28

- 2016-6-14: **Toggle search by hit enter** #26, prevent crash while searching for not existing repo

- 2016-5-26: Update mobile view


[![paypal donate][paypal-image]][paypal-url]

[paypal-image]: https://www.paypal.com/en_US/i/btn/btn_donate_SM.gif
[paypal-url]: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=timqian92@qq.com&currency_code=USD&amount=1&return=https://github.com/timqian&item_name=timqian&undefined_quantity=1&no_note=0
