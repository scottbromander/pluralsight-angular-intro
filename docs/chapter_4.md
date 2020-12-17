# Chapter 4 Notes

## What is a component

- Components contain `templates`

- Templates are created with HTML

- Includes binding and directives

- Class, code supporting the view - Created in TypeScript - Properties: data - Methods: logic

- Metadata, extra data for Angular - Defined with a decorator

Example:

```
import { Component } from '@angular/core';

// METADATA AND TEMPLATE
@Component({
    selector: 'pm-root',
    template: `
        <div>
            <h1>{{pageTitle}}</h1>
            <div>My first component</div>
        </div>
    `
})

// CLASS
export class AppComponent {
    pageTitle: string = 'Acme Product Management';
}
```
