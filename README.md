# t3_Calendar

## Minimal Dependencies
* TYPO3 CMS 7.6 or greater

## Infos 
* Inclu la librairie javascript [Totem jquery plugin](http://buildinternet.com/project/totem/)


## Usage
Pour activer les vues Fluid

* Dans le setup d'un gabarit
```
plugin.tx_cal_controller {
    activateFluid = 1
}
```

* ou dans l'onglet Typoscript du plugin dans la zone de texte "plugin.tx_cal_controller: ":
```
activateFluid = 1
```

*Ne pas oublier d'inclure l'extension dans le gabarit*

## Examples
[Vertical Ticker](https://github.com/CDG47-Dev/t3_Calendar/blob/master/Examples/vertical_ticker.png)
