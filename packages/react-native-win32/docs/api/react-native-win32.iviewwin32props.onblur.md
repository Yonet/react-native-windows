<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@office-iss/react-native-win32](./react-native-win32.md) &gt; [IViewWin32Props](./react-native-win32.iviewwin32props.md) &gt; [onBlur](./react-native-win32.iviewwin32props.onblur.md)

## IViewWin32Props.onBlur property

The onBlur event occurs when an element loses focus. The opposite of onBlur is onFocus. Note that in React Native, unlike in the web, the onBlur event bubbles (similar to onFocusOut in the web).

`ev.target === ev.currentTarget` when the focus is being lost from this component. `ev.target !== ev.currentTarget` when the focus is being lost from a descendant.

<b>Signature:</b>

```typescript
onBlur?: (ev: RN.NativeSyntheticEvent<{}>) => void;
```