# unframer

## 1.1.1

### Patch Changes

-   7615df6: Update framer to 2.4.1, update framer motion to 11.0.7
-   e5cc18b: Remove postinstall script

## 1.1.0

### Minor Changes

-   9ddc21d: Fix .json files in components
-   72602a7: Added --watch option to watch for Framer or config changes

### Patch Changes

-   4537169: remove additional LayoutGroup component, use the one already inside the Fremer component

## 1.0.1

### Patch Changes

-   eddf196: Update framer to 2.4.1, update framer motion to 11.0.7

## 1.0.0

### Major Changes

-   Use tailwind style breaking points instead of Desktop etc

## 0.7.1

### Patch Changes

-   Module not found: Default condition should be last one

## 0.7.0

### Minor Changes

-   Added index export. Export framer-motion from unframer, prevent mismatches by using unframer instead of framer-motion

## 0.6.3

### Patch Changes

-   Fix url redirect for root url

## 0.6.2

### Patch Changes

-   Render all variants at the same time again, nextjs was bugging

## 0.6.1

### Patch Changes

-   Fix layout animations getting triggered on mount, disable layout animations during hydration

## 0.6.0

### Minor Changes

-   Renamed to unframer from installable-framer

## 0.5.1

### Patch Changes

-   Fix variants types, don't render variants that are not in the current breakpoint on client, only do it on server thanks to useSyncExternalStore

## 0.5.0

### Minor Changes

-   a9d22e5: Added --watch option

## 0.4.1

### Patch Changes

-   defd822: fixed installable framer deadlock because of dprint

## 0.4.0

### Minor Changes

-   Use latest framer package bundle, should work with latest components

## 0.3.7

### Patch Changes

-   Added useLocaleCode export, fix #2

## 0.3.6

### Patch Changes

-   Fix missing dependency

## 0.3.5

### Patch Changes

-   update framer

## 0.3.4

### Patch Changes

-   fix expty defs

## 0.3.3

### Patch Changes

-   fix json handling in transform

## 0.3.2

### Patch Changes

-   Fix json handling again

## 0.3.1

### Patch Changes

-   support importing json files

## 0.3.0

### Minor Changes

-   Added Component.Responsive shortcut

## 0.2.1

### Patch Changes

-   fix semicolons syntax errors

## 0.2.0

### Minor Changes

-   Added more react utilities, format outputs

### Patch Changes

-   Added breakpoints styles

## 0.1.3

### Patch Changes

-   export framer styles to make ssr work

## 0.1.2

### Patch Changes

-   Fix components without props controls

## 0.1.1

### Patch Changes

-   remove deps

## 0.1.0

### Minor Changes

-   Better prop controls extraction

## 0.0.3

### Patch Changes

-   Added outDir option

## 0.0.2

### Patch Changes

-   Update framer fixed

## 0.0.1

### Patch Changes

-   Initial
