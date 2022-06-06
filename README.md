# removeDiacritics
a function that runs over string and replaces all Accent letters with English letters


## Usage

```typescript
import {removeDiacritics} from './RemoveDiacritics'

const str = 'Łagów';
const normalized = removeDiacritics(str);

console.log(normalized) 
> Lagow

```

## Source
https://stackoverflow.com/questions/990904/remove-accents-diacritics-in-a-string-in-javascript
