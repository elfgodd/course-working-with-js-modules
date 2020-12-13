Working with JavaScript Modules @Pluralsight

by Jonathan Mills

When writing web applications, JavaScript code can rapidly become difficult to maintain and understand. In this course, you will learn how to use modules to break up your code into manageable pieces that are easier to work with.

#### What Are Modules?

- Import and Export keyboards
- Encapsulate code
- Control access
- Reference its own dependencies

#### Module Considerations
- Modules are singletons
- Properties are bound
- Exports are static
- One module per file

#### Types of exports
- Export keyword
- Named exports
- Default exports
- Aggregating Modules

__Named exports__

export function sessionTemplate(items){

}

import { sessionTemplate } from './template';

__Default exports__

export default function sessionTemplate(items){

}
// it will get any functions
import anyName from './sessionTemplate';

#### Types of imports
- import keyboard
- Allowing modules
- Default imports
- Named imports