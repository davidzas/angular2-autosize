# angular2-autosize

***angular2-autosize*** is a fork from (https://github.com/stevepapa/angular2-autosize). It was modified to work with input tags instead of textarea.

## Use Example:

Add the declaration to your @NgModule:

```typescript
import {AutosizeDirective} from 'angular2-autosize';

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
