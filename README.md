# usestate VS Code Extension

[VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=benjervis.usestate)

When using the [useState hook](https://reactjs.org/docs/hooks-reference.html#usestate) in React, the common usage pattern looks like

```
const [myVariable, setMyVariable] = useState();
```

This is very repetitive, and the camelcase means that the variable name needs to be capitalised for the `set` variable, which means it can't be easily copy pasted, or added with multiple cursors.

## Usage

The "Insert useState line" command can be accessed from the [command palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette), but it's recommeded you set up a keybinding for it. Enter your variable name into the textbox (e.g. `myVariable` in the above example), and the properly camelcased line will be added. You may still need to import `useState` yourself.
