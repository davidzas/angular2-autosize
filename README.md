# angular2-autosize

***angular2-autosize*** is a fork from (https://github.com/stevepapa/angular2-autosize). It was modified to work with input tags instead of textarea.

## Demo

[http://stevepapa.com/angular2-autosize](http://stevepapa.com/angular2-autosize)

## Installation:

```bash
npm install angular2-autosize
```

## Use Example:

Add the declaration to your @NgModule:

```typescript
import {Autosize} from 'angular2-autosize';

...

@NgModule({
  declarations: [
    Autosize
  ]
})
```

Use directly inside your HTML templates

```
<input autosize class="my-input" type="text">
```

## Author

[Steve Papa](https://stevepapa.com)

## Licence

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
