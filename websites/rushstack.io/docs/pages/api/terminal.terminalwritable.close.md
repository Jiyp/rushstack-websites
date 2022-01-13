---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/terminal](./terminal.md) &gt; [TerminalWritable](./terminal.terminalwritable.md) &gt; [close](./terminal.terminalwritable.close.md)

## TerminalWritable.close() method

Calling this method flushes any remaining outputs and permanently transitions the `TerminalWritable` to a "closed" state, where no further chunks can be written.

<b>Signature:</b>

```typescript
/** @sealed */
close(): void;
```
<b>Returns:</b>

void

## Remarks

The subclass provides its implementation via the the [TerminalWritable.onClose()](./terminal.terminalwritable.onclose.md) method, which is called by `close()` .

If this method is called more than once, the additional calls are ignored; `TerminalWritable.onClose` will be called at most once.
