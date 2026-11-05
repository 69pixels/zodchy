# Component specifications

Each theme below includes a focused specification for every component in Graphical's preview catalog. Specifications combine the preview's resolved values with anatomy, geometry, state, and composition rules. Authored refinements are part of the target, not optional suggestions. Read the relevant files when building individual components; read every entry when setting up the full library.

Both setup choices include all specifications. When the full library is selected, components/graphical/ also contains the actual preview components, their shared styling runtime, styles.css, and the current theme.ts snapshot. Use that implementation directly and follow the component setup in base-ui.md; specifications explain and verify it, not replace it. The theme-and-skills choice includes no component source or component dependency installation; build or style components as needed. Follow the selected setup in GUI.md when present.

For a full installation, track every component below as implemented, reused and verified, or blocked with a concrete reason, and provide its import path. Also check the receiving version's [official Base UI catalog](https://base-ui.com/llms.txt) for supported additions; disclose components without a Graphical preview specification instead of claiming a verified visual match. Utility providers and hooks are integration tools, not standalone visual components.

Preserve the supplied assets and resolved styles. Free fallbacks can change appearance and must be disclosed. Honor the receiving app's dependency and review policies; only claim visual parity for what was actually verified.

## zodchy

[Theme foundations](themes/zodchy.md) · [Effective assignment tables](themes/zodchy-components.md)

- [Accordion](components/zodchy/accordion.md)
- [Alert dialog](components/zodchy/alert-dialog.md)
- [Autocomplete](components/zodchy/autocomplete.md)
- [Avatar](components/zodchy/avatar.md)
- [Button](components/zodchy/button.md)
- [Checkbox](components/zodchy/checkbox.md)
- [Checkbox group](components/zodchy/checkbox-group.md)
- [Collapsible](components/zodchy/collapsible.md)
- [Combobox](components/zodchy/combobox.md)
- [Context menu](components/zodchy/context-menu.md)
- [Dialog](components/zodchy/dialog.md)
- [Drawer](components/zodchy/drawer.md)
- [Field](components/zodchy/field.md)
- [Fieldset](components/zodchy/fieldset.md)
- [Form](components/zodchy/form.md)
- [Menu](components/zodchy/menu.md)
- [Menubar](components/zodchy/menubar.md)
- [Meter](components/zodchy/meter.md)
- [Navigation menu](components/zodchy/navigation-menu.md)
- [Number field](components/zodchy/number-field.md)
- [OTP field](components/zodchy/otp-field.md)
- [Popover](components/zodchy/popover.md)
- [Preview card](components/zodchy/preview-card.md)
- [Progress](components/zodchy/progress.md)
- [Radio](components/zodchy/radio.md)
- [Radio group](components/zodchy/radio-group.md)
- [Scroll area](components/zodchy/scroll-area.md)
- [Select](components/zodchy/select.md)
- [Separator](components/zodchy/separator.md)
- [Slider](components/zodchy/slider.md)
- [Switch](components/zodchy/switch.md)
- [Tabs](components/zodchy/tabs.md)
- [Text field](components/zodchy/input.md)
- [Toast](components/zodchy/toast.md)
- [Toggle](components/zodchy/toggle.md)
- [Toggle group](components/zodchy/toggle-group.md)
- [Toolbar](components/zodchy/toolbar.md)
- [Tooltip](components/zodchy/tooltip.md)
