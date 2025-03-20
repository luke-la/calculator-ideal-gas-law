# Ideal Gas Law Calculator
A simple, work-in-progress calculator for Ideal Gas Law.

## Description
This is a quick project to practice translating an equation like PV=nRT into code, and building interactive functionality. I picked JavaScript because it's what I've been working with recently, and googling the problem came up with a base to work with in that language. I restructured that and made it more dynamic and implemented Vue.js to make handling the input and updates a bit easier.

The initial project was put together in four or five hours, and despite being mostly functional was very rough around the edges with a few rounding errors and was not well optimized for mobile. I have now put together an update that doesn't address the rounding issues, but should make the site easier to use on both desktop and mobile.

## Getting Started
### Dependencies
This project uses Vue.js via CDN, so it doesn't require installation of Vue CLI.

For development purposes you may change the CLN in the head of index.html reference from:
```
<script src="https://unpkg.com/vue@3/dist/vue.global.prod.js"></script>
```
to:
```
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
```

### Using the Program
The easiest way to view the site is via [Github Pages](https://luke-la.github.io/calculator-ideal-gas-law/).

Alternately, you may follow these steps to run it locally: 
1. Download a .ZIP file of the repo
2. Extract the files to a folder in a easily found loation
3. Open index.html in your favorite web browser (On Windows: open a chrome browser and press `Ctrl+O` or double click on the file from your file explorer)

## Contributions
Contributions are welcome, but given the size of the project I would recommend simply creating your own application using this as the base.

That said, if there's a bug you want to squash I'd be much obliged.

## Version History
* 0.2
  * Moves Result Output
  * Changes Styling
  * Adds "Show Work" Featrue
* 0.1
  * Initial Release

## License
THis project is Licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements
Existing Ideal Gas Law calculators used as reference:
* [Omni Calculator](https://www.omnicalculator.com/physics/ideal-gas-law)
* [Calculator Soup](https://www.calculatorsoup.com/calculators/physics/ideal-gas-law.php)

Other Resources for constants and formulas:
* [Wikipedia - Ideal Gas Law](https://en.wikipedia.org/wiki/Ideal_gas_law)

Thanks Annie for telling me PV=nRT existed.
(I'm only a little bit upset I've spent so long on this)
