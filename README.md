# LFX NG SCHEMATICS

This project is designed to install the LFX Angular Schematics into an Angular project. The schematics are designed to help developers quickly create components, services, and modules that are compliant with the LFX design system.
Ref to NG CLI documentation: `https://angular.dev/tools/cli/schematics`

## Installation
```
ng add lfx-ng-schematics --registry http://localhost:4873/
```

## Check installed schematics
```
schematics lfx-ng-schematics: --list-schematics
```

## Usage
```
ng g lfx-ng-schematics:lfx-c --name test-component
```

## List of schematics

|     Full name     | Alias | Description                                                   |   Params   |
|:-----------------:|:-----:|---------------------------------------------------------------|:----------:|
|   lfx-component   | lfx-c | Generates set of files for component including storybook file | name, path |

## Development

```
npm run verdaccio // start verdaccio server
npm run build // build the schematics
npm run publish // publish the schematics
```

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
