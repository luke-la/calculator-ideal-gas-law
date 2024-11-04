# Ideal Gas Law Calculator
A simple, work-in-progress calculator for Ideal Gas Law.

## Description
This is a project that stemmed from wondering how I would translate the equation PV=nRT into code. I picked JavaScript because it's what I've been working with recently, and google came up with something workable. I wanted to restructure that and make it more dynamic and implementing Vue.js to make a full(ish) calculator was a natural step from there.

At this stage, this entire project was put together in four or five hours. Despite being mostly functional is very rough around the edges with a few rounding errors, and some graphics jumping because of imperfect CSS. It is not well optimized for mobile.

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
2. Extract the files to a folder you will be able to easily find
3. Open index.html in your favorite web browser (On Windows: open the browser and press `Ctrl+O` or double click on the file from your file explorer)

## Contributions
Contributions are welcome, but given the size of the project I would recommend fully cloning it and creating your own application using this as the base. It has been a good practice project and one I highly recommend.

That said, if there's a bug you want to squash I'd be much obliged.

## Version History
* 0.1
  * Initial Release

## License
THis project is Licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements
Thanks Annie for telling me PV=nRT existed.
(I'm only a little bit upset I've spent so long on this)

Existing Ideal Gas Law calculators used as reference:
* [Omni Calculator](https://www.omnicalculator.com/physics/ideal-gas-law)
* [Calculator Soup](https://www.calculatorsoup.com/calculators/physics/ideal-gas-law.php)

Other Resources for constants and formulas:
* [Wikipedia - Ideal Gas Law](https://en.wikipedia.org/wiki/Ideal_gas_law)
