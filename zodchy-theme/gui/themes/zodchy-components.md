# zodchy — component assignments

Use the component specifications below with the [theme foundations](zodchy.md). Each file contains its effective named assignments, complete resolved styles and CSS values, anatomy, geometry, and state rules. Defaults and shared part references are already resolved for both light and dark modes. The records live in those focused files once, so there is no second set of assignments to reconcile. Return to the [complete component index](../components.md).

Compose each shadow-based edge with elevation and preserve separate inner bevels. The ordered shadows assignment replaces the single legacy shadow choice and includes editable inner highlights. An empty list means no shadows. Colors remain theme references; clipToBorder keeps an inner highlight inside the edge on an inset overlay.

## Accordion

[Full Accordion specification](../components/zodchy/accordion.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled, open |
| panel | rest |
| content | rest, disabled, invalid |
| indicator | rest, disabled, invalid |

## Alert dialog

[Full Alert dialog specification](../components/zodchy/alert-dialog.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
| backdrop | rest |
| title | rest, disabled, invalid |
| description | rest, disabled, invalid |
| action | rest, hover, focus, disabled |
| close | rest, hover, focus, disabled |

## Autocomplete

[Full Autocomplete specification](../components/zodchy/autocomplete.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| input | rest, hover, focus, disabled |
| label | rest, disabled, invalid |
| popover | rest |
| option | rest, highlighted, selected, disabled |
| content | rest, disabled, invalid |

## Avatar

[Full Avatar specification](../components/zodchy/avatar.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest |
| fallback | rest, disabled, invalid |

## Button

[Full Button specification](../components/zodchy/button.md)

Variants: primary, secondary, outline, ghost, danger. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest, hover, focus, disabled |
| label | rest, hover, focus, disabled |

## Checkbox

[Full Checkbox specification](../components/zodchy/checkbox.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest, hover, focus, disabled, checked, indeterminate |
| indicator | rest, checked, indeterminate, disabled |
| label | rest, disabled |

## Checkbox group

[Full Checkbox group specification](../components/zodchy/checkbox-group.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| row | rest, hover, focus, disabled, checked, indeterminate |
| control | rest, hover, focus, disabled, checked, indeterminate |
| indicator | rest, checked, disabled, indeterminate |
| label | rest, disabled, invalid |

## Collapsible

[Full Collapsible specification](../components/zodchy/collapsible.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| trigger | rest, hover, focus, disabled, open |
| panel | rest |
| content | rest, disabled, invalid |
| indicator | rest, disabled, invalid |

## Combobox

[Full Combobox specification](../components/zodchy/combobox.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| label | rest, disabled |
| input | rest, hover, focus, disabled |
| popover | rest |
| option | rest, highlighted, selected, disabled |

## Context menu

[Full Context menu specification](../components/zodchy/context-menu.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled, open |
| popover | rest |
| option | rest, highlighted, selected, disabled |
| label | rest, disabled, invalid |
| separator | rest |
| indicator | rest, disabled, invalid |

## Dialog

[Full Dialog specification](../components/zodchy/dialog.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
| backdrop | rest |
| title | rest, disabled, invalid |
| description | rest, disabled, invalid |
| action | rest, hover, focus, disabled |
| close | rest, hover, focus, disabled |

## Drawer

[Full Drawer specification](../components/zodchy/drawer.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
| backdrop | rest |
| title | rest, disabled, invalid |
| description | rest, disabled, invalid |
| action | rest, hover, focus, disabled |
| close | rest, hover, focus, disabled |

## Field

[Full Field specification](../components/zodchy/field.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| input | rest, hover, focus, disabled, invalid, valid, readonly |
| label | rest, disabled, invalid |
| description | rest, disabled, invalid |
| error | rest, disabled, invalid |

## Fieldset

[Full Fieldset specification](../components/zodchy/fieldset.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| legend | rest, disabled, invalid |
| content | rest |
| input | rest, hover, focus, disabled, invalid, valid, readonly |
| label | rest, disabled, invalid |
| description | rest, disabled, invalid |
| error | rest, disabled, invalid |

## Form

[Full Form specification](../components/zodchy/form.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| content | rest |
| input | rest, hover, focus, disabled, invalid, valid, readonly |
| label | rest, disabled, invalid |
| description | rest, disabled, invalid |
| error | rest, disabled, invalid |
| action | rest, hover, focus, disabled |

## Menu

[Full Menu specification](../components/zodchy/menu.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled, open |
| popover | rest |
| option | rest, highlighted, selected, disabled |
| label | rest, disabled, invalid |
| separator | rest |
| indicator | rest, disabled, invalid |

## Menubar

[Full Menubar specification](../components/zodchy/menubar.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| trigger | rest, hover, focus, disabled, open |
| popover | rest |
| option | rest, highlighted, selected, disabled |
| label | rest, disabled, invalid |
| separator | rest |
| indicator | rest, disabled, invalid |

## Meter

[Full Meter specification](../components/zodchy/meter.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| track | rest |
| indicator | rest, low, high |
| label | rest, disabled, invalid |
| value | rest, disabled, invalid |

## Navigation menu

[Full Navigation menu specification](../components/zodchy/navigation-menu.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| list | rest |
| trigger | rest, hover, focus, disabled, open |
| popover | rest |
| link | rest, hover, focus, disabled, selected |

## Number field

[Full Number field specification](../components/zodchy/number-field.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| input | rest, hover, focus, disabled, readonly, invalid |
| label | rest, disabled, invalid |
| decrement | rest, hover, focus, disabled |
| increment | rest, hover, focus, disabled |

## OTP field

[Full OTP field specification](../components/zodchy/otp-field.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| input | rest, hover, focus, disabled, invalid, complete |
| label | rest, disabled, invalid |
| separator | rest |

## Popover

[Full Popover specification](../components/zodchy/popover.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
| title | rest, disabled, invalid |
| description | rest, disabled, invalid |
| action | rest, hover, focus, disabled |
| close | rest, hover, focus, disabled |

## Preview card

[Full Preview card specification](../components/zodchy/preview-card.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
| title | rest, disabled, invalid |
| description | rest, disabled, invalid |

## Progress

[Full Progress specification](../components/zodchy/progress.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| track | rest |
| indicator | rest, loading, complete |
| label | rest, disabled, invalid |
| value | rest, disabled, invalid |

## Radio

[Full Radio specification](../components/zodchy/radio.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest, hover, focus, disabled, checked |
| indicator | rest, checked, disabled |
| label | rest, disabled, invalid |

## Radio group

[Full Radio group specification](../components/zodchy/radio-group.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| row | rest, hover, focus, disabled, checked |
| control | rest, hover, focus, disabled, checked |
| indicator | rest, checked, disabled |
| label | rest, disabled, invalid |

## Scroll area

[Full Scroll area specification](../components/zodchy/scroll-area.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| viewport | rest |
| content | rest, disabled, invalid |
| scrollbar | rest |
| thumb | rest, hover, focus, disabled |

## Select

[Full Select specification](../components/zodchy/select.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest, hover, focus, disabled |
| label | rest, disabled |
| popover | rest |
| option | rest, highlighted, selected, disabled |

## Separator

[Full Separator specification](../components/zodchy/separator.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| separator | rest |

## Slider

[Full Slider specification](../components/zodchy/slider.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| track | rest, hover, focus, disabled |
| indicator | rest, disabled |
| thumb | rest, hover, focus, disabled |
| label | rest, disabled, invalid |
| value | rest, disabled, invalid |

## Switch

[Full Switch specification](../components/zodchy/switch.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| row | rest, hover, focus, disabled, checked |
| control | rest, hover, focus, disabled, checked |
| thumb | rest, hover, focus, disabled, checked |
| label | rest, disabled |

## Tabs

[Full Tabs specification](../components/zodchy/tabs.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| list | rest |
| trigger | rest, hover, focus, disabled, selected |
| panel | rest |
| content | rest, disabled, invalid |

## Text field

[Full Text field specification](../components/zodchy/input.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest, hover, focus, disabled, invalid, valid, readonly |
| label | rest, disabled |

## Toast

[Full Toast specification](../components/zodchy/toast.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
| title | rest, disabled, invalid |
| description | rest, disabled, invalid |
| action | rest, hover, focus, disabled |
| close | rest, hover, focus, disabled |

## Toggle

[Full Toggle specification](../components/zodchy/toggle.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| control | rest, hover, focus, disabled, pressed |
| label | rest, hover, focus, disabled, pressed |

## Toggle group

[Full Toggle group specification](../components/zodchy/toggle-group.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| control | rest, hover, focus, disabled, pressed |
| label | rest, hover, focus, disabled, pressed |

## Toolbar

[Full Toolbar specification](../components/zodchy/toolbar.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| group | rest |
| control | rest, hover, focus, disabled, pressed |
| label | rest, hover, focus, disabled, pressed |
| separator | rest |

## Tooltip

[Full Tooltip specification](../components/zodchy/tooltip.md)

Variants: default. Modes: light, dark.

| Part | States |
| --- | --- |
| trigger | rest, hover, focus, disabled |
| popover | rest |
