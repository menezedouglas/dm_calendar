# dm_calendar 
<img src="https://img.shields.io/static/v1?label=Alert&message=In%20development&color=blue&style=for-the-badge````"/>

## Installation

### [npm](https://www.npmjs.com/package/dm_calendar)
```
npm i dm_calendar
```

### yarn
```
yarn add dm_calendar
```

## Usage
```
<template>
    <div>
        <full />
    </div>
</template>

<script>
    import { full } from 'dm_calendar'
    
    [...]
    components: {
        [...]
        full,
    }
</script>
```

## Parameters

### Language
> Accept only Brazilian Portuguese (pt-br)

#### Declaration
```
<full
    lang="pt-br"
></full>
```

### Date
> Accepts date javascript object or date string only in United States format.
  (Example: "01/23/2021", "06/29/97")

### Options
|Name|Default|type|Accept|
|----|-------|----|------|
|selectLanguage|true|boolean|true or false|
|showDate|true|boolean|true or false|
