---
title: API
toc: true
---

## Angular Components

### ClrRange

#### Selector & Basic Usage

<DocDemo toggle="false">

```html
<form clrForm>
  <clr-range-container [clrRangeHasProgress]="true">
    <label>Full example</label>
    <input type="range" clrRange [(ngModel)]="input.two" name="three" />
    <clr-control-helper>Helper text</clr-control-helper>
  </clr-range-container>
</form>
```

</DocDemo>

#### Bindings

#### Bindings

<DocComponentApi component="ClrRange" item="bindings" />
<DocComponentApi component="ClrFormCommon" item="bindings" />